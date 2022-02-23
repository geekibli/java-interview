## Java并发


1. 创建线程的几种方式？
2. 如何启动线程？
3. start方法和run方法的区别？
4. 什么是守护线程？ 如何定义守护线程？
5. 请讲一下sleep方法？
6. sleep方法会释放锁吗？ 静态
7. yield方法有什么作用？是否会释放锁？ 静态
8. 请说一下中断机制？ 
9. 讲一下和中断相关的几个方法？
10. 线程的生命周期？以及状态之间的扭转是怎样的？
11. Executor的shutdownNow方法是如何实现的？ 调用每个线程的中断方法
12. 如何中断Executor中的一个线程？
13. java中的同步机制有哪些？ jvm实现的synchronized 和 jdk实现的 ReentrentLock
14. synchronized如何使用？
15. jvm实现的synchronized底层原理是什么？
16. synchronized如何实现同步？ monitor 和 队列 `**_WaitSet 和 _EntryList`
17. 什么是Monitor监视器锁？ 每个对象都有一个对应的monitor
18. synchronized能否保证原子操作？ 可以 
19. synchronized能否禁止指令重排序？ 不能
20. 讲一下锁升级的详细过程？
21. 为什么jdk6之后对锁升级进行了优化，添加偏向锁和轻量级锁？ 因为重量级锁设计OS互斥量Mutex lock 用户态和内核态切换
22. 锁升级过程是否可逆？
23. 为什么需要自旋锁？
24. 什么是可重入锁？
25. 什么是自适应锁?
26. 什么是ReentrentLock？ 有几种模式？
27. 怎么体现公平锁与非公平锁特性？
28. AQS是如何保证线程安全的？ cas
29. 讲一下什么是AQS？
30. AQS如何实现排他锁和共享锁？
31. AQS如何实现可重入锁特性？
32. jvm实现的synchronized VS jdk实现的 ReentrentLock
33. 讲一下join方法？底层是如何实现的？
34. 如果使用3个线程循环顺序打印ABC？
35. 如何使用3个线程顺序打印0～100
36. 说一下wait() notify() notifyAll()的作用？
37. wait方法的底层原理是什么？如何使用？ 必须在同步块中使用？
38. 如何使用wait 和 notify方法实现生产者和消费者
39. **如果使用ReentrentLock加锁之后，调用wait方法会怎样？**
40. sleep方法和wait方法的区别？
41. Condition的await VS Object的wait
42. 讲一下CountDownLatch是什么？ 如何使用 ？
43. 简述CountDownLatch的实现逻辑?
44. CountDownLatch的使用场景？
45. 讲一下CyclicBarrier是什么？ 
46. CyclicBarrier的使用场景以及如何使用？
47. CountDownLatch VS CyclicBarrier 
48. Semaphore 的作用是什么？ 如何实现的？
49. Semaphore 如何使用？
50. 讲一下FutureTask是什么？ FutureTask 可用于异步获取执行结果或取消执行任务的场景
51. 什么是BlockingQueue？ 创建的BlockingQueue有哪些？
52. 为什么Alibaba 开发规范中禁止使用Executors创建线程池？
53. BlockingQueue 哪些使用场景？
54. BlockingQueue 有哪些特性？ 阻塞
55. ForkJoin 有是什么？
56. ForkJoinPool 实现原理 ？ 工作窃取算法
57. volatile 关键字的作用？ 能否修饰局部变量？
58. volatile如何实现可见性？
59. 请手写一个DCL的单例模式 如果不用volatile修饰会怎样
60. 什么是JMM？
61. 什么是MESI协议？
62. MESI 数据失效之后，怎么读正确的数据呢？ store buffer
63. 内存交互之间的8种指令？
64. JMM的3大特性 原子  可见 有序
65. i++是不是原子操作？
66. i++ 如何保证正确性？  同步 JUC Atomic类
67. AtomicLong VS LongAdder
68. **LongAdder 实现原理**
69. 可见性的3种实现方式 ？ volatile synchronized final
70. 请讲一下final的内存语义？
71. 有序性是什么？ 如何保证有序性？
72. 指令重排序有几种类型？
73. 指令重拍的目的是什么？  涉及指令寄存器和CPU计算单元ALU ， 主要提升计算速度
74. 什么是内存屏障？ 有几种类型的屏障？
75. 什么是happens-before原则？
76. happens-before规定的8项规则？
77. 什么是管程锁定规则？ 一个 unlock 操作先行发生于后面对同一个锁的 lock 操作
78. 什么是CAS ，CAS底层原理？ 汇编指令
79. ABA问题如何解决？
80. 什么是ThreadLocal？ ThreadLocal如何实现？
81. jvm对synchronized的锁优化都有哪些？
82. 说一下什么是锁膨胀
83. 什么是锁消除？ 逃逸分析 局部变量 
84. 什么是逃逸分析？ 可以做什么？
85. synchronized锁标志是如何存储的？ 对象头markword   LockRecord
86. 锁对象hashCode在各种状态下都存放在那里？
87. 偏向锁的使用场景？ 只有一个线程竞争锁
88. 偏向锁是如何获取的？ 直接判断线程不需要cas
89. 多线程开发的注意点有哪些？


## 并发资料
- [CS-Notes Github java并发](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%B9%B6%E5%8F%91.md)
- [个人博客：并发中的一些问题](https://geekibli.github.io/wiki/%E5%B9%B6%E5%8F%91%E4%B8%AD%E7%9A%84%E4%B8%80%E4%BA%9B%E9%97%AE%E9%A2%98/)