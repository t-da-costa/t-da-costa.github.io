---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '3rem'

# Page sections
sections:
  - block: markdown
    content:
      title: Miscellaneous Projects
      subtitle: A list of selected works done during my bachelors or masters
      text: The first collection is written in English; the second in French.  
  - block: collection
    content:
     title: 
     text: . 
     filters:
       folders:
       - project-en
    design:
     view: article-grid
     fill_image: false
     columns: 2
  - block: collection
    content:
     title:
     text:
     filters:
       folders:
       - project-fr
    design:
     view: article-grid
     fill_image: false
     columns: 2
---
