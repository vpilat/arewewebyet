+++
title = "JSON Support"

[extra]

intro = "Whether you are offering an external API or just want to talk to the modern Javascript Frontend Interface, you need to support JSON. And while there is most certainly JSON on the way, many things web-specific are still lacking."

level = 3

packages = [
  "serde_json",
  "json_in_type",
  "jsonway",
  "jsonrpc",
  "iron_json_response",
  "json",
  "valico"
]

newstag = "json"
+++

{{ packages(packages='packages') }}