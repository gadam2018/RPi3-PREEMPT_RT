# RPi3-PREEMPT_RT
Latency measurements of RPi3 on default Raspbian Linux kernels and Raspbian Linux kernels with PREEMPT_RT patch

Software (master & slave) modules used to perform real-time performance test of Raspbian Linux (in a RPi), 
in a master-slave schema. 
The Raspberry device under test (slave) is connected to, and communicates with, another Raspberry (master) 
that performs the actual measurements. Measurements include the latency of response tasks in user and kernel space, 
the response at specific periodic rates on execution of periodic tasks in user and kernel space, 
the maximum sustained frequency.

Adam, G.K.; Petrellis, N.; Garani, G.; Stylianos, T. COTS-Based Architectural Framework for Reliable Real-Time Control Applications in Manufacturing. MDPI Applied Sciences 2020, 10, 3228. DOI: https://doi.org/10.3390/app10093228
