# 1-Java基础

> 基本类型、关键字（final static）、接口和抽象类、反射、注解、泛型
1. [Java1.5版本后的三大版本](https://blog.csdn.net/qq_28870891/article/details/104477819)
2. [Oracle JDK 和 OpenJDK 的对比](https://zhuanlan.zhihu.com/p/108675511)
3. [Java语言有什么特点](http://c.biancheng.net/view/1282.html)
4. [什么是字节码？采用字节码的最大好处是什么](https://zhuanlan.zhihu.com/p/137021803)
5. [什么是Java程序的主类？应用程序和小程序的主类有何不同？](https://zhuanlan.zhihu.com/p/137022037)
6. [long类型和double类型的线程安全问题：因为目前jvm的原子操作是32位](https://www.likecs.com/show-204683271.html)
7. [java 8大基本类型](https://zhuanlan.zhihu.com/p/39843539)
8. [为什么需要包装类型 ？ 面向对象 泛型](https://zhuanlan.zhihu.com/p/78590948)
9. [什么是装箱 拆箱](https://zhuanlan.zhihu.com/p/64004059)
10. [Math.round(11.5) 等于多少？Math.round(-11.5)等于多少](https://blog.csdn.net/u012110719/article/details/46351713)
11. [new Integer(123) 与 Integer.valueOf(123) 的区别？](https://blog.csdn.net/guzhong10/article/details/88865831)
12. [Integer 缓冲池范围？ 是否可以修改？ `-XX:AutoBoxCacheMax=<size> `](https://www.programminghunter.com/article/1567134782/)
13. [String 是否可以继承？ final](https://www.zhihu.com/question/31345592)
14. String在jdk8中的实现和在jdk9中的实现?
15. String 如何保证不可变？ final  不可变有什么好处？
16. [什么是String pool?](https://www.cnblogs.com/Andya/p/14067618.html)
17. [如何在运行时将字符串添加到String pool? intern()](https://darrenyjy.github.io/2016/05/28/String%E6%B1%A0%E5%8C%96%E5%8F%8Aintern%E6%96%B9%E6%B3%95%E7%9A%84%E4%BD%9C%E7%94%A8/)
18. String pool 存放在哪里？ 永久代 堆
19. String是否会导致OOM？ 会 常量池在堆中！
20. [float f=3.4 是否正确？](https://blog.csdn.net/qq_31279347/article/details/82557825);
21. 参数传递是指传递还是引用传递？
22. [使用 += 或者 ++ 运算符会执行隐式类型转换](https://www.cnblogs.com/zhangshuaiyin/p/12038092.html)
23. [switch 不支持哪些类型？ Long float double](https://blog.csdn.net/weixin_38251977/article/details/110880666)
24. switch 击穿现象？
25. final 用法 字段 方法 类
26. 什么方法重写和方法重载？
27. 静态变量和实例变量的区别？ 范围 生命周期
28. 静态方法是否可以是抽象的？ 不能 结合类加载
29. 静态初始化块 构造器 子类父类 初始化顺序？
30. 静态内部类 ： 非静态内部类依赖外部类，需要先创建外部类
31. 静态内部类不能访问外部类的非静态的变量和方法？ 是的
32. equals 方法比较的是什么？
33. 为什么重写equals方法一定要重写hashcode方法？ 保证hashcode一致
34. toString 方法 打印@后面的是什么？ hashcode的无符号16进制
35. clone方法的访问控制权限是什么？ protected native
36. 深拷贝和浅拷贝？
37. 访问控制符以及权限范围 ： 如果不加访问修饰符，表示包级可见。
38. 抽象类只能被继承不能实例化？ 是的
39. 抽象类是否可以继承抽象类？可以
40. 抽象类是否可以实现接口？可以
41. 抽象类是否可以继承非抽象类？ 可以
42. 接口是否可以实现接口？ 不可以
43. 接口是否可以继承接口？ 可以
44. 接口可以定义private的变量和方法吗？ 可以
45. 接口可以由自己的实现吗？ 可以 default
46. 接口可以继承抽象类？ 普通类？ 都不可以
47. 接口是否可以定义变量？ 不可以 只能是常量
48. 反射的优缺点？
49. 什么是异常？
50. 什么是错误？
51. 受查异常和非受查异常？ IOException NullPointException
52. Java异常机制的意义？ 中断程序
53. [泛型的10道面试题](https://cloud.tencent.com/developer/article/1033693 )
54. Java中的泛型是什么 ? 使用泛型的好处是什么?
55. Java的泛型是如何工作的?
56. 什么是类型擦除 ? 
57. 什么是泛型中的限定通配符和非限定通配符?   `extends super      <?>`
58. `List<? extends T>`和 `List <? super T>`之间有什么区别?
59. 如何声明泛型和使用泛型？
60. 你可以把  `List<String>` 传递给一个接受`List<Object>`参数的方法吗？  编译错误
61. Array中可以用泛型吗? 不支持
62. [泛型详解](https://www.cnblogs.com/Blue-Keroro/p/8875898.html)
63. 泛型方法 泛型接口 泛型类 ？
64. [注解的实现原理](https://www.cnblogs.com/acm-bingzi/p/javaAnnotation.html)



> [以上参考文档链接 🔗](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%9F%BA%E7%A1%80.md)
> [Java程序员要达到什么水平才能社招进阿里](https://www.its203.com/article/QLCZ0809/119546435)


# 2-Java容器

1. set接口实现类有哪些？
2. treeSet底层数据结构是什么？ 查询时间复杂度多少？ 红黑树 O(logn) 范围查询
3. hashSet底层实现是什么？ 查询复杂度多少？ hash表 O(1) 单值查询
4. linkedHashSet  具有 HashSet 的查找效率，并且内部使用双向链表维护元素的插入顺序
5. list的实现类有哪些？
6. ArrayList底层实现是什么？ 优缺点 动态数组 随机访问
7. ArrayList如何提现随机访问？ RandomAccess 接口标识着该类支持快速随机访问。
8. ArrayList默认大小？ 10
9. ArrayList扩容机制 `oldCapacity + (oldCapacity >> 1)`
10. ArrayList动态扩容性能？`Arrays.copyOf()` 内存
11. ArrayList删除性能？ O(n)
12. 什么是Fail-Fast机制？
13. Vector底层实现？ 优缺点？ 动态数组 线程安全
14. Vector如何实现线程安全？
15. Vector扩容策略？ `oldCapacity + oldCapacity`
16. CopyOnWriteArrayList实现机制？
17. CopyOnWriteArrayList使用场景？
18. CopyOnWriteArrayList缺点？ 内存占用 读操作误差
19. LinkedList底层实现？ 双向链表 顺序访问
20. Queue实现类有哪些？
21. PriorityQueue ： 基于堆结构实现，可以用它来实现优先队列。
22. treemap底层数据结构以及特点？
23. HashMap底层数据结构以及特点？
24. 解决hash冲突的方法？ 拉链 开放寻址
25. hashmap jdk1.7中的数据结构？ 数组 + 链表
26. hashmap jdk1.7下链表闭环？ 头插法 扩容的时候
27. hashmap jdk1.7下线程不安全的场景？ 
29. hashmap jdk1.7中put方法流程？ 初始化 寻址 冲突 赋值 扩容
30. hashmap jdk1.8中的数据结构？
31. hashmap jdk1.8下线程不安全的场景？
32. hashmap jdk1.8下如何扩容？
33. hashmap jdk1.8 下put方法流程？  初始化 寻址 冲突 赋值 扩容
34. hashmap 初始值为什么是16
35. 什么时候触发扩容？ 
36. 加载因子是做什么的？
37. 加载因子为什么是0.75？ 调整大了会怎样？ 调整小了会怎样？
38. 什么时候链表转成红黑树？ 链表长度>=8 并且 数组长度>64
39. hashmap扩容流程？ 区分jdk1.7 和 jdk1.8
40. 数组下标是如何确定的？ 位运算 
41. 讲一下什么是扰动机制，目的是什么？ 
42. HashTable底层数据结构以及特点？
43. 如何确保hashmap线程安全，有哪些方法？ 
44. 讲一下concurrentHashmap在jdk1.7 和 jdk1.8下的数据结构？ 有什么优化？ 并发度
45. concurrnetHashMap是如何确保线程安全的？ ReentrentLock    synchronized + cas
46. concurrentHashMap在jdk1.7下扩容和在jdk1.8下的扩容过程讲一下？
47. concurrentHashMap put方法和get方法 不同版本下，如何实现讲一下？
48. LinkedHashMap底层数据结构以及特点？
49. **LinkedHashMap 如何保证 有序性**
50. LinkedHashMap如何实现LRU算法？
51. **什么是WeakHashMap?**

> [以上参考文档链接 🔗](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%AE%B9%E5%99%A8.md)


# 3-Java并发
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
  


# 4-Java虚拟机

1. [讲一下jvm的主要构成？ 运行时数据区 类加载 执行引擎](https://www.jianshu.com/p/70c7755151f7)
2. [讲一下运行时数据区的几个部分？ 主要5种](https://blog.csdn.net/weixin_45151795/article/details/108458096)
3. 什么是程序计数器？ 有什么特性？
4. 什么是java虚拟机栈？
5. 什么是栈桢？ 一个方法对应一个栈桢
6. 栈桢有哪些组成部分 ？ 局部变量表 操作数栈 动态链接 方法出口 
7. java虚拟机栈会有哪些异常？ OOM StackOverFlow
8. 什么是本地方法栈？ 会产生哪些异常？
9. 什么是堆？
10. 堆内部有哪些分区？
11. 为什么Eden和Servior分区的比例默认为8:1:1
12. 什么是方法区（元空间） OOM
13. [Java 垃圾回收机制（GC）简述](https://blog.csdn.net/liyifan687/article/details/80075189)
14. [垃圾回收的优点和原理，并考虑2种回收机制](https://blog.csdn.net/will130/article/details/49681103)
15. Full GC 发生在哪些区域？ 堆 方法区
16. 什么是直接内存？ 堆外内存
17. [为什么会有垃圾回收？](https://cloud.tencent.com/developer/article/1198886)
18. 垃圾回收都回收哪些东西？
19. [如何判断对象是垃圾？](https://blog.csdn.net/zx1293406/article/details/104535414)
20. [引用计数算法弊端是什么？ 循环引用](https://blog.csdn.net/qq_42185762/article/details/115667911)
21. [可达性分析是什么？](https://segmentfault.com/a/1190000021820577)
22. [垃圾回收器的基本原理是什么？垃圾回收器可以马上回收内存吗？有什么办法主动通知虚拟机进行垃圾回收？](https://www.cnblogs.com/zhangxiaopeng/p/5001171.html)
23. 什么可以作为GC ROOT?
24. 类卸载有哪些条件？ 实例 类加载器 引用
25. 什么是finalize方法？ finalize如何实现自救？
26. finalize对象自救只能实现一次？ yes
27. [java中 4中对象引用类型？ 以及区别 ？ 强软弱虚 ](https://www.cnblogs.com/frankcui/p/12492973.html)
28. [常见的垃圾收集算法？](https://developer.aliyun.com/ask/274518)
29. [什么是标记清除算法？ 有哪些缺点？ 效率低 碎片](https://www.cnblogs.com/xuwc/p/14054104.html)
30. 标记复制算法是什么？ 有哪些缺点？ 内存利用率低
31. **标记整理算法是什么？** 有哪些缺点？ 有哪些优势？
32. [**什么是三色标记法？**](https://segmentfault.com/a/1190000021820577)
33. 三色标记进行并发标记的时候，会产生哪些问题？
34. [**什么场景下会“对象消失”?**](https://segmentfault.com/a/1190000021820577)
35. [**并发标记如何解决对象消失的问题？**](https://segmentfault.com/a/1190000021820577)
36. 讲一下分代收集算法？
37. 讲一下常见的垃圾收集器？ 7种
38. 年轻代的收集器有哪些？
39. 老年代的垃圾收集器有哪些？
40. 讲一下G1收集器？
41. 什么是STW？为什么会有STW？
42. 讲一下Serial收集器的缺点？ 单线程
43. 讲一下ParNew收集器？  Serial收集器多线程版本  年轻代 只能和CMS配合
44. Parallel Scavenge收集器的目标是什么？ 吞吐量
45. 讲一下CMS收集器的工作机制？
46. CMS收集器使用的垃圾收集算法？有哪些缺点？
47. 什么是浮动垃圾？
48. 什么是Concurrent Mode Failure？
49. 讲一下G1收集器？ G1 可以直接对新生代和老年代一起回收。
50. G1收集器的工作流程？
51. Minor GC 和 Full GC
52. 对象内存分配策略是怎样的？
53. 什么时候下会触发Full GC ?
54. 请讲述什么是类加载机制？ 过程是什么？
55. 什么是静态链接｜动态链接
56. bootstarpClassLoader是在哪里实现的？ C++实现的
57. 类加载器都有哪些？
58. 如何自定义类加载器？
59. 什么是双亲委派机制？
60. 双亲委派机制的优点？
61. 自定义的 java.lang.String能否被加载？
62. 为什么加载先是在app加载器而不是bootstrap加载器？
63. 如何破坏双亲委派机制？
64. Tomcat打破双亲委派？
65. Tomcat为什么不使用默认的双亲委派
66. Tomcat几种加载器分别是什么？ 各自的作用是什么？
67. [内存溢出异常](https://blog.csdn.net/clover_lily/article/details/80099849)
68. 哪些地方会发生OOM异常？
69. 什么场景下会产生OOM异常？
70. 哪些地方会发生StackOverFlow异常？
71. 什么场景下会产生StackOverFlow异常？
72. 什么是逃逸分析？
73. 什么是标量替换？
74. 什么是对象年龄动态判断机制？
75. 什么是空间担保机制？
76. [为对象分配内存](https://blog.csdn.net/qq_42605393/article/details/119192213)
77. [创建对象的线程安全问题](https://blog.csdn.net/qq_38930804/article/details/121592294)
78. [创建对象的线程安全问题1](https://blog.csdn.net/m0_48333563/article/details/113783060)
79. [对象的定位访问](https://www.jianshu.com/p/536b6fe077d0)
80. [java中会存在内存泄漏吗，请简单描述。](https://blog.csdn.net/m0_37204491/article/details/64500151)


## Java虚拟机资料
- [CS-Notes Github java虚拟机](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E8%99%9A%E6%8B%9F%E6%9C%BA.md)
- [GeekIbli Github 深入学习jvm（图灵-诸葛）](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)



# 5-Java IO


1. Java IO分类
2. Java IO 使用到的设计模式？ 装饰器模式
3. java中的UTF8和MySQL中的utf8是一样的吗？ 有什么区别？
4. 什么是编码？什么是解码？
5. String默认的编码方式是什么？ UTF-8 
6. java中如何操作字符？ InputStreamReader OutputStreamWriter
7. 什么是字节流？什么是字符流？
8. 什么是序列化？
9. java中如何对一个对象进行序列化？ Serializable接口
10. 如果一个字段不需要进行序列化，如何处理？ transient
11. Java中如何实现TCP通讯？ sockets
12. Java中如何实现UDP通讯？ DatagramSocket
13. 什么叫做URL？ 什么是URI？
14. 什么是NIO？
15. 什么是BIO？
16. BIO VS NIO
17. NIO的三大核心是什么
18. 什么是非阻塞？ 和阻塞的区别？
19. 什么叫异步IO？ 同步IO？
20. NIO 如何使用？
21. NIO用到的设计模式？ 监视器模式
22. 什么是零拷贝？
23. 零拷贝的实现方式有哪些？ mmap 和 send file





## Java IO资料 💾
- [CS-Notes Github Java IO](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20IO.md)
- 
