## Java编码常用工具类类库



| 主要版本 | 更新时间   | 备注     |
| -------- | ---------- | -------- |
| v1.0     | 2020-09-29 | 首次整理 |
| v1.1     | 2020-10-30 | 内容补充 |

逐渐更新中... 

欢迎大家参与共建~

### 参与共建

如果您对本项目中的内容有建议或者意见，欢迎提出专业方面的建议，共同维护。

请直接在[GitHub](https://github.com/wind7rui/Javalib)上以issue或者PR的形式提出。

## 正文

### 应用开发脚手架
1.Spring Framework

Spring框架为现代基于Java的企业应用程序提供了一个全面的编程和配置模型，使用开发基于Java语言的应用更加简单、便捷。

github：https://github.com/spring-projects/spring-framework/

官网：https://spring.io/projects/spring-framework

2.Spring Boot

Spring Boot使创建独立的、基于Spring的产品级应用程序变得非常容易。

官网：https://spring.io/projects/spring-boot

3.Spring Cloud

Spring Cloud为开发人员提供了丰富的使用工具，开发人员基于这些工具可以快速构建分布式系统中的一些常见功能（例如，配置管理，服务发现，断路器，智能路由，微代理，控制总线，一次性令牌，全局锁，领导选举，分布式会话等）。

官网：https://spring.io/projects/spring-cloud

### Web服务接口

1.Jersey

Jersey是一个REST框架，它提供JAX-RS参考实现等。Jersey提供了自己的api，这些api通过附加的特性和实用程序扩展了JAX-RS工具包，从而进一步简化了RESTful服务和客户端开发。Jersey还公开了许多扩展spi，以便开发人员可以扩展Jersey以最适合他们的需求。

github：https://github.com/eclipse-ee4j/jersey

2.Spring Web MVC

Spring Web MVC是基于Servlet API构建的原始Web框架，从一开始就已包含在Spring框架中。正式名称“ Spring Web MVC”来自其源模块的名称（spring-webmvc），但通常称为“Spring MVC”。

官网：https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/web.html

### 数据持久化框架

1.MyBatis

MyBatis是一个一流的持久性框架，支持自定义SQL、存储过程和高级映射，它几乎消除了JDBC代码、参数手动设置和结果检索。MyBatis可以使用简单的XML或注释进行配置，并将原语、接口和javapojo（普通的旧Java对象）映射到数据库记录。

官网：https://mybatis.org/mybatis-3/

github：https://github.com/mybatis/mybatis-3

2.MyBatis-Plus

MyBatis-Plus是MyBatis的功能强大的增强工具包，用于简化开发。该工具包为MyBatis提供了一些高效，有用，即用的功能，使用它可以有效地节省您的开发时间。

github：https://github.com/baomidou/mybatis-plus

3.Hibernate

Hibernate是一个开放源代码的对象关系映射框架，它对JDBC进行了非常轻量级的对象封装，它将POJO与数据库表建立映射关系，是一个全自动的orm框架，hibernate可以自动生成SQL语句，自动执行，使得Java程序员可以随心所欲的使用对象编程思维来操纵数据库。 

官网：http://hibernate.org/

### Excel读写

1.Alibaba EasyExcel

Java解析、生成Excel比较有名的框架有Apache poi、jxl。但他们都存在一个严重的问题就是非常的耗内存，poi有一套SAX模式的API可以一定程度的解决一些内存溢出的问题，但POI还是有一些缺陷，比如07版Excel解压缩以及解压后存储都是在内存中完成的，内存消耗依然很大。easyexcel重写了poi对07版Excel的解析，能够原本一个3M的excel用POI sax依然需要100M左右内存降低到几M，并且再大的excel不会出现内存溢出，03版依赖POI的sax模式。在上层做了模型转换的封装，让使用者更加简单方便。

github：https://github.com/alibaba/easyexcel

2.Apache POI

一个用于读写Microsoft Office二进制和OOXML文件格式的Java库，可用于读写Excel 97-2008。

github：https://github.com/apache/poi

### CSV读写

1.Apache Commons CSV

Apache Commons CSV库提供了用于读取和写入各种类型CSV文件的接口。

github：https://github.com/apache/commons-csv

2.Java CSV

Java CSV是一个小型、快速且开源Java库，用于读、写各种CSV文件。

官网：https://www.csvreader.com/java_csv.php

API：http://javacsv.sourceforge.net/

3.Super CSV

Super CSV是一个快速、免费跨平台的CSV格式数据的读写库，可以方便的处理对象、Map、列表的读写操作，以及自动化的类型转换和数据检查功能。

官网：http://super-csv.github.io/super-csv/index.html

github：https://github.com/super-csv/super-csv

### JSON读写

1.Jackson

Jackson被称为Java的标准JSON库，号称“Java的最佳JSON解析器”。

github：https://github.com/FasterXML/jackson

2.Gson

Gson是谷歌开源的一个Java库，可用于将Java对象转换为其JSON表示形式。它还可以用于将JSON字符串转换为等效的Java对象。Gson可以处理任意Java对象，包括您没有源代码的现有对象。

github：https://github.com/google/gson

3.fastjson

fastjson是阿里巴巴的开源JSON解析库，它可以解析JSON格式的字符串，支持将Java Bean序列化为JSON字符串，也可以从JSON字符串反序列化到JavaBean。

github：https://github.com/alibaba/fastjson

### XML读写

1.dom4j

dom4j是用于处理XML的开源框架，该框架与XPath集成在一起，并完全支持DOM、SAX、JAXP和Java平台。

github：https://github.com/dom4j/dom4j

官网：https://dom4j.github.io/

2.StAX

StAX全称Streaming API for XML，一种全新的、基于流的Java XML解析标准类库。

3.jaxb-api

jaxb-api用于执行XML文档和Java对象之间的映射。

文档：https://docs.oracle.com/javase/8/docs/api/javax/xml/bind/JAXB.html

4.XStream

XStream是一个可以轻易的将Java对象和xml文档相互转换的类库。

官网：http://x-stream.github.io/

### IO读写

1.Apache Commons IO
Apache Commons IO是一个实用程序库，可协助开发IO功能。

官网：https://commons.apache.org/proper/commons-io/

2.Okio

Okio是对java.io和java.nio的补充，使访问、存储和处理数据变得更加容易。

github：https://github.com/square/okio

### HTTP客户端

1.OkHttp

OkHttp是一个HTTP客户端，使用OkHttp很容易，它的请求/响应API具有流畅的构建器和不变性。它支持同步阻塞调用和带有回调的异步调用。

github：https://github.com/square/okhttp

官网：https://square.github.io/okhttp/

2.Apache HttpClient

Apache HttpClient提供了对基本HTTP协议的强大支持，用于构建基于HTTP的客户端。

官网：http://hc.apache.org/index.html

github：https://github.com/apache/httpcomponents-client

### Java Bean复制

1.Cglib BeanCopier

Cglib库内的BeanCopier提供了ava Bean到Java Bean的复制功能，性能优于Spring BeanUtils。

```java
BeanCopier beanCopier = BeanCopier.create(sourceClass, targetClass, false);
beanCopier.copy(source, target, null);
```

2.Spring BeanUtils

Spring框架的Spring Beans库中的BeanUtils也实现了Java Bean到Java Bean的复制。

3.Dozer

Dozer是Java Bean到Java Bean映射器，它以递归方式将数据从一个对象复制到另一个对象。Dozer支持简单属性映射、复杂类型映射、双向映射、隐式显式映射以及递归映射。Dozer不仅支持属性名称之间的映射，而且还可以在类型之间自动转换。开箱即用地支持大多数转换方案，同时也允许您通过XML或基于代码的配置指定自定义转换。

github：https://github.com/DozerMapper/dozer

文档：https://dozermapper.github.io/gitbook/

### Redis客户端

1.Redission

Redis推荐的Java客户端Redisson是一个在Redis的基础上实现的Java驻内存数据网格（In-Memory Data Grid），它充分利用了Redis键值数据库提供的一系列优势，基于Java实用工具包中常用接口，为使用者提供了一系列具有分布式特性的常用工具类，让使用Redis更加简单、便捷，从而让使用者能够将更多精力集中到业务逻辑处理上。

github：https://github.com/redisson/redisson/

2.Jedis

Redis推荐的Java客户端。

github：https://github.com/xetorthio/jedis

### 数据库连接池

数据库连接池提供了一套高效的连接分配、使用策略， 最终实现连接的高效管理。

1.HikariCP

快速、简单、可靠。HikariCP是“零开销”生产就绪的JDBC连接池。

github：https://github.com/brettwooldridge/HikariCP

2.Druid

Druid是Java语言中最好的数据库连接池之一，Druid能够提供强大的监控和扩展功能。

github：https://github.com/alibaba/druid/

3.Tomcat JDBC

JDBC连接池是Apache Commons DBCP连接池的替代品。

官网：http://tomcat.apache.org/tomcat-7.0-doc/jdbc-pool.html

### 网络编程

1.Netty

Netty是一个广泛使用的Java网络编程框架。

github：https://github.com/netty/netty

官网：https://netty.io/

### 文件上传

1.Apache Commons FileUpload

Apache Commons FileUpload使高性能的文件上传功能变得容易。

官网：http://commons.apache.org/proper/commons-fileupload/

### 发送邮件

1.Apache Commons Email

Apache commons Email旨在提供用于发送电子邮件的API，它建立在Java Mail API之上，它的目标就是简便。

官网：http://commons.apache.org/proper/commons-email/

### 编码和解码

1.Apache Commons Codec

Apache Commons Codec提供了常见编码器和解码器的实现，例如Base64，Hex，Phonetic和URL。

官网：http://commons.apache.org/proper/commons-codec/

### IO操作

1.Apache Commons IO

简单、快捷的IO操作。

官网：http://commons.apache.org/proper/commons-io/index.html

### 对象池

1.Apache Commons Pool

提供了通用对象池。

官网：http://commons.apache.org/proper/commons-pool/

### java.lang包工具类

1.Apache Commons Lang

为java.lang中的类提供额外的功能，例如StringUtils、DateUtils、RandomUtils、FastDateFormat(线程安全版本的SimpleDateFormat)。

官网：http://commons.apache.org/proper/commons-lang/index.html

### 集合操作

1.Apache Commons Collections

集合相关操作工具类。

官网：http://commons.apache.org/proper/commons-collections/

2.Guava

Guava是Google的一组核心Java库，除了可以操作我们常用的集合类型之外，还可以操作新的集合类型（例如多图和多集）和不可变的集合。

github：https://github.com/google/guava

### 全能型工具类

1.Guava

Guava是Google的一组核心Java库，其中包括新的集合类型（例如多图和多集），不可变的集合，图形库以及用于并发，I / O，哈希，缓存，基元，字符串等的实用程序！它广泛用于Google的大多数Java项目中，也被许多其他公司广泛使用。

github：https://github.com/google/guava

2.Hutool

Hutool是一个Java工具包，也只是一个工具包，它帮助我们简化每一行代码，减少每一个方法，让Java语言也可以“甜甜的”。

github：https://github.com/looly/hutool

### 日期和时间操作

1.Joda-Time

Joda-Time提供了Java日期和时间类的质量替代。

官网：https://www.joda.org/joda-time/

### 单元测试

1.JUnit

官网：https://junit.org/junit5/

2.Mockito

Mockito是一个Java单元测试模拟框架。

官网：https://site.mockito.org/

3.PowerMock

PowerMock也是一个Java单元测试模拟框架，它可以模拟静态方法、构造函数、最终类和方法、私有方法、删除静态初始化器等。

官网：http://powermock.github.io/

4.moco

在日常接口测试的工作中，经常需要依赖其他系统的API，但是联调不常有，只能自己通过mock完成数据依赖。Moco是一个模拟服务器端服务的项目，可以用于测试打桩。

github：https://github.com/dreamhead/moco

### 接口测试

1.REST Assured

REST Assured是Java DSL，用于简化对基于HTTP Builder的基于REST的服务的测试。它支持POST，GET，PUT，DELETE，OPTIONS，PATCH和HEAD请求，可用于验证和验证这些请求的响应。

github：https://github.com/rest-assured/rest-assured

### 集成测试

1.Testcontainers

Testcontainers是一个Java库，支持JUnit测试，它提供常见数据库，Selenium Web浏览器或可以在Docker容器中运行的任何其他东西的轻量级一次性实例。可应用于数据访问层集成测试、应用程序集成测试、UI/验收测试等。

官网：https://www.testcontainers.org/

### 安全框架

1.Apache Shiro

Apache Shiro是一个功能强大且易于使用的Java安全框架，它用于身份验证、授权、加密和会话管理。使用Shiro易于理解的API，可以快速轻松地保护任何应用程序，从最小的移动应用程序到最大的Web和企业应用程序。

官网：http://shiro.apache.org/

### 日志

1.SLF4J + Logback

SLF4J是为各种loging APIs提供一个简单统一的接口，从而使得最终用户能够在部署的时候配置自己希望的loging APIs实现，它是一个日志接口。

Logback是由[log4j](https://baike.baidu.com/item/log4j)创始人设计的又一个开源日志组件，它是一个日志的实现。

SLF4J官网：http://www.slf4j.org/

Logback官网：https://logback.qos.ch/

### 对象池

1.Apache Commons Pool

Apache Commons Pool提供了对象池API和一系列对象池实现。

官网：https://commons.apache.org/proper/commons-pool/

### 基本网络通讯

1.Apache Commons Net

Apache Commons Net库实现了许多基本互联网协议的客户端。该库的目的是提供基本协议访问，而不是更高级别的抽象。

官网：http://commons.apache.org/proper/commons-net/index.html

### 作业调度框架(定时任务)

1.Quartz

Quartz是一个开源的作业调度框架，它完全由Java编写，能够用它来为执行一个作业而创建简单的或复杂的调度。

官网：http://www.quartz-scheduler.org/

github：https://github.com/quartz-scheduler/quartz

2.ElasticJob

ElasticJob是一种分布式调度解决方案，解决了Quartz不支持分布式的弊端。Elastic job主要的功能有支持弹性扩容，通过Zookepper集中管理和监控job，支持失效转移等。

github：https://github.com/apache/shardingsphere-elasticjob

### 配置中心

1.Nacos

Nacos是一个更易于构建云原生应用的动态服务发现、配置管理和服务管理平台。Nacos的动态配置服务让您能够以中心化、外部化和动态化的方式管理所有环境的配置。动态配置消除了配置变更时重新部署应用和服务的需要。配置中心化管理让实现无状态服务更简单，也让按需弹性扩展服务更容易。

官网：https://nacos.io/

github：https://github.com/alibaba/nacos

2.Spring Cloud Config

Spring Cloud Config为分布式系统中的外部化配置提供服务器端和客户端支持。使用Config Server，您可以在中心位置管理所有环境中应用程序的外部属性。

文档：https://cloud.spring.io/spring-cloud-config/reference/html/

3.Apollo

Apollo（阿波罗）是携程框架部门研发的分布式配置中心，能够集中化管理应用不同环境、不同集群的配置，配置修改后能够实时推送到应用端，并且具备规范的权限、流程治理等特性，适用于微服务配置管理场景。

github：https://github.com/ctripcorp/apollo

### 限流

1.Guava RateLimiter

RateLimiter基于令牌桶算法，即以用户设定的恒定速率向令牌桶内放置令牌，用户来执行任务时，只有拿到令牌才能执行。

2.Sentinel

Sentinel是面向分布式服务架构的高可用防护组件，主要以流量为切入点，从流量控制、熔断降级、系统自适应保护等多个维度来帮助用户保障微服务的稳定性。

官网：https://sentinelguard.io/

github：https://github.com/alibaba/Sentinel

### 熔断降级

当调用链路中某个资源出现不稳定，例如，表现为timeout，异常比例升高的时候，则对这个资源的调用进行限制，并让请求快速失败，避免影响到其它的资源，最终产生雪崩的效果。

1.Sentinel

Sentinel通过并发线程数进行限制和通过响应时间对资源进行降级两种手段对资源调用进行限制，让请求快速失败，避免影响到其它的资源。

官网：https://sentinelguard.io/

github：https://github.com/alibaba/Sentinel

2.Hystrix

Hystrix 通过线程池的方式，来对资源进行了隔离。这样做的好处是资源和资源之间做到了最彻底的隔离。缺点是除了增加了线程切换的成本，还需要预先给各个资源做线程池大小的分配。Hystrix不再处于主动开发中，并且当前处于维护模式，官方推荐使用Resilience4j替代。

github：https://github.com/Netflix/Hystrix

3.Resilience4j

Resilience4j是受Netflix Hystrix启发的轻量级容错库，但专为Java 8和函数式编程而设计。轻巧，因为该库仅使用Vavr，而Vavr没有任何其他外部库依赖项。

github：https://github.com/resilience4j/resilience4j

### 分库分表

1.Apache ShardingSphere

Apache ShardingSphere定位为关系型数据库中间件，旨在充分合理地在分布式的场景下利用关系型数据库的计算和存储能力，而并非实现一个全新的关系型数据库。支持数据分片、读写分离、多数据副本、数据加密、影子库压测等功能。

官网：https://shardingsphere.apache.org/

github：https://github.com/apache/shardingsphere

2.Mycat

Mycat是数据库分库分表中间件。

官网：http://www.mycat.org.cn/

github：https://github.com/MyCATApache

### 序列化

1.Kryo

Kryo是用于Java的快速高效的二进制对象图序列化框架。该项目的目标是高速，小尺寸和易于使用的API。每当需要将对象持久保存到文件，数据库还是通过网络时，该项目都是有用的。

github：https://github.com/EsotericSoftware/kryo

2.Hessian

Hessian是一款支持多种语言进行序列化操作的框架技术，同时在进行序列化之后产生的码流也较小，处理数据的性能方面远超于java内置的jdk序列化方式。

官网：http://hessian.caucho.com/

3.Protobuf

Protobuf是谷歌开源的一个灵活的、高效的用于序列化数据的协议。相比较XML和JSON格式，protobuf更小、更快、更便捷。

github：https://github.com/protocolbuffers/protobuf

官网：https://developers.google.com/protocol-buffers/

### RPC框架
1.Dubbo
Apache Dubbo是一款高性能、轻量级的开源Java RPC框架，它提供了三大核心能力：面向接口的远程方法调用，智能容错和负载均衡，以及服务自动注册和发现。

官网：http://dubbo.apache.org/zh-cn/

github：https://github.com/apache/dubbo

2.Thrift
Thrift是一个软件框架（远程过程调用框架），用来进行可扩展且跨语言的服务的开发。它结合了功能强大的软件堆栈和代码生成引擎，以构建在C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, and OCaml这些编程语言间无缝结合的、高效的服务。Thrift最初由facebook开发，07年四月开放源码，08年5月进入apache孵化器，现在是 Apache 基金会的顶级项目。Thrift允许你定义一个简单的定义文件中的数据类型和服务接口，以作为输入文件，编译器生成代码用来方便地生成RPC客户端和服务器通信的无缝跨编程语言。

官网：http://thrift.apache.org/

3.gRPC
gRPC是一个现代的、开源的、高性能的远程过程调用（RPC）框架，可以在任何地方运行。gRPC使客户机和服务器应用程序能够透明地通信，并简化了连接系统的构建。目前提供C、Java和Go语言版本，分别是：grpc, grpc-java, grpc-go. 其中C版本支持C, C++, Node.js, Python, Ruby, Objective-C, PHP和C#支持。

官网：https://www.grpc.io/

github：https://github.com/grpc/grpc

### 消息中间件

1.Kafka

Apache Kafka是一个开放源代码的分布式事件流平台，成千上万的公司使用它来实现高性能数据管道、流分析、数据集成和关键任务应用程序。Kafka是一种高吞吐量的分布式发布订阅消息系统，它可以处理消费者在网站中的所有动作流数据。

英文官网：http://kafka.apache.org/

中文官网：https://kafka.apachecn.org/

2.Rocketmq

Apache RocketMQ是一个分布式消息传递和流平台，具有低延迟，高性能和可靠性，万亿级容量和灵活的可伸缩性。

官网：http://rocketmq.apache.org/

中文文档：https://github.com/apache/rocketmq/tree/master/docs/cn

github：https://github.com/apache/rocketmq

![关注我的公众号](https://mmbiz.qpic.cn/mmbiz_png/gDHRjEowjKSD6uGeBkX7mgGjPHJjeVrWFLupqaxwrHAMYoibmfl5CD6ibfYMPJffvpVo6mO25fyFur7EZF0nFFTw/640?wx_fmt=png)
