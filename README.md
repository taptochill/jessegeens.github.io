# TapToChill legal website

## About

This git repository contains all the files for the TapToChill legal website, hosted at [legal.taptochill.app](https://legal.taptochill.app).

## Usage

This site runs on Jekyll. Find installation instructions [here](https://jekyllrb.com/docs/installation/)
When you have installed Jekyll, you can compile the static site by running `bundle exec jekyll build` in your command line.

All pages are written in markdown, where a heading is prepended to the markdown file to indicate website metadata. An example from the privacy policy page:
```
---
layout: page
title: Privacy Policy
permalink: /privacy/
---
```

When you are happy with the results, just push the website to master and it will automatically be served by github pages.
