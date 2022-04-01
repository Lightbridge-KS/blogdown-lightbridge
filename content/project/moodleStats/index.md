---
title: moodleStats
summary: A high-level R 📦 for quiz & questions analysis of Moodle Grades Report. 
date: "2022-04-01"
author: "Kittipos Sirivongrungson"
external_link: https://lightbridge-ks.github.io/moodleStats/
image:
  focal_point: Smart
tags:
  - R
  - R-pkg
  - Education
  - Analysis
categories:
  - R-pkg
  - Stats
  - Analysis
  - Education
# layout options: single or single-sidebar
layout: single
links:
- icon: book-open
  icon_pack: fas
  name: website
  url: https://lightbridge-ks.github.io/moodleStats/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Lightbridge-KS/moodleStats/
---

<img src="featured-hex.png" alt="logo-moodleStats" width="200" style="display: block; margin: auto;" />


## Rationale

Quiz and question analysis is vital for improving the quality of exam.
[Moodle](https://moodle.org) is a popular learning management system in which teacher can create online quiz for the student. After students have submitted their work, grades and answers can be obtain by [Moodle Quiz Report](https://docs.moodle.org/311/en/Quiz_reports#Grades_report). The Moodle Quiz Reports are structured is a particular pattern that one can write code (such as R) to perform various data analysis on them. The code based analysis have an advantage of reducing human error, reducing time required for manual analysis, and allowing more reproducible workflow.

## Goal

The goal of this package it to provide a high-level functions for analysis of [Moodle Grades Report](https://docs.moodle.org/311/en/Quiz_reports#Grades_report) such as calculation of descriptive statistics for quiz & questions, and performing an item analysis.