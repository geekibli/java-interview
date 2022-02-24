
## Java基础

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
14. [枚举是否可以继承? 枚举中是否可以实现方法?](https://www.iteye.com/blog/pf-miles-187155)
15. String在jdk8中的实现和在jdk9中的实现?
16. String 如何保证不可变？ final  不可变有什么好处？
17. [String、StringBuffer、StringBuilder 的区别？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-02.md#stringstringbufferstringbuilder-%E7%9A%84%E5%8C%BA%E5%88%ABstring-%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E4%B8%8D%E5%8F%AF%E5%8F%98%E7%9A%84)
18. [什么是String pool?](https://www.cnblogs.com/Andya/p/14067618.html)
19. [如何在运行时将字符串添加到String pool? intern()](https://darrenyjy.github.io/2016/05/28/String%E6%B1%A0%E5%8C%96%E5%8F%8Aintern%E6%96%B9%E6%B3%95%E7%9A%84%E4%BD%9C%E7%94%A8/)
20. [String#equals() 和 Object#equals() 有何区别？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-02.md#stringstringbufferstringbuilder-%E7%9A%84%E5%8C%BA%E5%88%ABstring-%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E4%B8%8D%E5%8F%AF%E5%8F%98%E7%9A%84)
21. [String pool 存放在哪里？ 永久代 堆](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-02.md#%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%B8%B8%E9%87%8F%E6%B1%A0%E7%9A%84%E4%BD%9C%E7%94%A8%E4%BA%86%E8%A7%A3%E5%90%97)
22. String是否会导致OOM？ 会 常量池在堆中！
23. [float f=3.4 是否正确？](https://blog.csdn.net/qq_31279347/article/details/82557825);
24. [参数传递是指传递还是引用传递？为什么 Java 中只有值传递？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/why-there-only-value-passing-in-java.md#%E4%B8%BA%E4%BB%80%E4%B9%88-java-%E4%B8%AD%E5%8F%AA%E6%9C%89%E5%80%BC%E4%BC%A0%E9%80%92)
25. [使用 += 或者 ++ 运算符会执行隐式类型转换](https://www.cnblogs.com/zhangshuaiyin/p/12038092.html)
26. [switch 不支持哪些类型？ Long float double](https://blog.csdn.net/weixin_38251977/article/details/110880666)
27. [什么是switch击穿现象？](https://blog.csdn.net/zhangfuzhi123/article/details/96569124)
28. final 用法 字段 方法 类
29. [方法重写和方法重载？](https://segmentfault.com/a/1190000037753553)
30. [静态变量和实例变量的区别？ 范围 生命周期](https://bbs.huaweicloud.com/blogs/233112)
31. [Object 类的常见方法有哪些？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-02.md#object-%E7%B1%BB%E7%9A%84%E5%B8%B8%E8%A7%81%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B)
32. 静态方法是否可以是抽象的？ 不能 结合类加载
33. 静态初始化块 构造器 子类父类 初始化顺序？
34. 静态内部类 ： 非静态内部类依赖外部类，需要先创建外部类
35. 静态内部类不能访问外部类的非静态的变量和方法？ 是的
36. equals 方法比较的是什么？
37. 为什么重写equals方法一定要重写hashcode方法？ 保证hashcode一致
38. toString 方法 打印@后面的是什么？ hashcode的无符号16进制
39. clone方法的访问控制权限是什么？ protected native 
40. [深拷贝和浅拷贝？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-02.md#%E6%B7%B1%E6%8B%B7%E8%B4%9D%E5%92%8C%E6%B5%85%E6%8B%B7%E8%B4%9D%E5%8C%BA%E5%88%AB%E4%BA%86%E8%A7%A3%E5%90%97%E4%BB%80%E4%B9%88%E6%98%AF%E5%BC%95%E7%94%A8%E6%8B%B7%E8%B4%9D)
41. 访问控制符以及权限范围 ： 如果不加访问修饰符，表示包级可见。
42. [java的抽象方法为什么不能是static、final、private?](https://www.cnblogs.com/datamining-bio/p/10007567.html)
43. [抽象类（abstract class）和接口（Interface）的区别](https://blog.csdn.net/aptentity/article/details/68942916)
44. 抽象类只能被继承不能实例化？ 是的
45. 抽象类是否可以继承抽象类？可以
46. 抽象类是否可以实现接口？可以
47. 抽象类是否可以继承非抽象类？ 可以
48. 接口是否可以实现接口？ 不可以
49. 接口是否可以继承接口？ 可以
50. 接口可以定义private的变量和方法吗？ 可以
51. 接口方法可以有自己的实现吗？ 可以 default
52. 接口可以继承抽象类？ 普通类？ 都不可以
53. 接口是否可以定义变量？ 不可以 只能是常量
54. [内部类可以引用它的包含类的成员吗？有没有什么限制？]()
55. [Java反射机制](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/reflection.md)
56. 反射的优缺点？
57. [什么是异常？什么是错误？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#exception-%E5%92%8C-error-%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
58. [受查异常和非受查异常？ IOException NullPointException](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#checked-exception-%E5%92%8C-unchecked-exception-%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
59. [Throwable 类常用方法有哪些？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#throwable-%E7%B1%BB%E5%B8%B8%E7%94%A8%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B)
60. [try-catch-finally 如何使用？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#try-catch-finally-%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8)
61. [finally 中的代码一定会执行吗？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#finally-%E4%B8%AD%E7%9A%84%E4%BB%A3%E7%A0%81%E4%B8%80%E5%AE%9A%E4%BC%9A%E6%89%A7%E8%A1%8C%E5%90%97)
62. [如何使用 try-with-resources 代替try-catch-finally？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8-try-with-resources-%E4%BB%A3%E6%9B%BFtry-catch-finally)
63. Java异常机制的意义？ 中断程序
64. [泛型的10道面试题](https://cloud.tencent.com/developer/article/1033693)
65. [Java中的泛型是什么 ? 使用泛型的好处是什么?](https://geekibli.github.io/wiki/Java%E6%B3%9B%E5%9E%8B/)
66. Java的泛型是如何工作的?
67. 什么是类型擦除 ? 
68. 什么是泛型中的限定通配符和非限定通配符?   `extends super      <?>`
69. `List<? extends T>`和 `List <? super T>`之间有什么区别?
70. 如何声明泛型和使用泛型？
71. 你可以把  `List<String>` 传递给一个接受`List<Object>`参数的方法吗？  编译错误
72. Array中可以用泛型吗? 不支持
73. [泛型详解](https://www.cnblogs.com/Blue-Keroro/p/8875898.html)
74. 泛型方法 泛型接口 泛型类 ？
75. [你的项目中哪里用到了泛型？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#%E4%BD%A0%E7%9A%84%E9%A1%B9%E7%9B%AE%E4%B8%AD%E5%93%AA%E9%87%8C%E7%94%A8%E5%88%B0%E4%BA%86%E6%B3%9B%E5%9E%8B)
76. [注解的实现原理](https://www.cnblogs.com/acm-bingzi/p/javaAnnotation.html) [链接1](https://geekibli.github.io/wiki/Java%E6%B3%A8%E8%A7%A3/) 
77. [注解是如何进行解析的？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/java-basic-questions-03.md#%E6%B3%A8%E8%A7%A3)
78. [Java 中如何实现序列化，有什么意义？](https://geekibli.github.io/wiki/%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98%E7%9B%AE/)
79. [阐述 JDBC 操作数据库的步骤](https://geekibli.github.io/wiki/%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98%E7%9B%AE/)
80. [Statement 和 PreparedStatement 有什么区别？哪个性能更好？](https://geekibli.github.io/wiki/%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98%E7%9B%AE/)
81. [在进行数据库编程时，连接池有什么作用？](https://geekibli.github.io/wiki/%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98%E7%9B%AE/)
82. [什么是 DAO 模式?](https://geekibli.github.io/wiki/%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98%E7%9B%AE/)
83. [Java 中是如何支持正则表达式操作的？](https://geekibli.github.io/wiki/%E5%9F%BA%E7%A1%80%E9%9D%A2%E8%AF%95%E9%A2%98%E7%9B%AE/)
84. [Java位运算](https://geekibli.github.io/wiki/Java%E4%BD%8D%E8%BF%90%E7%AE%97/)
85. [什么是代理模式，代理模式的目的是什么？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/proxy.md#1-%E4%BB%A3%E7%90%86%E6%A8%A1%E5%BC%8F)
86. [JDK 动态代理机制](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/proxy.md#31-jdk-%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86%E6%9C%BA%E5%88%B6)
87. [CGLIB 动态代理机制](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/proxy.md#32-cglib-%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86%E6%9C%BA%E5%88%B6)
88. [BigDecimal解决浮点数运算精度丢失问题](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/bigdecimal.md)
89. [为什么浮点数 float 或 double 运算的时候会有精度丢失的风险呢？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/basis/bigdecimal.md#bigdecimal-%E4%BB%8B%E7%BB%8D)



> [以上参考文档链接 🔗](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%9F%BA%E7%A1%80.md)
> [Java程序员要达到什么水平才能社招进阿里](https://www.its203.com/article/QLCZ0809/119546435)