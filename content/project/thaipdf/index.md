---
title: thaipdf
summary: R package that helps render R Markdown to PDF in Thai language 🇹🇭. 
date: "2022-03-28"
author: "Kittipos Sirivongrungson"
external_link: https://lightbridge-ks.github.io/thaipdf/
image:
  focal_point: Smart
tags:
  - R
  - R-pkg
categories:
  - R-pkg
  - R-markdown
  - LaTeX
# layout options: single or single-sidebar
layout: single
links:
- icon: book-open
  icon_pack: fas
  name: website
  url: https://lightbridge-ks.github.io/thaipdf/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Lightbridge-KS/thaipdf/
---

<img src="featured-hex.png" alt="logo-thaipdf" width="200" style="display: block; margin: auto;" />

## Rationale

It is not easy to create a PDF from R Markdown written in **Thai language** since there are LaTeX configurations that need to be added to the preamble of the document. That's why I build [thaipdf](https://lightbridge-ks.github.io/thaipdf/) package.


## Goal

The goal is to facilitate R users who not know very much about LaTeX to have an ability to **knit** Thai R Markdown document to a PDF **out of the box**. 

Also, for pro LaTeX user can also benefit from this package in that this package provides helper funcions to use template for Thai language configuration quickly.