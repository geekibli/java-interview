# 系统设计问题



## 设计基础

1. 测评性能的指标都有哪些？ 
   1. 什么叫做响应时间？
   2. 什么叫做吞吐量？
   3. 什么叫做并发用户数？
2. 什么叫做伸缩性？
3. 如何判定性能是否与伸缩性有关？ 或者系统是否可以通过调整伸缩性来优化性能？
4. 什么叫做扩展性？ 如何实现系统的可扩展？
5. 说一下什么是可用性？ 
6. 可用性一般都有哪些方面？ 一般都如何解决呢？     节点冗余  主从  主备  监控 降级
7. 如何保障安全性？
8. [如何设计一个高并发系统？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/high-concurrency-design.md)
9. [为什么要进行系统拆分？如何进行系统拆分？拆分后不用 dubbo 可以吗？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/why-dubbo.md)
10. [如何自己设计一个RPC框架？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/dubbo-rpc-design.md)
11. [zookeeper实现分布式锁？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-lock-redis-vs-zookeeper.md#zk-分布式锁)
12. [**redis如何实现分布式锁？**](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-lock-redis-vs-zookeeper.md#redis-分布式锁)
13. [**zookeeper 都有哪些使用场景？**](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/zookeeper-application-scenarios.md)
14. [分布式事务了解吗？ 有哪些解决方案？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-transaction.md)  // TODO
   
### 💾 资料

- [CS-Notes github 系统设计基础](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1%E5%9F%BA%E7%A1%80.md)




## 分布式

1. [什么是分布式架构？](https://developer.aliyun.com/article/44562) 
2. 什么是分布式锁？ 什么场景下需要使用到分布式锁？
3. 分布式锁的常见实现方式都有哪些？
   1. 使用数据库实现分布式锁都有哪些方式呢？
      1. 数据库实现分布式锁的缺点有哪些？
   2. 讲述一下如何使用redis实现分布式锁？
      1. setnx
      2. redlock
      3. redission
   3. 如何使用zookeeper实现分布式锁？ 原理是什么？
4. 什么是分布式事务？ 什么场景下会使用到分布式事务？
5. 分布式事务都有哪些实现方式呢？
   1. 讲一下两阶段提交（2PC）?
      1. 两阶段提交的具体流程是怎样的？
      2. 两阶段提交有什么弊端？ 
   2. 本地消息表实现分布式事务的原理？
6. [**讲一下CAP理论，以及各自的含义？**](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-system-cap.md)
7. 为什么CAP只能保证其中的2个？
8. 什么是BASE理论？ 
9. 讲一下Paxos算法？
10. 讲一下Raft协议？ 主要用途？
11. 分布式缓存
12. 分布式Session
13. 分布式任务调度
14. [分布式服务接口幂等性如何处理？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-system-idempotency.md)
15. [分布式服务接口请求的顺序性如何保证？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-system-request-sequence.md)


### 💾 资料

- [CS-Notes github 分布式](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E5%88%86%E5%B8%83%E5%BC%8F.md)
- 




## 集群

1. [什么叫做集群？](https://developer.aliyun.com/article/44562)
2. 什么叫做负载均衡？
3. 常见的负载均衡策略都有哪些？ 
4. 请求转发的实现方式有哪些？ 
5. 集群下session如何进行管理？ 


### 💾 资料

- [CS-Notes github 集群](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E9%9B%86%E7%BE%A4.md)




## 攻防安全

1. 跨站脚本攻击（Cross-Site Scripting, XSS）是什么？ 如何规避？ 
2. 跨站请求伪造（Cross-site request forgery，CSRF）是什么？  如何规避？
3. 拒绝服务攻击（denial-of-service attack，DoS）是什么？ 如何规避？
4. SQL注入是什么？ 如何规避？


## 缓存问题

1. 常见的缓存有哪些？ 
2. 什么是CDN?  具备哪些优点？ 
3. 什么是一致性hash算法？
4. 什么是LRU算法？
5. 什么是LFU算法？
6. 如何使用java实现LRU算法？      linkedHashMap




### 💾 资料
 
- [CS-Notes github 缓存](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E7%BC%93%E5%AD%98.md)


