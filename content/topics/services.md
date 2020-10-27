+++
title = "External Services"

[extra]

intro = "The modern web development stack doesn't only need a web-server but is often built on a range of external services to provide specific features, from worker queues to search and pubsub. There are many mature crates for popular external services. For services accessed through a Web API, such as Cloud SDKs, see: [External Web APIs](https://www.arewewebyet.org/topics/web-apis/) and for database support, see: [Databases](https://www.arewewebyet.org/topics/database/)"

level = 1

queues = [
  "lapin",
  "tokio-amqp",
  "beanstalkc",
  "celery",
  "rdkafka",
  "nats",
  "tmq"
]

data = [
  "arrow",
  "arrow-flight",
  "datafusion",
  "parquet"
]

search = [
  "elasticsearch",
  "meilisearch-sdk",
  "tantivy"
]

pubsub = [
  "pulsar",
  "redis"
]

newstag = "services"
+++
<h2>Worker Queue</h2>

{{ packages(packages='queues') }}

<h2>Data Processing</h2>

{{ packages(packages='data') }}

<h2>Search Services</h2>

{{ packages(packages='search') }}

<h2>Pubsub</h2>

{{ packages(packages='pubsub') }}
