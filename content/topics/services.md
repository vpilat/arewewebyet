+++
title = "External Services"

[extra]

intro = "The modern web development stack doesn't only need a web-server but is often built on a range of external services to provide specific features, from worker queues to search and pubsub. Rust support for these is certainly not the greatest, but there are popular crates for the most popular services."

level = 4

cloud = [
  "rusoto_core",
  "azure_sdk_for_rust"
]

queues = [
  "amqp",
  "beanstalkd",
  "celery",
  "kafka",
  "lapin",
  "stomp"
]

queries = [
  "datafusion"
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

connectors = [
  "efflux"
]

newstag = "services"
+++
<h2>Cloud SDK</h2>

{{ packages(packages='cloud') }}

<h2>Worker Queue</h2>

{{ packages(packages='queues') }}

<h2>Query engines</h2>

{{ packages(packages='queries') }}

<h2>Search Services</h2>

{{ packages(packages='search') }}

<h2>Pubsub</h2>

{{ packages(packages='pubsub') }}

<h2>Connectors</h2>

{{ packages(packages='connectors') }}
