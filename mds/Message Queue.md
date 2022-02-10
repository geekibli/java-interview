
# 消息队列


1. [为什么需要消息队列？ 你的项目是如何使用MQ的？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md#为什么使用消息队列)
2. 讲一下什么是发布/订阅消息模式？
3. [消息队列有哪些使用场景？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md)
   1. [如何理解消息队列在异步处理方面的应用？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md#异步)
   2. [消息队列是如何处理流量削峰的？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md#削峰)
   3. [消息队列进行系统解耦合？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md#解耦)
4. [消息队列有什么优缺点](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md#消息队列有什么优缺点)
5. [Kafka、ActiveMQ、RabbitMQ、RocketMQ 有什么优缺点？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/why-mq.md#kafkaactivemqrabbitmqrocketmq-有什么优缺点)
6. [消息队列如何保证高可用](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-high-availability-of-message-queues.md#面试题)
7.  [kafka如何保证高可用](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-high-availability-of-message-queues.md#kafka-的高可用性)
8.  [如何保证消息不被重复消费？ 如何保证消息消费的幂等性？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-that-messages-are-not-repeatedly-consumed.md)
9.  [如何解决消息丢失的问题？ 如何保证消息传输的可靠性](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-the-reliable-transmission-of-messages.md#面试题)
    1.  [kafka如何处理消息丢失的问题？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-the-reliable-transmission-of-messages.md#kafka)
    2.  [rabbitmq如何解决消息丢失问题？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-the-reliable-transmission-of-messages.md#rabbitmq)
10. [如何保证消息的顺序性？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/how-to-ensure-the-order-of-messages.md)
11. [如何解决消息队列的延时以及过期失效问题？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/mq-time-delay-and-expired-failure.md#mq-中的消息过期失效了)
12. [有几百万消息持续积压几小时，说说怎么解决？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/mq-time-delay-and-expired-failure.md#大量消息在-mq-里积压了几个小时了还没解决)
13. [消息队列满了以后该怎么处理？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/mq-time-delay-and-expired-failure.md#mq-都快写满了)
14. [RocketMQ官方针对消息积压问题提供的解决方案？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/mq-time-delay-and-expired-failure.md#1-提高消费并行度)
15. [如果让你写一个消息队列，该如何进行架构设计？](https://github.com/doocs/advanced-java/blob/main/docs/high-concurrency/mq-design.md)



## 💾 资料 

- [CS-Notes github 消息队列](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E6%B6%88%E6%81%AF%E9%98%9F%E5%88%97.md)