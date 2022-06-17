---
title: Books & Notes
description: |
  These are my collection of books and personal notes.
author: ""
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
show_post_time: true
# for listing page layout
layout: list # list, list-sidebar

# for list-sidebar layout
sidebar: 
  title: Talks that Last
  description: |
    This is a list for your talks, workshops, or 
    other events with a time, date, and place. 
    Even this sidebar offers a ton of customizations.
    
    Check out the _index.md file in the /talk folder 
    to edit this content. 
  author: "The R Markdown Team @RStudio"
  text_link_label: Subscribe via RSS
  text_link_url: /talk/index.xml
  show_sidebar_adunit: false # show ad container

# Project Type (see: https://hugo-apero-docs.netlify.app/start/section-config/#level-3-rename-your-folder)
type: project
cascade:
  type: project

# set up common front matter for all pages inside blog/
cascade:
  author: "Kittipos Sirivongrungson"
  show_author_byline: true
  show_post_date: true
  show_post_time: true
  show_comments: false # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent books
    text_link_url: /book/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the talk _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside talk/. You may still override any of these by changing them in a page's front matter.**