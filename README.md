# TivaCLibrary

A collection of various libraries I've written for the Texas Instruments Tiva C TM4C123G microcontroller. Use/modify however you would like, I will be trying to add example main.c on how to use each of them.

Currently included libraries and their functions
/ser - Serial Communcication
- Library for handling the sending/receiving of messages over UART. Allows you to ignore received LF/CR as well as remove them from send messages (especially important since CCS terminal doesn't have carriage returns)

/sch - Scheduler
- Super basic scheduler for that can act as a real-time operating system. Tasks are added to the scheduler which will handle their initialization/execution based on 1) Time, 2) Function returning a _Bool or 3) a pointer to a _Bool


Planned libraries/Possible future additions
/pid - PID Controller
- For PID control of DC motors
