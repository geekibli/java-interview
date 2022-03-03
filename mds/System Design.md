# 系统设计问题



## 系统设计

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
8. [系统设计面试题：综合考察面试者的大招](https://www.wangtianyi.top/blog/2018/08/31/xi-tong-she-ji-mian-shi-ti-zong-he-kao-cha-mian-shi-zhe-de-da-zhao/?utm_source=github&utm_medium=github)
9. [如何设计一个高并发系统？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/high-concurrency-design.md)
10. [为什么要进行系统拆分？如何进行系统拆分？拆分后不用 dubbo 可以吗？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/why-dubbo.md)
11. [如何自己设计一个RPC框架？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/dubbo-rpc-design.md)
12. [**zookeeper 都有哪些使用场景？**](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/zookeeper-application-scenarios.md)
13. [分布式事务了解吗？ 有哪些解决方案？]()  // TODO
14. [设计一个高并发发红包系统？](https://github.com/xbox1994/Java-Interview/blob/master/MD/系统设计-高并发抢红包.md)
15. [设计一个秒杀系统？](https://github.com/qiurunze123/miaosha) [why神](https://mp.weixin.qq.com/s?__biz=Mzg3NjU3NTkwMQ==&mid=2247520243&idx=1&sn=270f0f6f5981fb1ad73f35b706d744b2&chksm=cf32e201f8456b17850060db61e9480487453d08ec8a886a51d10b006bfb0f918ce99145ec05#rd)
16. 设计一个微博feed流/信息流系统?
17. 如何设计一个短链系统?
18. 如何设计一个站内消息系统?
19. 如何解决大文件上传的问题？
20. 如何统计网站的UV？
21. [设计一个敏感词过滤系统，有什么思路？](https://zhuanlan.zhihu.com/p/65115496) [链接1](https://github.com/Snailclimb/JavaGuide/blob/main/docs/system-design/security/sentive-words-filter.md)
22. [京东毫秒级热key探测框架设计与实践，已实战于618大促](https://mp.weixin.qq.com/s/xOzEj5HtCeh_ezHDPHw6Jw) [Gitee](https://gitee.com/jd-platform-opensource/hotkey#https://gitee.com/link?target=https%3A%2F%2Fmp.weixin.qq.com%2Fs%2FxOzEj5HtCeh_ezHDPHw6Jw)
23. [如何设计一个并行框架](https://gitee.com/jd-platform-opensource/asyncTool)
24. 
   
### 💾 资料

- [CS-Notes github 系统设计基础](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1%E5%9F%BA%E7%A1%80.md)



## 分布式

1. [什么是分布式架构？](https://developer.aliyun.com/article/44562) 
2. 什么是分布式锁？ 什么场景下需要使用到分布式锁？
3. 分布式锁的常见实现方式都有哪些？
   1. 使用数据库实现分布式锁都有哪些方式呢？
      1. 数据库实现分布式锁的缺点有哪些？
   2. [讲述一下如何使用redis实现分布式锁？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-lock-redis-vs-zookeeper.md#redis-分布式锁)
      1. setnx
      2. redlock
      3. redission
   3.[如何使用zookeeper实现分布式锁？ 原理是什么？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-lock-redis-vs-zookeeper.md#zk-分布式锁)
4. [什么是分布式事务？ 什么场景下会使用到分布式事务？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-transaction.md)
5. [分布式事务都有哪些实现方式呢？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-transaction.md)
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


