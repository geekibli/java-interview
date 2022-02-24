## Java容器

1. [说说 List, Set, Queue, Map 四者的区别？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E8%AF%B4%E8%AF%B4-list-set-queue-map-%E5%9B%9B%E8%80%85%E7%9A%84%E5%8C%BA%E5%88%AB)
2. [集合框架底层数据结构汇总](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6%E5%BA%95%E5%B1%82%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E6%80%BB%E7%BB%93)
3. set接口实现类有哪些？
4. treeSet底层数据结构是什么？ 查询时间复杂度多少？ 红黑树 O(logn) 范围查询
5. hashSet底层实现是什么？ 查询复杂度多少？ hash表 O(1) 单值查询
6. linkedHashSet  具有 HashSet 的查找效率，并且内部使用双向链表维护元素的插入顺序
7. list的实现类有哪些？
8. ArrayList底层实现是什么？ 优缺点 动态数组 随机访问
9. ArrayList如何提现随机访问？ RandomAccess 接口标识着该类支持快速随机访问。
10. ArrayList默认大小？ 10
11. ArrayList扩容机制 `oldCapacity + (oldCapacity >> 1)`
12. ArrayList动态扩容性能？`Arrays.copyOf()` 内存
13. ArrayList删除性能？ O(n)
14. 什么是Fail-Fast机制？
15. Vector底层实现？ 优缺点？ 动态数组 线程安全
16. Vector如何实现线程安全？
17. Vector扩容策略？ `oldCapacity + oldCapacity`
18. CopyOnWriteArrayList实现机制？
19. CopyOnWriteArrayList使用场景？
20. CopyOnWriteArrayList缺点？ 内存占用 读操作误差
21. LinkedList底层实现？ 双向链表 顺序访问
22. Queue实现类有哪些？
23. PriorityQueue ： 基于堆结构实现，可以用它来实现优先队列。
24. treemap底层数据结构以及特点？
25. HashMap底层数据结构以及特点？
26. 解决hash冲突的方法？ 拉链 开放寻址
27. hashmap jdk1.7中的数据结构？ 数组 + 链表
28. hashmap jdk1.7下链表闭环？ 头插法 扩容的时候
29. hashmap jdk1.7下线程不安全的场景？ 
30. hashmap jdk1.7中put方法流程？ 初始化 寻址 冲突 赋值 扩容
31. hashmap jdk1.8中的数据结构？
32. hashmap jdk1.8下线程不安全的场景？
33. hashmap jdk1.8下如何扩容？
34. hashmap jdk1.8 下put方法流程？  初始化 寻址 冲突 赋值 扩容
35. hashmap 初始值为什么是16
36. 什么时候触发扩容？ 
37. 加载因子是做什么的？
38. 加载因子为什么是0.75？ 调整大了会怎样？ 调整小了会怎样？
39. 什么时候链表转成红黑树？ 链表长度>=8 并且 数组长度>64
40. hashmap扩容流程？ 区分jdk1.7 和 jdk1.8
41. 数组下标是如何确定的？ 位运算 
42. 讲一下什么是扰动机制，目的是什么？ 
43. HashTable底层数据结构以及特点？
44. 如何确保hashmap线程安全，有哪些方法？ 
45. 讲一下concurrentHashmap在jdk1.7 和 jdk1.8下的数据结构？ 有什么优化？ 并发度
46. concurrnetHashMap是如何确保线程安全的？ ReentrentLock    synchronized + cas
47. concurrentHashMap在jdk1.7下扩容和在jdk1.8下的扩容过程讲一下？
48. concurrentHashMap put方法和get方法 不同版本下，如何实现讲一下？
49. [LinkedHashMap 源码详细分析（JDK1.8）](https://www.imooc.com/article/22931)
50. LinkedHashMap底层数据结构以及特点？
51. **LinkedHashMap 如何保证 有序性**
52. LinkedHashMap如何实现LRU算法？
53. **什么是WeakHashMap?**

> [以上参考文档链接 🔗](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%AE%B9%E5%99%A8.md)