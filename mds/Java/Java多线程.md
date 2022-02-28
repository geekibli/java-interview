## Java并发


1. 什么是线程？
2. [什么是进程？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%95%E4%B8%BA%E8%BF%9B%E7%A8%8B)
3. 创建线程的几种方式？
4. 如何启动线程？
5. start方法和run方法的区别？
6. 什么是守护线程？ 如何定义守护线程？
7. 请讲一下sleep方法？
8. sleep方法会释放锁吗？ 静态
9. yield方法有什么作用？是否会释放锁？ 静态
10. 请说一下中断机制？ 
11. 讲一下和中断相关的几个方法？
12. 线程的生命周期？以及状态之间的扭转是怎样的？
13. Executor的shutdownNow方法是如何实现的？ 调用每个线程的中断方法
14. 如何中断Executor中的一个线程？
15. java中的同步机制有哪些？ jvm实现的synchronized 和 jdk实现的 ReentrentLock
16. synchronized如何使用？
17. jvm实现的synchronized底层原理是什么？
18. synchronized如何实现同步？ monitor 和 队列 `**_WaitSet 和 _EntryList`
19. 什么是Monitor监视器锁？ 每个对象都有一个对应的monitor
20. synchronized能否保证原子操作？ 可以 
21. synchronized能否禁止指令重排序？ 不能
22. 讲一下锁升级的详细过程？
23. 为什么jdk6之后对锁升级进行了优化，添加偏向锁和轻量级锁？ 因为重量级锁设计OS互斥量Mutex lock 用户态和内核态切换
24. 锁升级过程是否可逆？
25. 为什么需要自旋锁？
26. 什么是可重入锁？
27. 什么是自适应锁?
28. 什么是ReentrentLock？ 有几种模式？
29. 怎么体现公平锁与非公平锁特性？
30. AQS是如何保证线程安全的？ cas
31. 讲一下什么是AQS？
32. AQS如何实现排他锁和共享锁？
33. AQS如何实现可重入锁特性？
34. jvm实现的synchronized VS jdk实现的 ReentrentLock
35. 讲一下join方法？底层是如何实现的？
36. 如果使用3个线程循环顺序打印ABC？
37. 如何使用3个线程顺序打印0～100
38. 说一下wait() notify() notifyAll()的作用？
39. wait方法的底层原理是什么？如何使用？ 必须在同步块中使用？
40. 如何使用wait 和 notify方法实现生产者和消费者
41. **如果使用ReentrentLock加锁之后，调用wait方法会怎样？**
42. sleep方法和wait方法的区别？
43. Condition的await VS Object的wait
44. 讲一下CountDownLatch是什么？ 如何使用 ？
45. 简述CountDownLatch的实现逻辑?
46. CountDownLatch的使用场景？
47. 讲一下CyclicBarrier是什么？ 
48. CyclicBarrier的使用场景以及如何使用？
49. CountDownLatch VS CyclicBarrier 
50. Semaphore 的作用是什么？ 如何实现的？
51. Semaphore 如何使用？
52. 讲一下FutureTask是什么？ FutureTask 可用于异步获取执行结果或取消执行任务的场景
53. 什么是BlockingQueue？ 创建的BlockingQueue有哪些？
54. 为什么Alibaba 开发规范中禁止使用Executors创建线程池？
55. BlockingQueue 哪些使用场景？
56. BlockingQueue 有哪些特性？ 阻塞
57. ForkJoin 有是什么？
58. ForkJoinPool 实现原理 ？ 工作窃取算法
59. volatile 关键字的作用？ 能否修饰局部变量？
60. volatile如何实现可见性？
61. 请手写一个DCL的单例模式 如果不用volatile修饰会怎样
62. 什么是JMM？
63. 什么是MESI协议？
64. MESI 数据失效之后，怎么读正确的数据呢？ store buffer
65. 内存交互之间的8种指令？
66. JMM的3大特性 原子  可见 有序
67. i++是不是原子操作？
68. i++ 如何保证正确性？  同步 JUC Atomic类
69. AtomicLong VS LongAdder
70. **LongAdder 实现原理**
71. 可见性的3种实现方式 ？ volatile synchronized final
72. 请讲一下final的内存语义？
73. 有序性是什么？ 如何保证有序性？
74. 指令重排序有几种类型？
75. 指令重拍的目的是什么？  涉及指令寄存器和CPU计算单元ALU ， 主要提升计算速度
76. 什么是内存屏障？ 有几种类型的屏障？
77. 什么是happens-before原则？
78. happens-before规定的8项规则？
79. 什么是管程锁定规则？ 一个 unlock 操作先行发生于后面对同一个锁的 lock 操作
80. 什么是CAS ，CAS底层原理？ 汇编指令
81. ABA问题如何解决？
82. 什么是ThreadLocal？ ThreadLocal如何实现？
83. jvm对synchronized的锁优化都有哪些？
84. 说一下什么是锁膨胀
85. 什么是锁消除？ 逃逸分析 局部变量 
86. 什么是逃逸分析？ 可以做什么？
87. synchronized锁标志是如何存储的？ 对象头markword   LockRecord
88. 锁对象hashCode在各种状态下都存放在那里？
89. 偏向锁的使用场景？ 只有一个线程竞争锁
90. 偏向锁是如何获取的？ 直接判断线程不需要cas
91. 多线程开发的注意点有哪些？


## 并发资料
- [CS-Notes Github java并发](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%B9%B6%E5%8F%91.md)
- [个人博客：并发中的一些问题](https://geekibli.github.io/wiki/%E5%B9%B6%E5%8F%91%E4%B8%AD%E7%9A%84%E4%B8%80%E4%BA%9B%E9%97%AE%E9%A2%98/)