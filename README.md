基础

2020年11月19日

0:35

# Jvm

Jvm概述 ： https://blog.csdn.net/liuwenbo0920/article/details/53886431

Java内存模型 ：http://www.hollischuang.com/archives/2509 

JVM老年代和新生代的比例: https://www.cnblogs.com/shoshana-kong/p/11314677.html

可作为GC Root的对象: https://blog.csdn.net/sinat_36246371/article/details/72903233

Java垃圾收集器及算法比对 ： https://blog.csdn.net/tjiyu/article/details/53983650

Classloader加载机制 ：[https://www.cnblogs.com/aspirant/p/7200523.html ](https://www.cnblogs.com/aspirant/p/7200523.html)

字符串常量池、class常量池和运行时常量池: https://blog.csdn.net/qq_26222859/article/details/73135660

CMS垃圾收集器产生的问题和解决方案: https://my.oschina.net/hosee/blog/674181

JVM：内存监视手段及各区域内存溢出解决： https://blog.csdn.net/jiyiqinlovexx/article/details/51171452

G1垃圾收集器: https://hllvm-group.iteye.com/group/topic/44381#post-272188 

 https://blog.csdn.net/lijingyao8206/article/details/80566384

ZGC: https://zhuanlan.zhihu.com/p/105921339

https://mp.weixin.qq.com/s/ag5u2EPObx7bZr7hkcrOTg

[https://tech.meituan.com/2020/08/06/new-zgc-practice-in-meituan.html ](https://tech.meituan.com/2020/08/06/new-zgc-practice-in-meituan.html)

https://juejin.cn/post/6844904057916620813

深度解析默认 hashCode() 的工作机制 https://mp.weixin.qq.com/s/O8SIoyICc5NmZOBbjlCXhg 

SPI机制： https://developer.aliyun.com/article/640161

JDK动态代理实现原理: https://www.cnblogs.com/zuidongfeng/p/8735241.html

Arthas实战: https://blog.csdn.net/zhang_jiayuan/article/details/109261904

CMS 垃圾回收器: https://cloud.tencent.com/developer/article/1624694

https://www.cnblogs.com/aspirant/p/8663911.html

JVM 三色标记法: https://blog.csdn.net/stone_tomcate/article/details/105588780

软引用、弱引用、虚引用： https://juejin.cn/post/6844903665241686029

 

# 集合

HashMap的死循环: https://juejin.im/post/5a66a08d5188253dc3321da0 

HashMap为何从头插入改为尾插入:  https://juejin.im/post/6844903682664824845

 http://ifeve.com/hashmap-infinite-loop/

Java8的HashMap详解（存储结构，功能实现，扩容优化，线程安全，遍历方法）: 

https://cloud.tencent.com/developer/article/1806707

https://blog.csdn.net/login_sonata/article/details/76598675 
 CopyOnWriteArrayList实现原理以及源码解析: https://www.cnblogs.com/heqiyoujing/p/11144803.html

ConcurrentHashMap 原理解析（JDK1.8）: https://cloud.tencent.com/developer/article/1129465

 https://segmentfault.com/a/1190000016066203

https://crossoverjie.top/2018/07/23/java-senior/ConcurrentHashMap/

深入理解HashMap+ConcurrentHashMap的扩容策略: https://www.cnblogs.com/lfs2640666960/p/9621461.html

深入理解 hashcode() 和 HashMap 中的hash 算法: https://blog.csdn.net/q5706503/article/details/85114159

红黑树： https://zhuanlan.zhihu.com/p/143396578

hashCode 跟 Equals 方法 : https://blog.csdn.net/javazejian/article/details/51348320

LinkedHashMap原理: https://www.jianshu.com/p/8f4f58b4b8ab

 

 

 

数据库

2020年11月19日

0:36

 

# 数据库

数据库隔离级别 ： https://blog.csdn.net/jianghuchuanke/article/details/81026355

MySQL InnoDB中的行锁 Next-Key Lock消除幻读： https://quguang.wang/post/mysql-next-key-lock/

表锁和行锁 : https://juejin.im/entry/5a55c7976fb9a01cba42786f

MVCC : https://mp.weixin.qq.com/s/2VwtExIKJV9fPFNwZjUW6g

MySQL中事务的实现： https://mp.weixin.qq.com/s/qw8m4TdX0sta3utiOglFPg

 https://draveness.me/mysql-transaction

MySQL乐观锁实现线程安全： https://segmentfault.com/q/1010000000215640

MySQ复制，数据一致性： https://www.cnblogs.com/ivictor/p/5735580.html

阿里巴巴分库分表 ： https://mp.weixin.qq.com/s/5bG563TGy5tDaV9WTNXA7A

分表分库： https://juejin.im/entry/591968f6a0bb9f005ff7af23

美团分库分表: https://tech.meituan.com/2016/11/18/dianping-order-db-sharding.html

索引的级别： https://blog.csdn.net/xtdhqdhq/article/details/20377273

B+树原理： https://zhuanlan.zhihu.com/p/149287061 

https://zhuanlan.zhihu.com/p/54102723

MySQL索引原理之聚簇索引: https://blog.csdn.net/lisuyibmd/article/details/53004848

MySQL索引解析（联合索引/最左前缀/覆盖索引）: 

https://my.oschina.net/u/4287823/blog/4335429

索引下推： https://blog.csdn.net/weichi7549/article/details/108179998 

MySQL索引背后的数据结构及算法原理 : http://blog.codinglabs.org/articles/theory-of-mysql-index.html

MySQL实现两主多从架构: https://blog.csdn.net/cs729298/article/details/70255245

MySQL 8.0 之Index Skip Scan: https://cloud.tencent.com/developer/article/1641469

数据库连接池到底应该设多大 https://www.cnblogs.com/luoahong/articles/9007444.html

https://github.com/brettwooldridge/HikariCP/wiki/About-Pool-Sizing

B tree和B+ tree的区别及原理: https://zhuanlan.zhihu.com/p/27700617

MYSQL索引失效的各种情形总结: https://blog.csdn.net/weixin_33843947/article/details/91496226

join原理

https://mp.weixin.qq.com/s/MD8OBQ4ZxK9OgCbL1tT2Ig

InnoDB的磁盘文件及落盘机制： https://juejin.im/post/6844903672762089485

Mysql隔离性之Read View: https://blog.csdn.net/longgeqiaojie304/article/details/98872857

https://zhuanlan.zhihu.com/p/166152616

深入理解数据库行锁与表锁: https://zhuanlan.zhihu.com/p/52678870

https://www.cnblogs.com/itdragon/p/8194622.html

MySQL BTree索引和hash索引的区别: https://blog.csdn.net/oChangWen/article/details/54024063

阿里数据库专家的文章： https://github.com/hedengcheng/tech/tree/master/database/MySQL

WAL(事务底层原理): https://zhuanlan.zhihu.com/p/137512843 

https://cloud.tencent.com/developer/article/1163460

为什么Mongodb索引用B树，而Mysql用B+树: https://zhuanlan.zhihu.com/p/107228878

 

 

Redis

2020年11月19日

0:37

 

# Redis

Redis高频面试题: https://www.codenong.com/cs106264559/

Redis底层数据结构: https://juejin.cn/post/6844903936520880135

Redis正确加分布式锁的方式： https://segmentfault.com/a/1190000020631732

https://blog.huoding.com/2015/09/14/463

https://www.shangyun51.com/articledetail?id=4276

RedLock算法-使用Redis实现分布式锁服务： 

https://blog.csdn.net/varyall/article/details/88422492

https://juejin.cn/post/6844904039218429960

Redis集群种类，优缺点： https://juejin.im/post/5db851706fb9a0203c34de54 

降低Redis内存使用与减少请求延迟: https://blog.csdn.net/yockie/article/details/79929739

Redis持久化（RDB、AOF、混合持久化） https://www.cnblogs.com/chichung/p/12687101.html

redis4.0之RDB-AOF混合持久化: https://developer.aliyun.com/article/193034

Redis使用SDS的原因: https://blog.csdn.net/keq_keq/article/details/88749554

[https://blog.csdn.net/qq_35152037/article/details/84583573 ](https://blog.csdn.net/qq_35152037/article/details/84583573)

https://www.shangyexinzhi.com/article/1878437.html

Redis扩容、分片： https://www.infoq.cn/article/UIqypvrTNQ4BuErrm3Dc

https://zhuanlan.zhihu.com/p/99037321

Redis大key和热key的解决方案:

https://juejin.cn/post/6844903743083773959

https://www.cnblogs.com/rjzheng/p/10874537.html

Redis集群之Redis-Cluster实践详解: https://blog.csdn.net/J080624/article/details/103121930 

Redis分布式锁的原理以及如何续期: https://blog.csdn.net/lzhcoder/article/details/88387751

使用Redis SETNX 命令实现分布式锁： https://blog.csdn.net/lihao21/article/details/49104695

Redis集群：https://www.cnblogs.com/leeSmall/p/8414687.html 

Redis Sentinel: https://xiaoyue26.github.io/2019/02/24/2019-02/redis设计与实现笔记8-sentinel哨兵模式

Redis主从同步: [https://zhuanlan.zhihu.com/p/55532249 ](https://zhuanlan.zhihu.com/p/55532249)

Redis 缓存雪崩、击穿、穿透: https://segmentfault.com/a/1190000022029639 

 https://blog.csdn.net/womenyiqilalala/article/details/105205532

Redis布隆过滤开源实现（基于redis模块开发）： https://github.com/RedisLabsModules/redisbloom

Redis过期策略实现原理: 

https://blog.csdn.net/xiangnan129/article/details/54928672

https://segmentfault.com/a/1190000023060522

Redis内部数据结构之跳表: 

https://juejin.cn/post/6844903446475177998

https://www.jianshu.com/p/09c3b0835ba6

List数据类型底层编码转换: https://juejin.cn/post/6855129008071016456

https://mp.weixin.qq.com/s/Ok0laJMn4_OzL-LxPTHawQ

Redis渐进式Rehash机制: http://dwz.date/aWcn 

http://redisbook.com/preview/dict/incremental_rehashing.html

Redis限流： https://pandaychen.github.io/2020/09/21/A-DISTRIBUTE-GOREDIS-RATELIMITER-ANALYSIS/

Redis迁移期间查询: https://blog.csdn.net/qq_41453285/article/details/103395224

限流方案： https://segmentfault.com/a/1190000023552181

万亿级日访问量下，Redis 在微博的 9 年优化历程: https://www.21cto.com/article/2366

Redis如何实现异地多活？: https://zhuanlan.zhihu.com/p/96917394

HyperLogLog 基数统计应用场景: https://blog.csdn.net/maoyuanming0806/article/details/81814610

https://blog.csdn.net/ThinkWon/article/details/103522351

Redis-集群 redis cluster：和哨兵机制的本质区别？ https://juejin.im/post/6844903872519995400 

Redis Cluster 有哪些优势和限制？ https://cloud.tencent.com/developer/article/1541285

Redis并发扣库存： https://www.cnblogs.com/scy251147/p/8371636.html

Redis事务、MULTI 命令和EXEC 命令 https://www.it610.com/article/1288860623534366720.htm

Redis如何实现异地多活？ https://zhuanlan.zhihu.com/p/96917394

Redis Cluster 协议： https://zhuanlan.zhihu.com/p/328728595

Redis 发生高延迟原因： https://developer.aliyun.com/article/726785

Redis-AOF重写，AOF后台重写实现原理: https://blog.csdn.net/sand_clock/article/details/88624424

golang防缓存击穿利器--singleflight: https://segmentfault.com/a/1190000022347874

http://yangxikun.github.io/golang/2017/03/07/golang-singleflight.html

应对缓存击穿的解决方法: https://blog.csdn.net/sanyaoxu_2/article/details/79472465

Bloom Filter 的选型: https://www.modb.pro/db/32203

redis事务： https://cloud.tencent.com/developer/article/1189074

 https://cloud.tencent.com/developer/article/1189074

Redis 中 bgsave: 

 https://blog.csdn.net/zmflying8177/article/details/103500645

LRU和LFU算法以及其在Redis中的实现: https://my.oschina.net/lscherish/blog/4467394

如何处理redis集群的hot key和big key: https://zhuanlan.zhihu.com/p/52393940

https://www.cnblogs.com/rjzheng/p/10874537.html

redis-shake数据同步&迁移工具: https://developer.aliyun.com/article/691794

https://www.infoq.cn/article/redis-replication-redis-replicator

redis计数器 https://zhuanlan.zhihu.com/p/366250641

redis滑动窗口限流： https://www.haoyizebo.com/posts/e6aa238e/

 

 

分布式

2020年11月19日

0:36

 

# 分布式

Hash一致性： https://blog.csdn.net/justloveyou_/article/details/78313649 

分布式配置中心Apollo : 

 https://mp.weixin.qq.com/s/-hUaQPzfsl9Lm3IqQW3VDQ

移动端支付系统如何设计有效地防重: https://zhuanlan.zhihu.com/p/42035451

分布式事务选型的取舍（Saga Seata TCC）： https://www.infoq.cn/article/8bu33kuSyJ6P-wAAoELT

TCC分布式事务： https://juejin.im/post/5bf201f7f265da610f63528a

二阶段提交：https://blog.csdn.net/lengxiao1993/article/details/88290514

分布式系统的CAP理论 : https://zhuanlan.zhihu.com/p/33999708 

微服务分布式一致性模式: https://zhuanlan.zhihu.com/p/81081524

阿里分布式事务框架： https://seata.io/zh-cn/docs/overview/what-is-seata.html

ZooKeeper分布式锁: https://juejin.im/post/5c01532ef265da61362232ed

负载均衡SLB高可用的四个层次：https://developer.aliyun.com/article/191149

分布式系统调度，Zookeeper集群化管理: https://mp.weixin.qq.com/s/Yr4A95poVjlFsQ-Q0dF7hA 

Dapper，大规模分布式系统的跟踪系统: http://bigbully.github.io/Dapper-translation/ 

分布式系统：Lamport 逻辑时钟： https://developer.aliyun.com/article/689658

Skywalking分布式追踪： https://blog.csdn.net/wuzhiwei549/article/details/108856398 

mysql redolog binlog 之二阶段提交: https://blog.csdn.net/daijiguo/article/details/104982890

 

 

中间件

2020年11月19日

0:37

 

 

# Kafka

Kafka架构： https://zhuanlan.zhihu.com/p/38269875

https://zhuanlan.zhihu.com/p/114657208

Kafka 消息丢失与消费精确一次性: https://mp.weixin.qq.com/s/6-bgLMg5ISfB6i2pcPKGBg 

kafka顺序消费： https://blog.csdn.net/shangmingtao/article/details/79567921

基于Canal和Kafka实现MySQL的Binlog近实时同步: https://juejin.im/post/5e70dc2b6fb9a07cbd01f021

kafka的partition的 主从选举 、kafka 幂等 、ack: kafka权威指南第五-第六章

Kafka的Rebalance机制: https://blog.csdn.net/lzxlfly/article/details/106246879

https://www.cnblogs.com/chanshuyi/p/kafka_rebalance_quick_guide.html

Kafka的零拷贝: https://cloud.tencent.com/developer/article/1421266

Kafka分区分配策略: https://developer.aliyun.com/article/768415

kafka面试题： https://juejin.cn/post/6844904034722136072

Kafka为什么吞吐量大、速度快？: https://zhuanlan.zhihu.com/p/120967989

https://mp.weixin.qq.com/s/Z5L81WBw7lF45EBJi2Dgrg

Kafka时间轮(TimingWheel): https://juejin.cn/post/6844904110399946766

 

# Spring cloud

深入了解服务注册与发现 https://zhuanlan.zhihu.com/p/161277955

微服务的定义和优缺点 :https://zhuanlan.zhihu.com/p/31613331

Eureka注册中心集群如何实现客户端请求负载及故障转移？: https://segmentfault.com/a/1190000022994119 

spring cloud2 ribbon客户端负载故障重试转发: https://blog.csdn.net/dangshushu/article/details/80421344

Eureka Client源码分析:  https://cloud.tencent.com/developer/article/1443739

微服务注册中心如何承载大型系统的千万级访问: https://juejin.im/post/5be3f8dcf265da613a5382ca

微服务架构设计基础之领域驱动设计 https://juejin.im/post/6844903764634107911

Spring Cloud使用场景： https://juejin.im/post/5be13b83f265da6116393fc7

Spring Cloud Ribbon负载均衡策略: https://blog.csdn.net/u010816545/article/details/80461957

负载平衡算法：https://blog.csdn.net/sinat_36246371/article/details/78160448  

Hystrix的几种模式的使用: https://blog.csdn.net/weixin_41650839/article/details/100061856

Eureka通信过程: https://blog.csdn.net/cc907566076/article/details/77838502

grpc控制超时： https://blog.csdn.net/m0_38031406/article/details/104044904

https://docs.microsoft.com/zh-cn/aspnet/core/grpc/deadlines-cancellation?view=aspnetcore-5.0

微服务编排 https://zhuanlan.zhihu.com/p/78925640

 

# 其他中间件

RocketMQ实现分布式事务原理-消息事务：

 https://www.cnblogs.com/qdhxhz/p/11191399.html

https://mp.weixin.qq.com/s/9Vs7HiBfJnuNkeHDjrUafQ

mq保证消息可靠性 https://mp.weixin.qq.com/s/ZYXqmfGfBHabrbqvIX6hVw

etcd、Zookeeper和Consul一致键值数据存储的性能对比: https://my.oschina.net/dabird/blog/2052917

etcd 实现故障时主备秒级切换高可用架构 https://mp.weixin.qq.com/s/VFJg14JcapijOyhfJJMYUg

如果让你设计一个消息中间件： https://mp.weixin.qq.com/s/AzNfb7b6MmNUdGcsrwj9Iw

RocketMQ 消息的投递机制 https://cloud.tencent.com/developer/article/1443812

Elasticsearch如何做到数十亿数据查询毫秒级响应: https://zhuanlan.zhihu.com/p/99718374

Elasticsearch乐观锁： https://segmentfault.com/a/1190000021199668 

百亿级实时查询优化实战，让你的Elasticsearch飞起来： https://cloud.tencent.com/developer/article/1447804

Easticsearch部分更新： https://www.cnblogs.com/shoufeng/p/11348277.html 

PB 级大规模 Elasticsearch 集群运维与调优实践 https://mp.weixin.qq.com/s/OuACr9lNrzmWTbyiBLKq4w

rabbitmq死信队列： https://mfrank2016.github.io/breeze-blog/2020/05/04/rabbitmq/rabbitmq-how-to-use-dead-letter-queue/

 

 

并发

2020年11月19日

0:38

 

# 并发

线程池： https://tech.meituan.com/2020/04/02/java-pooling-pratice-in-meituan.html 

https://cloud.tencent.com/developer/article/1380284  

**Aqs** :https://zhuanlan.zhihu.com/p/52280869 

https://www.cnblogs.com/liqiangchn/p/11960944.html

https://mp.weixin.qq.com/s/2zDW1abkTUMKs6RuRyrPpw

https://www.cnblogs.com/liqiangchn/p/11960944.html

Synchronize原理 : 

https://blog.csdn.net/javazejian/article/details/72828483 

https://blog.csdn.net/yexianyi/article/details/4125633

CAS : https://zhuanlan.zhihu.com/p/34556594

volatile 原理： https://baijiahao.baidu.com/s?id=1663045221235771554&wfr=spider&for=pc

Java线程阻塞： https://blog.csdn.net/evane1890/article/details/3313416

进程通信：[https://mp.weixin.qq.com/s/SA0gjKHQL_6iMZBhBOZDEw ](https://mp.weixin.qq.com/s/SA0gjKHQL_6iMZBhBOZDEw)

线程池任务拒绝策略： https://blog.csdn.net/u010412719/article/details/52132613

https://www.cnblogs.com/diegodu/p/7381735.html

CountDownLatch （超出的直接执行 ）、CyclicBarrier Semaphore: https://blog.csdn.net/walle167/article/details/97933749

Synchronized与Lock的区别与应用场景： https://blog.csdn.net/fly910905/article/details/79765381

ReetrantLook condition: https://www.cnblogs.com/xiaoxi/p/7651360.html

Thread.sleep: https://www.zhihu.com/question/23328075/answer/111700419

Java线程上下文切换: https://juejin.im/post/5b10e53b6fb9a01e5b10e9be 

[https://zhuanlan.zhihu.com/p/79772089 ](https://zhuanlan.zhihu.com/p/79772089)

ThreadLocal原理： http://cmsblogs.com/?p=2442 

https://cloud.tencent.com/developer/article/1110183

乐观锁与悲观锁 : https://juejin.im/post/5b4977ae5188251b146b2fc8

自旋锁简单实现： https://blog.csdn.net/u010900754/article/details/77476936

线程的优先级、sleep()、yield()、join(): https://blog.csdn.net/u011936381/article/details/17511051

 线程状态： https://blog.csdn.net/doujinlong1/article/details/81289268

LinkedBlockingQueue与 ArrayBlockingQueue : https://blog.csdn.net/javazejian/article/details/77410889

公平锁跟非公平锁： https://blog.csdn.net/rickiyeat/article/details/78307739

偏向锁、轻量级锁、重量级锁: https://juejin.cn/post/6844903550586191885

线程池线程复用 ： https://blog.csdn.net/hollis_chuang/article/details/106798600

JAVA 的wait(), notify()与synchronized同步机制 https://www.cnblogs.com/x_wukong/p/4009709.html

ReentrantReadWriteLock源码及实现原理分析: https://blog.csdn.net/fxkcsdn/article/details/82217760

Java nio :https://mp.weixin.qq.com/s/O40MlDhAgCmcyUgu2jX1dg

 https://www.cnblogs.com/xiaoxi/p/6576588.html

nginx : https://blog.csdn.net/u012486840/article/details/53098890

IO多路复用机制详解: https://blog.csdn.net/chinabhlt/article/details/51983622

 https://blog.csdn.net/u011671986/article/details/79449853

响应式编程：[https://blog.csdn.net/qq_41737716/article/details/105913665 ](https://blog.csdn.net/qq_41737716/article/details/105913665)

https://www.zhihu.com/question/49618581

https://developer.aliyun.com/article/682897

在 Java 中一步步构建 I/O 多路复用的请求模型 : https://juejin.im/entry/6844903492121788429

为什么 Go 允许百万级别的 goroutines，而 Java 只允许数千级别的 threads:

https://zhuanlan.zhihu.com/p/162668146

Linux下的I/O复用与epoll详解: https://www.cnblogs.com/lojunren/p/3856290.html

https://mp.weixin.qq.com/s/OmRdUgO1guMX76EdZn11UQ

mmap: https://blog.csdn.net/qq_36675830/article/details/79283113

linux下共享内存mmap和DMA: https://www.cnblogs.com/sky-heaven/p/5956721.html

NIO效率高的原理之零拷贝与直接内存映射: https://cloud.tencent.com/developer/article/1488087

Redis单线程原理: https://juejin.im/post/6844903581783425037

https://segmentfault.com/a/1190000020252203

https://blog.csdn.net/A1373712651/article/details/82253030

如何搭建一个红包架构: https://cloud.tencent.com/developer/article/1097433

高并发库存扣减： https://www.iteye.com/blog/gao-xianglong-2400106

https://zhuanlan.zhihu.com/p/134012175

redis扣库存： https://zq99299.github.io/mysql-tutorial/ali-new-retail/06/01.html

高并发余额扣减： https://cloud.tencent.com/developer/news/312422 

https://www.zhihu.com/question/61484424

百亿级微信红包的高并发资金交易系统设计方案: https://www.infoq.cn/article/2017hongbao-weixin

红包算法：

https://www.zhihu.com/answer/85530416

tomcat线程模型： https://www.cnblogs.com/54chensongxia/p/13289174.html 

微信红包系统架构的设计和优化分享: https://www.cnblogs.com/chinanetwind/articles/9460820.html

京东抢购服务高并发实践: https://my.oschina.net/javahongxi/blog/807521

高性能短连接: https://juejin.cn/post/6844904090602848270

高并发下的请求合并: https://segmentfault.com/a/1190000038255460

高并发下单https://zhuanlan.zhihu.com/p/358037287

 

 

Spring

2020年11月19日

0:39

 

# Spring

Spring Boot 总结: https://segmentfault.com/a/1190000016686735

Spring Aop : https://www.cnblogs.com/hongwz/p/5764917.html

Spring源码解析之事务篇： http://www.linkedkeeper.com/1045.html

Spring Bean作用范围 : https://blog.csdn.net/elim168/article/details/75581612

Spring容器 :https://blog.csdn.net/chenssy/article/details/8188570

循环依赖： https://juejin.cn/post/6844904122160775176

 https://zhuanlan.zhihu.com/p/62382615

 

 

网络

2020年11月19日

0:40

 

# 网络

一台机器最多能撑多少个TCP连接? ： https://zhuanlan.zhihu.com/p/290651392

TCP 为什么三次握手而不是两次握手: https://blog.csdn.net/lengxiao1993/article/details/82771768 

HTTP和RPC概念： https://www.cnblogs.com/jokerjason/p/10696467.html

TCP 三次、四次握手 : https://blog.csdn.net/qzcsu/article/details/72861891

基于 Kotlin + Netty 实现一个简单的 TCP 自定义协议: https://cloud.tencent.com/developer/article/1677616

HTTPS原理： https://netsecurity.51cto.com/art/201912/607179.htm

TCP-IP详解：滑动窗口（Sliding Window）: https://blog.csdn.net/wdscq1234/article/details/52444277

TCP窗口拥塞控制： https://blog.csdn.net/baidu_33604078/article/details/78140120

KeepAlive的总结： https://blog.csdn.net/u014209205/article/details/81218656

Unix socket日志（日志写入socket不走磁盘）： https://alexstocks.github.io/html/log.html

Netty网络编程框架: 

 https://juejin.im/post/6858097664656211982

 https://mp.weixin.qq.com/s/aIdEnTWqr27VpCqEVDvyDg

https://www.cnblogs.com/dafanjoy/p/13050823.html

Netty 职责链 Pipeline 详解: https://my.oschina.net/shadowolf/blog/4269165

一文理解Netty模型架构: https://juejin.im/post/5bea1d2e51882523d3163657

反向代理和负载均衡有何区别？ https://www.zhihu.com/question/20553431/answer/130698230

浏览器发送http请求过程分析: https://segmentfault.com/a/1190000010156898

https://zhuanlan.zhihu.com/p/61927945

零拷贝： https://mp.weixin.qq.com/s/ERpGez6OqgkEAIqaiwT2Mg 

nagle算法: https://blog.csdn.net/wdscq1234/article/details/52432095

socket缓冲 https://zhuanlan.zhihu.com/p/372798949

 

 

操作系统

Monday, May 10, 2021

9:35 PM

 

# 操作系统

linux内存 https://mp.weixin.qq.com/s/I0BbNCQSSgUKVbvXBj5ttw

读一个字节实际会发生多大的磁盘IO https://mp.weixin.qq.com/s/vekemOfUHBjZSy3uXb49Rw

 

 

其他

Monday, March 15, 2021

1:58 PM

 

   

# 其他

设计模式： http://www.jasongj.com/tags/Design-Pattern/

技术前沿： https://insights.thoughtworks.cn/

热门算法排行榜： https://codetop.cc/#/home

 

 

读书笔记

2020年11月19日

0:40

 

# 各种读书笔记

 

Effective Java

 

https://www.shuzhiduo.com/A/pRdBx8knJn/

Redis实战 

https://blog.csdn.net/yums467/article/details/51498417

Redis设计与实现

https://zhuanlan.zhihu.com/p/70962407

亿级流量网站架构核心技术

https://www.cnblogs.com/Xjng/archive/2004/01/13/11624418.html

高性能MySql

https://zhuanlan.zhihu.com/p/70961995

https://my.oschina.net/zhangxufeng/blog/907896

深入理解Java虚拟机

https://juejin.cn/post/6844904039994359821

Java性能权威指南

https://my.oschina.net/serverx/blog/704677

https://my.oschina.net/serverx/blog/704947

现代操作系统

https://blog.csdn.net/houjian914/article/details/50762056

Elasticsearch实战

https://www.cnblogs.com/xujanus/p/11661869.html

RocketMQ实战与原理解析 

https://github.com/Shellbye/Shellbye.github.io/issues/83

Kafka权威指南

https://pegasuswang.readthedocs.io/zh/latest/分布式/Kafka权威指南/

Netty实战

https://www.dazhuanlan.com/2019/10/04/5d9740bb0a9a2/

ZooKeeper-分布式过程协同技术详解

https://rustberry.github.io/2019/09/22/Zookeeper/

企业it架构转型之道阿里巴巴中台战略思想与架构实战

https://www.cnblogs.com/MikeYao/archive/2020/07/05/13251995.html

微服务设计

https://segmentfault.com/a/1190000011690048

数据密集型应用系统 

https://blog.csdn.net/breavo_raw/article/details/105274856

https://blog.csdn.net/breavo_raw/article/details/105431780

 

 

 

 

 

golang

Sunday, May 30, 2021

10:52 PM

 

# golang

golang知识图谱 https://learnku.com/articles/56078

 

 

面试题大全

Thursday, April 1, 2021

10:47 PM

 

# 面试题大全

Redis https://blog.csdn.net/ThinkWon/article/details/103522351

Kafka https://developer.aliyun.com/article/766272

https://xie.infoq.cn/article/6c879c4c3b52e416f251b2909

http://www.mstx.com.cn/archives/3.html

综合： [Java-Interview-Advanced: 中华石杉--互联网Java面试训练营 (gitee.com)](https://gitee.com/shishan100/Java-Interview-Advanced#面试突击第一季)

 