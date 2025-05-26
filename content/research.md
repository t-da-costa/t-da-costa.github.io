---
title: "Research"
date: 2023-10-24
type: landing

design:
  spacing: "3rem"

sections:

  # Collection of publications
  - block: collection
    id: publications               # optional but handy for linking
    content:
      title: "Publications"       # section header
      filters:
        folders:
          - publication           # fetch pages under content/publication/
    design:
      view: citation               # compact / citation / list
      columns: "1"                # one column layout

  # (Optional) keep your Working papers markdown block
  - block: markdown
    id: working-papers
    content:
      title: "Working papers"
      text: "Idem."
---