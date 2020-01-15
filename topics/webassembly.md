---
layout: topic
title: "WebAssembly"

level: 2

intro: WebAssembly is currently being designed as an open standard by the W3C Community Group
 that includes representatives from all major browsers.
 There are two major libraries for JavaScript ffi - `wasm-bindgen` and `stdweb`. Eventually,
 they will [share](https://github.com/koute/stdweb/issues/318) the same build tools.
 But at the moment to build `wasm-bindgen` project - `wasm-pack` is required, and
 for `stdweb` there is a `cargo-web`. Current ffi bindings for JavaScript api
 are quite low-level. There is an initiative to build a modular toolkit
 named [gloo](https://rustwasm.github.io/2019/03/12/lets-build-gloo-together.html)

packages:
 - cargo-wasi
 - cargo-web
 - console_error_panic_hook
 - console_log
 - dodrio
 - dominator
 - futures-signals
 - gloo
 - mogwai
 - moxie-dom
 - plaster
 - plotters
 - seed
 - smithy
 - squark
 - state_machine_future
 - stdweb
 - virtual-dom-rs
 - wasm-bindgen
 - wasm-bindgen-futures
 - wasm-pack
 - wasm-tracing-allocator
 - woz
 - yew

news_tag: webassembly
---
