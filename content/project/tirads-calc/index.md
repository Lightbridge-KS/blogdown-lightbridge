---
title: TI-RADS Calculator App
summary: Web-application for grading Thyroid Nodule on Ultrasound. 
date: "2024-04-03"
author: "Kittipos Sirivongrungson"
external_link: https://kittipos-sir.shinyapps.io/tirads-calculator/
image:
  focal_point: Smart
tags:
  - R
  - Python
  - Shiny
  - Quarto
categories:
  - R
  - Python
  - Shiny
  - Quarto
# layout options: single or single-sidebar
layout: single
links:
- icon: globe
  icon_pack: fas
  name: app-py
  url: https://kittipos-sir.shinyapps.io/tirads-calculator/
- icon: python
  icon_pack: fab
  name: code-py
  url: https://github.com/Lightbridge-KS/tirads-calc-py
- icon: globe
  icon_pack: fas
  name: app-r
  url: https://kittipos-sir.shinyapps.io/tirads-calc/
- icon: github
  icon_pack: fab
  name: code-r
  url: https://github.com/Lightbridge-KS/tirads-calc
---

<img src="featured-hex.png" alt="logo-tirads-calc-app" width="200" style="display: block; margin: auto;" />

## What

> [TI-RADS Calculator App](https://kittipos-sir.shinyapps.io/tirads-calculator/) is a web application that facilitate categorization of Thyroid nodule by ultrasound using [TI-RADS™](https://www.acr.org/Clinical-Resources/Reporting-and-Data-Systems/TI-RADS) system, and also provides some management suggestions.


## Why

Just pure curiosity and passion for building web application that relevant in my field. Using Quarto & Shiny combination (described next) is very fun !

## Design

This app directly implement logic from the following diagram. It is programmatically *hard-coded*, since the goal here is not to predict result from some kind of model, but to give an interactive experience as you selecting choices from each categories (with examples of ultrasound images included) and the final results are displayed at the bottom of the app.

![TI-RADS Chart](tirads-chart.png)


## Ingredients

I've implemented this app in both R and Python using [Shiny](https://shiny.posit.co) as webapp engine and [Quarto](https://quarto.org) as UI structure:

**TI-RADS Calculator (Python version):** 
- [Source code](https://github.com/Lightbridge-KS/tirads-calc-py)
- [WebApp](https://kittipos-sir.shinyapps.io/tirads-calculator/)

**TI-RADS Calculator (R version):** 
- [Source code](https://github.com/Lightbridge-KS/tirads-calc)
- [WebApp](https://kittipos-sir.shinyapps.io/tirads-calc/)

[**Quarto**](https://quarto.org) is an open-source scientific and technical publishing system, a next-generation [R Markdown](https://rmarkdown.rstudio.com) that language and engine agnostic. The source code of this app was written in quarto's markdown and rendered to HTML combined with server-side processing by Shiny.

[**Shiny**](https://shiny.posit.co) is R or Python package for web application framework. It was primary use for delivers products of R or Python code to the user.


The great thing about using Shiny in Quarto document is that it leverage *beautiful* Quarto's UI "out of the box". Also, Quarto's features such as table of contents, tabset panels, and cross-referencing are available, as I've implemented them in this app.

Note: For R version, logic of this app comes from another experimental R package: [`{radcalc}`](https://github.com/Lightbridge-KS/radcalc).

## Future Improvement

- Deploy to [**ShinyLive**](https://shiny.posit.co/py/docs/shinylive.html), which still fail in current Python edition.