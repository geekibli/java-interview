## Java容器

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