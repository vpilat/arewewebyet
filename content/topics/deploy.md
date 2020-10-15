+++
title = "Deployment"

[extra]

level = 3

intro = "How is Rust deployment onto existing server infrastructures? Well, stuff is looking quite good actually."

missing = [
  "Google Cloud (App Engine, Functions, Run) Support",
  "Microsoft Azure Support",
]
+++
<h2>Heroku {{ level(level=3) }}</h2>

[Heroku](https://www.heroku.com/) is a cloud PaaS tool that supports collections of languages. It does not support Rust natively, however, you can run Heroku with [github.com/emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust), a popular but unofficial buildpack.

<h2>AWS Lambda{{ level(level=0) }}</h2>

[AWS Lambda](https://aws.amazon.com/lambda/) supports Rust natively with an [opensource runtime](https://github.com/awslabs/aws-lambda-rust-runtime)! There is also an unofficial but very popular AWS SDK, [rusoto](/topics/services/#pkg-rusoto_core).

<h2>Docker {{ level(level=0) }}</h2>

There are [official docker images](https://github.com/rust-lang-nursery/docker-rust) for rust ([`rust`](https://hub.docker.com/_/rust/)) with over 10+ Million downloads! There are also nightly images ([`rustlang/rust`](https://hub.docker.com/r/rustlang/rust/)) if your application requires it. If you use docker's [multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build/), you can build your application binary and then copy it into a container. This allows you to avoid deploying the entire compilation toolchain with your web application.

<h2>Vercel Now {{ level(level=3) }}</h2>

[Vercel Now](https://vercel.com/), (formerly Zeit Now) is a cloud platform for serverless functions. There is a a community rust runtime, [now-rust](https://github.com/mike-engel/now-rust).

<h2>Unikernels {{ level(level=2) }}</h2>

Unikernels are the rising star and newest hot thing to do big scale deployment. With Rust being a system language unikernels are an obvious approach to the problem and doing your research you'll find that there is a lot happening here indeed. There's a number of unikernels which support rust:
 - [nanos](https://github.com/nanovms/nanos)
 - [rumprun](https://github.com/rumpkernel/rumprun) with `--target x86_64-rumprun-netbsd`
