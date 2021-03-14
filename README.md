# OS
operating system project one By Yaqout Hmaid 

Grade : 96/100 

semester : fall 2020 

instructor : ALI jaber

--------------- project one description --------------- 

The project is a simulation for some of the CPU scheduling algorithms and making a comparison between them.

Write a program that does the following:

1- Simulates the scheduling algorithms FCFS, SJF, RR, Priority, Multilevel Feedback Queues.

2- Create 8 processes in the ready queue with a random CPU-burst for each process between 10 & 999 units of time. You should use a suitable data structure for each process representing the PCB which may contain the data you feel you need it in your program.

3- When creating the processes, assign some kind of order for their arrival time and priority .

4- For RR, use a slice time (quantum, Q = 40units). k 
5- In multilevel feedback Queue, consider 3 queues, Q1: RR with 40 units Q2: RR with 400 units. Q3: FCFS

6- For each of the scheduling algorithms above, you should compute the average turnaround time (ATT) and average waiting time (AWT).

7- Repeat steps (2) to (6) for 100 times, 1000 times, 10000 times, and 100000 times.

8- Create a table summarizing your results showing ATT & AWT for all cases



--------------- project two description --------------- 

	The project simulates the memory management technique, "Multiple Partitions - Fixed Regions", known in IBM machines as MFT (Multiprogramming with Fixed number of Tasks).


	Write a program which simulates the function and behavior of MFT memory management Technique.

	Consider a memory of size 1 GB =1000 MB, 200 MB is allocated for the OS, leaving 800 MB for execution area.

	The execution area is partitioned into 4 regions as follows:


Partition	Size
1	20MB
2	80MB
3	200MB
4	500MB

That is, the degree of multiprogramming is 4.

	Initially, create 4 jobs in the ready queue, each with size fits one of the regions, and a time limit the job will stay in memory. Use a random function to crate these jobs.

	Create a job queue which contains 6 jobs randomly, each job will be associated with its size in MBs, and the time requires to stay in memory. Jobs must be size  500MB, and the time limit must be reasonable.

	When a job finishes execution, a new job is selected from the job queue on FCFS with Skip and admitted to the ready queue if there is a job that fits the free region, at the same time a replacement job is created randomly & added to the job queue, if no such job exists, the processor continues execution with another job leaving only 3 jobs in the ready queue temporarily and so on and so forth.

