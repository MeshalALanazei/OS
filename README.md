1.	Introduction
It is required in this project, to write a program in Java that simulates the behavior of the multiprogramming operating system. At the end of the simulation, you are expected tooutput some statistics regarding the behavior of the system. In the following sections, we will introduce the hardware specification.

2.	Specification
Hardware: The computer hardware is assumed to have:

A RAM of size 192MB, where 32MB is used to store the OS.
A single core CPU that executes one instruction each unit of time.
An I/O device for input and output operations.
An internal clock that allows to measure time in milliseconds.
3.	Assumptions:
First memory requirement of each process should be positive.
The Counter "Time" is used as our time unit, so each increment is considered as a millisecond.  
