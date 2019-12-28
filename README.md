# Pintos_Proj1_Linux

1 Overview
This is my course project from the course of Operation System Laboratory. Pintos is a simple operating system framework for 80x86 architecture. It supports kernel threads, loading and running user programs, and a file system, but is implements all of these in a very simple way. In this project, I only complete the part of the optimization of kernel threads. For more details, please visit: http://www.stanford.edu/class/cs140/projects/pintos/pintos.html#SEC_Top.

2 Introduction
I have mainly solved four problems:
* lab1: I solve the problem of busy waiting by removing dormant thread from ready list and performing system interruption 
        regularly to determine whether awakening it so as to improve the CPU utilization. 
* lab2: I implement priority preemption scheduling using sorting algorithms in order to improve the real-time response of the   
        system. 
* lab3: I solve the problem of priority inversion to prevent the system from disordering. 
* lab4: I realize multilevel feedback queue scheduling to prevent the thread starvation. 

3 Getting Started
To start this project, please see the document "installation_document.pdf".
