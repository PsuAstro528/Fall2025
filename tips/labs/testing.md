+++
title = "Testing Labs"
tags = ["tips","labs","testing"]
+++

# Testing your Lab
\toc


## Running automated tests on your system
- When you're done with a notebook, make sure it is saved (Ctrl+S) and close the tab.
- Make sure all the packages needed to run your test code are installed.  
```shell
cd REPO_DIR
julia --project -e 'using Pkg; Pkg.instantiate(); Pkg.activate("test"); Pkg.instantiate(); '
```
- Make sure all all the packages need to run the notebook you want to test are installed.  For example, for a notebook named `ex1.jl`, you would do
```shell
cd REPO_DIR
julia -e 'using Pkg, Pluto; Pluto.activate_notebook_environment("ex1.jl"); Pkg.instantiate(); '
```
If there are multiple notebooks to test, then you can combine this for multiple notebook files in one command such as
```shell
cd REPO_DIR
julia -e 'using Pkg, Pluto; Pluto.activate_notebook_environment("ex1.jl"); Pkg.instantiate();   Pluto.activate_notebook_environment("ex2.jl"); Pkg.instantiate(); '
```
In many cases this step will be unnecessary because the packages will have been installed what you ran the Pluto notebook.  But this can become important in some scenarios such as if you've done some work within a notebook on another computer.
- Run the tests for first notebook
For the first few labs, I suggested using a command like
```shell
cd REPO_DIR
julia --project=test test/runtest1.jl
```
or run tets for all the notebooks like
```shell
cd REPO_DIR
julia --project=test test/runtests.jl
```
However, I've since realized that this resulted in some complications in including files.  Therefore, I've changed the way the test scripts are setup.  Starting with lab4 (or if you get the updated version of lab3), you can run the tests like
```shell
cd REPO_DIR
julia --project -e 'cd("test"); include("test1.jl")'
```
or run tets for all the notebooks like
```shell
cd REPO_DIR
julia --project -e 'cd("test"); include("runtests.jl")'
```
The reason for the change is that julia test systems sets the working directory to be "test" when you run a command like
```shell
cd REPO_DIR
julia --project -e 'import Pkg; Pkg.test()'
```
which is how the GitHub continuous integration testing is running the tests.  By switching to this pattern, it'll be easier to make sure tests give consistent results when run locally or when run as part of continuous integration testing as a GitHub Action.

- Inspect the test report results and identify any areas that you want to revisit before submitting.
- Once  you're happy with the results (or run out of time) [commit your changes](../commit) and [submit](../submitting).

---
## Push commits to Github and review results of automated testing via web
- Return to the terminal tab, make sure you're in your repo's directory.
- [Commit your changes](../commit) to your local repository and [submit](../submitting) by pushing to your GitHub repository.
- For repositories that are configured to apply tests via continuous integration, you can navigate to your repository's webpage, click Actions, then look under "All Workflows" and choose "Test notebooks".  There will be some tests of early versions that have red x's next to them.  Hopefully, your latest submission (typically at the top of the list) will have a green checkbox next to it.  If not, then you can click on that commit string, then click "test (...)" and see the results of the continuous integration tests.
