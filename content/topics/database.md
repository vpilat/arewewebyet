+++
title = "Database drivers"

[extra]

level = 2

intro = "Proper Database support is crucial for modern web development. This page gives an overview of the various drivers, ORMs, integrations and tools."

drivers = [
  "mysql",
  "mysql_async",
  "postgres",
  "pleingres",
  "redis",
  "redis-async",
  "darkredis",
  "rusqlite",
  "tokio-postgres",
  "leveldb",
  "rocksdb",
  "couchdb",
  "etcd",
  "influent",
  "cassandra-cpp",
  "cdrs",
  "memcache",
  "mongodb",
  "mongo_driver",
  "sqlx"
]

orms = [
  "diesel",
  "quaint",
  "rustorm",
  "tql"
]

pools = [
    "mobc",
    "r2d2"
]

tools = [
  "migrant",
  "refinery",
  "schemamama",
  "trek"
]

newstag = "database"
+++

<h2 id="drivers">Drivers</h2>

{{ packages(packages='drivers') }}

<h2 id="orms">ORMs</h2>

{{ packages(packages='orms') }}

<h2 id="pools">Connection pools</h2>

{{ packages(packages='pools') }}

<h2 id="tooling">Tooling</h2>

{{ packages(packages='tools') }}


