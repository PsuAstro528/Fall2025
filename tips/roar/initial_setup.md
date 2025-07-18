+++
title = "Setup Script on Roar"
tags = ["tips","getting_started","icds","aci","roar"]
+++

### Run Setup Script on Roar

For students using Roar for the first time,
- Open [rcportal.hpc.psu.edu](https://rcportal.hpc.psu.edu/) in your browser's guest or incognito mode.
- Log in with your Penn State credentials (and authenticate if necessary).
- Select Clusters._ACI Shell Access (You'll likely have to complete 2 factor authentication again.)

We'll want to make a few updates to your Roar environment.  To make this easy, Justin has provided a script that you can easily run from a terminal window on Roar,
```shell
bash /storage/group/RISE/classroom/astro_528/scripts/class_setup
```
<!--
If you’re curious, this will update your .bashrc startup script so that it automatically loads a module (so software for the course is in your path; `module use /storage/group/RISE/sw7/modules`), and move your .julia and .conda directories from the home filesystem to the work filesystem (since those can get rather large).  
-->
If you already have customized your Roar environment for your research, then you may want to look at the script and make changes incrementally, so you don’t accidentally break something.  
<!--
If something does break, you can run `/storage/group/RISE/classroom/astro_528/scripts/class_setup restore` to undo the setup changes above.  
-->
After you exit the terminal, your next Roar session will automatically use those settings.


The next step is to [setup git on Roar](../git).

<!-- No longer required for Roar Collab
Now you're ready to move on to [starting ](../sshkeys/)
-->

