## Java虚拟机

1. [讲一下jvm的主要构成？ 运行时数据区 类加载 执行引擎](https://www.jianshu.com/p/70c7755151f7)
2. [讲一下运行时数据区的几个部分？ 主要5种](https://blog.csdn.net/weixin_45151795/article/details/108458096)
3. [什么是程序计数器？ 有什么特性？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E7%A8%8B%E5%BA%8F%E8%AE%A1%E6%95%B0%E5%99%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E7%A7%81%E6%9C%89%E7%9A%84)
4. [程序计数器为什么是私有的? ](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/concurrent/java-concurrent-questions-01.md#%E7%A8%8B%E5%BA%8F%E8%AE%A1%E6%95%B0%E5%99%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E7%A7%81%E6%9C%89%E7%9A%84)
5. 什么是java虚拟机栈？
6. 什么是栈桢？ 一个方法对应一个栈桢
7. 栈桢有哪些组成部分 ？ 局部变量表 操作数栈 动态链接 方法出口 
8. java虚拟机栈会有哪些异常？ OOM StackOverFlow
9. 什么是本地方法栈？ 会产生哪些异常？
10. 什么是堆？
11. 堆内部有哪些分区？
12. 为什么Eden和Servior分区的比例默认为8:1:1
13. 什么是方法区（元空间） OOM
14. [Java 垃圾回收机制（GC）简述](https://blog.csdn.net/liyifan687/article/details/80075189)
15. [垃圾回收的优点和原理，并考虑2种回收机制](https://blog.csdn.net/will130/article/details/49681103)
16. Full GC 发生在哪些区域？ 堆 方法区
17. 什么是直接内存？ 堆外内存
18. [为什么会有垃圾回收？](https://cloud.tencent.com/developer/article/1198886)
19. 垃圾回收都回收哪些东西？
20. [如何判断对象是垃圾？](https://blog.csdn.net/zx1293406/article/details/104535414)
21. [引用计数算法弊端是什么？ 循环引用](https://blog.csdn.net/qq_42185762/article/details/115667911)
22. [可达性分析是什么？](https://segmentfault.com/a/1190000021820577)
23. [垃圾回收器的基本原理是什么？垃圾回收器可以马上回收内存吗？有什么办法主动通知虚拟机进行垃圾回收？](https://www.cnblogs.com/zhangxiaopeng/p/5001171.html)
24. 什么可以作为GC ROOT?
25. 类卸载有哪些条件？ 实例 类加载器 引用
26. 什么是finalize方法？ finalize如何实现自救？
27. finalize对象自救只能实现一次？ yes
28. [java中 4中对象引用类型？ 以及区别 ？ 强软弱虚 ](https://www.cnblogs.com/frankcui/p/12492973.html)
29. [常见的垃圾收集算法？](https://developer.aliyun.com/ask/274518)
30. [什么是标记清除算法？ 有哪些缺点？ 效率低 碎片](https://www.cnblogs.com/xuwc/p/14054104.html)
31. 标记复制算法是什么？ 有哪些缺点？ 内存利用率低
32. **标记整理算法是什么？** 有哪些缺点？ 有哪些优势？
33. [**什么是三色标记法？**](https://segmentfault.com/a/1190000021820577)
34. 三色标记进行并发标记的时候，会产生哪些问题？
35. [**什么场景下会“对象消失”?**](https://segmentfault.com/a/1190000021820577)
36. [**并发标记如何解决对象消失的问题？**](https://segmentfault.com/a/1190000021820577)
37. 讲一下分代收集算法？
38. 讲一下常见的垃圾收集器？ 7种
39. 年轻代的收集器有哪些？
40. 老年代的垃圾收集器有哪些？
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