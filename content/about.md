+++
title = "About"
description = "Hugo, the world's fastest framework for building websites"
date = "2019-02-28"
aliases = ["about-us", "about-hugo", "contact"]
author = "Hugo Authors"
+++

## From hugo-test-minimal-theme README

### Using

1. [Install Hugo](https://gohugo.io/overview/installing/)
2. Clone this repository

```bash
git clone https://github.com/danielfdickinson/hugo-test-minimal-theme.git
cd hugo-test-minimal-theme
```
3. Run Hugo local server

```bash
hugo server -b http://localhost:1313/
```

4. Under `/content/` this repository contains the following:

- A section called `/post/` with sample markdown content
- A section called `/docs` with the documentation for the included theme (``hugo-minimal-test``) and a nested module used to generate an optional list of debug tables (``hugo-debug-tables``).

## From hugo-minimal-test README

This theme is not intended to be used as a normal theme. It is intended as a framework for creating minimal reproducible test cases. As such, one does not simply drop it in a site, but rather creates a repository specifically designed to isolate and demonstrate the issue one is facing.

The goal is to minimize the amount of 'layout grunt work' one has to do to create the test case.

It includes the ability to enable less minimal features via custom layouts (with thanks to members of the [Hugo Forum](https://discourse.gohugo.io) for their suggestions).

## Documentation

[hugo-minim-test-theme-docs](/docs/hugo-minimal-test-theme-docs)

### Obtaining hugo-minimal-test

You can get it from <https://github.com/danielfdickinson/hugo-minimal-test>.
## From hugoBasicExample About page

Written in Go, Hugo is an open source static site generator available under the [Apache Licence 2.0.](https://github.com/gohugoio/hugo/blob/master/LICENSE) Hugo supports TOML, YAML and JSON data file types, Markdown and HTML content files and uses shortcodes to add rich content. Other notable features are taxonomies, multilingual mode, image processing, custom output formats, HTML/CSS/JS minification and support for Sass SCSS workflows.

Hugo makes use of a variety of open source projects including:

* https://github.com/yuin/goldmark
* https://github.com/alecthomas/chroma
* https://github.com/muesli/smartcrop
* https://github.com/spf13/cobra
* https://github.com/spf13/viper

Hugo is ideal for blogs, corporate websites, creative portfolios, online magazines, single page applications or even a website with thousands of pages.

Hugo is for people who want to hand code their own website without worrying about setting up complicated runtimes, dependencies and databases.

Websites built with Hugo are extremely fast, secure and can be deployed anywhere including, AWS, GitHub Pages, Heroku, Netlify and any other hosting provider.

Learn more and contribute on [GitHub](https://github.com/gohugoio).
