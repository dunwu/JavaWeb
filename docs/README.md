---
home: true
heroImage: https://raw.githubusercontent.com/dunwu/images/dev/common/dunwu-logo-200.png
heroText: JAVATECH
tagline: ☕ javatech 汇总了 Java 开发中常见的主流技术的应用、特性、原理。
actionLink: /
footer: CC-BY-SA-4.0 Licensed | Copyright © 2018-Now Dunwu
---

![license](https://badgen.net/github/license/dunwu/javatech)
![build](https://travis-ci.com/dunwu/javatech.svg?branch=master)

> ☕ **javatech** 汇总了 Java 开发中常见的主流技术的应用、特性、原理。
>
> - 🔁 项目同步维护：[Github](https://github.com/dunwu/javatech/) | [Gitee](https://gitee.com/turnon/javatech/)
> - 📖 电子书阅读：[Github Pages](https://dunwu.github.io/javatech/) | [Gitee Pages](http://turnon.gitee.io/javatech/)
>
> 说明：
>
> - 下面的内容清单中，凡是有 📚 标记的技术，都已整理成详细的教程。
> - 部分技术因为可以应用于不同领域，所以可能会同时出现在不同的类别下。

## 📖 内容

### 框架

- [Spring](https://dunwu.github.io/spring-tutorial/) 📚
- [Spring Boot](https://dunwu.github.io/spring-boot-tutorial/) 📚
- [Spring Cloud](https://github.com/dunwu/spring-cloud-tutorial) 📚
- MyBatis
  - [Mybatis 应用指南](framework/Mybatis应用指南.md)
  - [Mybatis 原理](framework/Mybatis原理.md)
- [Netty](soa/netty.md)

### 消息队列

> 消息队列（Message Queue，简称 MQ）技术是分布式应用间交换信息的一种技术。
>
> 消息队列主要解决应用耦合，异步消息，流量削锋等问题，实现高性能，高可用，可伸缩和最终一致性架构。是大型分布式系统不可缺少的中间件。
>
> 如果想深入学习各种消息队列产品，建议先了解一下 [消息队列基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/mq.md) ，有助于理解消息队列特性的实现和设计思路。

- [消息队列面试题](mq/mq-interview.md) 💯
- [Kafka](https://github.com/dunwu/bigdata-tutorial/tree/master/docs/kafka) 📚
- [RocketMQ](mq/rocketmq.md)
- [ActiveMQ](mq/activemq.md)

### [缓存](cache)

> 缓存可以说是优化系统性能的第一手段，在各种技术中都会有缓存的应用。
>
> 如果想深入学习缓存，建议先了解一下 [缓存基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/cache.md)，有助于理解缓存的特性、原理，使用缓存常见的问题及解决方案。

![img](https://raw.githubusercontent.com/dunwu/images/dev/snap/20200710163555.png)

- [缓存面试题](cache/cache-interview.md) 💯
- [缓存基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/cache.md)
- [Java 缓存框架](cache/cache-framework.md) - 关键词：Spring Cache、J2Cache、JetCache
- [Redis 教程](https://github.com/dunwu/db-tutorial/tree/master/docs/nosql/redis) 📚
- [Memcached 应用指南](cache/memcached.md)
- [Java 缓存库](cache/cache-libs.md) - 关键词：ConcurrentHashMap、LRUHashMap、Guava Cache、Caffeine、Ehcache
- [Ehcache 应用指南](cache/ehcache.md)
- [Http 缓存](cache/http-cache.md)

### 微服务

- [Dubbo](soa/dubbo.md)
- [**Spring Cloud**](https://github.com/dunwu/spring-cloud-tutorial) 📚
  - Eureka
  - Consul
  - Nacos
  - Zuul
  - Gateway
- 通信
  - [Netty](soa/netty.md)

### 搜索引擎

- [ElasticSearch](search/elasticsearch)
  - [ElasticSearch 应用指南](search/elasticsearch/elasticsearch-quickstart.md)
  - [ElasticSearch API](search/elasticsearch/elasticsearch-api.md)
  - [ElasticSearch 运维](search/elasticsearch/elasticsearch-ops.md)
- [Elastic 技术栈](search)
  - [Elastic 技术栈快速入门](search/elastic-quickstart.md)
  - [Beats 入门指南](search/elastic-beats.md)
  - [Beats 运维](search/elastic-beats-ops.md)
  - [Kibana 入门指南](search/elastic-kibana.md)
  - [Kibana 运维](search/elastic-kibana-ops.md)
  - [Logstash 入门指南](search/elastic-logstash.md)
  - [Logstash 运维](search/elastic-logstash-ops.md)
- Solr
- Lucene

### 安全

> Java 领域比较流行的安全框架就是 shiro 和 spring-security。
>
> shiro 更为简单、轻便，容易理解，能满足大多数基本安全场景下的需要。
>
> spring-security 功能更丰富，也比 shiro 更复杂。值得一提的是由于 spring-security 是 spring 团队开发，所以集成 spring 和 spring-boot 框架更容易。

- [Shiro](security/shiro.md)
- [Spring Security](security/spring-security.md)

### 测试

- [Junit](test/junit.md)
- [Mockito](test/mockito.md)
- [JMH](test/jmh.md)
- [Jmeter](test/jmeter.md)

### 服务器

> Tomcat 和 Jetty 都是 Java 比较流行的轻量级服务器。
>
> Nginx 是目前最流行的反向代理服务器，也常用于负载均衡。

- [Tomcat 应用指南](server/Tomcat应用指南.md)
- [Tomcat 连接器](server/Tomcat连接器.md)
- [Tomcat 容器](server/Tomcat容器.md)
- [Tomcat 优化](server/Tomcat优化.md)
- [Jetty](server/jetty.md)
- [Nginx](https://github.com/dunwu/nginx-tutorial) 📚

### 大数据

> 大数据技术点以归档在：[bigdata-tutorial](https://github.com/dunwu/bigdata-tutorial)

- [Hdfs](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/hdfs) 📚
- [Hbase](https://github.com/dunwu/bigdata-tutorial/tree/master/docs/hbase) 📚
- [Hive](https://github.com/dunwu/bigdata-tutorial/tree/master/docs/hive) 📚
- [MapReduce](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/mapreduce/mapreduce.md)
- [Yarn](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/yarn.md)
- [ZooKeeper](https://github.com/dunwu/bigdata-tutorial/tree/master/docs/zookeeper) 📚
- [Kafka](https://github.com/dunwu/bigdata-tutorial/tree/master/docs/kafka) 📚
- Spark
- Storm
- [Flink](https://github.com/dunwu/bigdata-tutorial/tree/master/docs/flink)

### LIB

- [日志](lib/javalib-log.md) - log4j2、logback、log4j、Slf4j
- [序列化](lib/serialized/)
  - [JSON](lib/serialized/javalib-json.md) - Fastjson、Jackson、Gson
  - [二进制](lib/serialized/javalib-binary.md) - Protobuf、Thrift、Hessian、Kryo、FST
- [模板引擎](lib/template) - [Freemark](lib/template/freemark.md)、[Velocity](lib/template/velocity.md)、[Thymeleaf](lib/template/thymeleaf.md)
- JavaBean - [Lombok](lib/bean/lombok.md)、[Dozer](lib/bean/dozer.md)
- 工具包 - Apache Common、Guava、Hutool
- 辅助 - swagger

## 📚 资料

## 🚪 传送

◾ 🏠 [JAVACORE 首页](https://github.com/dunwu/javacore) ◾ 🎯 [我的博客](https://github.com/dunwu/blog) ◾

> 你可能会感兴趣：

- [Java 教程](https://github.com/dunwu/java-tutorial) 📚
- [JavaCore 教程](https://dunwu.github.io/javacore/) 📚
- [JavaTech 教程](https://dunwu.github.io/javatech/) 📚
- [Spring 教程](https://dunwu.github.io/spring-tutorial/) 📚
- [Spring Boot 教程](https://dunwu.github.io/spring-boot-tutorial/) 📚
- [数据库教程](https://dunwu.github.io/db-tutorial/) 📚
- [数据结构和算法教程](https://dunwu.github.io/algorithm-tutorial/) 📚
- [Linux 教程](https://dunwu.github.io/linux-tutorial/) 📚
- [Nginx 教程](https://github.com/dunwu/nginx-tutorial/) 📚
