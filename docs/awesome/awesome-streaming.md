<div class="github-widget" data-repo="manuzhang/awesome-streaming"></div>

## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions)

精选的很棒的清单 [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 框架，应用程序，阅读材料和其他资源. 受启发 [other awesome projects](https://github.com/sindresorhus/awesome). 

## Website

[https://manuzhang.github.io/awesome-streaming/](https://manuzhang.github.io/awesome-streaming/) 是一个更具活力的网站，您可以在此处找到**令人敬畏的项目的更新.



### Streaming Engine

- [Apache Apex](https://github.com/apache/apex-core) [Java]-大数据流和批处理的统一平台.
- [Apache Ballista](https://github.com/apache/arrow-datafusion/tree/master/ballista) [Rust]-由Apache Arrow支持的分布式计算平台.
- [Apache Flink](https://github.com/apache/flink) [Java]-高吞吐量，低延迟的数据流处理系统，支持状态计算，数据驱动的窗口语义和迭代流处理.
- [Apache Heron (incubating)](https://github.com/apache/incubator-heron) [Java]-来自Twitter的实时，分布式，容错流处理引擎.
- [Apache Samza](https://github.com/apache/samza) [Scala / Java]-基于Kafka（消息，存储）和YARN（容错，处理器隔离，安全性和资源管理）构建的分布式流处理框架.
- [Apache Spark Streaming](https://github.com/apache/spark) [Scala]-使构建可扩展的容错流应用程序变得容易.
- [Apache Storm](https://github.com/apache/storm)  [Clojure / Java]-分布式实时计算系统.  Storm是流处理，而Hadoop是批处理. 
- [AthenaX](https://github.com/uber/AthenaX) [Java]-生产中使用的Uber流分析框架
- [Faust](https://github.com/robinhood/faust) [Python]-流处理库，将想法从Kafka Streams移植到Python
- [Gearpump](https://github.com/gearpump/gearpump) [Scala]-基于Akka构建的轻量级实时分布式流引擎.
- [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) [Java]-基于Hazelcast构建的通用分布式数据处理引擎.
- [hailstorm](https://github.com/hailstorm-hs/hailstorm) [Haskell]-基于Storm的具有一次精确语义的分布式流处理.
- [Maki Nage](https://github.com/maki-nage/makinage) [Python]-基于Kafka和ReactiveX的数据科学家流处理框架.
- [mantis](https://github.com/Netflix/mantis) [Java]-Netflix的平台，用于构建实时流处理应用程序生态系统
- [mupd8(muppet)](https://github.com/walmartlabs/mupd8) [Scala / Java]-用于处理快速/流数据的mapReduce样式的框架.
- [Onyx](https://github.com/onyx-platform/onyx) [Clojure]-分布式，无主控，高性能，容错数据处理.
- [s4](https://github.com/apache/incubator-s4) [Java]-通用的，分布式的，可伸缩的，容错的，可插拔的平台，允许程序员轻松开发用于处理连续无限制数据流的应用程序.
- [SABER](https://github.com/lsds/Saber) [Java / C]-基于窗口的混合CPU / GPU流处理引擎.
- [SPQR](https://github.com/ottogroup/SPQR) [Java]-用于通过管道处理大量数据流的动态框架.
- [tigon](https://github.com/caskdata/tigon) [C ++ / Java]-基于Hadoop和HBase构建的高吞吐量实时流处理框架.
- [Teknek](https://github.com/edwardcapriolo/teknek-core) [Java]-具有交互式原型外壳SOL（流操作员语言）的简单优雅的流处理
Mesos专为需要灵活性和控制力的高性能数据处理作业而设计.
- [Trill](https://github.com/Microsoft/trill) [.NET/C#] - Trill is a high-performance one-pass in-memory streaming analytics engine from Microsoft Research.
- [Wallaroo](https://github.com/WallarooLabs/wallaroo)  [Python]-一种快速的流处理框架. 使用Wallaroo，可以轻松地实时响应数据. 通过消除基础架构的复杂性，从原型到生产的过程从未如此简单.
- [LightSaber](https://github.com/lsds/LightSaber)  [C ++]-多核基于窗口的流处理引擎.  LightSaber使用代码生成来进行有效的窗口聚合.
- [HStreamDB](https://github.com/hstreamdb/hstream) [Haskell]-为IoT数据存储和实时处理而构建的流数据库.
- [Kuiper](https://github.com/emqx/kuiper) [Golang]-由Golang实施的边缘轻量级IoT数据分析/流软件，可以在各种资源受限的边缘设备上运行.

### Streaming Library

- [Apache Kafka Streams](https://github.com/apache/kafka) [Java]-Apache Kafka中包含的轻量级流处理库（从0.10版本开始）.
- [Akka Streams](https://github.com/akka/akka) [Scala]-Akka Actors上的流处理库. 
- [Benthos](https://github.com/Jeffail/benthos) [开始]-Benthos是一种高性能且具有弹性的消息流服务，能够连接各种源和接收器，并对有效负载执行任意操作，转换和过滤器
- [FS2(prev. 'Scalaz-Stream')](https://github.com/functional-streams-for-scala/fs2) [Scala]-用于Scala的组合式流I / O库.
- [monix](https://github.com/monix/monix) [Scala]-高性能的Scala / Scala.js库，用于编写异步和基于事件的程序.
- [Streamline](https://github.com/hortonworks/streamline)  [Java]-Hortonworks的Stream Analytics Framework，被设计为诸如Storm之类的现有流解决方案的包装. 旨在允许用户拖放流组件以专注于业务逻辑.
- [StreamAlert](https://github.com/airbnb/streamalert) [Python]-Airbnb的实时数据分析和警报.
- [Swave](https://github.com/sirthias/swave) [Scala]-用于Scala的轻量级Reactive Streams基础结构工具包.
- [Streamz](https://github.com/python-streamz/streamz)  [Python]-用于构建管道以管理连续数据流的轻量级库； 支持涉及分支，连接，流量控制，反馈，背压等的复杂管道.
- [Stream Ops](https://github.com/nanosai/stream-ops-java) [Java]-Java的完全可嵌入的数据流引擎和流处理API.
- [Tributary](https://github.com/timkpaine/tributary)  [Python]-用于构造数据流图的python库. 支持使用可模拟复杂事件处理器的python生成器构建的同步，反应性数据流，以及惰性计算的非循环图和函数性currying流.

### Streaming Application

- [straw](https://github.com/rwalk/straw) [Python / Java]-实时流搜索的平台.
- [storm-crawler](https://github.com/DigitalPebble/storm-crawler) [Java]-基于Apache Storm的Web爬网程序SDK.

### IoT

- [sensorbee](https://github.com/sensorbee/sensorbee) [开始]-物联网的轻量级流处理引擎.
- [Apache Edgent](https://github.com/apache/incubator-edgent) [Java]-一种编程模型和运行时，可在网关和边缘设备上进行连续的流分析，可以与集中式系统一起使用，以在整个IoT生态系统中提供高效，及时的分析：从中心到边缘，由IBM开源.
- [Apache StreamPipes](https://github.com/apache/incubator-streampipes) [Java]-自助（工业）IoT工具箱，使非技术用户可以连接，分析和探索IoT数据流.

### DSL

- [Apache Beam](https://github.com/apache/beam) [Java，Python，SQL，Scala，Go]-用于定义和执行数据处理工作流以及数据摄取和集成流程的统一模型和特定于语言的SDK集，支持企业集成模式（EIP）和领域特定语言（DSL） ），由Google开源.
- [coast](https://github.com/bkirwi/coast) [Scala]-DSL，它在Samza之上构建DAG，并提供一次精确的语义.
- [Esper](https://github.com/espertechinc/esper) [Java]-用于复杂事件处理（CEP）和事件序列分析的组件.
- [Streamparse](https://github.com/Parsely/streamparse) [Python]-使您可以通过Apache Storm针对实时数据流运行Python代码.
- [summingbird](https://github.com/twitter/summingbird) [Scala]-一种库，可让您编写看起来像本机Scala或Java集合转换的MapReduce程序，并在许多著名的分布式MapReduce平台（包括Storm和Scalding）上执行它们.

### Data Pipeline

- [Apache Kafka](https://github.com/apache/kafka) [Scala / Java]-分布式，分区，复制的提交日志服务，该服务提供消息传递系统的功能，但具有独特的设计.
- [Apache Pulsar](https://github.com/apache/incubator-pulsar) [Java]-具有非常灵活的消息传递模型和直观的客户端API的分布式pub-sub消息传递平台.
- [brooklin](https://github.com/linkedin/Brooklin/) [Java]-一种分布式系统，旨在通过Linkedin（替代数据总线）实现大规模，高可靠性和高吞吐量的各种异构源系统和目标系统之间的数据流.
- [camus](https://github.com/linkedin/camus) [Java]-Linkedin的Kafka-&gt; HDFS管道.
- [databus](https://github.com/linkedin/databus) [Java]-Linkedin的与源无关的分布式更改数据捕获系统.
- [flume](https://github.com/apache/flume) [Java]-分布式，可靠且可用的服务，用于有效地收集，聚集和移动大量日志数据.
- [Gazette](https://github.com/gazette/core) [golang]-基于云存储构建的分布式流式基础结构，可轻松混合和匹配批处理和流式范例.
- [LogDevice](https://logdevice.io/) [C ++]-Facebook的高性能分布式系统，用于使用日志结构流式传输和存储顺序数据.
- [metaq](https://github.com/killme2008/Metamorphosis) [Java]-淘宝的高可用性，高性能分布式消息传递系统
- [NATS streaming](https://github.com/nats-io/nats-streaming-server) [开始]-快速的磁盘支持消息传递解决方案
- [nsq](https://github.com/nsqio/nsq) [运行]-实时分布式消息传递平台，旨在大规模运行，每天处理数十亿条消息.
- [RudderStack](https://github.com/rudderlabs/rudder-server) [开始]-开源客户数据基础架构（细分市场，mparticle替代产品）.
- [suro](https://github.com/Netflix/suro) [Java]-数据管道服务，用于收集，聚集和调度包括日志数据在内的大量应用程序事件.
- [StreamSets Data Collector](https://github.com/streamsets/datacollector-oss) [Java]-连续的大数据摄取基础结构，可从大量端点读取和写入，包括S3，JDBC，Hadoop，Kafka，Cassandra等.

### Online Machine Learning 

- [Apache Samoa](https://github.com/apache/incubator-samoa) [Java]-分布式流机器学习（ML）框架，其中包含针对分布式流ML算法的编程抽象.
- [DataSketches](https://github.com/DataSketches/sketches-core) [Java]-Yahoo!的草图库.
- [streamDM](https://github.com/huawei-noah/streamDM) [Scala]-使用华为的Spark Streaming挖掘大数据流.
- [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) [Python]-提供一个网络服务器，以快速设置和评估针对上下文多臂匪徒（cMAB）问题的可能解决方案.
- [StormCV](https://github.com/sensorstorm/StormCV) [Java]-通过添加特定于计算机视觉（CV）的操作和数据模型，可以将Apache Storm用于视频处理.
- [trident-ml](https://github.com/pmerienne/trident-ml) [Java]-基于Trident的实时在线机器学习库.
- [yurita](https://github.com/paypal/yurita) [Scala]-基于Paypal的Spark结构化流构建的异常检测框架.

### Streaming SQL

- [pipelinedb](https://github.com/pipelinedb/pipelinedb) [C]-一个开放源代码关系数据库，该数据库在流上连续运行SQL查询，并将结果增量存储在表中.
- [squall](https://github.com/epfldata/squall) [Java]-Squall在Storm之上执行SQL查询以进行在线处理.
- [StreamCQL](https://github.com/Zhiqiang-He/StreamCQL) [Java]-实时计算系统上的连续查询语言.
- [ksqlDB](https://github.com/confluentinc/ksql) [Java]-原生云，源可用 [database](https://ksqldb.io/) 专为流处理应用而构建
- [Materialize](https://materialize.com) [Rust] - A source-available streaming SQL engine for maintaining materialized views on data from message brokers and databases.
- [Siddhi](https://github.com/siddhi-io/siddhi) [Java]-一种云原生的流和复杂事件处理引擎，该引擎理解流SQL查询，以便捕获来自各种数据源的事件，对其进行处理，检测复杂条件并实时将输出发布到各个端点.

### Benchmark

- [storm-benchmark](https://github.com/intel-hadoop/storm-benchmark) [Java]-一组测试Storm性能的基准.
- [storm-perf-test](https://github.com/yahoo/storm-perf-test) [Java]-一个简单的风暴性能/压力测试.
- [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) [Java]-低延迟（流）解决方案的基准，包括Apache Storm，Apache Spark，Apache Flink等.
- [flotilla](https://github.com/tylertreat/Flotilla) [执行]-自动化的消息队列编排，用于按比例放大的基准测试.

### Toolkit

- [akka](https://github.com/akka/akka) [Scala]-用于在JVM上构建高度并发，分布式和弹性消息驱动的应用程序的工具箱和运行时.
- [pulsar](https://github.com/quantmind/pulsar/) [Python]-基于Actor的事件驱动的Python并发框架.
- [aeron](https://github.com/real-logic/Aeron) [Java / C ++]-高效可靠的单播和多播消息传输.
- [StreamFlow](https://github.com/lmco/streamflow) [Java]-流处理工具，旨在帮助构建和监视处理工作流.
- [samza-luwak](https://github.com/romseygeek/samza-luwak) [Java]-使用Luwak（一种基于Lucene构建的存储查询引擎）在流上实现全文搜索.
- [Turbine](https://github.com/Netflix/Turbine) [Java]-用于将服务器发送事件（SSE）JSON数据流聚合到单个流中的工具.

### Closed Source

- [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) [Java]-AWS提供的实时，完全托管和可扩展的数据流引擎. 
- [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) [.NET]由Microsoft Azure提供的可大规模扩展，完全托管的实时数据流引擎.
- [Cloud Dataflow](https://cloud.google.com/dataflow/) [Java，Python，SQL，Scala]-Google的托管流和批处理数据处理引擎. 支持正在运行的Beam管道.
- [concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) [C ++]-在Apache之上以C ++构建的分布式流处理框架.
- [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/) [Python/Java/Scala] - platform for distributed processing and real-time analytics. Provides toolkits for advanced analytics like geospatial, time series, etc. out of the box.
- [jubatus](http://jubat.us/en/) [C ++]-分布式处理框架和流机器学习库.
- [millwheel](http://research.google.com/pubs/pub41378.html) -用于构建低延迟数据处理应用程序的框架，该框架已在Google上广泛使用.


### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 由泰勒·阿基道（Tyler Akidau）设计. 
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](http://www.vldb.org/pvldb/vol8/p2040-Kejariwal.pdf)
4. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) 乔什·菲舍尔（Josh Fischer）和王宁（Ning Wang）

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

根据许可 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
