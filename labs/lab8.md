+++
title = "Lab 8: GPU Accelerators"
course_inst = "Penn State"
course_number = "Astro 528"
course_name = "High-Performance Scientific Computing for Astrophysics"
weight = 0308  #03nn

chapter= false

creatordisplayname = "Eric Ford"
creatoremail = "ebf11 at psu dot edu"
lastmodifierdisplayname = "Eric Ford"
lastmodifieremail = "ebf11 at psu dot edu"
tags = ["labs",]
+++

#### Warning
For this lab, you will need access to a CUDA-enabled GPU **before** you can run any GPU code.
To request access to a GPU for your entire JupyterLab session, 
from the Lynx portal, go to the HPC for Astro Jupyter App page where you normally create your JupyterLab session, but **click "Enable advanced Slurm options" and then type --gres=gpu:1 in the Sbatch options before clicking launch**. 
This should allow you to interactively run commands on the GPU. The downside of this option is that it blocks others from accessing "your" GPU until you close your session, even though you're likely not using the GPU most of the time.
If all the GPUs allocated to our class are in use, then you may get started by viewing the html versions of the lab.

\textinput{labs/lab8}
