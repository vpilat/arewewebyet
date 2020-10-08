---
layout: main
---

# Are we _web_ yet?

**Yes! And it's freaking fast!**

## Can I replace my Rails/Django/Flask already?

**Yup!** Rust has mature and production ready frameworks in <a href="/topics/frameworks/#pkg-actix-web">Actix Web</a> and <a href="/topics/frameworks/#pkg-rocket">Rocket</a>, and newer ones like <a href="/topics/frameworks/#pkg-warp">Warp</a> and <a href="/topics/frameworks/#pkg-tide">Tide</a>. These provide everything you'd expect from a web framework, from routing and middleware, to templating, and JSON/form handling. There are crates for everything, and more! For databases, there's:

<ul>
  <li>
    <a href="/topics/database/#pkg-diesel">Diesel</a>, a full-fledged ORM.
  </li>
  <li>
    <a href="/topics/database/#pkg-sqlx">sqlx</a>, the async sql toolkit.
  </li>
  <li>
    As well as native drivers for <a href="/topics/database/#pkg-mongo">MongoDB</a>, <a href="/topics/database/#pkg-rusqlite">SQlite</a>, <a href="/topics/database/#pkg-postgres">Postgres</a>, and <a href="/topics/database/#pkg-mysql">MySQL</a>.
  </li>
</ul>

There are many integrations to third-party services, such as:

<ul>
  <li>
    <a href="/topics/services/#pkg-rusoto">Rusoto</a> (AWS)
  </li>
  <li>
    <a href="/topics/services/#pkg-azure_sdk_for_rust">Azure</a>
  </li>
  <li>
    <a href="/topics/services/#pkg-redis">Redis</a>
  </li>
  <li>
    <a href="/topics/services/#pkg-elasticsearch">Elasticsearch</a>
  </li>
</ul>

<p>And of course, there is plenty of support for basic web needs, like <a href="/topics/logging/">logging</a> {% include level.html level=2 %}, <a href="/topics/auth/">authorization</a> {% include level.html level=4 %}, <a href="/topics/templating/">templating</a> {% include level.html level=4 %}, and <a href="/topics/email/">email</a> {% include level.html level=4 %}.</p>

While development might not be as smooth as something like Rails or Django, the Rust web development ecosystem and community is engaged and very helpful. A lot of work has been put into the web in the past few years, and we're getting there!

### WebAssembly???

<p>Rust can even run on the browser, by compiling to <a href="/topics/webassembly/">WebAssembly</a> {% include level.html level=2 %}. This means that you can take advantage of the amazing Rust ecosystem on the browser! Rust and WebAssembly integrate with existing Javascript tooling. It supports NPM, Webpack, and ECMAScript modules! There are some <a href="/topics/webassembly/">awesome Rust and WebAssembly</a> projects out there. For example, <a href="https://github.com/yewstack/yew">Yew</a> and <a href="https://github.com/seed-rs/seed">Seed</a> let you create front-end web apps with Rust in a way that feels almost like React.js.</p>

For more information about Rust and WebAssembly, check out the [Rust and WebAssembly Book](https://rustwasm.github.io/docs/book/introduction.html).

### Getting started

After you've set up your Rust and worked yourself [through "The Book"](https://doc.rust-lang.org/book/), you might want to check any of these resources:

- [Building web apps with Rust using the Rocket framework](https://blog.logrocket.com/rust-web-apps-using-rocket-framework/)
- [Educational Rust Live Coding - Web App From Scratch](https://www.youtube.com/watch?v=yNe9Xr35n4Q&list=PL8lUUBadSMNBNKMYJpUE830tBiN6bxVRw&ab_channel=DavidPedersen)
- [Actix-Web Auth Microservice](https://gill.net.in/posts/auth-microservice-rust-actix-web1.0-diesel-complete-tutorial/)
- [Practical Rust Web Development (Series)](https://dev.to/werner/practical-rust-web-development-api-rest-29g1)
- [Build an API in Rust with JWT Authentication](https://auth0.com/blog/build-an-api-in-rust-with-jwt-authentication-using-actix-web/)
- [Rocket Quickstart](https://rocket.rs/v0.4/guide/quickstart/)

Either way you choose, if you find yourself stuck and looking for help, you can check out the [official Rust forum](https://users.rust-lang.org/c/help), the [rust tag on stackoverflow](https://stackoverflow.com/questions/tagged/rust), or the [Rust Discord server](https://discord.com/invite/rust-lang) where you are welcome to post your questions and will find excellent help.

## In detail

Learn more about the state of web development in Rust by topic:

<ul class="topic-list">
  {% for page in site.pages %}
    {% if page.layout == 'topic' %}
      <li><a href="{{page.url}}">{{page.title}}</a>  {% include level.html level=page.level%}</li>
    {% endif %}
  {% endfor %}
</ul>

<ul class="legend">
  <li>{% include level.html level=0 %}: everything is awesome<a href="https://www.youtube.com/watch?v=9cQgQIMlwWw" target="_blank">™</a>: stable, tested and mature</li>
  <li>{% include level.html level=1 %}: stuff's pretty great</li>
  <li>{% include level.html level=2 %}: getting there, stable but still maturing</li>
  <li>{% include level.html level=3 %}: not yet stable, but progressing</li>
  <li>{% include level.html level=4 %}: unstable/incomplete, needs work</li>
  <li>{% include level.html level=5 %}: barely there, needs serious work</li>
  <li>{% include level.html level=6 %}: basically nonexistent</li>
</ul>
