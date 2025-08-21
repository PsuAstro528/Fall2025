+++
title = "Requirements"
course_inst = "Penn State"
course_number = "Astro 528"
course_name = "High-Performance Scientific Computing for Astrophysics"
weight = 50

creatordisplayname = "Eric Ford"
creatoremail = "ebf11 at psu dot edu"
lastmodifierdisplayname = "Eric Ford"
lastmodifieremail = "ebf11 at psu dot edu"
+++

## Computing Requirements
### Hardware
We anticipate that students will have access to a laptop computer or workstation with good internet to work on exercises both during and outside of classes (pairing up is encouraged even if you both have laptops).  As long as students have a good internet connection, then their local computer can be used for accessing cloud resources and need not be high-powered.  If anyone is likely to work form a location with poor internet speed/reliability, then they are encouraged install and run software locally, particularlly for the early part of the class.  While students will still need to submit jobs to the ICDS Roar supercomputer during the second half of the class, much of the software development can be done locally before connecting to Roar to submit jobs and retrieve results.

### Basic Software
Students will need regular access to the following software:

- Browser:  Many cloud resources such as those we will be using regularly (e.g., [Lynx Portal](https://portal.lynx.hpc.psu.edu)/, [GitHub](http://github.com/), etc.) require a modern browser.  Based on documentation that I've found for the most demanding sites, I beleive that that Chrome (22+), Firefox (16+), and Internet Explorer (11+) _should_ work, however it's not practical for the instructor to test each possible browser, OS, etc.  I plan to test the in class and homework exercises using Chrome.  If you find a problem that arises or is fixed by changing browsers, please let the instructor and class know, so others can benefit from your experience.

Many of the early assignments could be executed either on the student's local computer or on Penn State's Lynx cluster operated by the [Institute for Computational and Data Sciences](https://icds.psu.edu). However, once we get to parallelizing code, students will need to use the HPC resources provided by ICDS.  Therefore, all students should become familiar with the Lynx cluster to effectively utilize it during the later parts of the course, regardless of whether they install local software. The Lynx cluster is an instructional cluster and is specifically used for supporting courses, such as this one. [Roar Collab](https://www.icds.psu.edu/roar-collab/) is the flagship HPC cluster utilized for research efforts. Skills and workflows developed during this course on the Lynx cluster are entirely transferrable to Roar Collab for further work beyond the scope of this course. The [Roar User Guide](https://docs.icds.psu.edu) provides further details on accessing and utilizing Roar Collab.

### Optional Software
For students who find it convenient to install additional software on their local computer, they would likely to want to setup:

  + [Julia](http://julialang.org/downloads/) with the [Pluto](https://github.com/fonsp/Pluto.jl) and [IJulia](https://github.com/JuliaLang/IJulia.jl) packages for accessing  Pluto and Jupyter notebooks.
  + [Git](https://git-scm.com/) is typically run from the command line, but it is also possible to use git via a GUI such as [GitHub Desktop](https://desktop.github.com/) or  [GitKraken](https://www.gitkraken.com/git-client).  The command line version is likely installed by default. 
  + ssh:  [Setting up ssh keys for github](https://help.github.com/articles/connecting-to-github-with-ssh/) can make it easier to connect to a laptop/desktop workstation to your github repository without needing to retype passwords as often.  The command line version is likely installed by default. 
  + An [integrated development environment](https://en.wikipedia.org/wiki/Integrated_development_environment) that supports Julia, such as:
    - [VS Code](https://code.visualstudio.com/) and the [Julia for VSCode extension](https://www.julia-vscode.org/docs/dev/) (recommended)
  + [Jupyter](http://jupyter.org/install)  (Typically, Jupyter will be setup automatically by adding the IJulia package within Julia.) 

<!--
Some students may prefer to setup their system using a [Docker container](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook) that includes Julia, Python, R and Jupter notbook.  (If anyone tweaks this to prepare a custom dockerfile for the class, please share it with the rest of the class.)  To use Docker containers, students will need to install:

  + [Docker CE](https://docs.docker.com/install/)
  + [VirtualBox](https://www.virtualbox.org/wiki/Downloads) (if using Windows 7 or Windows 10 Home)
-->

<!--
(https://github.com/PsuAstro528/notebook) or image (astro528/notebook:latest) that has been preconfigured with all the software needed for the course assignments (except those requiring distributed computing or GPUs at ICDS-ACI).  
-->

### Accounts

<!--
- All students should [request an account on Roar Collab](/tips/aci/create_account/) (via the[ICDS website](https://www.icds.psu.edu/account-setup/) before the second class meeting.  
-->
- Students should create an account on [GitHub](http://github.com/).  Note that we will examine and discuss student's code both during class and via peer code review.  Students may choose to protect their privacy by choosing a github account id that does not identify them.  Students may wish to create a separate github account just for this class, so as to avoid being identified by other projects.
- Prior to the second class meeting, students should send the instructor their GitHub userid.
<!-- 
- Students should make use of [Top Hat](https://www.tophat.psu.edu/) for submitting reading questions.  [Top Hat Activation Instructions](https://pennstate.service-now.com/sp?id=kb_article_view&sysparm_article=KB0015827&sys_kb_id=476eb94edb47e81029b24a28139619b1&spa=1) are avaliable.
-->
