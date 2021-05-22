<p align="center">
    <a href="https://dunwu.github.io/javatech/" target="_blank" rel="noopener noreferrer">
        <img src="https://raw.githubusercontent.com/dunwu/images/dev/common/dunwu-logo-200.png" alt="logo" width="150px"/>
    </a>
</p>

<p align="center">
    <img src="https://badgen.net/github/license/dunwu/javatech" alt="license">
    <img src="https://travis-ci.com/dunwu/javatech.svg?branch=master" alt="build">
</p>

<h1 align="center">JAVATECH</h1>

> ☕ **JavaTech** 汇总了 Java 后端开发中常见的主流技术的应用、特性、原理。
>
> - 🔁 项目同步维护：[Github](https://github.com/dunwu/javatech/) | [Gitee](https://gitee.com/turnon/javatech/)
> - 📖 电子书阅读：[Github Pages](https://dunwu.github.io/javatech/) | [Gitee Pages](http://turnon.gitee.io/javatech/)
>
> 说明：
>
> - 下面的内容清单中，凡是有 📚 标记的技术，都已整理成详细的教程。
> - 部分技术因为可以应用于不同领域，所以可能会同时出现在不同的类别下。

## 📖 内容

### [框架](docs/framework)

- [Spring](https://dunwu.github.io/spring-tutorial/) 📚
- [Spring Boot](https://dunwu.github.io/spring-boot-tutorial/) 📚
- [Spring Cloud](https://github.com/dunwu/spring-cloud-tutorial) 📚
- [MyBatis](docs/framework/mybatis)
  - [Mybatis 应用指南](docs/framework/mybatis/Mybatis应用指南.md)
  - [Mybatis 原理](docs/framework/mybatis/Mybatis原理.md)
- [Netty](docs/framework/netty.md)

### [消息队列](docs/mq)

> 消息队列（Message Queue，简称 MQ）技术是分布式应用间交换信息的一种技术。
>
> 消息队列主要解决应用耦合，异步消息，流量削锋等问题，实现高性能，高可用，可伸缩和最终一致性架构。是大型分布式系统不可缺少的中间件。
>
> 如果想深入学习各种消息队列产品，建议先了解一下 [消息队列基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/mq.md) ，有助于理解消息队列特性的实现和设计思路。

- [消息队列基本原理](docs/mq/消息队列基本原理.md)
- [消息队列面试题](docs/mq/消息队列面试.md) 💯
- [Kafka](https://dunwu.github.io/bigdata-tutorial/kafka) 📚
- [RocketMQ](docs/mq/rocketmq.md)
- [ActiveMQ](docs/mq/activemq.md)

### [缓存](docs/cache)

> 缓存可以说是优化系统性能的第一手段，在各种技术中都会有缓存的应用。
>
> 如果想深入学习缓存，建议先了解一下 [缓存基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/cache.md)，有助于理解缓存的特性、原理，使用缓存常见的问题及解决方案。

![img](https://raw.githubusercontent.com/dunwu/images/dev/snap/20200710163555.png)

- [缓存面试题](docs/cache/cache-interview.md) 💯
- [缓存基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/cache.md)
- [Java 缓存框架](docs/cache/cache-framework.md) - 关键词：Spring Cache、J2Cache、JetCache
- [Redis 教程](https://dunwu.github.io/db-tutorial/nosql/redis/) 📚
- [Memcached 应用指南](docs/cache/memcached.md)
- [Java 缓存库](docs/cache/cache-libs.md) - 关键词：ConcurrentHashMap、LRUHashMap、Guava Cache、Caffeine、Ehcache
- [Ehcache 应用指南](docs/cache/ehcache.md)
- [Http 缓存](docs/cache/http-cache.md)

### [微服务](docs/microservice)

- [Dubbo](docs/microservice/dubbo.md)
- [**Spring Cloud**](https://github.com/dunwu/spring-cloud-tutorial) 📚
  - Eureka
  - Consul
  - Nacos
  - Zuul
  - Gateway
- 通信
  - [Netty](docs/framework/netty.md)

### 搜索引擎

- [ElasticSearch](docs/search/elasticsearch)
  - [ElasticSearch 应用指南](docs/search/elasticsearch/elasticsearch-quickstart.md)
  - [ElasticSearch API](docs/search/elasticsearch/elasticsearch-api.md)
  - [ElasticSearch 运维](docs/search/elasticsearch/elasticsearch-ops.md)
- [Elastic 技术栈](docs/search)
  - [Elastic 技术栈快速入门](docs/search/elastic-quickstart.md)
  - [Beats 入门指南](docs/search/elastic-beats.md)
  - [Beats 运维](docs/search/elastic-beats-ops.md)
  - [Kibana 入门指南](docs/search/elastic-kibana.md)
  - [Kibana 运维](docs/search/elastic-kibana-ops.md)
  - [Logstash 入门指南](docs/search/elastic-logstash.md)
  - [Logstash 运维](docs/search/elastic-logstash-ops.md)
- Solr
- Lucene

### [安全](docs/security)

> Java 领域比较流行的安全框架就是 shiro 和 spring-security。
>
> shiro 更为简单、轻便，容易理解，能满足大多数基本安全场景下的需要。
>
> spring-security 功能更丰富，也比 shiro 更复杂。值得一提的是由于 spring-security 是 spring 团队开发，所以集成 spring 和 spring-boot 框架更容易。

- [Shiro](docs/security/shiro.md)
- [Spring Security](docs/security/spring-security.md)

### [测试](docs/test)

- [Junit](docs/test/junit.md)
- [Mockito](docs/test/mockito.md)
- [JMH](docs/test/jmh.md)
- [Jmeter](docs/test/jmeter.md)

### [服务器](docs/server)

> Tomcat 和 Jetty 都是 Java 比较流行的轻量级服务器。
>
> Nginx 是目前最流行的反向代理服务器，也常用于负载均衡。

- [Tomcat 应用指南](docs/server/Tomcat应用指南.md)
- [Tomcat 连接器](docs/server/Tomcat连接器.md)
- [Tomcat 容器](docs/server/Tomcat容器.md)
- [Tomcat 优化](docs/server/Tomcat优化.md)
- [Jetty](docs/server/jetty.md)
- [Nginx](https://github.com/dunwu/nginx-tutorial) 📚

### [大数据](https://dunwu.github.io/bigdata-tutorial)

> 大数据技术点以归档在：[bigdata-tutorial](https://dunwu.github.io/bigdata-tutorial)

- [Hdfs](https://dunwu.github.io/bigdata-tutorial/hdfs) 📚
- [Hbase](https://dunwu.github.io/bigdata-tutorial/hbase) 📚
- [Hive](https://dunwu.github.io/bigdata-tutorial/hive) 📚
- [MapReduce](https://dunwu.github.io/bigdata-tutorial/mapreduce)
- [Yarn](https://dunwu.github.io/bigdata-tutorial/yarn)
- [ZooKeeper](https://dunwu.github.io/bigdata-tutorial/zookeeper) 📚
- [Kafka](https://dunwu.github.io/bigdata-tutorial/kafka) 📚
- Spark
- Storm
- [Flink](https://dunwu.github.io/bigdata-tutorial/tree/master/docs/flink)

### [LIB](docs/lib)

- [日志](docs/lib/javalib-log.md) - log4j2、logback、log4j、Slf4j
- [序列化](docs/lib/serialized/)
  - [JSON](docs/lib/serialized/javalib-json.md) - Fastjson、Jackson、Gson
  - [二进制](docs/lib/serialized/javalib-binary.md) - Protobuf、Thrift、Hessian、Kryo、FST
- [模板引擎](docs/lib/template) - [Freemark](docs/lib/template/freemark.md)、[Velocity](docs/lib/template/velocity.md)、[Thymeleaf](docs/lib/template/thymeleaf.md)
- JavaBean - [Lombok](docs/lib/bean/lombok.md)、[Dozer](docs/lib/bean/dozer.md)
- 工具包 - Apache Common、Guava、Hutool
- 辅助 - swagger

## 📚 资料

## 🚪 传送

◾ 🏠 [JAVATECH 首页](https://github.com/dunwu/javatech) ◾ 🎯 [我的博客](https://github.com/dunwu/blog) ◾

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
