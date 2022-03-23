## 分布式系统&中间件总结

#### roadmap

概念 -> 实践 -> 源码 -> 自定义组件

#### 分布式系统

- [分布式系统-CAP理论、BASE理论]()
- [分布式系统-全局唯一ID实现方案](/docs/general/分布式系统-全局唯一ID实现方案.md)
- [分布式系统-分布式事务及实现方案](/docs/general/分布式系统-分布式事务及实现方案.md)
- [分布式系统-分布式会话及实现方案](/docs/general/分布式系统-分布式会话及实现方案.md)
- [分布式系统-分布式缓存及方案实现](/docs/general/分布式系统-分布式缓存及方案实现.md)
- [分布式系统-分布式锁及实现方案](/docs/general/分布式系统-分布式锁及实现方案.md)
- [分布式系统-幂等性问题解决方案](/docs/general/分布式系统-如何保证接口幂等.md)
- [分布式系统-一致性哈希实现方案](/)
- [分布式系统-分布式链路追踪](/)
- [架构之高可用：负载均衡](/docs/general/架构之高可用：负载均衡.md)
- [架构之高并发：缓存](/docs/general/架构之高并发：缓存.md)
- [架构之高并发：降级和熔断](/docs/general/架构之高并发：降级和熔断.md)
- [架构之高并发：限流](/docs/general/架构之高并发：限流.md)
- [系统设计：RESTful API最佳实践]()

#### 中间件-MySQL系列

- [MySQL-数据类型](/docs/mysql/MySQL-数据类型.md)
- [MySQL-索引(B+树)](/docs/mysql/MySQL-索引(B+树).md)
- [MySQL-存储引擎](/docs/mysql/MySQL-存储引擎.md)
- [MySQL-性能优化](/docs/mysql/MySQL-性能优化.md)
- [MySQL-MySQL InnoDB的MVCC实现机制](/docs/mysql/MySQL-MySQL-InnoDB的MVCC实现机制.md)
- [MySQL-分表分库](/docs/mysql/MySQL-分表分库.md)
- [MySQL-主从复制与读写分离](/docs/mysql/MySQL-主从复制与读写分离.md)
- [MySQL-一条 SQL 的执行过程详解](/docs/mysql/MySQL-一条SQL的执行过程详解.md)

#### 中间件-redis系列

- [Redis入门-Redis概念和基础](/docs/redis/Redis入门-Redis概念和基础.md)
- [Redis入门-数据类型：3种特殊类型详解](/docs/redis/Redis入门-数据类型：3种特殊类型详解.md)
- [Redis入门-数据类型：5种基础数据类型详解](/docs/redis/Redis入门-数据类型：5种基础数据类型详解.md)
- [redis入门-数据类型：stream详解Redis入门-数据类型：Stream详解](/docs/redis/redis入门-数据类型：stream详解Redis入门-数据类型：Stream详解.md)
- [Redis进阶-数据结构：redis对象与编码(底层结构)对应关系详解](/docs/redis/Redis进阶-数据结构：redis对象与编码(底层结构)对应关系详解.md)
- [Redis进阶-数据结构：对象机制详解](/docs/redis/Redis进阶-数据结构：对象机制详解.md)
- [Redis进阶-数据结构：底层数据结构详解](/docs/redis/Redis进阶-数据结构：底层数据结构详解.md)
- [Redis进阶-事件：Redis事件机制详解](/docs/redis/Redis进阶-事件：Redis事件机制详解.md)
- [Redis进阶-性能调优：Redis性能调优详解](/docs/redis/Redis进阶-性能调优：Redis性能调优详解.md)
- [Redis进阶-持久化：RDB和AOF机制详解](/docs/redis/Redis进阶-持久化：RDB和AOF机制详解.md)
- [Redis进阶-高可用：主从复制详解](/docs/redis/Redis进阶-高可用：主从复制详解.md)
- [Redis进阶-高可用：哨兵机制（Redis Sentinel）详解](/docs/redis/Redis进阶-高可用：哨兵机制（RedisSentinel）详解.md)
- [Redis进阶-高可拓展：分片技术（Redis Cluster）详解](/docs/redis/Redis进阶-高可拓展：分片技术（RedisCluster）详解.md)
- [Redis进阶-缓存问题：一致性, 穿击, 穿透, 雪崩, 污染等](/docs/redis/Redis进阶-缓存问题：一致性、穿击、穿透、雪崩、污染等.md)
- [Redis进阶-运维监控：Redis的监控详解](/docs/redis/Redis进阶-运维监控：Redis的监控详解.md)
- [Redis大厂经验-微博：万亿级日访问量下，Redis在微博的9年优化历程](/docs/redis/Redis大厂经验-微博：万亿级日访问量下，Redis在微博的9年优化历程.md)
- [Redis面试-redis问题总结](/docs/redis/Redis面试-redis问题总结.md)

#### 中间件-kafka系列

#### 中间件-mongo系列

#### 中间件-elasticsearch系列

- [ES详解-认知：ElasticSearch基础概念](/docs/elastic/ES详解-认知：ElasticSearch基础概念.md)
- [ES详解-认知：ElasticStack生态和场景方案](/docs/elastic/ES详解-认知：ElasticStack生态和场景方案.md)
- [ES详解-入门：查询和聚合的基础使用](/docs/elastic/ES详解-入门：查询和聚合的基础使用.md)
- [ES详解-索引：索引模板(Index Template)详解](/docs/elastic/ES详解-索引：索引模板(Index-Template)详解.md)
- [ES详解-索引：索引管理详解](/docs/elastic/ES详解-索引：索引管理详解.md)
- [ES详解-查询：DSL查询之Term详解](/docs/elastic/ES详解-查询：DSL查询之Term详解.md)
- [ES详解-查询：DSL查询之全文搜索详解](/docs/elastic/ES详解-查询：DSL查询之全文搜索详解.md)
- [ES详解-查询：DSL查询之复合查询详解](/docs/elastic/ES详解-查询：DSL查询之复合查询详解.md)
- [ES详解-聚合：聚合查询之Bucket聚合详解](/docs/elastic/ES详解-聚合：聚合查询之Bucket聚合详解.md)
- [ES详解-聚合：聚合查询之Metric聚合详解](/docs/elastic/ES详解-聚合：聚合查询之Metric聚合详解.md)
- [ES详解-聚合：聚合查询之Pipline聚合详解](/docs/elastic/ES详解-聚合：聚合查询之Pipline聚合详解.md)
- [ES详解-原理：ES原理之索引文档流程详解](/docs/elastic/ES详解-原理：ES原理之索引文档流程详解.md)
- [ES详解-原理：ES原理之读取文档流程详解](/docs/elastic/ES详解-原理：ES原理之读取文档流程详解.md)
- [ES详解-原理：ES原理知识点补充和整体结构](/docs/elastic/ES详解-原理：ES原理知识点补充和整体结构.md)
- [ES详解-原理：从图解构筑对ES原理的初步认知](/docs/elastic/ES详解-原理：从图解构筑对ES原理的初步认知.md)
- [ES详解-优化：ElasticSearch性能优化详解](/docs/elastic/ES详解-优化：ElasticSearch性能优化详解.md)
- [ES详解-大厂实践：腾讯万亿级 Elasticsearch 技术实践](/docs/elastic/ES详解-大厂实践：腾讯万亿级Elasticsearch技术实践.md)
- [ElasticSearch-备份和迁移](/docs/elastic/ElasticSearch-备份和迁移.md)