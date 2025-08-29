+++
title = "SSH keys on ACI"
tags = ["ssh"]
+++

For students using Lynx for the first time, run the following commands from the terminal on Lynx.
(If you're not already at a terminal, see [first step](../initial_setup/).)
<!--
- Open [portal.lynx.hpc.psu.edu](https://portal.lynx.hpc.psu.edu/) in your browser's guest or incognito mode.
- Log in with your Penn State credentials (and authenticate if necessary).
- Select Clusters > Shell Access (You'll likely have to complete 2 factor authentication again.)
-->
- Check if you already have ssh keys installed by running
```shell
ls -al ~/.ssh/
```
If you see a file `id_rsa.pub`, then you already have an ssh key.  If not, then run 
```shell
ssh-keygen
```
you can accept the default path.  Do not specify a password.

- Now you want to [add the new ssh key to the list of authorized keys for your github account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/#platform-linux) in order to push code from the Lynx cluster to github.
<!-- - Follow the link to your github repository for Lab 1 (the one like https://github.com/PsuAstro528/lab1-yourgithubid), -->
- Login to [GitHub](https://github.com/)
- Click the circular avatar at the top right, select "Settings", then click "SSH and GPG keys" on the left.  Then click the green "New SSH key" button.  
- In the Title box enter "ICDS Lynx" (or your preferred identifier).  
- In the "Key" box paste the contents of the file `~/.ssh/id_rsa.pub` from the Lynx cluster.  You can get your ssh public key by running `cat  ~/.ssh/id_rsa.pub` from the command line while logged into the Lynx cluster (or download it from the ACI portal by going to Files.Home Directory, clicking "Show Dotfiles" (at the top of the page), double clicking .ssh, clicking `id_rsa.pub` and then download.  Then copy from your favorite text editor.)  

\\

Now you're ready to [open a Pluto notebook for the first lab](../pluto).
