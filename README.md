# Hugo Test Minimal Theme

This repository offers an example site for [hugo-minimal-test](https://github.com/danielfdickinson/hugo-minimal-test) theme for [Hugo](https://gohugo.io/). It began as a fork of [hugoBasicExample](https://github.com/gohugoio/hugoBasicExample).

You can view [a demonstration on Netlify](https://hugo-test-minimal-theme.wildtechgarden.ca).

## Using

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
