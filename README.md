#### 采用QT进行可视化，设计了一个抢占式优先权调度算法实现多处理机调度的程序，并且实现在可变分区管理方式下，采用首次适应算法实现主存空间的分配和回收。


（1）PCB内容包括：进程名/PID；要求运行时间（单位时间）；优先权；状态；进程属性：独立进程、同步进程（前趋、后继）。 


（2）可以随机输入若干进程，可随时添加进程，并按优先权排序；。


（3）采用QT可视化，利用定时器模拟处理机调度，可以显示处理机状态和内存分配状态。


（4）考虑两个处理机，考虑同步进程的处理机分配问题，每次调度后，显示各进程状态，运行进程要显示在哪个处理机上执行。 
