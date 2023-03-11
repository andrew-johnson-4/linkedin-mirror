# Round Robin Scheduling

Round-robin is a scheduling algorithm used to schedule processes or threads for execution in a time-sharing system. 
Each process is given a fixed time to execute before being pre-empted and moved to the end of the ready queue.

In round-robin scheduling, processes are arranged in a circular queue. The scheduler assigns a fixed time to each process in the queue. 
The first process is then executed for its allotted time. If it doesn't complete within that time, it is pre-empted and moved to the end of the queue. 
The next process in the queue is then executed for its allotted time, and the process continues until all processes have been executed.
