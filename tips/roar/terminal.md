## Finding a terminal on Lynx
There are three good options.
1. Using SSH from a terminal on your laptop
- You may need to connect to the Penn State VPN prior to this method working.
- ssh to Lynx cluster
```shell
ssh userid@feed.lynx.hpc.psu.edu
```
- Login.  
- Note that you'll likely have to complete 2 factor authentication again.
- Run script to setup the class environment 
```shell
source ~/hpc4astro/astro_528/scripts/env_setup
```

2. A terminal within the portal
  - Open [portal.lynx.hpc.psu.edu](https://portal.lynx.hpc.psu.edu/) in your browser's guest or incognito mode.
  - Log in with your Penn State credentials (and authenticate if necessary).
  - Select Clusters > Shell Access 
  - Note that you'll likely have to complete 2 factor authentication again.
  - Run script to setup the class environment 
```shell
source ~/hpc4astro/astro_528/scripts/env_setup
```

3. A terminal within JupyterLab
- Open [portal.lynx.hpc.psu.edu](https://portal.lynx.hpc.psu.edu/) in your browser's guest or incognito mode.
  - Log in with your Penn State credentials (and authenticate if necessary).
  - Request a Jupyter Lab session via the [Lynx portal](https://portal.lynx.hpc.psu.edu/) (see [starting Jupyter Lab & Pluto Servers](../../roar/jupyterlab/))
  - Click _Click to Connect to Jupyter_ button. Click it.
  - Go to the newly opened tab, you'll have a Jupyter Lab Server or a Pluto Server.
  - If you don't see tiles for Python, Julia and Pluto Notebooks, then click _File.NewLauncher_.
  - Find the _Terminal_ tile or in the menu system, _File.New.Terminal_.

