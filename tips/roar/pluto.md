+++
title = "Starting Jupyter & Pluto Notebook Servers on Roar Collab"
tags = ["tips","labs","icds","aci","roar","pluto"]
+++

# Start Roar Session with Jupyter & Pluto Server

If this is your first time to run Pluto on Roar, then first make sure you have an account on ACI and have completed the [initial setup](../tips/roar/) steps.
Then, each time you want to start a Jupyter notebook session on Roar, you'll follow the instructions below:
1. Browse to [rcportal.hpc.psu.edu](https://rcportal.hpc.psu.edu).
Using "guest" or "incognito" mode is recommended.
Login and authenticat (as necessary).

1. Under _Interactive Servers_, choose _BYOE Jupyter Server__
1. Select:
   - Jupyter Interface: JupyterLab
   - Conda environment type: "Use custom text field"
   - Environment Setup: `source /storage/group/RISE/classroom/astro_528/scripts/env_setup`
   - Node type: Standard Cores
   - Account: "ebf11-fa23" (for most labs), "ebf11-fa23_p_gpu" (for labs/project using a GPU) 
   - partition: "SLA Prio"
   - Number of hours: 3  (can choose longer if you plan to continue after class or outside of class)
   - Number of cores: 4
   - Memory per core: 4 GB
1. Click _Launch_
   (Wait while your job starts.)
1. Once the _Connect to JupyterLab Server_ button appears, click it.
   + The top row of tiles (labeled "Notebook") should include a tile labeled "Pluto.jl".  Click it.  
   + A new browser tab should open with a Pluto session.
   + The first time you open Pluto it will take a few minutes and is likely to time out.  Just wait a few minutes and try again.  (Behind the scenes, it's installing a lot of packages.)
   + Open a Pluto notebook
       - For a blank notebook, click "new notebook"
       - To open an existing notebook, or enter the path to the notebook in the text box under "Open from file" and click the "Open" button.   (I find using tab completion is very helpful.) 
   + Do your work in the Pluto notebook.
   + Remembering to save your notebook before you quit.
1. See [Starting & Submitting Assignments](/tips/labs/) for more information on accessing and submitting assignments.
1. When you're done, close notebook tabs and click logout in upper right (of the Jupyter server session).
1. Go back to the "My Interactive Sessions" tab in the Roar Collab Portal, click "Delete" for this Sessions and confirm.
