# Cpu_Scheduling_Algo
1. Banker's Algorithm
Purpose: Used for deadlock avoidance in operating systems.
How it works: The Banker's algorithm ensures that resources are allocated safely, checking if the current request can be satisfied without leading to a deadlock. It does so by simulating the allocation of resources, testing for a "safe state" where all processes can finish eventually.
2. Best Fit (Memory Allocation)
Purpose: Used in memory management to allocate memory blocks.
How it works: When a process requests memory, the system searches the free memory list for the smallest block that is big enough to satisfy the request, thus minimizing wasted space.
3. First Come First Serve (FCFS)
Purpose: A CPU scheduling algorithm.
How it works: Processes are executed in the order of their arrival. The process that arrives first is executed first, regardless of its size or required time. It’s simple but can lead to the convoy effect where short processes wait for long ones to finish.
4. First Fit (Memory Allocation)
Purpose: A memory allocation strategy.
How it works: The system scans from the start of the free memory list and allocates the first block that is large enough for the requested memory. It's faster than Best Fit but can lead to external fragmentation.
5. Priority Scheduling
Purpose: CPU scheduling algorithm.
How it works: Each process is assigned a priority, and the CPU is allocated to the process with the highest priority. If two processes have the same priority, FCFS is used. It can be preemptive or non-preemptive. It may cause starvation, where low-priority processes might never get executed.
6. Round Robin (RR)
Purpose: A preemptive CPU scheduling algorithm.
How it works: Each process is given a small unit of CPU time, called a time quantum. After the quantum expires, the process is moved to the back of the queue, and the next process is executed. This continues in a circular manner, giving the impression of parallel execution. It’s widely used in time-sharing systems.
7. Shortest Job First (SJF)
Purpose: A CPU scheduling algorithm.
How it works: The process with the shortest execution time (or burst time) is selected next for execution. This can be preemptive (Shortest Remaining Time First) or non-preemptive. It can minimize the average waiting time but requires knowledge of execution times, which is often not known in advance. It also suffers from starvation of longer processes.
Each of these algorithms is designed for specific scenarios, balancing factors like throughput, response time, and resource utilization in computing systems.
