# 1-Java基础

> 基本类型、关键字（final static）、接口和抽象类、反射、注解、泛型
- long类型和double类型的线程安全问题：因为目前jvm的原子操作是32位。
- java 8大基本类型
- 为什么需要包装类型 ？ 面向对象 泛型
- 什么是装箱 拆箱
- new Integer(123) 与 Integer.valueOf(123) 的区别？
- Integer 缓冲池范围？ 是否可以修改？ `-XX:AutoBoxCacheMax=<size> `
- String 是否可以继承？ final
- String在jdk8中的实现和在jdk9中的实现?
- String 如何保证不可变？ final  不可变有什么好处？
- 什么是String pool?
- 如何在运行时将字符串添加到String pool? intern()
- String pool 存放在哪里？ 永久代 堆
- String是否会导致OOM？ 会 常量池在堆中！
- 参数传递是指传递还是引用传递？
- 使用 += 或者 ++ 运算符会执行隐式类型转换
- switch 不支持哪些类型？ Long float double
- switch 击穿现象？
- final 用法 字段 方法 类
- 什么方法重写和方法重载？
- 静态变量和实例变量的区别？ 范围 生命周期
- 静态方法是否可以是抽象的？ 不能 结合类加载
- 静态初始化块 构造器 子类父类 初始化顺序？
- 静态内部类 ： 非静态内部类依赖外部类，需要先创建外部类
- 静态内部类不能访问外部类的非静态的变量和方法？ 是的
- equals 方法比较的是什么？
- 为什么重写equals方法一定要重写hashcode方法？ 保证hashcode一致
- toString 方法 打印@后面的是什么？ hashcode的无符号16进制
- clone方法的访问控制权限是什么？ protected native
- 深拷贝和浅拷贝？
- 访问控制符以及权限范围 ： 如果不加访问修饰符，表示包级可见。
- 抽象类只能被继承不能实例化？ 是的
- 抽象类是否可以继承抽象类？可以
- 抽象类是否可以实现接口？可以
- 抽象类是否可以继承非抽象类？ 可以
- 接口是否可以实现接口？ 不可以
- 接口是否可以继承接口？ 可以
- 接口可以定义private的变量和方法吗？ 可以
- 接口可以由自己的实现吗？ 可以 default
- 接口可以继承抽象类？ 普通类？ 都不可以
- 接口是否可以定义变量？ 不可以 只能是常量
- 反射的优缺点？
- 什么是异常？
- 什么是错误？
- 受查异常和非受查异常？ IOException NullPointException
- Java异常机制的意义？ 中断程序
- [泛型的10道面试题](https://cloud.tencent.com/developer/article/1033693 )
- Java中的泛型是什么 ? 使用泛型的好处是什么?
- Java的泛型是如何工作的?
- 什么是类型擦除 ? 
- 什么是泛型中的限定通配符和非限定通配符?   `extends super      <?>`
-  `List<? extends T>`和 `List <? super T>`之间有什么区别?
- 如何声明泛型和使用泛型？
- 你可以把  `List<String>` 传递给一个接受`List<Object>`参数的方法吗？  编译错误
- Array中可以用泛型吗? 不支持
- [泛型详解](https://www.cnblogs.com/Blue-Keroro/p/8875898.html)
- 泛型方法 泛型接口 泛型类 ？
- 注解的实现原理
> https://www.cnblogs.com/acm-bingzi/p/javaAnnotation.html  
> 以上参考文档链接 https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%9F%BA%E7%A1%80.md


# 2-Java容器







