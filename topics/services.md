---
layout: topic
title: "External Services"

intro: The modern web development stack doesn't only need a web-server but is often built on a range of external services to provide specific features, from worker queues to search and pubsub. Rust support for these is certainly not the greatest, but there are popular crates for the most popular services.

level: 4

cloud:
  - rusoto_core
  - azure_sdk_for_rust

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
  - elasticsearch
  - meilisearch-sdk
  - tantivy

pubsub:
  - pulsar
  - redis

connectors:
  - efflux

news_tag: services
---

<h2>Cloud SDK</h2>

{% include packages.html packages=page.cloud %}

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
