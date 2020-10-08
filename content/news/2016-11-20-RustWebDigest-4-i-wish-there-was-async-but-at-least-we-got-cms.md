+++
title = "RustWebDigest #4: I wish there was async, but at least we got CMSs!"

[extra]

source = { author = "ben" }

tags = [
  "async",
  "cms",
  "stack"
]
+++

With the release of futures and soon after the Tokio-frameworks, this summer was async became all the range in the rust (web) world. While we were hoping to be able to start a new async-section and populate it with amazing libraries by now, even pushing down the timeframe of the digest itself, there isn't sufficient work on this (in the web area) yet. But in order to track these "in development"-things better, and also shed some light into it for people not familiar, we added another section to selected topics, called **upcoming**.

Secondly, we also added another site tracking [Content Management Systems](/topics/cms/). While it currently also features only cobolt-bin (do you know some others?), it takes full advantage of the new upcoming feature and lets you know where you can help.


## Crate updates:


### Added to index:
The following have been added to our tracking index (and the website where appropriate)

 - [atarashii_imap](https://crates.io/crates/atarashii_imap) (0.2.1)
 - [edge](https://crates.io/crates/edge) (0.0.1), [also see this comment by the author](https://github.com/bashyHQ/arewewebyet/pull/56#issuecomment-247916996)
 - [libphonenumber-sys](https://crates.io/crates/libphonenumber-sys) (0.1.1)
 - [cobalt](https://crates.io/crates/cobalt) (0.11.0)
 - [rouille](https://crates.io/crates/rouille) (0.2.2)
 - [rustls](https://crates.io/crates/rustls) (0.5.2)
 - [valico](https://crates.io/crates/valico) (1.0.1)


### Updates recorded:

Further more we recorded new releases to the following crates
## Crates updates found: 
 
 - [amqp](https://crates.io/crates/amqp) (0.0.16 => 0.0.19)
 - [argon2rs](https://crates.io/crates/argon2rs) (0.2.1 => 0.2.5)
 - [atom_syndication](https://crates.io/crates/atom_syndication) (0.1.4 => 0.3.0)
 - [backtrace](https://crates.io/crates/backtrace) (0.2.3 => 0.3.0)
 - [base64](https://crates.io/crates/base64) (0.2.0 => 0.2.1)
 - [bcrypt](https://crates.io/crates/bcrypt) (0.1.1 => 0.1.2)
 - **major** [bitsparrow](https://crates.io/crates/bitsparrow) (0.3.2 => 1.0.0)
 - [bodyparser](https://crates.io/crates/bodyparser) (0.4.0 => 0.4.1)
 - [brotli](https://crates.io/crates/brotli) (1.0.6 => 1.0.7)
 - [cassandra](https://crates.io/crates/cassandra) (0.7.2 => 0.7.3)
 - [chrono](https://crates.io/crates/chrono) (0.2.22 => 0.2.25)
 - [clap](https://crates.io/crates/clap) (2.9.3 => 2.18.0)
 - [conduit](https://crates.io/crates/conduit) (0.7.4 => 0.8.0)
 - [cookie](https://crates.io/crates/cookie) (0.2.5 => 0.3.1)
 - [crust](https://crates.io/crates/crust) (0.16.1 => 0.19.0)
 - [curl](https://crates.io/crates/curl) (0.3.1 => 0.4.1)
 - [dbmigrate](https://crates.io/crates/dbmigrate) (0.2.4 => 0.2.7)
 - [diesel](https://crates.io/crates/diesel) (0.6.2 => 0.8.1)
 - [discord](https://crates.io/crates/discord) (0.6.0 => 0.7.0)
 - [djangohashers](https://crates.io/crates/djangohashers) (0.2.2 => 0.2.5)
 - [docopt](https://crates.io/crates/docopt) (0.6.81 => 0.6.86)
 - [ease](https://crates.io/crates/ease) (0.5.0 => 0.6.1)
 - [encoding](https://crates.io/crates/encoding) (0.2.32 => 0.2.33)
 - [env_logger](https://crates.io/crates/env_logger) (0.3.4 => 0.3.5)
 - [etcd](https://crates.io/crates/etcd) (0.5.4 => 0.5.5)
 - [feed](https://crates.io/crates/feed) (1.2.3 => 1.2.4)
 - [flexi_logger](https://crates.io/crates/flexi_logger) (0.5.0 => 0.5.2)
 - [fnv](https://crates.io/crates/fnv) (1.0.3 => 1.0.5)
 - [formdata](https://crates.io/crates/formdata) (0.9.0 => 0.11.0)
 - **major** [ftp](https://crates.io/crates/ftp) (0.0.8 => 2.0.0)
 - [handlebars-iron](https://crates.io/crates/handlebars-iron) (0.15.3 => 0.19.2)
 - [handlebars](https://crates.io/crates/handlebars) (0.19.0 => 0.22.0)
 - [horrorshow](https://crates.io/crates/horrorshow) (0.5.6 => 0.6.1)
 - [hubcaps](https://crates.io/crates/hubcaps) (0.2.2 => 0.2.4)
 - [hyper](https://crates.io/crates/hyper) (0.9.10 => 0.9.12)
 - [influent](https://crates.io/crates/influent) (0.3.0 => 0.3.1)
 - [iron-hmac](https://crates.io/crates/iron-hmac) (0.3.3 => 0.4.0)
 - [iron-login](https://crates.io/crates/iron-login) (0.4.1 => 0.5.0)
 - [iron-test](https://crates.io/crates/iron-test) (0.3.0 => 0.4.0)
 - [json](https://crates.io/crates/json) (0.10.0 => 0.11.0)
 - [jsonrpc](https://crates.io/crates/jsonrpc) (0.7.6 => 0.8.0)
 - [jsonway](https://crates.io/crates/jsonway) (1.0.0 => 1.0.1)
 - [kafka](https://crates.io/crates/kafka) (0.4.1 => 0.5.0)
 - [keen](https://crates.io/crates/keen) (1.1.0 => 1.3.0)
 - [lettre](https://crates.io/crates/lettre) (0.5.1 => 0.6.1)
 - [liquid](https://crates.io/crates/liquid) (0.8.4 => 0.9.0)
 - [log4rs](https://crates.io/crates/log4rs) (0.4.8 => 0.5.0)
 - [logger](https://crates.io/crates/logger) (0.0.3 => 0.2.0)
 - [macaroons](https://crates.io/crates/macaroons) (0.2.1 => 0.3.1)
 - [maud](https://crates.io/crates/maud) (0.9.0 => 0.13.0)
 - [md5](https://crates.io/crates/md5) (0.1.1 => 0.2.1)
 - [mongodb](https://crates.io/crates/mongodb) (0.1.4 => 0.1.8)
 - [mongo_driver](https://crates.io/crates/mongo_driver) (0.3.0 => 0.4.0)
 - [mount](https://crates.io/crates/mount) (0.2.0 => 0.2.1)
 - [multipart](https://crates.io/crates/multipart) (0.7.0 => 0.9.0-alpha.2)
 - **major** [mysql](https://crates.io/crates/mysql) (5.2.2 => 7.1.2)
 - [nickel](https://crates.io/crates/nickel) (0.8.1 => 0.9.0)
 - [oauth2](https://crates.io/crates/oauth2) (0.1.10 => 0.2.0)
 - [oauth-client](https://crates.io/crates/oauth-client) (0.1.2 => 0.1.4)
 - [openssl](https://crates.io/crates/openssl) (0.7.14 => 0.9.1)
 - [oven](https://crates.io/crates/oven) (0.3.0 => 0.4.0)
 - [pencil](https://crates.io/crates/pencil) (0.2.1 => 0.3.0)
 - [persistent](https://crates.io/crates/persistent) (0.2.0 => 0.2.1)
 - [postgres](https://crates.io/crates/postgres) (0.11.9 => 0.13.1)
 - [queryst](https://crates.io/crates/queryst) (1.0.0 => 1.0.1)
 - [random](https://crates.io/crates/random) (0.12.1 => 0.12.2)
 - [regex](https://crates.io/crates/regex) (0.1.73 => 0.1.80)
 - [requests](https://crates.io/crates/requests) (0.0.22 => 0.0.25)
 - [ring](https://crates.io/crates/ring) (0.2.3 => 0.6.0-alpha)
 - [robotparser](https://crates.io/crates/robotparser) (0.4.4 => 0.8.0)
 - [rocksdb](https://crates.io/crates/rocksdb) (0.4.1 => 0.5.0-rc.1)
 - [router](https://crates.io/crates/router) (0.1.1 => 0.4.0)
 - [rs-es](https://crates.io/crates/rs-es) (0.4.6 => 0.6.0)
 - [rss](https://crates.io/crates/rss) (0.3.1 => 0.4.0)
 - [rusoto](https://crates.io/crates/rusoto) (0.15.3 => 0.18.1)
 - [rustache](https://crates.io/crates/rustache) (0.0.2 => 0.0.4)
 - [rustc-serialize](https://crates.io/crates/rustc-serialize) (0.3.19 => 0.3.21)
 - [rustless](https://crates.io/crates/rustless) (0.8.0 => 0.9.0)
 - [rustorm](https://crates.io/crates/rustorm) (0.5.4 => 0.5.6)
 - [schemamama](https://crates.io/crates/schemamama) (0.1.0 => 0.2.0)
 - [secp256k1](https://crates.io/crates/secp256k1) (0.5.4 => 0.6.0)
 - [sentry](https://crates.io/crates/sentry) (0.1.4 => 0.1.8)
 - [serde](https://crates.io/crates/serde) (0.8.0-rc3 => 0.8.17)
 - [serde_json](https://crates.io/crates/serde_json) (0.7.4 => 0.8.3)
 - [slog](https://crates.io/crates/slog) (0.6.0 => 1.3.0)
 - [staticfile](https://crates.io/crates/staticfile) (0.2.0 => 0.3.1)
 - [syndication](https://crates.io/crates/syndication) (0.2.0 => 0.4.0)
 - [tar](https://crates.io/crates/tar) (0.4.7 => 0.4.8)
 - [telegram-bot](https://crates.io/crates/telegram-bot) (0.4.2 => 0.5.0)
 - [tera](https://crates.io/crates/tera) (0.1.2 => 0.3.1)
 - [tiny-http](https://crates.io/crates/tiny-http) (0.5.2 => 0.5.5)
 - [urlencoded](https://crates.io/crates/urlencoded) (0.4.0 => 0.4.1)
 - [url](https://crates.io/crates/url) (1.1.1 => 1.2.3)
 - [uuid](https://crates.io/crates/uuid) (0.2.2 => 0.3.1)
 - [vkrs](https://crates.io/crates/vkrs) (0.6.2 => 0.6.3)
 - [webpki](https://crates.io/crates/webpki) (0.1.1 => 0.7.0)
 - [ws](https://crates.io/crates/ws) (0.5.1 => 0.5.3)
 - [yup-oauth2](https://crates.io/crates/yup-oauth2) (0.6.2 => 1.0.1)
 - [zip](https://crates.io/crates/zip) (0.1.17 => 0.2.0)
 - [zstd](https://crates.io/crates/zstd) (0.1.11 => 0.4.1)

Anything we missed? [Let us know](https://github.com/bashyHQ/arewewebyet/issues/new)!