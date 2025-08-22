+++
title = "Updating lab"
tags = ["tips","labs"]
+++

### Updating files from a lab
In case the instructor makes changes to the template after you've cloned the template, it would be useful to be able to merge in those changes easily.  
- If you've made changes to files in your repository that you want to save, then [save, commit and push](../submitting/) them.
- Close and shutdown all notebooks that you have open in Pluto.  Close and save any other files (e.g., README.md) that you may have opened.
- From your private GitHub repository, click "Pull requests"
- Click "GitHub Classroom: Sync Assignment"
- Check if it says "No conflicts with base branch" and there is a green "Merge pull request" button.
- If yes, then click "Merge pull request" and then "Confirm merge".  
  + Wait until Github shows a purple "Merged" button near the top.  
  + From the terminal, make sure you are in your repository directory and then run
``` shell
git pull
```
- If no, then click "Files changed".  Unfortunately, Pluto notebooks can be a bit finicky, particularly if you start adding, moving or removing cells (which can result in code being moved within the file even if it didn't change).  
  + Review the changes that have been made and see if you can easily incorporate the substantive ones into your notebook.
  + Alternatively, it may make more sense to:
   - make a backup copy of the notebook that you've been working in,  
   - download the replacement notebook from the starter repository,
   - overwrite your notebook, and
   - copy and paste in any important additions/changes you've made from your backup notebook to the new notebook.  
  + Save, commit and push these changes before continuing with the lab.
- Hopefully, you won't need to do this often!

<!--

To prepare for that, you can set a remote upstream repository.  Here I assume that your REPO_URL was https://github.com/GITHUBID/example-GITHUBID.git.  Notice that we're replacing the first GITHUB id by the organization name "PsuAstro528" and remove the "-GITHUBID" at the end.
```shell
git remote add upstream git@github.com:PsuAstro528/example.git
```

If you haven't started or have only made a few minor changes to existing cells, then you can attempt to have git merge changes from the starting repository by running either
```shell
git pull upstream main
```
or if you have a newer version of git
```shell
git pull upstream main --allow-unrelated-histories
```
-->
