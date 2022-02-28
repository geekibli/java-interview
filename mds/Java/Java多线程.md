## Java并发


1. [什么是线程？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%95%E4%B8%BA%E7%BA%BF%E7%A8%8B)
2. [什么是进程？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%95%E4%B8%BA%E8%BF%9B%E7%A8%8B)
3. [说说并发与并行的区别?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E8%AF%B4%E8%AF%B4%E5%B9%B6%E5%8F%91%E4%B8%8E%E5%B9%B6%E8%A1%8C%E7%9A%84%E5%8C%BA%E5%88%AB)
4. [为什么要使用多线程呢?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E4%BD%BF%E7%94%A8%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%91%A2)
5. [使用多线程可能带来什么问题?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%BF%E7%94%A8%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%8F%AF%E8%83%BD%E5%B8%A6%E6%9D%A5%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98)
6. [什么是上下文切换](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BB%80%E4%B9%88%E6%98%AF%E4%B8%8A%E4%B8%8B%E6%96%87%E5%88%87%E6%8D%A2)
7. 创建线程的几种方式？
8. [如何启动线程？start方法和run方法的区别？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E8%B0%83%E7%94%A8-start-%E6%96%B9%E6%B3%95%E6%97%B6%E4%BC%9A%E6%89%A7%E8%A1%8C-run-%E6%96%B9%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E4%B8%8D%E8%83%BD%E7%9B%B4%E6%8E%A5%E8%B0%83%E7%94%A8-run-%E6%96%B9%E6%B3%95)
9.  什么是守护线程？ 如何定义守护线程？
10. 请讲一下sleep方法？
11. sleep方法会释放锁吗？ 静态
12. yield方法有什么作用？是否会释放锁？ 静态····
13. [说说 sleep() 方法和 wait() 方法区别和共同点?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E8%AF%B4%E8%AF%B4-sleep-%E6%96%B9%E6%B3%95%E5%92%8C-wait-%E6%96%B9%E6%B3%95%E5%8C%BA%E5%88%AB%E5%92%8C%E5%85%B1%E5%90%8C%E7%82%B9)
14. 请说一下中断机制？ 
15. 讲一下和中断相关的几个方法？
16. 进程的生命周期
17. [线程的生命周期？以及状态之间的扭转是怎样的?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E8%AF%B4%E8%AF%B4%E7%BA%BF%E7%A8%8B%E7%9A%84%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%E5%92%8C%E7%8A%B6%E6%80%81)
18. Executor的shutdownNow方法是如何实现的？ 调用每个线程的中断方法·～
19. 如何中断Executor中的一个线程？
20. java中的同步机制有哪些？ jvm实现的synchronized 和 jdk实现的 ReentrentLock
21. [synchronized如何使用？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#12-%E8%AF%B4%E8%AF%B4%E8%87%AA%E5%B7%B1%E6%98%AF%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97)
22. [构造方法可以使用 synchronized 关键字修饰么](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#13-%E6%9E%84%E9%80%A0%E6%96%B9%E6%B3%95%E5%8F%AF%E4%BB%A5%E4%BD%BF%E7%94%A8-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97%E4%BF%AE%E9%A5%B0%E4%B9%88)
23. [synchronized底层原理是什么？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#13-%E8%AE%B2%E4%B8%80%E4%B8%8B-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E5%BA%95%E5%B1%82%E5%8E%9F%E7%90%86) [小米](https://xiaomi-info.github.io/2020/03/24/synchronized/)
24. synchronized如何实现同步？ monitor 和 队列 `**_WaitSet 和 _EntryList`
25. 什么是Monitor监视器锁？ 每个对象都有一个对应的monitor
26. synchronized能否保证原子操作？ 可以 
27. synchronized能否禁止指令重排序？ 不能
28. 讲一下锁升级的详细过程？
29. 为什么jdk6之后对锁升级进行了优化，添加偏向锁和轻量级锁？ 因为重量级锁设计OS互斥量Mutex lock 用户态和内核态切换
30. 锁升级过程是否可逆？
31. 为什么需要自旋锁？
32. 什么是可重入锁？
33. 什么是自适应锁?
34. 什么是ReentrentLock？ 有几种模式？
35. 怎么体现公平锁与非公平锁特性？
36. AQS是如何保证线程安全的？ cas
37. 讲一下什么是AQS？
38. AQS如何实现排他锁和共享锁？
39. AQS如何实现可重入锁特性？
40. jvm实现的synchronized VS jdk实现的 ReentrentLock
41. 讲一下join方法？底层是如何实现的？
42. 如果使用3个线程循环顺序打印ABC？
43. 如何使用3个线程顺序打印0～100
44. 说一下wait() notify() notifyAll()的作用？
45. wait方法的底层原理是什么？如何使用？ 必须在同步块中使用？
46. 如何使用wait 和 notify方法实现生产者和消费者
47. **如果使用ReentrentLock加锁之后，调用wait方法会怎样？**
48. sleep方法和wait方法的区别？
49. Condition的await VS Object的wait
50. 讲一下CountDownLatch是什么？ 如何使用 ？
51. 简述CountDownLatch的实现逻辑?
52. CountDownLatch的使用场景？
53. 讲一下CyclicBarrier是什么？ 
54. CyclicBarrier的使用场景以及如何使用？
55. CountDownLatch VS CyclicBarrier 
56. Semaphore 的作用是什么？ 如何实现的？
57. Semaphore 如何使用？
58. 讲一下FutureTask是什么？ FutureTask 可用于异步获取执行结果或取消执行任务的场景
59. 什么是BlockingQueue？ 创建的BlockingQueue有哪些？
60. 为什么Alibaba 开发规范中禁止使用Executors创建线程池？
61. BlockingQueue 哪些使用场景？
62. BlockingQueue 有哪些特性？ 阻塞
63. ForkJoin 有是什么？
64. ForkJoinPool 实现原理 ？ 工作窃取算法
65. volatile 关键字的作用？ 能否修饰局部变量？
66. volatile如何实现可见性？
67. 请手写一个DCL的单例模式 如果不用volatile修饰会怎样
68. 什么是JMM？
69. 什么是MESI协议？
70. MESI 数据失效之后，怎么读正确的数据呢？ store buffer
71. 内存交互之间的8种指令？
72. JMM的3大特性 原子  可见 有序
73. i++是不是原子操作？
74. i++ 如何保证正确性？  同步 JUC Atomic类
75. AtomicLong VS LongAdder
76. **LongAdder 实现原理**
77. 可见性的3种实现方式 ？ volatile synchronized final
78. 请讲一下final的内存语义？
79. 有序性是什么？ 如何保证有序性？
80. 指令重排序有几种类型？
81. 指令重拍的目的是什么？  涉及指令寄存器和CPU计算单元ALU ， 主要提升计算速度
82. 什么是内存屏障？ 有几种类型的屏障？
83. 什么是happens-before原则？
84. happens-before规定的8项规则？
85. 什么是管程锁定规则？ 一个 unlock 操作先行发生于后面对同一个锁的 lock 操作
86. 什么是CAS ，CAS底层原理？ 汇编指令
87. ABA问题如何解决？
88. 什么是ThreadLocal？ ThreadLocal如何实现？
89. jvm对synchronized的锁优化都有哪些？
90. 说一下什么是锁膨胀
91. 什么是锁消除？ 逃逸分析 局部变量 
92. 什么是逃逸分析？ 可以做什么？
93. synchronized锁标志是如何存储的？ 对象头markword   LockRecord
94. 锁对象hashCode在各种状态下都存放在那里？
95. 偏向锁的使用场景？ 只有一个线程竞争锁
96. 偏向锁是如何获取的？ 直接判断线程不需要cas
97. 多线程开发的注意点有哪些？
98. [什么是死锁，如何避免死锁](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BB%80%E4%B9%88%E6%98%AF%E7%BA%BF%E7%A8%8B%E6%AD%BB%E9%94%81%E5%A6%82%E4%BD%95%E9%81%BF%E5%85%8D%E6%AD%BB%E9%94%81)
99. 死锁产生的条件
100. 


## 并发资料
- [CS-Notes Github java并发](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%B9%B6%E5%8F%91.md)
- [个人博客：并发中的一些问题](https://geekibli.github.io/wiki/%E5%B9%B6%E5%8F%91%E4%B8%AD%E7%9A%84%E4%B8%80%E4%BA%9B%E9%97%AE%E9%A2%98/)