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
      is_education_first: true
  - block: resume-skills
    content:
      title: Skills
      username: admin
      skills:
        - name: Technical Skills
          items:
            - name: Python
              description: ''
              percent: 80
              icon: code-bracket
            - name: Data Science
              description: ''
              percent: 100
              icon: chart-bar
    design:
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
      awards:
        - title: Rawlings Cornell III Presidential Research Scholarship 
          url: https://example.com
          date: '2016-08-01'
          awarder: Cornell University
          icon: none
          summary: |
            Funded undergraduate research award
---
