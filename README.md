# OSexperiment
## 操作系统课程设计
### 题目要求
基于信号量与P/V操作同步机制的读者/写者问题的设计与实现 

功能要求
(1)设置读者、写者个数输入（界面）；实现读者、写者进程的动态创建；

(2)用信号量与P/V操作同步机制实现写者优先的读者/写者问题。

(3)设计并实现运行结果（界面）包括：

动态显示多个读者或一个写者的读/写操作互斥状态：

显示正在进行读或写操作的进程，以及等待读或写操作的进程；

动态显示写者优先的过程： 
    
    即当有读者进程在读时，有写者进程要求写操作，后续的读者进程应该等待；并且当读操作的读者进程结束读操作后，等待的写者进程应能立即进行写操作。设计相应的等待队列 
实现

（1）在原来用信号量与P/V操作实现的读者/写者问题解决方法基础上进行修改，反应写者优先的原则；

（2）进行读/写操作的进程可通过随机延时的方式来模拟读/写操作的时间过程。
