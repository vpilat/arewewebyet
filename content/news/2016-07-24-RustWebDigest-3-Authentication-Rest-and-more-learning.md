+++
title = "RustWebDigest #3: Authentication, Rust and Rest and more learning"

[extra]

source = { author = "ben" }

tags = [
  "logging",
  "rest"
]
+++

The biggest news since the last RustWebDigest is without question the alpha release of Servo – the web rendering engine entirely written in Rust by Mozilla. It's a big effing deal and if you haven't downloaded it yet, I highly recommend doing so. While its still in alpha stage, it is very impressive what the team has delivered and keeps delivering with their nightly builds 👏.

The second most widely spread news Armin Ronacher's – you know, the person behind Flask – blog post about doing nice [API development for Rest-APIs with Rust](http://lucumr.pocoo.org/2016/7/10/rust-rest/) that he encountered while implementing the Sentry Rust Client. Similarly big waves only received Dropbox for their [all rust brotli implementation, claiming to bring pied piper to life](https://blogs.dropbox.com/tech/2016/06/lossless-compression-with-brotli/), but weirdly only implementing _de_ compression so far. But both of sources of big credit showing strengths of Rust in very public posts, increasing the visibility and viability of Rust as decent web development environment.

## Authentication, remote logging

After due consideration we've decided to rename the prior OAuth topic to a broader "Authentication/Authorization" topic as suggested by [Marcel Müller](https://github.com/TheNeikos). Thanks, Marcel, good idea!

Making that topic more broad also allowed us to add more libraries to that area. [Go check it out](/topics/auth/).

The second big change on the website is around logging: We've added slog (a structured logging facility) and a few remote logging implementations (sentry, airbrake) – very important tooling for every web developer!


## More Learning

_Disclaimer: the author is co-organiser of RustFest._

### Connecting RustFest and View Source

More of a side note the [RustFest team announced their collaboration with Mozilla sponsored "View Source"](http://www.rustfest.eu/blog/this-week-in-rustfest-7-first-talks-and-viewsource), a conference dedicated to the open web. Within that side note, they announced to be hosting a discussion area about rust at View Source – reaching out to the web developer folks on their own turf. Despite not having announced any web-related talks at that conference, that's an important sign. I highly recommend to get in touch if you are interested making that discussion awesome.

### More blogs

We've also seen a few more interesting blog posts about rust for web development and updates the main website accordingly:


- [Rust and Rest](http://lucumr.pocoo.org/2016/7/10/rust-rest/) (as previously mentioned)
- [REST in Rust](https://gsquire.github.io/static/post/rest-in-rust/)
- [Connecting a webservice to a database in Rust](http://hermanradtke.com/2016/05/23/connecting-webservice-database-rust.html)

### arewewebyet/web development talk at Berlin Rust User Group

And finally, you have the chance to see [me on stage this week at Berlin Rust User Group](http://www.meetup.com/Rust-Berlin/events/232583152/), trying to convince the folks in front of me to do web development with rust by implementing a tiny microservice with the help of arewewebyet. Come by and say hi!


## Crate updates:

### Added to index:
The following have been added to our tracking index (and the website where appropriate)

 - [airbrake](https://crates.io/crates/airbrake) (0.1.0)
 - [brotli](https://crates.io/crates/brotli) (1.0.6)
 - [catapult](https://crates.io/crates/catapult) (0.1.2)
 - [frank_jwt](https://crates.io/crates/frank_jwt) (2.2.1)
 - [horrorshow](https://crates.io/crates/horrorshow) (0.5.6)
 - [macaroons](https://crates.io/crates/macaroons) (0.2.1)
 - [otpauth](https://crates.io/crates/otpauth) (0.2.5)
 - [slog](https://crates.io/crates/slog) (0.6.0)
 - [sentry](https://crates.io/crates/sentry) (0.1.4)
 - [zstd](https://crates.io/crates/zstd) (0.1.11)

### Updates recorded:

Further more we recorded new releases to the following crates

 - [backtrace](https://crates.io/crates/backtrace) (0.2.1 => 0.2.3)
 - [base64](https://crates.io/crates/base64) (0.1.1 => 0.2.0)
 - [bodyparser](https://crates.io/crates/bodyparser) (0.3.0 => 0.4.0)
 - [cassandra](https://crates.io/crates/cassandra) (0.6.10 => 0.7.2)
 - [clap](https://crates.io/crates/clap) (2.5.1 => 2.9.3)
 - [cookie](https://crates.io/crates/cookie) (0.2.4 => 0.2.5)
 - [crust](https://crates.io/crates/crust) (0.14.0 => 0.16.1)
 - [curl](https://crates.io/crates/curl) (0.2.19 => 0.3.1)
 - [dbmigrate](https://crates.io/crates/dbmigrate) (0.2.3 => 0.2.4)
 - [discord](https://crates.io/crates/discord) (0.5.0 => 0.6.0)
 - [docopt](https://crates.io/crates/docopt) (0.6.80 => 0.6.81)
 - [ease](https://crates.io/crates/ease) (0.4.2 => 0.5.0)
 - [env_logger](https://crates.io/crates/env_logger) (0.3.3 => 0.3.4)
 - [etcd](https://crates.io/crates/etcd) (0.5.3 => 0.5.4)
 - _feedreader_ was renamed to [feed](https://crates.io/crates/feed) (1.2.3)
 - [fnv](https://crates.io/crates/fnv) (1.0.2 => 1.0.3)
 - [formdata](https://crates.io/crates/formdata) (0.8.2 => 0.9.0)
 - [ftp](https://crates.io/crates/ftp) (0.0.7 => 0.0.8)
 - [googl](https://crates.io/crates/googl) (0.0.3 => 0.0.4)
 - [handlebars-iron](https://crates.io/crates/handlebars-iron) (0.15.2 => 0.15.3)
 - [handlebars](https://crates.io/crates/handlebars) (0.16.1 => 0.19.0)
 - [hubcaps](https://crates.io/crates/hubcaps) (0.2.1 => 0.2.2)
 - [hyper](https://crates.io/crates/hyper) (0.9.6 => 0.9.10)
 - [imap](https://crates.io/crates/imap) (0.0.5 => 0.0.6)
 - [influent](https://crates.io/crates/influent) (0.2.2 => 0.3.0)
 - [iron](https://crates.io/crates/iron) (0.3.0 => 0.4.0)
 - [iron_vhosts](https://crates.io/crates/iron_vhosts) (0.1.0 => 0.2.0)
 - [json](https://crates.io/crates/json) (0.8.4 => 0.10.0)
 - [json_macros](https://crates.io/crates/json_macros) (0.3.0 => 0.3.2)
 - [jsonrpc](https://crates.io/crates/jsonrpc) (0.7.4 => 0.7.6)
 - [kafka](https://crates.io/crates/kafka) (0.3.1 => 0.4.1)
 - [libsodium-sys](https://crates.io/crates/libsodium-sys) (0.0.10 => 0.0.12)
 - [liquid](https://crates.io/crates/liquid) (0.8.0 => 0.8.4)
 - [log4rs](https://crates.io/crates/log4rs) (0.4.4 => 0.4.8)
 - [maud](https://crates.io/crates/maud) (0.8.1 => 0.9.0)
 - [mongo_driver](https://crates.io/crates/mongo_driver) (0.2.4 => 0.3.0)
 - [mount](https://crates.io/crates/mount) (0.1.0 => 0.2.0)
 - [mysql](https://crates.io/crates/mysql) (5.0.0 => 5.2.2)
 - [openssl](https://crates.io/crates/openssl) (0.7.13 => 0.7.14)
 - [pencil](https://crates.io/crates/pencil) (0.2.0 => 0.2.1)
 - [persistent](https://crates.io/crates/persistent) (0.1.0 => 0.2.0)
 - [pop3](https://crates.io/crates/pop3) (0.0.5 => 0.0.6)
 - [postgres](https://crates.io/crates/postgres) (0.11.7 => 0.11.9)
 - [random](https://crates.io/crates/random) (0.10.0 => 0.12.1)
 - [redis](https://crates.io/crates/redis) (0.5.3 => 0.7.0)
 - [regex](https://crates.io/crates/regex) (0.1.71 => 0.1.73)
 - [requests](https://crates.io/crates/requests) (0.0.10 => 0.0.22)
 - [rocksdb](https://crates.io/crates/rocksdb) (0.3.5 => 0.4.1)
 - [rs-es](https://crates.io/crates/rs-es) (0.3.4 => 0.4.6)
 - [rusoto](https://crates.io/crates/rusoto) (0.13.1 => 0.15.3)
 - [rusqlite](https://crates.io/crates/rusqlite) (0.7.2 => 0.7.3)
 - [rustache](https://crates.io/crates/rustache) (0.0.1 => 0.0.2)
 - [rustful](https://crates.io/crates/rustful) (0.8.0 => 0.9.0)
 - [rustorm](https://crates.io/crates/rustorm) (0.4.3 => 0.5.4)
 - [serde](https://crates.io/crates/serde) (0.7.5 => 0.8.0-rc3)
 - [serde_json](https://crates.io/crates/serde_json) (0.7.0 => 0.7.4)
 - [syndication](https://crates.io/crates/syndication) (0.1.1 => 0.2.0)
 - [syslog](https://crates.io/crates/syslog) (3.1.0 => 3.2.0)
 - [tar](https://crates.io/crates/tar) (0.4.5 => 0.4.7)
 - [tempfile](https://crates.io/crates/tempfile) (2.1.3 => 2.1.4)
 - [tera](https://crates.io/crates/tera) (0.1.1 => 0.1.2)
 - [tiny-http](https://crates.io/crates/tiny-http) (0.5.1 => 0.5.2)
 - [url](https://crates.io/crates/url) (1.1.0 => 1.1.1)
 - [urlencoded](https://crates.io/crates/urlencoded) (0.3.0 => 0.4.0)
 - [ws](https://crates.io/crates/ws) (0.4.7 => 0.5.1)
 - [yup-oauth2](https://crates.io/crates/yup-oauth2) (0.6.1 => 0.6.2)

Anything we missed? [Let us know](https://github.com/bashyHQ/arewewebyet/issues/new)!
