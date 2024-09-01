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
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      spacing:
        padding: ['0', '20px', '0', '20px']
  - block: markdown
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        #### Advanced Model Predictive Control at ETH Zurich, 2020-2024
        - Produced recitation content such as slides, problem sets and 8 programming exercises and taught weekly exercise classes
        - Scored an average of 4.5/5.0 on student feedback regarding the recitation

        #### Summer School Teaching Assistant
        - Produced recitation content such as slides and programming exercises and taught recitations at the following summer schools:
          - "Learning-Based Predictive Control" Session at the EECI IGSC PhD School 2021, 2022 and 2023
          - "Safe Learning For Control" Session at the DS3 Data Science Summer School 2021
          - "Safety filters for learning-based control" Session at the International Summer School of Automatic Control 2021, Grenoble

        #### Control Systems II at ETH Zurich, 2018
        - Taught weekly exercise classes

    design:
      colums: '1' 
      spacing:
        padding: ['0', '20px', '0', '20px']
  - block: markdown
    content:
      title: 'Academic Activities'
      subtitle: ''
      text: |-
        #### Invited Session Organisation
        - Co-organiser of the “Regret in Control of Dynamical Systems” Session at IFAC World Congress 2023
        - Co-organiser and co-chair of the “Online Learning for Optimization and Control” Session at IEEE Conference on Decision and Control 2023
        
        #### Student Project Supervision
        - Supervised 13 student projects including 5 Master theses and 3 research assistants projects
        
        #### Reviews
        - I regularly review for TAC, T-RO, Automatica, RA-L, L-CSS, CDC, L4DC, ECC, NMPC

    design:
      columns: '1'
      spacing:
        padding: ['0', '20px', '0', '20px']
  #- block: resume-awards
  #  content:
  #    title: Awards
  #    username: admin
  - block: resume-languages
    content:
      title: Languages
      username: admin
    #design:
    #  show_language_percentage: false
---
