+++
title = "About"
description = "Hugo, the world's fastest framework for building websites"
date = "2019-02-28"
aliases = ["about-us", "about-hugo", "contact"]
author = "Hugo Authors"
+++

## From hugoTestMinimalTheme README

This repository offers an example site for [hugoMinimalTestTheme](https://hugo-minimal-test-theme-demo.wildtechgarden.ca) theme for [Hugo](https://gohugo.io/). It is began as a fork of [hugoBasicExample](https://github.com/gohugoio/hugoBasicExample).

### Using

1. [Install Hugo](https://gohugo.io/overview/installing/)
2. Clone this repository

```bash
git clone https://github.com/danielfdickinson/hugoTestMinimalTheme.git
cd hugoTestMinimalTheme
```
3. Run Hugo local server

```bash
hugo server -b http://localhost:1313/
```

4. Under `/content/` this repository contains the following:

- A section called `/post/` with sample markdown content
- A section called `/docs` with the documentation for the included theme (``hugoMinimalTestTheme``) and a nested module used to generate an optional list of debug tables (``hugoDebugTables``).
- A headless bundle called `homepage` that you may want to use for single page applications. You can find instructions about headless bundles over [here](https://gohugo.io/content-management/page-bundles/#headless-bundle)
- An `about.md` that is intended to provide the `/about/` page for a theme demo


## From hugoMinimalTestTheme README

A minimum test theme to generate the full site of unstyled pages for https://github.com/gohugoio/hugoBasicExample (and other Hugo sites).

Includes the ability to enable less minimal features via custom layouts (with thanks to members of the [Hugo Forum](https://discourse.gohugo.io) for their suggestions).

The purpose of the repo is not for CI or automated testing, but to have a set of layouts for creating minimum reproducible test cases for reporting bugs to the Hugo developers.

The site content is mostly from the [hugoBasicExample](https://github.com/gohugoio/hugoBasicExample) demonstration site by the Steve Francia and the Hugo Authors

### Obtaining hugoMinimalTestTheme

You can get it from <https://github.com/danielfdickinson/hugoMinimalTestTheme>.
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
