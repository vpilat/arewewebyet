+++
title = "En- & Decoding"

[extra]

level = 1

intro = "Encoding is one of those things you don't really want to bother about, but just rely on a well tested library for – there are just too many edge and quirky cases. Luckily, as a system language, this is one of the things rust shines at – and offers a set of nice packages already."

packages = [
  "data-encoding",
  "encoding",
  "base64",
  "urlencoded",
  "multipart",
  "bitsparrow"
]

newstag = "encoding"
+++

{{ packages(packages='packages') }}