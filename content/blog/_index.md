---
title: Blog
description: |
  Read, Comment, critique and share.
author: "Tiny Data Tales"
show_post_thumbnail: true
thumbnail_left: true # for list-sidebar only
show_author_byline: true
show_post_date: true
show_button_links: false
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Thoughts on Data Analysis
  description: |
  
    In this section, we will share the most talked about data stories for the week.
  author: "Tiny Data Tales"
  text_link_label: Data of the Day
  text_link_url: /about/
  categories_link: true
  series_link: true
  tags_link: true
  show_sidebar_adunit: true # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: ""
  show_author_byline: true
  show_post_date: true
  show_comments: true # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container
# set up common front matter for all individual pages in series
cascade:
  type: collection
  layout: single-series       # for a series, do not change
  show_author_byline: true
  show_post_date: true
  sidebar:
    show_sidebar_adunit: false # show ad container
    text_series_label: "In this series" 
    text_contents_label: "On this page" 
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**
