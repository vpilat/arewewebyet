+++
title = "RustWebDigest #2: Learn More with Blogs and Events"

[extra]

source = { author = "ben" }

tags = [
  "frameworks",
  "digest",
  "events"
]
+++

Great things have happened in the Rust(Web) Ecosphere since the first RustWebDigest was published about two months ago. You've probably figured by now that we are doing this digest on an irregular bases with a summary of news as we see fit. If you want to help us get these out more regularly, we are looking for more people to join the team!

## Events

The announcement period for this years autumn conference season has come and it has blasting us all away with three major events dedicated to Rust. And all of them continue the trend to have another dedicated workshop day alongside their talk days. We hope to see plenty Web-Related Workshops there!

It goes without saying that we'd love to have you send in a talk proposal (and workshop proposals!) – especially if you want to talk/teach about the Web!

### RustConf

On **September 10th** there will be another official [RustConf](http://rustconf.com/) organised by the RustCore Team. It will take place in Portland, Oregon, USA. Further more, they also offer a day of training by the Rust Core Team if you come a day early.

Tickets aren't available yet, but the [Call for Papers is still open until Jun 5th](http://cfp.rustconf.com/events/rustconf-2016).

### RustFest

_(Disclaimer: The author is part of the organising team!)_

Following just a week later on Sept 17th [RustFest](http://www.rustfest.eu) will be the first dedicated Rust Conference on european grounds. Taking place in lovely, central Berlin this community conference will host one day of talks followed by a workshop day.

Tickets aren't available yet either, however you still have until [June 20th to send in your talk proposal](https://cfp.rustfest.eu/authentications).

### Rust Belt Rust

Last but not least, [Rust Belt Rust](http://www.rust-belt-rust.com/) will take place again October 29th & 28th in Pittsburgh, PA, USA. It also features one day of workshops, followed by a single track talks day.

Although the latest in the year, the CfP is already closed. Tickets aren't available yet. Nothing to do other than staying tuned.

## More Example Blogs

For those, who can't wait to learn about stuff at the conferences – and their official workshop days, you are in luck. Since the last publication, we've also seen an influx of new blog posts helping you get started with Rust Web. We've also restructured the Learn-More-Section on the website to allow space for more posts (ordered latest first). The latest additions are:

- [Let's Build a Web Server in Rust](https://dfockler.github.io/2016/05/20/web-server.html)
- [Creating a basic webservice in Rust](http://hermanradtke.com/2016/05/16/creating-a-basic-webservice-in-rust.html)
- [Rust for Node.js developers](http://fredrik.anderzon.se/2016/05/10/rust-for-node-developers-part-1-introduction/)


### Notable crates

[Sapper](https://github.com/sappworks/sapper) is not yet released as a crate but has already quite some impressive benchmarks, showing how Rust can boost Web a ton. [Sapper Works](https://github.com/sappworks) appears to want to build an entire ecosystem for "snappy" web development. We are excited to see what will come out of that!

[Neon](http://calculist.org/blog/2015/12/23/neon-node-rust/) combines Node and Rust. It essentially allows you to write native code in rust, which can then easily interact with NodeJS. This is clearly web – somehow, but we aren't really sure where to put this in the category tree. If you have an idea, [let us know here](https://github.com/bashyHQ/arewewebyet/issues/31).

[RustW](https://github.com/nrc/rustw) is a web frontend for the rust compiler. Allowing you to paste your code to a web-server and see the results (and errors) rendered in a webpage.

[Hyper announced](http://seanmonstar.com/post/141495445652/async-hyper) they will be adding asynchronous IO – using our all beloved MIO. The branch mentioned in the blog post has even been merged now and it should be working with the latest release!

### Added to index:
The following have been added to our tracking index (and the website where appropriate)

 - [bitsparrow](https://crates.io/crates/bitsparrow) (0.3.2)
 - [tera](https://crates.io/crates/tera) (0.1.1)
 - [frank_jwt](https://crates.io/crates/frank_jwt) (2.1.1)
 - [iron_json_response](https://crates.io/crates/iron_json_response) (0.1.1)
 - [log4rs](https://crates.io/crates/log4rs) (0.4.4)
 - [flexi_logger](https://crates.io/crates/flexi_logger) (0.5.0)

### Updates recorded:

Further more we recorded new releases to the following crates

 - [amqp](https://crates.io/crates/amqp) (0.0.15 => 0.0.16)
 - [atom_syndication](https://crates.io/crates/atom_syndication) (0.1.3 => 0.1.4)
 - [backtrace](https://crates.io/crates/backtrace) (0.1.8 => 0.2.1)
 - [bcrypt](https://crates.io/crates/bcrypt) (0.1.0 => 0.1.1)
 - [bodyparser](https://crates.io/crates/bodyparser) (0.2.0 => 0.3.0)
 - [cassandra](https://crates.io/crates/cassandra) (0.6.7 => 0.6.10)
 - [chrono](https://crates.io/crates/chrono) (0.2.20 => 0.2.22)
 - [clap](https://crates.io/crates/clap) (2.1.2 => 2.5.1)
 - [cookie](https://crates.io/crates/cookie) (0.2.2 => 0.2.4)
 - [crust](https://crates.io/crates/crust) (0.9.0 => 0.14.0)
 - [curl](https://crates.io/crates/curl) (0.2.16 => 0.2.19)
 - [dbmigrate](https://crates.io/crates/dbmigrate) (0.2.2 => 0.2.3)
 - [diesel](https://crates.io/crates/diesel) (0.5.0 => 0.6.2)
 - [discord](https://crates.io/crates/discord) (0.4.0 => 0.5.0)
 - [djangohashers](https://crates.io/crates/djangohashers) (0.1.0 => 0.2.2)
 - [doapi](https://crates.io/crates/doapi) (0.1.2 => 0.1.3)
 - [docopt](https://crates.io/crates/docopt) (0.6.78 => 0.6.80)
 - [env_logger](https://crates.io/crates/env_logger) (0.3.2 => 0.3.3)
 - [etcd](https://crates.io/crates/etcd) (0.3.1 => 0.5.3)
 - [farmhash](https://crates.io/crates/farmhash) (1.1.4 => 1.1.5)
 - [fastcgi](https://crates.io/crates/fastcgi) (1.0.0-alpha.3 => 1.0.0-beta)
 - [flate2](https://crates.io/crates/flate2) (0.2.13 => 0.2.14)
 - [formdata](https://crates.io/crates/formdata) (0.7.9 => 0.8.2)
 - [gettext](https://crates.io/crates/gettext) (0.1.0 => 0.2.0)
 - [handlebars-iron](https://crates.io/crates/handlebars-iron) (0.12.0 => 0.15.2)
 - [handlebars](https://crates.io/crates/handlebars) (0.15.0 => 0.16.1)
 - [http2parse](https://crates.io/crates/http2parse) (0.2.1 => 0.2.2)
 - [hubcaps](https://crates.io/crates/hubcaps) (0.1.1 => 0.2.1)
 - [hyper](https://crates.io/crates/hyper) (0.7.2 => 0.9.6)
 - [inflate](https://crates.io/crates/inflate) (0.1.0 => 0.1.1)
 - [inth-oauth2](https://crates.io/crates/inth-oauth2) (0.8.0 => 0.10.0)
 - [iron-hmac](https://crates.io/crates/iron-hmac) (0.3.0 => 0.3.3)
 - [iron-login](https://crates.io/crates/iron-login) (0.2.0 => 0.4.1)
 - [iron-test](https://crates.io/crates/iron-test) (0.2.0 => 0.3.0)
 - [iron](https://crates.io/crates/iron) (0.2.6 => 0.3.0)
 - [jsonway](https://crates.io/crates/jsonway) (0.3.5 => 1.0.0)
 - [kafka](https://crates.io/crates/kafka) (0.2.0 => 0.3.1)
 - [libsodium-sys](https://crates.io/crates/libsodium-sys) (0.0.9 => 0.0.10)
 - [liquid](https://crates.io/crates/liquid) (0.4.1 => 0.8.0)
 - [log](https://crates.io/crates/log) (0.3.5 => 0.3.6)
 - [maud](https://crates.io/crates/maud) (0.8.0 => 0.8.1)
 - [mongo_driver](https://crates.io/crates/mongo_driver) (0.2.2 => 0.2.4)
 - [mongodb](https://crates.io/crates/mongodb) (0.1.3 => 0.1.4)
 - [mount](https://crates.io/crates/mount) (0.0.10 => 0.1.0)
 - [multipart](https://crates.io/crates/multipart) (0.5.0-alpha.1 => 0.7.0)
 - [mysql](https://crates.io/crates/mysql) (2.1.0 => 5.0.0)
 - [names](https://crates.io/crates/names) (0.10.0 => 0.11.0)
 - [nickel](https://crates.io/crates/nickel) (0.7.3 => 0.8.1)
 - [oauth2](https://crates.io/crates/oauth2) (0.1.9 => 0.1.10)
 - [openssl](https://crates.io/crates/openssl) (0.7.6 => 0.7.13)
 - [oven](https://crates.io/crates/oven) (0.2.16 => 0.3.0)
 - [pencil](https://crates.io/crates/pencil) (0.1.0 => 0.2.0)
 - [persistent](https://crates.io/crates/persistent) (0.0.9 => 0.1.0)
 - [postgres](https://crates.io/crates/postgres) (0.11.4 => 0.11.7)
 - [queryst](https://crates.io/crates/queryst) (0.1.16 => 1.0.0)
 - [random](https://crates.io/crates/random) (0.9.2 => 0.10.0)
 - [raven](https://crates.io/crates/raven) (0.2.0 => 0.2.1)
 - [redis](https://crates.io/crates/redis) (0.5.2 => 0.5.3)
 - [regex](https://crates.io/crates/regex) (0.1.55 => 0.1.71)
 - [requests](https://crates.io/crates/requests) (0.0.4 => 0.0.10)
 - [robotparser](https://crates.io/crates/robotparser) (0.4.1 => 0.4.4)
 - [rocksdb](https://crates.io/crates/rocksdb) (0.3.0 => 0.3.5)
 - [rotor-http](https://crates.io/crates/rotor-http) (0.6.0 => 0.7.0)
 - [router](https://crates.io/crates/router) (0.1.0 => 0.1.1)
 - [rs-es](https://crates.io/crates/rs-es) (0.2.5 => 0.3.4)
 - [rusoto](https://crates.io/crates/rusoto) (0.12.1 => 0.13.1)
 - [rusqlite](https://crates.io/crates/rusqlite) (0.6.0 => 0.7.2)
 - [rust-crypto](https://crates.io/crates/rust-crypto) (0.2.34 => 0.2.36)
 - [rustc-serialize](https://crates.io/crates/rustc-serialize) (0.3.18 => 0.3.19)
 - [rustful](https://crates.io/crates/rustful) (0.7.0 => 0.8.0)
 - [schemamama](https://crates.io/crates/schemamama) (0.0.11 => 0.1.0)
 - [serde](https://crates.io/crates/serde) (0.7.0 => 0.7.5)
 - [staticfile](https://crates.io/crates/staticfile) (0.1.0 => 0.2.0)
 - [tar](https://crates.io/crates/tar) (0.4.4 => 0.4.5)
 - [telegram-bot](https://crates.io/crates/telegram-bot) (0.4.1 => 0.4.2)
 - [tempfile](https://crates.io/crates/tempfile) (2.1.1 => 2.1.3)
 - [time](https://crates.io/crates/time) (0.1.34 => 0.1.35)
 - [url](https://crates.io/crates/url) (0.5.7 => 1.1.0)
 - [urlencoded](https://crates.io/crates/urlencoded) (0.2.1 => 0.3.0)
 - [uuid](https://crates.io/crates/uuid) (0.1.18 => 0.2.2)
 - [vkrs](https://crates.io/crates/vkrs) (0.6.1 => 0.6.2)
 - [websocket](https://crates.io/crates/websocket) (0.15.1 => 0.17.1)
 - [ws](https://crates.io/crates/ws) (0.4.5 => 0.4.7)
 - [yup-oauth2](https://crates.io/crates/yup-oauth2) (0.5.5 => 0.6.1)
 - [zip](https://crates.io/crates/zip) (0.1.16 => 0.1.17)

Anything we missed? [Let us know](https://github.com/bashyHQ/arewewebyet/issues/new)!
