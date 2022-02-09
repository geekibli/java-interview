# MySQL


## mysql系统

1. mysql的整体架构是怎样的？
2. 一条update语句是如何执行的？
3. 谈谈什么是redo log？ 环
4. 谈谈什么是 binlog？  有几种格式？ row statement mixed
5. 谈谈什么是两阶段提交？ redo log 和 binlog
6. redo log 为什么这么设计，有什么优势？ sql顺序io
7. 什么是change buffer
8. 常见的存储引擎有哪些？ 
9. InnoDB VS MyISAM
10. INT(11)中的11的意义是什么？
11. double(5,3) 5和3的意义分别是什么？ 11.234
12. char vs varchar
13. datetime vs timestamp？     8字节 4字节
14. 什么是水平切分？ 什么是垂直拆分？
15. mysql主从复制的原理？
16. 如何实现读写分离？
17. 常见分库分表的策略有哪些？
18. 分库分表分别解决哪些问题？
19. **数据库三范式**


## sql语法

1. 什么是MDL？ DDL？ DCL？
2. sql执行顺序？ 一条sql执行的顺序。orderby groupby having等等？
3. 如何创建数据库？ create database name
4. 如何选择数据库？ use
5. 如何创建表？ create
6. 如何添加一列？ alter table name add col char(10);
7. 如何删除一列？ alter table T_name drop column col;
8. 如何删除一张表？ drop table t_name
9. mysql中有哪些自带的函数？ avg min max count sum
10. 字符串函数都有哪些？ left right ltrim rtrim length lower upper...
11. count(*) count(1) count(column) 区别？
12. mysql有哪些连接操作？ 
13. 如何创建账户 CREATE USER myuser IDENTIFIED BY 'mypassword';
14. 如何修改账户名 RENAME USER myuser TO newuser;
15. 如何删除账户 DROP USER myuser;
16. 如何查看权限 SHOW GRANTS FOR myuser;
17. 如何授予权限  GRANT SELECT, INSERT ON mydatabase.* TO myuser;
18. 如何删除权限？ REVOKE SELECT, INSERT ON mydatabase.* FROM myuser;
19. 如何更改密码？ SET PASSWROD FOR myuser = Password('new_password');




## 索引&优化

1.  什么是索引？ 为什么需要索引？
2.  mysql索引的数据结构常见的有哪些？
3.  为什么没有使用红黑树作为索引底层的数据结构？
4.  hash表作为索引结构的优缺点？
5.  分析Btree和B+tree，B+tree有哪些优点？
6.  b+tree添加数据的过程？
7.  什么是磁盘预读特性？ 空间局部性原理
8.  什么是全文索引？ 倒排索引
9.  谈谈索引优化？
10. 什么是前缀索引？ 
11. 什么是最左前缀原则？
12. 什么是覆盖索引？
13. 什么是回表？
14. 什么是索引下推 ICP ？
15. 如何查看执行计划？ explain
16. 为什么唯一索引不适合使用change buffer？
17. 为什么建议自增的整形主键？
18. 如果没有创建主键会怎样？
19. 什么叫做聚集索引和非聚集索引？
20. 什么叫做二级索引？
21. 讲一下order by的底层逻辑是什么？ sort buffer
22. 什么情况下会产生临时表？


## 事务与锁机制

1. 什么是行锁？什么是表锁？
2. 什么是元数据锁 mdl？
3. 什么是全局锁？
4. 什么是死锁？ 如何解决死锁问题？
5. 什么是意向锁？
6. 什么是事务？
7. 事务有什么特性？
8. mysql的事务隔离级别有哪些？ 默认的事务隔离界别是什么？
9. 不同的事务级别下分别有哪些问题？
10. 如何修改事务和查看事务隔离级别？
11. mysql中如何开启一个事务？
12. 什么是脏读？
13. 什么是可重复读？
14. 什么是幻读？
15. 什么是当前读？ 什么是快照读？
16. 什么是一致性试图？
17. 一致性视图在什么时候创建的？
18. 一致性试图的可见性原则是什么？
19. 什么是mvcc？ 为什么需要mvcc？ 优化一般读写并发度
20. RR级别下如何解决幻读问题？
21. 什么是间隙锁？
22. 什么是临键锁？
23. 



## mysql资料💾
- [CS-Notes Github mysql](https://github.com/CyC2018/CS-Notes/blob/master/notes/MySQL.md)
- [CS-Notes 数据库系统原理](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B3%BB%E7%BB%9F%E5%8E%9F%E7%90%86.md)