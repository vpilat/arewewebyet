+++
title = "CMS"

[extra]

level = 4

intro = "Managing digital content is a fundamental part of the web as we have it today. Content management systems aim to make it easier to create, update, and serve digital content. Currently, the Rust CMS ecosytem consists only of static site generators, which serve as frameworks for creating websites from static content files."

static-site-generators = [
  "blades",
  "cobalt-bin",
  "mdbook"
]

news_tag = "cms"
+++

<h2>Static Site Generators {{ level(level=1) }}</h2>

<ul class="pkg-list">
  <li id="pkg-zola" class="pkg">
    <span class="pkg-name">zola</span>
    <a class="pkg-link" title="homepage" href="https://www.getzola.org/"><i class="fa fa-home"></i></a>
    <a class="pkg-link" title="documentation" href="https://www.getzola.org/documentation/getting-started/overview/"><i   class="fa fa-book"></i></a>
    <a class="pkg-link" title="repository" href="https://github.com/getzola/zola"><i class="fa fa-code"></i></a>
    <p class="pkg-meta">
      <img src="https://img.shields.io/github/last-commit/getzola/zola.svg">
    </p>
    <p class="pkg-desc">
      A fast static site generator in a single binary with everything built-in. This very site is generated with zola!
    </p>
  </li>
</ul>

{{ packages(packages='static-site-generators') }}
