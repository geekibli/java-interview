
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