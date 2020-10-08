+++
title = "Lower Web-Stack"

[extra]

level = 2

intro = "A strong lower web-stack is important not only to build strong web frameworks on top, but also to allow performance critical systems to reach deeper to squeeze out extra juice. Rust has a good support on HTTP servers, even an HTTP2 implementation, websockets and other protocols."

servers = [
  "hyper",
  "tiny-http"
]

http2 = [
  "h2"
]

quic = [
  "quinn"
]

websocket = [
  "tungstenite",
  "websocket",
  "ws"
]

protocols = [
  "crust",
  "ftp",
  "fastcgi",
  "sozu"
]

newstag = "stack"

upcoming = [
  { name = "fractalide", url = "https://github.com/fractalide/fractalide", desc = "simple rust microservices" }
]

+++
## HTTP Servers

{{ packages(packages='servers') }}

## HTTP2

{{ packages(packages='http2') }}

## QUIC

{{ packages(packages='quic') }}

## Websocket

{{ packages(packages='websocket') }}

## Other protocols

{{ packages(packages='protocols') }}
