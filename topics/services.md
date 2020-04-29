---
layout: topic
title: "External Services"

intro: The modern web development stack doesn't only need a web-server but is often built on a range of external services to provide specific features, from worker queues over search and pubsub, rust support for these is seriously lacking at the moment. Be sure you are able to build the connection yourself if needed.

level: 5

queues:
 - amqp
 - beanstalkd
 - celery
 - kafka
 - lapin
 - stomp

queries:
 - datafusion

search:
 - rs-es

pubsub:
 - pulsar
 - redis

connectors:
 - efflux

news_tag: services
---


<h2>Worker Queue</h2>

{% include packages.html packages=page.queues %}

<h2>Query engines</h2>

{% include packages.html packages=page.queries %}

<h2>Search Services</h2>

{% include packages.html packages=page.search %}

<h2>Pubsub</h2>

{% include packages.html packages=page.pubsub %}

<h2>Connectors</h2>

{% include packages.html packages=page.connectors %}
