+++
title = "Class Project"
course_inst = "Penn State"
course_number = "Astro 528"
course_name = "High-Performance Scientific Computing for Astrophysics"
weight = 590

creatordisplayname = "Eric Ford"
creatoremail = "ebf11 at psu dot edu"
lastmodifierdisplayname = "Eric Ford"
lastmodifieremail = "ebf11 at psu dot edu"
tags = ["project",]
+++

# Class Project
The class project consists of several parts, each of which has its own submission deadline listed below.  It is particularly important that you provide code for peer review on time, so that your peer reviewer is able to provide thoughtful and helpful feedback in time for it to improve your code for the latter parts of the project.  The project grade will be based on:

## Project Components
- Project Proposal (5 points) 
- Checkpoint 1: Serial version of code (10 points)
- Checkpoint 2: Multi-core version of code (10 points)
- Peer code reviews (5 points)
- Distributed-memory/GPU/Cloud version of code (10 points)
- Final Submission (5 points)
- Project Presentation (5 points)

## Instructions & Grading Rubrics for each step

### Project Proposal (due {{project_proposal_due}})
Use the link provided via course announcement or Canvas to create your repository for the project proposal.

#### Rubric
\textinput{rubrics/project_proposal}

### Serial version of code (due {{project_serial_due}})
At this point the code does not need to be optimized.
If possible, try to include the results of benchmarking and/or profiling in the README, to help both you and the reviewer identify which sections are ammenable to optimization.

#### Rubric
\textinput{rubrics/project_serial}

### Peer Code Reviews (due {{project_codereview_due}})
#### Instructions
- [How to prepare your code for review](code_reviews/prep)
- [How to perform a code review](code_reviews/how_to)
- [How to follow-up on code review](code_reviews/follow_up)
For more information, see [instructions for code review](code_reviews).

#### Rubric
\textinput{rubrics/code_review}


### First parallel version of code (due {{project_parallel1_due}})
Typically, the first parallel version runs on multiple cores using a shared memory system.
#### Rubric
\textinput{rubrics/project_parallel1}

### Submit second parallel version of code (due {{project_parallel2_due}})
Typically, the second parallel version of the code is parallelized using one of: multiple cores with distributed-memory or a GPU.  Other alternatives include using Intel Phis, TPUs, or a cloud environment like AWS, JuliaHub or Open Science Grid.
#### Rubric
\textinput{rubrics/project_parallel2}

### Completed Project  (due {{project_final_due}})
Completed project code with documetation, benchmarking results and summary of lessons learned.  
#### Rubric
\textinput{rubrics/project_final}

### Project Presentation (due {{project_presentation_due}})
[Schedule of Student Presentations](https://github.com/PsuAstro528/PresentationsSchedule2023/blob/master/README.md)
#### Rubric
\textinput{rubrics/project_presentation}
