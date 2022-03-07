## Java并发


1. [什么是线程？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%95%E4%B8%BA%E7%BA%BF%E7%A8%8B)
2. [什么是进程？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%95%E4%B8%BA%E8%BF%9B%E7%A8%8B)
3. [说说并发与并行的区别?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E8%AF%B4%E8%AF%B4%E5%B9%B6%E5%8F%91%E4%B8%8E%E5%B9%B6%E8%A1%8C%E7%9A%84%E5%8C%BA%E5%88%AB)
4. [为什么要使用多线程呢?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E4%BD%BF%E7%94%A8%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%91%A2)
5. [使用多线程可能带来什么问题?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BD%BF%E7%94%A8%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%8F%AF%E8%83%BD%E5%B8%A6%E6%9D%A5%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98)
6. [什么是上下文切换](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BB%80%E4%B9%88%E6%98%AF%E4%B8%8A%E4%B8%8B%E6%96%87%E5%88%87%E6%8D%A2)
7. [CPU 缓存模型](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#21-cpu-%E7%BC%93%E5%AD%98%E6%A8%A1%E5%9E%8B)
8. 创建线程的几种方式？
9. [实现 Runnable 接口和 Callable 接口的区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#42-%E5%AE%9E%E7%8E%B0-runnable-%E6%8E%A5%E5%8F%A3%E5%92%8C-callable-%E6%8E%A5%E5%8F%A3%E7%9A%84%E5%8C%BA%E5%88%AB)
10. [如何启动线程？start方法和run方法的区别？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E8%B0%83%E7%94%A8-start-%E6%96%B9%E6%B3%95%E6%97%B6%E4%BC%9A%E6%89%A7%E8%A1%8C-run-%E6%96%B9%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E4%B8%8D%E8%83%BD%E7%9B%B4%E6%8E%A5%E8%B0%83%E7%94%A8-run-%E6%96%B9%E6%B3%95)
11. 什么是守护线程？ 如何定义守护线程？
12. 请讲一下sleep方法？
13. sleep方法会释放锁吗？ 静态
14. yield方法有什么作用？是否会释放锁？ 静态····
15. [说说 sleep() 方法和 wait() 方法区别和共同点?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E8%AF%B4%E8%AF%B4-sleep-%E6%96%B9%E6%B3%95%E5%92%8C-wait-%E6%96%B9%E6%B3%95%E5%8C%BA%E5%88%AB%E5%92%8C%E5%85%B1%E5%90%8C%E7%82%B9)
16. 请说一下中断机制？ 
17. 讲一下和中断相关的几个方法？
18. 进程的生命周期
19. [线程的生命周期？以及状态之间的扭转是怎样的?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E8%AF%B4%E8%AF%B4%E7%BA%BF%E7%A8%8B%E7%9A%84%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%E5%92%8C%E7%8A%B6%E6%80%81)
20. Executor的shutdownNow方法是如何实现的？ 调用每个线程的中断方法·～
21. 如何中断Executor中的一个线程？
22. java中的同步机制有哪些？ jvm实现的synchronized 和 jdk实现的 ReentrentLock
23. [synchronized如何使用？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#12-%E8%AF%B4%E8%AF%B4%E8%87%AA%E5%B7%B1%E6%98%AF%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97)
24. [构造方法可以使用 synchronized 关键字修饰么](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#13-%E6%9E%84%E9%80%A0%E6%96%B9%E6%B3%95%E5%8F%AF%E4%BB%A5%E4%BD%BF%E7%94%A8-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97%E4%BF%AE%E9%A5%B0%E4%B9%88)
25. [synchronized底层原理是什么？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#13-%E8%AE%B2%E4%B8%80%E4%B8%8B-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E5%BA%95%E5%B1%82%E5%8E%9F%E7%90%86) [小米](https://xiaomi-info.github.io/2020/03/24/synchronized/)
26. [synchroinized为什么称为重量级锁?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#11%E8%AF%B4%E4%B8%80%E8%AF%B4%E8%87%AA%E5%B7%B1%E5%AF%B9%E4%BA%8E-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E4%BA%86%E8%A7%A3)
27. [说说 synchronized 关键字和 volatile 关键字的区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#24-%E8%AF%B4%E8%AF%B4-synchronized-%E5%85%B3%E9%94%AE%E5%AD%97%E5%92%8C-volatile-%E5%85%B3%E9%94%AE%E5%AD%97%E7%9A%84%E5%8C%BA%E5%88%AB)
28. synchronized如何实现同步？ monitor 和 队列 `**_WaitSet 和 _EntryList`
29. 什么是Monitor监视器锁？ 每个对象都有一个对应的monitor
30. synchronized能否保证原子操作？ 可以 
31. synchronized能否禁止指令重排序？ 不能
32. 讲一下锁升级的详细过程？
33. [为什么jdk6之后对锁升级进行了优化，添加偏向锁和轻量级锁？ 因为重量级锁设计OS互斥量Mutex lock 用户态和内核态切换](https://www.cnblogs.com/wuqinglong/p/9945618.html)
34. 锁升级过程是否可逆？
35. 为什么需要自旋锁？
36. 什么是可重入锁？
37. 什么是自适应锁?
38. 什么是ReentrentLock？ 有几种模式？
39. 怎么体现公平锁与非公平锁特性？
40. AQS是如何保证线程安全的？ cas
41. [讲一下什么是AQS？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#61-aqs-%E4%BB%8B%E7%BB%8D) [链接1](https://www.cnblogs.com/waterystone/p/4920797.html) [链接2](https://www.cnblogs.com/chengxiao/archive/2017/07/24/7141160.html) [一枝花算不算浪漫](https://juejin.cn/post/6844904146127044622)
42. AQS如何实现排他锁和共享锁？
43. AQS如何实现可重入锁特性？
44. [jvm实现的synchronized VS jdk实现的 ReentrentLock](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#15-%E8%B0%88%E8%B0%88-synchronized-%E5%92%8C-reentrantlock-%E7%9A%84%E5%8C%BA%E5%88%AB)
45. 讲一下join方法？底层是如何实现的？
46. 如果使用3个线程循环顺序打印ABC？
47. 如何使用3个线程顺序打印0～100
48. 说一下wait() notify() notifyAll()的作用？
49. wait方法的底层原理是什么？如何使用？ 必须在同步块中使用？
50. 如何使用wait 和 notify方法实现生产者和消费者
51. **如果使用ReentrentLock加锁之后，调用wait方法会怎样？**
52. sleep方法和wait方法的区别？
53. Condition的await VS Object的wait
54. 讲一下CountDownLatch是什么？ 如何使用 ？
55. 简述CountDownLatch的实现逻辑?
56. CountDownLatch的使用场景？
57. 讲一下CyclicBarrier是什么？ 
58. CyclicBarrier的使用场景以及如何使用？
59. CountDownLatch VS CyclicBarrier 
60. Semaphore 的作用是什么？ 如何实现的？
61. Semaphore 如何使用？
62. 讲一下FutureTask是什么？ FutureTask 可用于异步获取执行结果或取消执行任务的场景
63. 什么是BlockingQueue？ 创建的BlockingQueue有哪些？
64. [如何创建线程池？为什么Alibaba 开发规范中禁止使用Executors创建线程池？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#44-%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BA%E7%BA%BF%E7%A8%8B%E6%B1%A0) [why神](https://mp.weixin.qq.com/s?__biz=Mzg3NjU3NTkwMQ==&mid=2247505103&idx=1&sn=a041dbec689cec4f1bbc99220baa7219&source=41#wechat_redirect) [美团](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651751537&idx=1&sn=c50a434302cc06797828782970da190e&chksm=bd125d3c8a65d42aaf58999c89b6a4749f092441335f3c96067d2d361b9af69ad4ff1b73504c&scene=21#wechat_redirect)
65. [什么是线程池? 为什么使用线程池?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#41-%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E7%94%A8%E7%BA%BF%E7%A8%8B%E6%B1%A0)
66. [execute()方法和 submit()方法的区别是什么呢？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#43-%E6%89%A7%E8%A1%8C-execute%E6%96%B9%E6%B3%95%E5%92%8C-submit%E6%96%B9%E6%B3%95%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88%E5%91%A2)
67. [线程池的实现原理]
68. 线程池的参数有哪些？分别有什么含义？
69. BlockingQueue 哪些使用场景？
70. BlockingQueue 有哪些特性？ 阻塞
71. ForkJoin 有是什么？
72. ForkJoinPool 实现原理 ？ 工作窃取算法
73. volatile 关键字的作用？ 能否修饰局部变量？
74. volatile如何实现可见性？
75. 请手写一个DCL的单例模式 如果不用volatile修饰会怎样
76. [什么是JMM？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#22-%E8%AE%B2%E4%B8%80%E4%B8%8B-jmmjava-%E5%86%85%E5%AD%98%E6%A8%A1%E5%9E%8B)
77. 什么是MESI协议？
78. MESI 数据失效之后，怎么读正确的数据呢？ store buffer
79. 内存交互之间的8种指令？
80. [JMM的3大特性 原子  可见 有序](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#23-%E5%B9%B6%E5%8F%91%E7%BC%96%E7%A8%8B%E7%9A%84%E4%B8%89%E4%B8%AA%E9%87%8D%E8%A6%81%E7%89%B9%E6%80%A7)
81. i++是不是原子操作？
82. i++ 如何保证正确性？  同步 JUC Atomic类
83. AtomicLong VS LongAdder
84. **LongAdder 实现原理**
85. 可见性的3种实现方式 ？ volatile synchronized final
86. 请讲一下final的内存语义？
87. 有序性是什么？ 如何保证有序性？
88. 指令重排序有几种类型？
89. 指令重拍的目的是什么？  涉及指令寄存器和CPU计算单元ALU ， 主要提升计算速度
90. 什么是内存屏障？ 有几种类型的屏障？
91. 什么是happens-before原则？
92. happens-before规定的8项规则？
93. 什么是管程锁定规则？ 一个 unlock 操作先行发生于后面对同一个锁的 lock 操作
94. 什么是CAS ，CAS底层原理？ 汇编指令
95. ABA问题如何解决？
96. [万字解析 ThreadLocal 关键字](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/threadlocal.md#threadlocal%E9%A1%B9%E7%9B%AE%E4%B8%AD%E4%BD%BF%E7%94%A8%E5%AE%9E%E6%88%98)
97. [什么是ThreadLocal？ ThreadLocal如何实现？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#3-threadlocal)
98. [ThreadLocal的内存泄露问题?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#34-threadlocal-%E5%86%85%E5%AD%98%E6%B3%84%E9%9C%B2%E9%97%AE%E9%A2%98)
99. [threadlocal在项目中的实战场景](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/threadlocal.md#threadlocal%E9%A1%B9%E7%9B%AE%E4%B8%AD%E4%BD%BF%E7%94%A8%E5%AE%9E%E6%88%98)
100. threadlocal的作用： 1、线程隔离 2、跨方法参数传递，比如session
101. threadlocal变量为什么需要使用`private static final `   来修饰？ 
102. threadlocal在jdk1.7 和 jdk1.8 的结构上有什么不同?  `1.7是一个threadlocal变量对应一个<thread, val>的map ， jdk1.8之后是一个thread下有一个 <threadlocal, val>的map`
103. jvm对synchronized的锁优化都有哪些？
104. 说一下什么是锁膨胀
105. 什么是锁消除？ 逃逸分析 局部变量 
106. 什么是逃逸分析？ 可以做什么？
107. synchronized锁标志是如何存储的？ 对象头markword   LockRecord
108. 锁对象hashCode在各种状态下都存放在那里？
109. 偏向锁的使用场景？ 只有一个线程竞争锁
110. 偏向锁是如何获取的？ 直接判断线程不需要cas
111. 多线程开发的注意点有哪些？
112. [什么是死锁，如何避免死锁](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E4%BB%80%E4%B9%88%E6%98%AF%E7%BA%BF%E7%A8%8B%E6%AD%BB%E9%94%81%E5%A6%82%E4%BD%95%E9%81%BF%E5%85%8D%E6%AD%BB%E9%94%81)
113. 死锁产生的条件
114. [JUC下有哪些Atomic原子类](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#51-%E4%BB%8B%E7%BB%8D%E4%B8%80%E4%B8%8B-atomic-%E5%8E%9F%E5%AD%90%E7%B1%BB) [javaguide](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/atomic-classes.md)
115. [能不能给我简单介绍一下 AtomicInteger 类的原理](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-02.md#51-%E4%BB%8B%E7%BB%8D%E4%B8%80%E4%B8%8B-atomic-%E5%8E%9F%E5%AD%90%E7%B1%BB)
116. [CompletableFuture是什么，如何实现的](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/completablefuture-intro.md)
117. [Java 常见并发容器总结](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-collections.md)
118. [1000 多个并发线程，10 台机器，每台机器 4 核，如何设计线程池大小?](https://whywhy.vip/archives/148)
119. [面试官问我：什么是高并发下的请求合并？](https://mp.weixin.qq.com/s?__biz=Mzg3NjU3NTkwMQ==&mid=2247505190&idx=1&sn=b1b3251fec254ec758af3a8ab05ce9f4&chksm=cf32b8d4f84531c2ba67af98333cd44bb53672f4359f09ae5bee1f2227a9ce56d525dd88d258&token=1947525029&lang=zh_CN#rd)
120. [如何设置线程的优先级](https://blog.csdn.net/qq_35400008/article/details/80219947)
121. [什么情况下线程池会执行拒绝策略](https://www.cnblogs.com/javastack/p/12786848.html) 线程池关闭的时候也会执行拒绝策略，isShutDown()
122. [Executors 可缓冲线程池有什么缺点](https://blog.csdn.net/wenniuwuren/article/details/51700080?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.edu_weight&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.edu_weight)
123. [newScheduledThreadPool线程池有什么缺点]() : 当同时提交大量任务时，会造成任务在队列中堆积，甚至产生OOM,并不是说创建无限的线程
124. 线程工厂的作用是什么？ 设置一些线程参数，daemon 或者线程名称之类的
125. 


## 并发资料
- [CS-Notes Github java并发](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%B9%B6%E5%8F%91.md)
- [个人博客：并发中的一些问题](https://geekibli.github.io/wiki/%E5%B9%B6%E5%8F%91%E4%B8%AD%E7%9A%84%E4%B8%80%E4%BA%9B%E9%97%AE%E9%A2%98/)