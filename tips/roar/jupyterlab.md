+++
title = "Starting Jupyter Lab & Pluto Notebook Servers on Lynx"
tags = ["tips","labs","icds","aci","roar","lynx","pluto"]
+++

# Start Lynx Session with Jupyter Lab & Pluto Servers

If this is your first time to run Pluto on Lynx, then first make sure you have an account on Lynx and have completed the [initial setup](../tips/roar/) steps.
Then, each time you want to start a Jupyter Lab session on Lynx, you'll follow the instructions below:
1. Browse to [portal.lynx.hpc.psu.edu](https://portal.lynx.hpc.psu.edu).
Using "guest" or "incognito" mode is recommended.
Login and authenticate (as necessary).

1. Under _Interactive Apps_, choose _HPC for Astro Jupyter_
1. Select:
   - Jupyter Interface: Jupyter Lab
   - Environment setup: `source /storage/egroup/hpc4astro/default/astro_528/scripts/env_setup`
   - Number of hours: 2  (can choose longer if you plan to continue after class or outside of class)
   - Number of cores: 2  (or more if running parallel computation)
   - Memory per core: 8 GB
   - If necessary, feel free to select the _Enable advanced Slurm options_ box to directly enter additional Slurm resource directives. Note that these may override any previous selections, and the session will not successfully start if there are any mistakes in the provided directives.
1. Click _Launch_, and your session request will appear in the _My Interactive Sessions_ list. Wait while your job starts.
1. Once the _Click to Connect to Jupyter_ button appears, click it.
   + The top row of tiles within the Luancher (labeled "Notebook") should include a tile labeled "Pluto.jl".  Click it.  
   + A new browser tab should open with a Pluto session.
   + The first time you open Pluto it will take a few minutes and is likely to time out.  Just wait a few minutes and try again.  (Behind the scenes, it's installing a lot of packages.)
   + Open a Pluto notebook
       - For a blank notebook, click "Create a new notebook"
       - To open an existing notebook, or enter the path to the notebook in the text box under "Open a notebook" and click the "Open" button.   (I find using tab completion is very helpful.) 
   + Do your work in the Pluto notebook.
   1. See [Starting & Submitting Assignments](/tips/labs/) for more information on accessing and submitting assignments.
<!--
1. When you're done, save your notebook (Ctrl+S or button in top right of page), close the browser tab(s) with your Pluto notebook(s), and click File.LogoutShutdown from the Jupyter session.
-->
1. Go back to the "My Interactive Sessions" tab in the Lynx Portal, click "Delete" for this Jupyter session and confirm. 
