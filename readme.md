﻿# Elasticsearch tool list #

Here is an Elasticsearch tool list. I hope you will find one or two of them that you'd like to try out.

- [Elasticsearch tool list](#elasticsearch tool list)
	- [Elasticsearch](#elasticsearch plugins)
	- [Kibana](#kibana plugins)
	- [Elasticsearch Book](#elasticsearch books)
	- [Elasticsearch Problem](#elasticsearch problems and resolvements)
	- [Elasticsearch Ecosystem](#elasticsearch ecosystem)

---
## Elasticsearch
* [elasticsearch-head](https://github.com/mobz/elasticsearch-head) - A web front end for an Elasticsearch cluster. star: 1881(until 2016/04/26).
* [elastalert](https://github.com/Yelp/elastalert) - Easy & Flexible Alerting With ElasticSearch. ElastAlert is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch. star: 1574(until 2016/04/26).
* [elasticsearch-sql](https://github.com/NLPchina/elasticsearch-sql) - Query elasticsearch using familiar SQL syntax. You can also use ES functions in SQL. star: 1318(until 2016/04/26).
* [bigdesk](https://github.com/lukas-vlcek/bigdesk) - Live charts and statistics for Elasticsearch cluster. star: 1003(until 2016/04/26).
* [elasticsearch](https://github.com/elastic/elasticsearch/blob/v5.0.0-alpha1/README.textile) - A Distributed RESTful Search Engine. star: 16156(until 2016/04/26).

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

---
## Elasticsearch Problem
* [ES java very high CPU usage 100%](https://github.com/elastic/elasticsearch/issues/4288) - Force all memory to be locked, forcing the JVM to never swap.

  To solve 100% es cpu problems, my suggestion is as follows:
  - 1 close every shard's replica;
  - 2 set the refresh interval of every index from the default value 1s to 5 or 30s;
  - 3 set the minimum java memory space equal to its maximum value when es startups.

---
## Elasticsearch Ecosystem
* [awesome-elasticsearch](https://github.com/dzharii/awesome-elasticsearch) - A curated list of amazingly awesome redis and redis ecosystem resources. star: 265(until 2016/04/26).

---
* written by Alex Stocks on 2016/04/26
