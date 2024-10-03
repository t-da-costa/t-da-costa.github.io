---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
      spacing:
        margin-bottom: - 3 rem

  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: All the courses I've taken
          icon: hero/academic-cap
          url: uploads/Listes_cours.pdf
    design:
      spacing:
        margin-top: - 1 rem

  #- block: resume-skills
  #  content:
  #    title: Skills & Hobbies
  #    username: admin
  #  design:
  #    show_skill_percentage: false
  #- block: resume-awards
  #  content:
  #    title: Awards
  #    username: admin
  #- block: resume-languages
  #  content:
  #    title: Languages
  #    username: admin
---
