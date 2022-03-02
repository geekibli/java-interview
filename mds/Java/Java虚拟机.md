## Java虚拟机

1. [java虚拟机基础](大白话带你认识JVM)
2. [讲一下jvm的主要构成？ 运行时数据区 类加载 执行引擎](https://www.jianshu.com/p/70c7755151f7)
3. [讲一下运行时数据区的几个部分？ 主要5种](https://blog.csdn.net/weixin_45151795/article/details/108458096)
4. [什么是程序计数器？ 有什么特性？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E7%A8%8B%E5%BA%8F%E8%AE%A1%E6%95%B0%E5%99%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E7%A7%81%E6%9C%89%E7%9A%84)
5. [程序计数器为什么是私有的? ](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E7%A8%8B%E5%BA%8F%E8%AE%A1%E6%95%B0%E5%99%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E7%A7%81%E6%9C%89%E7%9A%84)
6. 什么是java虚拟机栈？
7. 什么是栈桢？ 一个方法对应一个栈桢
8. 栈桢有哪些组成部分 ？ 局部变量表 操作数栈 动态链接 方法出口 
9. java虚拟机栈会有哪些异常？ OOM StackOverFlow
10. 什么是本地方法栈？ 会产生哪些异常？
11. 什么是堆？
12. 堆内部有哪些分区？
13. 为什么Eden和Servior分区的比例默认为8:1:1
14. 什么是方法区（元空间） OOM
15. [Java 垃圾回收机制（GC）简述](https://blog.csdn.net/liyifan687/article/details/80075189)
16. [垃圾回收的优点和原理，并考虑2种回收机制](https://blog.csdn.net/will130/article/details/49681103)
17. Full GC 发生在哪些区域？ 堆 方法区
18. 什么是直接内存？ 堆外内存
19. [为什么会有垃圾回收？](https://cloud.tencent.com/developer/article/1198886)
20. 垃圾回收都回收哪些东西？
21. [如何判断对象是垃圾？](https://blog.csdn.net/zx1293406/article/details/104535414)
22. [引用计数算法弊端是什么？ 循环引用](https://blog.csdn.net/qq_42185762/article/details/115667911)
23. [可达性分析是什么？](https://segmentfault.com/a/1190000021820577)
24. [垃圾回收器的基本原理是什么？垃圾回收器可以马上回收内存吗？有什么办法主动通知虚拟机进行垃圾回收？](https://www.cnblogs.com/zhangxiaopeng/p/5001171.html)
25. 什么可以作为GC ROOT?
26. 类卸载有哪些条件？ 实例 类加载器 引用
27. 什么是finalize方法？ finalize如何实现自救？
28. finalize对象自救只能实现一次？ yes
29. [如何判断一个常量是废弃常量？](https://javaguide.cn/java/jvm/jvm-garbage-collection/#_2-5-%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E4%B8%80%E4%B8%AA%E5%B8%B8%E9%87%8F%E6%98%AF%E5%BA%9F%E5%BC%83%E5%B8%B8%E9%87%8F)
30. [如何判断一个类是无用的类](https://javaguide.cn/java/jvm/jvm-garbage-collection/#_2-6-%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E4%B8%80%E4%B8%AA%E7%B1%BB%E6%98%AF%E6%97%A0%E7%94%A8%E7%9A%84%E7%B1%BB)
31. [java中 4中对象引用类型？ 以及区别 ？ 强软弱虚 ](https://www.cnblogs.com/frankcui/p/12492973.html)
32. [常见的垃圾收集算法？](https://developer.aliyun.com/ask/274518)
33. [什么是标记清除算法？ 有哪些缺点？ 效率低 碎片](https://www.cnblogs.com/xuwc/p/14054104.html)
34. 标记复制算法是什么？ 有哪些缺点？ 内存利用率低
35. **标记整理算法是什么？** 有哪些缺点？ 有哪些优势？
36. [**什么是三色标记法？**](https://segmentfault.com/a/1190000021820577)
37. 三色标记进行并发标记的时候，会产生哪些问题？
38. [**什么场景下会“对象消失”?**](https://segmentfault.com/a/1190000021820577)
39. [**并发标记如何解决对象消失的问题？**](https://segmentfault.com/a/1190000021820577)
40. 讲一下分代收集算法？
41. 讲一下常见的垃圾收集器？ 7种
42. 年轻代的收集器有哪些？
43. 老年代的垃圾收集器有哪些？
44. 讲一下G1收集器？
45. 什么是STW？为什么会有STW？
46. 讲一下Serial收集器的缺点？ 单线程
47. 讲一下ParNew收集器？  Serial收集器多线程版本  年轻代 只能和CMS配合
48. Parallel Scavenge收集器的目标是什么？ 吞吐量
49. 讲一下CMS收集器的工作机制？
50. CMS收集器使用的垃圾收集算法？有哪些缺点？
51. 什么是浮动垃圾？
52. 什么是Concurrent Mode Failure？
53. 讲一下G1收集器？ G1 可以直接对新生代和老年代一起回收。
54. G1收集器的工作流程？
55. Minor GC 和 Full GC
56. 对象内存分配策略是怎样的？
57. 什么时候下会触发Full GC ?
58. [请讲述什么是类加载机制？ 过程是什么？](https://javaguide.cn/java/jvm/class-loading-process/)
59. 什么是静态链接｜动态链接
60. [bootstarpClassLoader是在哪里实现的？ C++实现的](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
61. [类加载器都有哪些？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
62. [如何自定义类加载器？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
63. [什么是双亲委派机制？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
64. [双亲委派机制的优点？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
65. [自定义的 java.lang.String能否被加载？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
66. [为什么加载先是在app加载器而不是bootstrap加载器？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
67. [如何破坏双亲委派机制？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
68. [Tomcat打破双亲委派？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
69. [Tomcat为什么不使用默认的双亲委派](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
70. [Tomcat几种加载器分别是什么？ 各自的作用是什么？](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
71. [内存溢出异常](https://blog.csdn.net/clover_lily/article/details/80099849)
72. 哪些地方会发生OOM异常？
73. 什么场景下会产生OOM异常？
74. 哪些地方会发生StackOverFlow异常？
75. 什么场景下会产生StackOverFlow异常？
76. 什么是逃逸分析？
77. 什么是标量替换？
78. [什么是对象年龄动态判断机制？](https://javaguide.cn/java/jvm/jvm-garbage-collection/#_1-4-%E5%8A%A8%E6%80%81%E5%AF%B9%E8%B1%A1%E5%B9%B4%E9%BE%84%E5%88%A4%E5%AE%9A)
79. [什么是空间担保机制？](https://javaguide.cn/java/jvm/jvm-garbage-collection/#_1-6-%E7%A9%BA%E9%97%B4%E5%88%86%E9%85%8D%E6%8B%85%E4%BF%9D)
80. [对象创建过程](https://javaguide.cn/java/jvm/memory-area/#_3-1-%E5%AF%B9%E8%B1%A1%E7%9A%84%E5%88%9B%E5%BB%BA)
81. [为对象分配内存](https://blog.csdn.net/qq_42605393/article/details/119192213) [碰撞指针 空闲列表](https://javaguide.cn/java/jvm/memory-area/#_3-1-%E5%AF%B9%E8%B1%A1%E7%9A%84%E5%88%9B%E5%BB%BA)
82. [创建对象的线程安全问题](https://blog.csdn.net/qq_38930804/article/details/121592294)  [cas重试 TLAB](https://blog.csdn.net/m0_48333563/article/details/113783060)
83. [对象在内存中的布局](https://javaguide.cn/java/jvm/memory-area/#_3-2-%E5%AF%B9%E8%B1%A1%E7%9A%84%E5%86%85%E5%AD%98%E5%B8%83%E5%B1%80)
84. 创建一个空对象需要多到的空间？
85. [对象的定位访问](https://www.jianshu.com/p/536b6fe077d0)
86. [java中会存在内存泄漏吗，请简单描述。](https://blog.csdn.net/m0_37204491/article/details/64500151)
87. [JVM常用的参数有哪些](https://javaguide.cn/java/jvm/jvm-intro/#_3-6-%E4%BA%86%E8%A7%A3-jvm%E7%9A%84%E5%B8%B8%E7%94%A8%E5%8F%82%E6%95%B0)


## Java虚拟机资料
- [CS-Notes Github java虚拟机](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E8%99%9A%E6%8B%9F%E6%9C%BA.md)
- [GeekIbli Github 深入学习jvm（图灵-诸葛）](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
- [Java 内存区域详解](https://javaguide.cn/java/jvm/memory-area/)
- [JVM 垃圾回收详解](https://javaguide.cn/java/jvm/jvm-garbage-collection/#)
- [深入学习jvm（图灵-诸葛）](https://geekibli.github.io/wiki/%E6%B7%B1%E5%85%A5%E5%AD%A6%E4%B9%A0jvm%EF%BC%88%E5%9B%BE%E7%81%B5-%E8%AF%B8%E8%91%9B%EF%BC%89/)
- [JDK 监控和故障处理工具总结](https://javaguide.cn/java/jvm/jdk-monitoring-and-troubleshooting-tools/#)