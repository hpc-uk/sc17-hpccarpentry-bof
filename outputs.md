---
---

# BoF group activity analysis

This document contains the analysed results from the group activities at the HPC Carpentry BoF at SC17.

* Actitivity 1: Groups were asked to brainstorm the characteristics of a potential learner on an
  HPC Carpentry course. (The precise level and content of the course was not specified but there
  was an implicit assumption running through the session that it was *introductory level* in some
  way.)

* Activity 2: Given a learner profile of a new graduate student in the biosciences who wants to potentially
  use HPC to help improve their research; the group was asked to specify what subjects should be
  covered in an HPC Carpentry course.

## Learner Profile

### Most important characteristics

Three groups produced sets of what they considered the most important characteristics of learners. Analysing
these sets leads to 4 main characteristics of a potential learner:

* Vague idea of what HPC is but not sure how this translates to their research.
* Lack of experience with Linux, command line, text editors, batch systems etc. i.e. the working environment is foreign to me.
* Lack of knowledge about what HPC systems are: how are they put together, how do they enable faster/larger calculations and how
  are resources shared?
* Want to know how to support themselves when things don't work and keen to learn more.

### Grouped charateristics

Analysing the feedback from the groups, there were a number of common charateristic groupings:

* I do not have the basic technical skills to use HPC
  + G2: Don’t know LINUX, may know Windows
  + G2: Thinks a computer is a box under a desk or a laptop
  + G2: May be most comfortable with GUI
  + G2: No familiarity with command line
  + G3: I am unsure what the terminal is, how it works, etc
  + G3: I do not know what version control is
  + G3: I am a student and I do not know how to get access to the remote system I have been granted
  + G4: I don't know Linux but HPC systems are typically running Linux
  + G4: I don't know how to create and edit code
  + G4: Comfort with command line environment in a linux environment.
  + G4: Bash.
  + G4: I prefer graphical or web-based interfaces.  
  + G5: I’ve never used a command line.
  + G5: I’ve never used a compiler.

* I am not sure how HPC can help my research?
  + G1: Why do I care?  
  + G2: New graduate student in sciences/engineering
  + G2: Are only using HPC because their Advising professor told them to
  + G2: Biologists becoming bioinformaticians
  + G2: Usually stuck or bogged down due to limitation of current machine/resources
  + G4: Do I have a use for HPC?

* Just give me what I need to get on with my research on HPC
  + G1: I just want to do my science
  + G1: I want it to be interactive
  + G1: Just show me what I need to do to get my results
  + G3: I have a code with a new dataset that’s too big to fit in memory/needs multiple cores now
  + G4: My supervisor wants me to run his favourite modelling code. How do I do that?
  + G4: I know my science, I have code, how do I use this tool to accelerate my science?
  + G4: How can I run my analytics on the data from my instrument using the cluster?
  + G4: I have Malab code that is too slow now.  Can I speed it up or use something else easy to get results faster
  + G4: I want to try using a GPU for my problem.

* What is an HPC system anyway? How does it differ from the comupter I am already using? What about "the Cloud"?
  + G1: Why aren’t things just faster automatically?
  + G1: Is this the fastest it can get ?
  + G1: Why is running more slowly?
  + G1: Why does my program not run on multiple nodes? And what do I have to do to have it run on multiple nodes?
  + G1: How much processing power is overkill ?
  + G1: Users have little idea of the resource they need (memory / CPU) so for safety go for exclusive sessions everywhere
  + G2: Does not know what parallel programming models are, parallel vs. SMP models, multicore vs multinode
  + G2: Thinks performance is how fast they can run Doom 4
  + G2: Bases notions of storage cost on $200 8TB drives at Frys or Microcenter
  + G2: Expect programs to run magically faster on a cluster
  + G3: I do not understand the difference between a cluster, supercomputer, cloud, etc
  + G4: Overview of HPC technologies - eg what’s a GPU and what is it good for?
  + G4: Concepts of why we use HPC systems and what they are


* HPC and programming are awesome, but I do not know much, tell me more!
  + G1: I just want to learn the “cool” stuff
  + G1: I've never programmed, how do I make cool things?
  + G3: Signed up for Software carpentry but I know there are things that it won’t cover
  + G5: Already have Software Carpentry and now want to apply that to HPC.
  + G5: I’ve just started working on a complex software problem with no computer science skills. 

* How do I get help and/or help my self when I get stuck?
  + G1: Why does it take so long to get things done? (software installation assistance; head node compiling/bottleneck; single core desktop vs single core HPC)

* I feel unsure and out of my depth with HPC
  + G1: My novice HPC user is intimidated by HPC 
  + G2: Researcher in soft/social sciences, scared by the thought of programming/scripting...
  + G2: ...but, brave enough to show up to an HPC Carpentry session
  + G4: I don’t have mentor with HPC experience (pioneer in group)

* I do not understand the shared nature of HPC systems
  + G1: What is a scheduler and why do I need to use it?
  + G1: Why can’t I have root or administrator privileges
  + G1: Why do I have to wait
  + G1: Obviously I can run on the login node.
  + G1: Novice users don’t understand that resources are competed for with the other users\
  + G2: Multi-user system is foreign to them
  + G3: I don’t know how to use my system scheduler
  + G4: Understanding of job submission in batch environment.

* I am experienced technically, what do I need to know about HPC?
  + G1: How to debug my program on multi threads ?
  + G1: I've been programming for years, just run me through the basics.
  + G2: Somewhat comfortable, but need help with optimization 
  + G3: I do not know how the linker works, I don’t understand why my dependencies are linking to different shared libraries, and what that means
  + G3: I am trying to use a profiler for the first time with MPI code and I don’t understand what normal MPI behavior is
  + G5: Informal education in programming (self taught)
  + G5: Lacks knowledge or experience of exploiting parallelism.
  + G5: I lack knowledge of optimisation or low level performance.

* Broad range of expertsie and experience among researchers
  + G2: Broad spectrum -- some quite good programmers, just not familiar with HPC
  + G2: All are good scientists in their own field with computing or data needs
  + G4: Generally have a science background, but not programming or comp.sci. Have taken 1 or 2 basic programming courses.
  + G4: Have run my apps on my laptop, but now want to go to the next level.

## Course and module design




