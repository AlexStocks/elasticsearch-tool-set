# Elasticsearch tool list #

Here is an Elasticsearch tool list.

* [Elasticsearch tool list](#elasticsearch-tool-list)
  * [Elasticsearch](#elasticsearch)
  * [Elasticsearch Log DB](#elasticsearch-log-db)
  * [Elasticsearch River](#elasticsearch-river)
  * [Elasticsearch Client](#elasticsearch-client)
  * [Elasticsearch Analyzer](#elasticsearch-analyzer)
  * [Elasticsearch Mapper](#elasticsearch-mapper)
  * [Kibana](#kibana)
  * [Elasticsearch Book](#elasticsearch-book)
  * [Elasticsearch Problem](#elasticsearch-problem)
  * [Elasticsearch Ecosystem](#elasticsearch-ecosystem)

---
## Elasticsearch
* [elasticsearch](https://github.com/elastic/elasticsearch/blob/v5.0.0-alpha1/README.textile) - A Distributed RESTful Search Engine. star: 16156(until 2016/04/26).
* [elasticsearch-head](https://github.com/mobz/elasticsearch-head) - A web front end for an Elasticsearch cluster. star: 1881(until 2016/04/26).
* [elastalert](https://github.com/Yelp/elastalert) - Easy & Flexible Alerting With ElasticSearch. ElastAlert is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch. star: 1574(until 2016/04/26).
* [kopf](https://github.com/lmenezes/elasticsearch-kopf) - web admin interface for elasticsearch. kopf is a simple web administration tool for elasticsearch written in JavaScript + AngularJS + jQuery + Twitter bootstrap. It offers an easy way of performing common tasks on an elasticsearch cluster. Not every single API is covered by this plugin, but it does offer a REST client which allows you to explore the full potential of the ElasticSearch API. star: 1351(until 2016/04/26). unmaintained now, its replacement is [cerebro](https://github.com/lmenezes/cerebro).
* [cerebro](https://github.com/lmenezes/cerebro/tree/v0.6.1) - cerebro is an open source(MIT License) elasticsearch web admin tool built using Scala, Play Framework, AngularJS and Bootstrap. star: 315(until 2017/03/12).
* [elasticsearch-sql](https://github.com/NLPchina/elasticsearch-sql) - Query elasticsearch using familiar SQL syntax. You can also use ES functions in SQL. star: 1318(until 2016/04/26).
* [bigdesk](https://github.com/lukas-vlcek/bigdesk) - Live charts and statistics for Elasticsearch cluster. star: 1003(until 2016/04/26).
* [elasticsearch-paramedic](https://github.com/karmi/elasticsearch-paramedic) - A simple tool to inspect the state and statistics about ElasticSearch clusters. It displays real-time statistics and information about your nodes and indices, as well as shard allocation within the cluster. star: 609 (until 2016/04/28).
* [elasticsearch-inquisitor](https://github.com/polyfractal/elasticsearch-inquisitor) - Site plugin for Elasticsearch to help understand and debug queries. just adapitve with elasticsearch 1.x. star: 596(until 2016/04/28).
* [elasticsearch-servicewrapper](https://github.com/elastic/elasticsearch-servicewrapper) - A service wrapper execution for elasticsearch using Java Service Wrapper. DEPRECATED: The service wrapper is deprecated and not maintained. It no longer works with Elasticsearch 2.x. Many of the features have been added to Elastisearch itself, and purpose built deb, rpm packages, as well as windows service, are avaialble. star: 394(until 2016/04/26);
* [elasticsearch-segmentspy](https://github.com/polyfractal/elasticsearch-segmentspy) - SegmentSpy is a tool to watch the segments in your indices. Segment graphs update in real-time, allowing you to watch as ElasticSearch (Lucene) merges your segments. SegmentSpy has only been tested on 0.20.2 – 0.90.3. star: 101(until 2016/04/26).
* [elasticsearch-migration](https://github.com/elastic/elasticsearch-migration) - A plugin to check whether your 0.90 or 1.x cluster can be upgraded directly to 2.x, or whether there are incompatibilites that need resolving first. star: 107(until 2016/04/27).
* [elastalert-elasticsearch_aggregations_query_support](https://github.com/errordaiwa/elastalert/tree/feature/elasticsearch_aggregations_query_support) -  support aggregation query from elasticsearch. star: 0(until 2016/05/05).

---
## Elasticsearch Log DB
* [elasticsearch-hadoop](https://github.com/elastic/elasticsearch-hadoop) -  Elasticsearch real-time search and analytics natively integrated with Hadoop. Supports Map/Reduce, Cascading, Apache Hive, Apache Pig, Apache Spark and Apache Storm. star: 695(until 2016/04/26).
* [elasticsearch-hdfs](https://github.com/elastic/elasticsearch-hdfs) - Hadoop Plugin for Elasticsearch. The Hadoop plugin allows to use Hadoop as a shared gateway for Elasticsearch. star: 39(until 2016/04/26).

---
## Elasticsearch River
* [elasticsearch-river-mongodb](https://github.com/richardwilly98/elasticsearch-river-mongodb) - MongoDB River Plugin for ElasticSearch. This plugin uses MongoDB or the TokuMX fork of MongoDB as datasource to store data in ElasticSearch. Filtering and transformation are also possible. star: 918(until 2016/04/26).
* [elasticsearch-river-web](https://github.com/codelibs/elasticsearch-river-web) - Elasticsearch River Web is a web crawler application for Elasticsearch. This application provides a feature to crawl web sites and extract the content by CSS Query. (As of version 1.5, River Web is not Elasticsearch plugin). star: 158(until 2016/04/26).
* [elasticsearch-river-couchdb(STOPPED)](https://github.com/elastic/elasticsearch-river-couchdb) - CouchDB River Plugin for Elasticsearch. The CouchDB River plugin allows to automatically index couchdb and make it searchable using the excellent _changes stream couchdb provides. CouchDB River Plugin for elasticsearch (STOPPED). star: 160(until 2016/04/26).
* [elasticsearch-river-rabbitmq(STOPPED)](https://github.com/elastic/elasticsearch-river-rabbitmq) - RabbitMQ River Plugin for Elasticsearch. The RabbitMQ River plugin allows index bulk format messages into elasticsearch. RabbitMQ River allows to automatically index a RabbitMQ queue. Important: This project has been stopped since elasticsearch 2.0. star: 154(until 2016/04/26).
* [elasticsearch-river-kafka](https://github.com/mariamhakobyan/elasticsearch-river-kafka) - The Kafka River plugin allows you to read messages from Kafka and index bulked messages into elasticsearch. The bulk size (the number of messages to be indexed in one request) and concurrent request number is configurable. The Kafka River also supports consuming messages from multiple Kafka brokers and multiple partitions. star: 56(until 2016/04/26).
* [elasticsearch-river-mysql(STOPPED)](https://github.com/scharron/elasticsearch-river-mysql) - A river for elasticsearch to automatically index mysql content using the replication feed. The Mysql River plugin allows to hook into Mysql replication feed using the excellent python-mysql-replication and automatically index it into elasticsearch. This plugin is based on the elasticsearch-river-couchdb plugin. star: 63(until 2016/04/26).
* [Elasticsearch-HBase-River](https://github.com/mallocator/Elasticsearch-HBase-River) - An import river similar to the elasticsearch mysql river. If you're looking for an alternative sollution that uses the core hbase libraries and uses hbase replication for moving data, you can find one here: https://github.com/posix4e/Elasticsearch-HBase-River. star: 15(until 2016/04/26).
* [kafka-connect-elasticsearch](https://github.com/confluentinc/kafka-connect-elasticsearch) - kafka-connect-elasticsearch is a Kafka Connector for copying data between Kafka and Elasticsearch. To build a development version you'll need a recent version of Kafka. You can build kafka-connect-elasticsearch with Maven using the standard lifecycle phases. start: 60(until 2017/03/17).
* [kafka-elasticsearch-consumer](https://github.com/BigDataDevs/kafka-elasticsearch-consumer/issues/46) - **Daily indices**. This application, Kafka ES Indexer, will read the messages from Kafka, processes (if needed) and batch index them into ElasticSearch. Kafka Version: 0.8.2.1, ElasticSearch: 2.x, Scala Version for Kafka Build: 2.10.0, JDK 1.8. star: 73(until 2017/03/17).
* [kafka-connect-elasticsearch](https://github.com/AlexStocks/kafka-connect-elasticsearch) - write batch data from Kafka into Elasticsearch index and set an index to output to that changes daily witten in Golang. star: 4(until 2017/07/21).

---
## Elasticsearch Client
* [play2-elasticsearch](https://github.com/cleverage/play2-elasticsearch) - Elasticsearch module for PlayFramework 2.x applications. star: 158(until 2016/04/26).
* [sql-on-es-cli](https://github.com/jason-heo/sql-on-es-cli) - sql-on-es-cli.py is a simple tool written in Python. It just reads SQL from user and requests the SQL to elasticsearch-SQL and parse Elasticsearch output and print output 2 dimentional table format. star 1(given by me, until 2017/03/15).
* [Securi in Elasticsearch and sql plugin](https://github.com/NLPchina/elasticsearch-sql/issues/135) - using the ( Python) base64.encodestring(username,password) and add the request to the header to use a user id and password to login to Elastic search. code examples:

		url="http://xxxxx:9200/_sql?sql=SELECT+****++AS+mykey%2C+count%28%2A%29+AS+myval1+FROM+xxxxx%2Fxxxx+WHERE+xxxx%3E0+AND+xxxxx+in%2847%2C37%2C27%2C7%29+and+GEO_BOUNDING_BOX%28xxx%2C-93.29192853733362%2C44.98521676873701%2C-93.24924922748754%2C44.972952619045344%29+GROUP+BY+xxxx+LIMIT+0"

	    req = urllib2.Request(url)
	    base64string = base64.encodestring('%s:%s' % ("username", "password")).replace('\n', '')
	    req.add_header("Authorization", "Basic %s" % base64string)
	    res=urllib2.urlopen(req)
	    print res.read()

---
## Elasticsearch Analyzer
* [elasticsearch-analysis-ik](https://github.com/medcl/elasticsearch-analysis-ik) - The IK Analysis plugin integrates Lucene IK analyzer (http://code.google.com/p/ik-analyzer/) into elasticsearch, support customized dictionary. Analyzer: ik_smart , ik_max_word , Tokenizer: ik_smart , ik_max_word. star:1068 (until 2016/04/28).
* [elasticsearch-analysis-pinyin](https://github.com/medcl/elasticsearch-analysis-pinyin) - The Pinyin Analysis plugin integrates Pinyin4j(http://pinyin4j.sourceforge.net/) module into elasticsearch. Pinyin4j is a popular Java library supporting convertion between Chinese characters and most popular Pinyin systems. The output format of pinyin could be customized. star:198 (until 2016/04/28).
* [elasticsearch-analysis-smartcn](https://github.com/elastic/elasticsearch-analysis-smartcn) - The Smart Chinese Analysis plugin integrates Lucene Smart Chinese analysis module into elasticsearch. star:194 (until 2016/04/28).
* [elasticsearch-analysis-mmseg](https://github.com/medcl/elasticsearch-analysis-mmseg) - The Mmseg Analysis plugin integrates Lucene mmseg4j-analyzer:http://code.google.com/p/mmseg4j/ into elasticsearch, support customized dictionary. The plugin ships with analyzers: mmseg_maxword ,mmseg_complex ,mmseg_simple and tokenizers: mmseg_maxword ,mmseg_complex ,mmseg_simple and token_filter: cut_letter_digit. star:193 (until 2016/04/28).
* [elasticsearch-analysis-ansj](https://github.com/NLPchina/elasticsearch-analysis-ansj) - based on ansj. compatible with elasticsearch 2.3.1. star:105 (until 2016/04/28).
* [elasticsearch-analysis-combo](https://github.com/yakaz/elasticsearch-analysis-combo) -The Combo Analyzer plugin provides with a new analyzer type that combines the output of multiple analyzers into one. star:66 (until 2016/04/28).
* [elasticsearch-analysis-stconvert](https://github.com/medcl/elasticsearch-analysis-stconvert) - STConvert is analyzer that convert chinese characters between traditional and simplified. star:39 (until 2016/04/28).

---
## Elasticsearch Mapper
* [elasticsearch-mapper-attachments](https://github.com/elastic/elasticsearch-mapper-attachments) - The mapper attachments plugin lets Elasticsearch index file attachments in over a thousand formats (such as PPT, XLS, PDF) using the Apache text extraction library Tika. In practice, the plugin adds the attachment type when mapping properties so that documents can be populated with file attachment contents (encoded as base64). IMPORTANT: this project now moved to elasticsearch repository (from elasticsearch 2.2.0). star: 338 (until 2016/04/28).
* [elasticsearch-analysis-string2int](https://github.com/medcl/elasticsearch-analysis-string2int) - string2integer analysis for elasticsearch,save your memory and reduce the size of your index,the size of the filedcache can be reduced from giga to mega,and also the query time can be reduced from minutes to millionseconds.. star:40 (until 2016/04/28).

---
## Kibana
* [grafana](https://github.com/grafana/grafana) - Grafana is an open source, feature rich metrics dashboard and graph editor for Graphite, Elasticsearch, OpenTSDB, Prometheus and InfluxDB. star: 9458(until 2016/04/26).
* [elasticsearch-HQ](https://github.com/royrusso/elasticsearch-HQ) - Monitoring and Management Web Application for ElasticSearch instances and clusters. star: 2153(until 2016/04/26).
* [kibana-authorization](https://github.com/chenryn/kibana-authorization) - Enhanced Kibana 3 with several aggregation panels, html5 notification, authentication and authorization. star: 94(until 2016/04/26).
* [oauth2](https://github.com/trevan/oauth2) - An OAuth Plugin for Kibana 4. It uses Bell for the OAuth handling. star: 14(until 2016/04/26).
* [kibana](https://github.com/elastic/kibana) - Kibana is an open source (Apache Licensed), browser based analytics and search dashboard for Elasticsearch. Kibana is a snap to setup and start using. Kibana strives to be easy to get started with, while also being flexible and powerful, just like Elasticsearch. star: 5197(until 2016/04/26).


---
## Elasticsearch Book
* [elasticsearch-definitive-guide-cn](https://github.com/looly/elasticsearch-definitive-guide-cn) - A Chinese translation book of [elastic/elasticsearch-definitive-guide](https://github.com/elastic/elasticsearch-definitive-guide). star: 750(until 2016/04/26).
* [elasticsearch-definitive-guide-cn](https://github.com/chenryn/ELKstack-guide-cn) - Elasticsearch, Logstash, Kibana user guide in Chinese. star: 121(until 2016/04/26).
* [Understanding the Memory Pressure Indicator](https://www.elastic.co/blog/found-understanding-memory-pressure-indicator)
* [新浪是如何分析处理32亿条实时日志的](http://dockone.io/article/505) - I upload its pdf doc to [my github repository](https://github.com/AlexStocks/elasticsearch-tool-set/blob/master/Better_ELK.pdf) because its primary storage place--vdisk.weibo.com of sina will be closed on 2016/06/30 by powerful force.
* [基于Flume+Kafka+ Elasticsearch+Storm的海量日志实时分析平台](https://mp.weixin.qq.com/s?__biz=MzIzMzEzODYwOA==&mid=2665283950&idx=1&sn=9005fcaf85f8d4673c62f4067bf3d0ca&scene=2&srcid=0426cgGHbl44hdDO98YUL1ER&from=timeline&isappinstalled=0&pass_ticket=Sf%2FiqNSerEetqlVE7xucKwOzQLuaGO45bEETgpGh49lRZHzeqclwnRNa6StbAp3y)

---
## Elasticsearch Problem
* [ES java very high CPU usage 100%](https://github.com/elastic/elasticsearch/issues/4288) - Force all memory to be locked, forcing the JVM to never swap.

  To solve 100% es cpu problems, my suggestion is as follows:
  - 1 close every shard's replica;
  - 2 set the refresh interval of every index from the default value 1s to 5 or 30s;
  - 3 set the minimum java memory space equal to its maximum value when es startups;
  - 4 create/close/delete timeout index in time;
  - 5 using mapping.
* [elastalert do not support aggregation]
  - 1 https://github.com/Yelp/elastalert/issues/369
        Basic terms aggregation is supported. Look for use_terms_query in the documentation. Beyond that, custom aggregations are not supported. Closing as duplicate of #169
  - 2 https://github.com/Yelp/elastalert/issues/401
        I have looked through ElastAlert config sheet and source code. It seems ElastAlert doesn't support aggregation query from ElasticSearch.
  - 3 https://github.com/Yelp/elastalert
        The only aggregation supported currently is a terms aggregation, by setting use_terms_query.

---
## Elasticsearch Ecosystem
* [awesome-elasticsearch](https://github.com/dzharii/awesome-elasticsearch) - A curated list of amazingly awesome redis and redis ecosystem resources. star: 265(until 2016/04/26).

---
* written by Alex Stocks on 2016/04/26
* add elasticsearch-migration on 2016/04/27
* add elasticsearch-paramedic && elasticsearch-inquisitor && elasticsearch-analysis-ik && elasticsearch-analysis-pinyin && elasticsearch-analysis-smartcn && elasticsearch-analysis-mmseg && elasticsearch-analysis-ansj && elasticsearch-analysis-combo && elasticsearch-analysis-stconvert && elasticsearch-mapper-attachments && elasticsearch-analysis-string2int on 2016/04/28
* add ELK doc & EFK doc & elastalert-elasticsearch_aggregations_query_support on 2016/05/05.
* add cerebro on 2017/03/12.
* add sql-on-es-cli on 2017/03/15.
* add kafka-connect-elasticsearch & kafka-elasticsearch-consumer on 2017/03/17.
* add kafka-connect-elasticsearch on 2017/07/21.
