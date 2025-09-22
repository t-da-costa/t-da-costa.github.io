---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '3rem'

# Page sections
sections:
  # - block: markdown
  #   content:
  #     title: Some Projects
  #     subtitle: My subtitle
  #     text: One day this page will be updated with some past projects or work in progress I currently have.
  - block: collection
    content:
     title: Miscellaneous Projects (EN)
     text: A list of selected works done during my bachelors or masters. 
     filters:
       folders:
       - project
    design:
     view: article-grid
     fill_image: false
     columns: 3
  - block: collection
    content:
     title: 
     text: In french
     filters:
       folders:
       - project
    design:
     view: article-grid
     fill_image: false
     columns: 3
---
