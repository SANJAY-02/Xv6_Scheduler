# Xv6_Scheduler
     Xv6 operating system provides a very basic set of
limited system calls and have a scheduling algorithm which is
not suitable for real time operating systems. Users can use only
those limited system calls and also the scheduling algorithm
which schedules the CPU is not efficient enough. Every user
will definitely want an efficient scheduler for processing, but
definitely not the default scheduler in Xv6. The default scheduling
algorithm is Round Robin in Xv6 which has high response time,
high average waiting time, high turnaround time, more context
switches and also low throughput. The following drawbacks make
Round Robin an inefficient algorithm. To overcome these effects
priority scheduling algorithm can be implemented, but priority
itself has starvation drawback. Addition of some useful system
calls enables us to implement our proposed algorithm efficiently.
The proposed algorithm overcomes the drawbacks of both round
robin and priority and also inherits their advantages.

