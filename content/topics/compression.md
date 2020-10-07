+++
title = "Compression Libs"

[extra]

level = 1

intro = "One of the first things almost anyone does to improve performance (specifically bandwidth) is to turn on compression. Luckily compression is well supported in rust."

packages = [
  "flate2",
  "tar",
  "inflate",
  "bzip2",
  "brotli",
  "zip",
  "zstd"
]

newstag = "compression"
+++

{{ packages(packages='packages') }}