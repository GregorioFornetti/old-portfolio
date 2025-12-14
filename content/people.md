---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
- block: markdown
  id: hero
  content:
    title: Hi, I'm George
    subtitle: I build open source software.
    text: |
      ![Alt text](../authors/admin/avatar.jpeg) ![Alt text](../authors/admin/avatar.jpeg)
      aaa
  design:
    spacing:
      # Top, Right, Bottom, Left
      padding: ['20px', '0', '20px', '0']
    css_class: 'my-custom-class'
- block: collection
  content:
    title: Current projects
    text: 
    filters:
      folders:
        - authors
  design:
    view: article-grid
    fill_image: false
    columns: 3
    show_date: false
    show_read_time: false
    show_read_more: false
---
