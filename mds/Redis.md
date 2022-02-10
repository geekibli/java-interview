# Redis

1. [为什么会有缓存或者redis？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-cache.md)
2. 什么是Redis？ 概念是什么？ 全称是什么？ 
3. [什么是非关系型数据库？ 什么是关系型数据库？](https://blog.csdn.net/clover_lily/article/details/79991300)
4. 非关系型数据库 VS 关系型数据库
5. Redis Vs MySQL
6. [Redis支持的数据类型有哪些？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-data-types.md)
7. String类型的底层实现？
8. String类型的编码方式有哪些 ？ integer row mixd
9. String类型的key最大容量？ 512MB
10. List类型的常用场景？
11. List常用的API操作？
12. List底层的实现方式有哪些？
13. Set类型的底层实现方式？
14. ZSet底层的实现方式？ 底层数据结构？
15. Hash结构底层的实现方式？
16. 如何解决hash冲突？
17. [什么是渐进式哈希？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-rehash.md)
18. 说一下 字典表dictht数据结构？
19. 讲一下hash的扩容过程？
20. 什么是跳跃表？ SkipList 多指针有序链表？ 可二分查找
21. 跳跃表的查找过程？ 从上层查找，然后到下层查找，类似于二分查找
22. 跳跃表有什么优点？
23. redis常见的使用场景有哪些？
24. 如何利用redis实现排行榜的功能？ zset
25. 如何使用redis实现点赞的功能？ zset / list
26. 如何使用redis实现签到的功能？ bitmap
27. 如何使用redis实现‘可能认识的朋友’功能？ set 求交集
28. [redis vs memcached](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-single-thread-model.md#redis-和-memcached-有啥区别)
29. [redis持久化的两种方式？ AOF RDB](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-persistence.md#redis-持久化的两种方式)
    1. [RDB 优缺点](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-persistence.md#rdb-优缺点)
    2. [AOP 优缺点](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-persistence.md#aof-优缺点)  
30. [redis的过期策略有哪些？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-expiration-policies-and-lru.md#redis-过期策略)
31. [redis的内存淘汰策略有哪些？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-expiration-policies-and-lru.md#内存淘汰机制) 
32. [手写一个LRU算法](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-expiration-policies-and-lru.md#手写一个-lru-算法)
33. redis如何实现事务功能？ MULTI 和 EXEC ， watch？
34. [redis底层的线程模型？ 多路复用  ](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-single-thread-model.md#redis-的线程模型)
35. [为什么redis是单线程效率还这么高？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-single-thread-model.md#redis-的线程模型)
36. [谈一下redis的主从架构](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-expiration-policies-and-lru.md#手写一个-lru-算法)
37. [Redis replication 的核心机制](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-master-slave.md#redis-replication-的核心机制)
38. 如何设置redis主从？slaveof host port 
39. redis是否支持主主复制？ 不支持 一个从服务器只能有一个主服务器
40. [redis主从复制原理是什么？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-master-slave.md#redis-主从复制的核心原理)
41. [redis主从复制的过程？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-master-slave.md#复制的完整流程)
42. [什么是无磁盘化复制？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-master-slave.md#无磁盘化复制)
43. [哨兵如何实现redis的高可用](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-sentinel.md#redis-哨兵集群实现高可用)
44. [slava到master的选举算法](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-sentinel.md#slave-master-选举算法)
45. [分布式寻址算法有哪些？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-cluster.md#分布式寻址算法)
46. [Redis cluster 的高可用与主备切换原理?](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-cluster.md#redis-cluster-的高可用与主备切换原理)
47. [如何保证缓存一致性？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-consistence.md)
48. [什么是缓存雪崩？ 如何解决？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-caching-avalanche-and-caching-penetration.md#缓存雪崩)
49. [什么是缓存击穿？ 如何解决？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-caching-avalanche-and-caching-penetration.md#缓存击穿)
50. [什么是缓存穿透？ 如何解决？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-caching-avalanche-and-caching-penetration.md#缓存穿透)
51. [Redis 的并发竞争问题是什么？如何解决这个问题？了解 Redis 事务的 CAS 方案吗？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-cas.md)
52. [生产环境中的 Redis 是怎么部署的？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/redis-production-environment.md)
53. [redis如何实现分布式锁？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-lock-redis-vs-zookeeper.md#redis-分布式锁)


## redis资料💾
- [CS-Notes Github Redis](https://github.com/CyC2018/CS-Notes/blob/master/notes/Redis.md) 
