---
title: zoomclass
summary: "A high-level data analysis R 📦 for Zoom’s participants report and Zoom’s chat file." 
date: "2022-04-03"
author: "Kittipos Sirivongrungson"
external_link: https://lightbridge-ks.github.io/zoomclass/
image:
  focal_point: Smart
tags:
  - R
  - R-pkg
  - Education
  - Analysis
  - Zoom
categories:
  - R-pkg
  - Analysis
  - Education
# layout options: single or single-sidebar
layout: single
links:
- icon: book-open
  icon_pack: fas
  name: website
  url: https://lightbridge-ks.github.io/zoomclass/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Lightbridge-KS/zoomclass/
---

<img src="featured-hex.png" alt="logo-zoomclass" width="200" style="display: block; margin: auto;" />

## Rationale

[Zoom](https://zoom.us) is a popular video conference platform for online teaching and sometimes for monitoring student taking an online-examination.

**Text-based data** obtained from Zoom classroom that show valuable information are **Zoom’s participants report** and **Zoom’s chat file**.


- **Zoom’s participants report** contains data related to participants who joined the classroom including join time and leave time. This record is valuable for teacher to check whether students have joined class, or if joined, check whether he/she late or not.

- **Zoom’s chat file** contains public contents in the Zoom chat box. It a convenient and quick way for students to ask, comment, or give answers to teacher in class. The chat message when downloaded as a text file give information about who, what, and when participants reply a message. It can be valuable for the teacher to review questions and answers in the class.

Theses 2 data has some underlying *fixed* structure; therefore, It can be helpful to write a piece of software to scrape, transform, and perform analysis on these data.

That's why I build [zoomclass](https://lightbridge-ks.github.io/zoomclass/) package.

## Goal

It is a high-level data analysis R package for Zoom’s participants report `.csv` and Zoom’s chat `.txt` file.

## See more

Please visit: [zoomclass website](https://lightbridge-ks.github.io/zoomclass/)