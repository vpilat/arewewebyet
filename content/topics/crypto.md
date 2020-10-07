+++
template = "topic.html"
title = "Crypto"

[extra]

level = 3

intro = "Cryptography is a corner stone of a trusted web. Without it many services could not be offered reliably. While rust has a strong RNG, the main suite in use isn't pure rust but the (in)famous openssl."

suites = [
  "openssl",
  "orion",
  "libsodium-sys",
  "gpgme",
  "ring"
]

rng = [
  "rand",
  "uuid"
]

passwords = [
  "bcrypt",
  "djangohashers",
  "pwhash"
]

tls = [
  "rustls",
  "tokio-openssl",
  "tokio-rustls",
  "tokio-tls",
  "openssl",
  "webpki",
]

hashing = [
  "fnv",
  "twox-hash",
  "md5",
  "djangohashers",
  "blake2-rfc",
  "bcrypt",
  "pwhash"
]

algorithms = [
  "blake2-rfc",
  "bulletproofs",
  "curve25519-dalek",
  "ed25519-dalek",
  "merlin",
  "secp256k1",
  "subtle",
  "twox-hash",
  "x25519-dalek",
  "zkp"
]

tooling = [
  "tempfile",
  "cookie",
  "frank_jwt"
]

newstag = "crypto"
+++

<h2>Suites  {% include level.html level=2 %}</h2>

{{ packages(packages='suites') }}

<h2>Random Number Generators  {% include level.html level=0 %}</h2>

{{ packages(packages='rng') }}

<h2>Password  {% include level.html level=3 %}</h2>

{{ packages(packages='passwords') }}

<h2>TLS  {% include level.html level=3 %}</h2>

{{ packages(packages='tls') }}

<h2>Tooling  {% include level.html level=4 %}</h2>

<p><em>Tooling is great, just a little scarce...</em></p>

{{ packages(packages='tooling') }}

+++

<h2>Also</h2>

<h3>Hashing  {% include level.html level=3 %}</h3>

{{ packages(packages='hashing') }}

<h3>Algorithms  {% include level.html level=3 %}</h3>

{{ packages(packages='algorithms') }}
