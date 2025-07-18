+++
title = "Submitting Labs"
tags = ["tips","labs","git"]
+++

# Submitting your Lab
\toc


## Save & commit changes before you submit
Ideally, you'd commit small changes as you go.  At a minimum, make sure that you [commit your changes to your local repository](../commit) each time you are wrapping up a coding session or about to take a break.
From the terminal tab, make sure you're in your repo's directory.
Then use the following command to commit all changes you've made to files being tracked by git in the current repository.  
```shell
git commit -a -m "Completed"    
```
Including "Completed" in the commit message lets the instructor and/or TA know that you're done with the assignment.  
Consider [testing your code locally](testing) on ACI (or you local computer) before submitting the final version of your code.

---
## Push commits to Github
- Return to the terminal tab, make sure you're in your repo's directory.
- Run the following commands

```shell
git push
```

