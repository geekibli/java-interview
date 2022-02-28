## Java容器

1. [说说 List, Set, Queue, Map 四者的区别？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E8%AF%B4%E8%AF%B4-list-set-queue-map-%E5%9B%9B%E8%80%85%E7%9A%84%E5%8C%BA%E5%88%AB)
2. [集合框架底层数据结构汇总](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6%E5%BA%95%E5%B1%82%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E6%80%BB%E7%BB%93)
3. set接口实现类有哪些？
4. [比较 HashSet、LinkedHashSet 和 TreeSet 三者的异同](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E6%AF%94%E8%BE%83-hashsetlinkedhashset-%E5%92%8C-treeset-%E4%B8%89%E8%80%85%E7%9A%84%E5%BC%82%E5%90%8C)
5. treeSet底层数据结构是什么？ 查询时间复杂度多少？ 红黑树 O(logn) 范围查询
6. hashSet底层实现是什么？ 查询复杂度多少？ hash表 O(1) 单值查询
7. [HashSet如何检查重复?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-02.md#hashset-%E5%A6%82%E4%BD%95%E6%A3%80%E6%9F%A5%E9%87%8D%E5%A4%8D)
8. linkedHashSet  具有 HashSet 的查找效率，并且内部使用双向链表维护元素的插入顺序
9. list的实现类有哪些？
10. [ArrayList是什么？](https://snailclimb.gitee.io/javaguide/#/docs/java/collection/arraylist-source-code?id=_1-arraylist-%e7%ae%80%e4%bb%8b)
11. ArrayList底层实现是什么？ 优缺点 动态数组 随机访问
12. [ArrayList如何提现随机访问？ RandomAccess 接口标识着该类支持快速随机访问。](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E8%A1%A5%E5%85%85%E5%86%85%E5%AE%B9randomaccess-%E6%8E%A5%E5%8F%A3)
13. ArrayList默认大小？ 10
14. [ArrayList扩容机制 `oldCapacity + (oldCapacity >> 1)` ](https://snailclimb.gitee.io/javaguide/#/docs/java/collection/arraylist-source-code?id=_3-arraylist-%e6%89%a9%e5%ae%b9%e6%9c%ba%e5%88%b6%e5%88%86%e6%9e%90)
15. ArrayList动态扩容性能？`Arrays.copyOf()` 内存
16. [System.arraycopy() 和 Arrays.copyOf()方法](https://javaguide.cn/java/collection/arraylist-source-code/#_3-2-%E4%B8%80%E6%AD%A5%E4%B8%80%E6%AD%A5%E5%88%86%E6%9E%90-arraylist-%E6%89%A9%E5%AE%B9%E6%9C%BA%E5%88%B6)
17. [讲一下ensureCapacity方法，你用过这个方法没有?](https://javaguide.cn/java/collection/arraylist-source-code/#_3-4-ensurecapacity%E6%96%B9%E6%B3%95)
18. ArrayList删除性能？ O(n)
19. [comparable和 Comparator的区别](https://segmentfault.com/a/1190000039361027)
20. [什么是fail-fast、fail-safe机制?](https://juejin.cn/post/6879291161274482695) [链接1](https://zhuanlan.zhihu.com/p/37476508) 
21. Vector底层实现？ 优缺点？ 动态数组 线程安全
22. Vector如何实现线程安全？
23. Vector扩容策略？ `oldCapacity + oldCapacity`
24. CopyOnWriteArrayList实现机制？
25. CopyOnWriteArrayList使用场景？
26. CopyOnWriteArrayList缺点？ 内存占用 读操作误差
27. [Arraylist 与 LinkedList 区别?](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#arraylist-%E4%B8%8E-linkedlist-%E5%8C%BA%E5%88%AB)
28. LinkedList底层实现？ 双向链表 顺序访问
29. [双向链表和循环双向链表](https://juejin.cn/post/6844903648154271757)
30. Queue实现类有哪些？
31. [Queue 与 Deque 的区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#queue-%E4%B8%8E-deque-%E7%9A%84%E5%8C%BA%E5%88%AB)
32. [PriorityQueue ： 基于堆结构实现，可以用它来实现优先队列。](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-01.md#%E8%AF%B4%E4%B8%80%E8%AF%B4-priorityqueue)
33. treemap底层数据结构以及特点？
34. [HashMap底层数据结构以及特点？](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/hashmap-source-code.md)
35. 解决hash冲突的方法？ 拉链 开放寻址
36. hashmap jdk1.7中的数据结构？ 数组 + 链表
37. [hashmap jdk1.7下链表闭环？ 头插法 扩容的时候](https://coolshell.cn/articles/9606.html)
38. hashmap jdk1.7下线程不安全的场景？ 
39. hashmap jdk1.7中put方法流程？ 初始化 寻址 冲突 赋值 扩容    
40. hashmap jdk1.8中的数据结构？
41. hashmap jdk1.8下线程不安全的场景？
42. hashmap jdk1.8下如何扩容？
43. [hashmap jdk1.8 下put方法流程？  初始化 寻址 冲突 赋值 扩容](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/hashmap-source-code.md#put-%E6%96%B9%E6%B3%95)
44. [hashmap 初始值为什么是16](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-02.md#hashmap-%E7%9A%84%E9%95%BF%E5%BA%A6%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF-2-%E7%9A%84%E5%B9%82%E6%AC%A1%E6%96%B9)
45. 什么时候触发扩容？ 
46. 加载因子是做什么的？
47. 加载因子为什么是0.75？ 调整大了会怎样？ 调整小了会怎样？
48. 什么时候链表转成红黑树？ 链表长度>=8 并且 数组长度>64
49. hashmap扩容流程？ 区分jdk1.7 和 jdk1.8
50. 数组下标是如何确定的？ 位运算 
51. 讲一下什么是扰动机制，目的是什么？ 
52. [HashMap 有哪几种常见的遍历方式?](https://mp.weixin.qq.com/s/zQBN3UvJDhRTKP6SzcZFKw)
53. HashTable底层数据结构以及特点？
54. [HashMap 和 Hashtable 的区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-02.md#hashmap-%E5%92%8C-hashtable-%E7%9A%84%E5%8C%BA%E5%88%AB)
55. [HashMap 和 HashSet 区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-02.md#hashmap-%E5%92%8C-hashset-%E5%8C%BA%E5%88%AB)
56. [HashMap 和 TreeMap 区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-02.md#hashmap-%E5%92%8C-treemap-%E5%8C%BA%E5%88%AB)
57. 如何确保hashmap线程安全，有哪些方法？ 
58. 讲一下concurrentHashmap在jdk1.7 和 jdk1.8下的数据结构？ 有什么优化？ 并发度
59. [ConcurrentHashMap 和 Hashtable 的区别](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java-collection-questions-02.md#concurrenthashmap-%E5%92%8C-hashtable-%E7%9A%84%E5%8C%BA%E5%88%AB)
60. [concurrnetHashMap是如何确保线程安全的？ ReentrentLock    synchronized + cas](https://www.cnblogs.com/chengxiao/p/6842045.html)
61. concurrentHashMap在jdk1.7下扩容和在jdk1.8下的扩容过程讲一下？
62. concurrentHashMap put方法和get方法 不同版本下，如何实现讲一下？
63. [LinkedHashMap 源码详细分析（JDK1.8）](https://www.imooc.com/article/22931)
64. LinkedHashMap底层数据结构以及特点？
65. **LinkedHashMap 如何保证 有序性**
66. LinkedHashMap如何实现LRU算法？
67. **什么是WeakHashMap?**
68. [java集合使用注意事项](https://github.com/Snailclimb/JavaGuide/blob/main/docs/java/collection/java%E9%9B%86%E5%90%88%E4%BD%BF%E7%94%A8%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md)

> [以上参考文档链接 🔗](https://github.com/CyC2018/CS-Notes/blob/master/notes/Java%20%E5%AE%B9%E5%99%A8.md)