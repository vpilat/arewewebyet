+++
title = "RustWebDigest #1: Getting Started Section, Servo this summer, iron session"
source = { author = "ben" }
tags = [
  "frameworks",
  "servo",
  "digest"
]
+++

About a month has passed since we relaunched [AreWeWebYet](http://www.arewewebyet.org/) and quite a few news and updates made the rounds. To make it easier for you to stay up to date with current developments in Rust-Web, we decided to launch the RustWebDigest – a semi regular blog series from the AWWY curators on the state of affairs and changes since the last update. Welcome to edition #1.

## Getting started just got easier

We've added a [new "Getting Started" section to the homepage](/#getting-started) to highlight great resources to make it easier for you get into rust web development. One especially important news in there was the [launch of the clippy service by the Bashy Initiative](http://www.bashy.io/news/2016/03/05/clippy-linting-as-a-service/), a rust linting service which ships [with 100% annotated source code](https://clippy.bashy.io/docs/) for everyone to learn from.

## Servo in Summer of code

Servo was accepted to both Google Summer of Code and Rails Girls Summer of Code. If you are interested to join either program, take a [look at the announcement blog post for more info](https://blog.servo.org/2016/03/02/summer-of-code/)

## rust-url approaches v1

In other news from the servo project, the famous Rust-URL-Crate for URL parsing and handling is approaching version 1.0 and is [looking for feedback on their API design and data structures](https://github.com/servo/rust-url/pull/176).

## Crate releases

### Notable crates

 - Iron has published a middleware for session management, appropriately named: [iron_session](https://crates.io/crates/iron_session) and we've found our first login-module: [iron-login](https://crates.io/crates/iron-login)
 - [oppgave](https://crates.io/crates/oppgave) is a simple redis-based worker queue implementation – finally!
 - [polly](https://crates.io/crates/polly) offers a truly logic-less templating language implementation in rust
 - With the latest rust release 1.7 [twox-hash](https://crates.io/crates/twox-hash) jumped a major version and released its version 1.0!

### Added to index:
The following have been added to our tracking index (and the website where appropriate)

- [polly](https://crates.io/crates/polly)  (0.1.2)
- [oppgave](https://crates.io/crates/oppgave)  (0.1.0)
- [hubcaps](https://crates.io/crates/hubcaps)  (0.1.1)
- [zip](https://crates.io/crates/zip)  (0.1.16)
- [robotparser](https://crates.io/crates/robotparser)  (0.4.1)
- [iron_session](https://crates.io/crates/iron_session)  (0.0.4)
- [iron-login](https://crates.io/crates/iron-login)  (0.2.0)
- [iron_vhosts](https://crates.io/crates/iron_vhosts)  (0.1.0)
- [staticdir](https://crates.io/crates/staticdir)  (0.3.1)
- [iron-hmac](https://crates.io/crates/iron-hmac)  (0.3.0)
- [iron-test](https://crates.io/crates/iron-test)  (0.2.0)
- [selective_middleware](https://crates.io/crates/selective_middleware)  (0.1.0)
- [persistent](https://crates.io/crates/persistent)  (0.0.9)
- [router](https://crates.io/crates/router)  (0.1.0)
- [staticfile](https://crates.io/crates/staticfile)  (0.1.0)
- [formdata](https://crates.io/crates/formdata)  (0.7.9)
- [mount](https://crates.io/crates/mount)  (0.0.10)
- [oven](https://crates.io/crates/oven)  (0.2.16)
- [static](https://crates.io/crates/static)  (0.0.4)

### Updates recorded:

Further more we recorded new releases to the following crates

 - [amqp](https://crates.io/crates/amqp) (0.0.13 => 0.0.15)
 - [blake2-rfc](https://crates.io/crates/blake2-rfc) (0.2.16 => 0.2.17)
 - [bodyparser](https://crates.io/crates/bodyparser) (0.1.0 => 0.2.0)
 - [cassandra](https://crates.io/crates/cassandra) (0.6.3 => 0.6.7)
 - [chrono](https://crates.io/crates/chrono) (0.2.19 => 0.2.20)
 - [clap](https://crates.io/crates/clap) (2.0.6 => 2.1.2)
 - [couchdb](https://crates.io/crates/couchdb) (0.5.0 => 0.5.1)
 - [crust](https://crates.io/crates/crust) (0.8.0 => 0.9.0)
 - [dbmigrate](https://crates.io/crates/dbmigrate) (0.2.1 => 0.2.2)
 - [discord](https://crates.io/crates/discord) (0.3.0 => 0.4.0)
 - [etcd](https://crates.io/crates/etcd) (0.3.0 => 0.3.1)
 - [handlebars-iron](https://crates.io/crates/handlebars-iron) (0.11.1 => 0.12.0)
 - [handlebars](https://crates.io/crates/handlebars) (0.14.0 => 0.15.0)
 - [influent](https://crates.io/crates/influent) (0.2.1 => 0.2.2)
 - [inth-oauth2](https://crates.io/crates/inth-oauth2) (0.7.0 => 0.8.0)
 - [jsonrpc](https://crates.io/crates/jsonrpc) (0.7.1 => 0.7.4)
 - [kafka](https://crates.io/crates/kafka) (0.1.8 => 0.2.0)
 - [keen](https://crates.io/crates/keen) (1.0.3 => 1.1.0)
 - [liquid](https://crates.io/crates/liquid) (0.3.0 => 0.4.1)
 - [lzw](https://crates.io/crates/lzw) (0.9.0 => 0.10.0)
 - [maud](https://crates.io/crates/maud) (0.7.4 => 0.8.0)
 - [multipart](https://crates.io/crates/multipart) (0.4.1 => 0.5.0-alpha.1)
 - [mysql](https://crates.io/crates/mysql) (1.2.1 => 2.1.0)
 - [pencil](https://crates.io/crates/pencil) (0.0.1 => 0.1.0)
 - [postgres](https://crates.io/crates/postgres) (0.11.1 => 0.11.4)
 - [rand](https://crates.io/crates/rand) (0.3.13 => 0.3.14)
 - [regex](https://crates.io/crates/regex) (0.1.48 => 0.1.55)
 - [robotparser](https://crates.io/crates/robotparser) (0.4.0 => 0.4.1)
 - [rotor-http](https://crates.io/crates/rotor-http) (0.5.0 => 0.6.0)
 - [rs-es](https://crates.io/crates/rs-es) (0.2.0 => 0.2.5)
 - [rusoto](https://crates.io/crates/rusoto) (0.12.0 => 0.12.1)
 - [rustful](https://crates.io/crates/rustful) (0.6.1 => 0.7.0)
 - [serde](https://crates.io/crates/serde) (0.6.11 => 0.7.0)
 - [serde_json](https://crates.io/crates/serde_json) (0.6.0 => 0.7.0)
 - [tar](https://crates.io/crates/tar) (0.4.0 => 0.4.4)
 - [telegram-bot](https://crates.io/crates/telegram-bot) (0.3.0 => 0.4.1)
 - [tempfile](https://crates.io/crates/tempfile) (2.1.0 => 2.1.1)
 - ✨ [twox-hash](https://crates.io/crates/twox-hash) (0.1.1 => 1.0.0)
 - [url](https://crates.io/crates/url) (0.5.5 => 0.5.7)
 - [urlparse](https://crates.io/crates/urlparse) (0.7.2 => 0.7.3)
 - [vkrs](https://crates.io/crates/vkrs) (0.5.0 => 0.6.1)
 - [websocket](https://crates.io/crates/websocket) (0.15.0 => 0.15.1)
 - [ws](https://crates.io/crates/ws) (0.4.4 => 0.4.5)


Anything we missed? [Let us know](https://github.com/bashyHQ/arewewebyet/issues/new)!
