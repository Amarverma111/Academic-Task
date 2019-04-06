# Academic-Task
This is assignment of operting system on which we  will finding the  FCFS(first come first serve) and SJF (Shortest job first).



6.Suppose that the following processes arrive for execution at the times indicated. Each process will run for the amount of time listed. In answering the questions, use nonpreemptive scheduling, and base all decisions on the information you have at the time the decision must be made.
___________________________________________
|  process  |  Arrival Time |   Burst Time |
|   p1      |    0.0        |     8        |
|   p2      |    0.4        |     4        | 
|   p3      |    1.0        |     1        | 
|__________________________________________|
a. What is the average turnaround time for these processes with the FCFS scheduling algorithm?
b. What is the average turnaround time for these processes with the SJF scheduling algorithm?
c. Compute what average turnaround time will be if the CPU is left idle for the first 1 unit and then SJF scheduling is used. Remember that processes P1 and P2 are waiting during this idle time, so their waiting time may increase.

Solution-

a. FCFS Gantt chart 
   FCFS is a first come first serve
___________________________________________
|  process  |  Arrival Time |   Burst Time |
|   p1      |    0.0        |     8        |
|   p2      |    0.4        |     4        | 
|   p3      |    1.0        |     1        | 
|__________________________________________|
    
    process :  _____________________
              |__P1__|__P2__|__P3__|
      Time  : 0      8      12     13
      
      Now Find turnaround Time=?
      
      Turnaround Time=completion time - Arrival Time
                 Now we finding the Trunaround time for p1,p2 and p3.
                 so,
                 p1= 8  - 0.0 =8 
                 p2= 12 - 0.4 =11.6
                 p3= 13 - 1.0 =12
                 
     Now,Average Turnaroundtime=total/nno.of process
                                31.6/3=10.53

b.SJF
Shortest job first
 ___________________________________________
|  process  |  Arrival Time |   Burst Time |
|   p1      |    0.0        |     8        |
|   p2      |    0.4        |     4        | 
|   p3      |    1.0        |     1        | 
|__________________________________________|
    
      
    process :  _____________________
              |__P1__|__P3__|__P2__|
      Time  : 0      8      9     13
    

Now Find turnaround Time=?
      
      Turnaround Time=completion time - Arrival Time
                 Now we finding the Trunaround time for p1,p2 and p3.
                 so,
                 p1= 8  - 0     =8
                 p2= 13 - 0.4   =12.6
                 p3= 9  - 1.0   =8                
     Now,Average Turnaroundtime=total/nno.of process
                                28.6/3=9.53
c.     

___________________________________________
|  process  |  Arrival Time |   Burst Time |
|   p1      |    0.0        |     8        |
|   p2      |    0.4        |     4        | 
|   p3      |    1.0        |     1        | 
|__________________________________________|
    
       
    process :  __________________________
              |__X__|__P3__|__P2__|__P1__|
      Time  : 0     1      2      6     14
    

Now Find turnaround Time=?
      
      Turnaround Time=completion time - Arrival Time
                 Now we finding the Trunaround time for p1,p2 and p3.
                 so,
                 p1= 14 - 0     =14
                 p2= 6 -  0.4   =5.6
                 p3= 2  - 1.0   =1                
     Now,Average Turnaroundtime=total/nno.of process
                                20.6/3=6.86
    
    
    
    
