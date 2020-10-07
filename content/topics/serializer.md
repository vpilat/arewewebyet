+++
title = "Serializers"

[extra]

intro = "Serializers allow you to easily transfer states and reliably get it back – important not only when working with JSON but also backbone of many types of worker-queue systems. Rust has good support for serializers, yet not many are web-tested..."

level = 3

packages = [
  "async-bincode",
  "bincode",
  "flatbuffers",
  "rmp",
  "serde",
  "serde_json",
  "jsonway"
]

newstag = "serialiser"
+++

{{ packages(packages='packages') }}