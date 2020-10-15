# Project Documentation

This document outlines the technologies used, the structure of the project and data and jump starts your development and setup.

## Getting started

This project is hosted on github pages and uses the [Zola](https://www.getzola.org/). Zola is a static website compiler – it uses our data to generate a bunch of HTML pages. If you do not have zola yet, you can install it by using brew (`brew install zola`), snap (`snap install --edge zola`) or any other way [outlined on the official website](https://www.getzola.org/documentation/getting-started/installation/).

To compile the documents, run from the main directory

```bash
zola serve
```

Now open a browser on `http://localhost:1111` and you'll be able to see the homepage in its latest version. Any changes you make immediately rerender the websites after saving the file, you just need to refresh the browser.

## Site structure

To make contributing easy we use markdown, where we can. So you'll find all topic pages (in `content/topics/`). You will find that this matches the different `zola` templates we provide (in `templates/`): `base` and `topic-page`.

A `topic` in this website refers to a distinct subset of the web ecosystem to investigate. For example, JSON is a topic and the file might look like this:

```toml
+++
title = "JSON Support"

[extra]

level = 3
packages = [
  "serde_json",
  "json_macros",
  "jsonway",
  "weakjson",
  "jsonrpc"
]
+++
```

Aside from the layout and it's title, a topic also has the "maturity" level – an indicator from 0-6, which indicates how mature the curators believe this topic to be in rust (0 being the most mature and tested). Usually a topic also comes with a list of packages. These reference the packages-filenames as mentioned below in the data structures section.

Anything after the second `+++` is then rendered after the title in the top of the page, before the packages are listed. If no packages are found, none are rendered. Which might be what you want, especially if you want to split them up into your own sections. In that case, however, you have to do the rendering yourself at the moment. Take a look at the `content/topics/services.md` for an example on how to achieve that.


## Data Handling

We load data from the crates.io API directly during the build proccess using the `load_data(url="")` macro provided by zola.

## Template Includes

### Level

You can easily render the level indicator (colored and with the right icon) by including the `level.html` macro. It takes one parameter `level`, which is an integer from 0-5, anything else will be understood as "worse than 6".

Example:

```html
{% import "macros/level.html" as level %}

{{ level::level(level=2) }}
```

Note that macros can only be used in templates (`.html`), not in markdown files. To get around this, we use [zola shortcodes](https://www.getzola.org/documentation/content/shortcodes/) that link to the corresponding macro. In markdown you do not need to import the file:

```markdown
{{ level(level=2) }}
```

### Package

You can render the package `li` element at any point by just rendering the `package` macro. It takes one parameter `name`, which is the name of the package in question.

Example:

```html
{{ package(pkg_name=pkg_name) }}
```

### Packages

To render a list of packages as a `ul` block, just include the `packages` macro or shortcode. It takes one parameter `packages`, which is the list of names of packages.

HTML Template Example:

```html
{% import "macros/packages.html" as packages %}

{{ packages::packages(packages=page.extra.packages) }}
```

In markdown, you can use the `packages` shortcode and pass in the name of the toml frontmatter array containing the packages:

```toml
+++
[extra]

queries = [
  "datafusion"
]
+++

{{ packages(packages='queries') }}
```
