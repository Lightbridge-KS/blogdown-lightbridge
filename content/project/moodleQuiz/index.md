---
title: moodleQuiz
summary: A high-level R 📦 for quiz & questions analysis of Moodle Grades Report. 
date: "2022-06-02"
author: "Kittipos Sirivongrungson"
external_link: https://lightbridge-ks.github.io/moodleQuiz/
image:
  focal_point: Smart
tags:
  - R
  - R-pkg
  - Education
  - Moodle
  - Wrangling
categories:
  - R-pkg
  - Data-processing
  - Education
  - Moodle
# layout options: single or single-sidebar
layout: single
links:
- icon: book-open
  icon_pack: fas
  name: website
  url: https://lightbridge-ks.github.io/moodleQuiz/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Lightbridge-KS/moodleQuiz/
---

<img src="featured-hex.png" alt="logo-moodleQuiz" width="200" style="display: block; margin: auto;" />


## Rationale

After students have finished quizzes from [Moodle](https://moodle.org) platform, [Moodle Quiz Reports](https://docs.moodle.org/311/en/Quiz_reports) will usually be collected, processed, graded, and combined with other reports to a single spreadsheet or store in a database before the final grading process. The intermediary score processing steps could be tedious if perform manually. Luckily, the **Moodle Quiz Reports** have some underlying structures that provides an opportunity to automate this processes with data manipulation software. That's why I've build this [`{moodleQuiz}`](https://github.com/Lightbridge-KS/moodleQuiz/) R package.


## Goal

The goal of this package it to provide a high-level ready-to-use functions for cleaning, encoding, filtering, and combining student’s score and responses from [Moodle Quiz Reports](https://docs.moodle.org/311/en/Quiz_reports).

Moreover, I've included the functions from `{moodleQuiz}` as a [*business logic engine*](https://engineering-shiny.org/structuring-project.html#business-logic-and-application-logic) to drive [this Shiny app](https://si-physio-intern.shinyapps.io/SELECx_combine_quiz/) using for student's score processing from [SELECx](http://selecx.si.mahidol.ac.th) (a Moodle platform from Faculty of Medicine Siriraj Hospital, Mahidol University, Thailand).


## See more

-   [moodleQuiz website](https://lightbridge-ks.github.io/moodleQuiz/)
  
-   [moodleQuiz repository](https://github.com/Lightbridge-KS/moodleQuiz/)

-   [SELECx Combine Quiz App](https://si-physio-intern.shinyapps.io/SELECx_combine_quiz/)