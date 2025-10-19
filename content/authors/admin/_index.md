---
# Display name
title: Alexandre Didier

# Full name (for SEO)
first_name: Alexandre
last_name: Didier

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Postdoctoral Researcher

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: ETH Zurich
    url: https://ethz.ch/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:adidier@ethz.ch'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/alexdidier
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/alex-didier
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=m_wFCFcAAAAJ
  - icon: academicons/orcid
    url: https://orcid.org/0000-0001-5396-8996

interests:
  - Artificial Intelligence
  - Control Systems
  - Model Predictive Control
  - Robotics
  - Machine Learning
  - Optimization

education:
  - area: PhD Control Systems
    institution: ETH Zurich
    date_start: 2020-11-01
    date_end: 2025-06-10
    summary: |
      - Development of optimization-based controllers (e.g., model predictive control) and safety filters for reinforcement learning
      - Integration of machine learning methods to allow for computationally efficient implementations
      - Focus on safety-critical systems
    #button:
    #  text: 'Read Thesis'
    #  url: 'https://example.com'
  - area: MSc Robotics, Systems and Control
    institution: ETH Zurich
    date_start: 2018-09-01 
    date_end: 2020-10-31
    summary: |
      Average Score: 5.80/6.00 with distinction

      Courses included:
      - Model Predictive Control
      - Probabilistic Artificial Intelligence
      - Autonomous Mobile Robots
  - area: BSc Mechanical Engineering
    institution: ETH Zurich
    date_start: 2015-09-01
    date_end: 2018-08-01
    summary: |
      Average Score: 5.18/6.00

      Courses included:
      - Computational Methods for Engineers I + II
      - Control Systems I + II
  - area: High School
    institution: Athénée de Luxembourg
    date_start: 2008-09-01
    date_end: 2015-07-01
    summary: |
      Average Score: 53/60 with distinction "Excellent"

      Graduation: Latin-Mathematics-Informatics

work:
  - position: Research Assistant
    company_name: ETH Zurich
    company_url: 'ethz.ch'
    date_start: 2019-10-01
    date_end: 2020-04-30
    summary: |2-
      Responsibilities include:
      - Design of a sum-of-squares optimization-based safety filter
      - Validation on simulation models
      - Application on a hardware cart-pole setup
  - position: Internship
    company_name: ABB Corporate Research
    company_url: 'abb.ch'
    date_start: 2018-10-01
    date_end: 2019-01-31
    summary: |2-
      Responsibilities include:
      - Integration of an Intel RealSense camera with an NVIDIA Jetson and the ABB YuMi robot
      - Development of real-time demonstrations including scanning a 2D workfield and maneuvering around obstacles as well as following human arm positions

# Skills
# Add your own SVG icons to `assets/media/icons/` 
#        description: ''
#        icon: code-bracket
skills:
  - name: Programming Languages
    items:
      - name: Python
      - name: MATLAB
      - name: C++
      - name: Unix Shell Script
  
  - name: Numerical Optimization
    items:
      - name: CasADi
      - name: CVXPy
      - name: YALMIP
      - name: acados
      - name: MPT3
  
  - name: Machine Learning
    items:
      - name: Pytorch
      - name: SciKit Learn
  
  - name: Simulation Frameworks
    items:
      - name: Simulink
      - name: ROS
    
  - name: Numerical Computing
    items:
      - name: NumPy
      - name: SciPy
      - name: Eigen
      - name: Pandas
    
  - name: Parallel Programming
    items:
      - name: CUDA
  
  - name: DevOps Tools
    items:
      - name: Git
      - name: Docker

  - name: Data Visualization
    items:
      - name: Matplotlib
      - name: Seaborn

  - name: Document Preparation
    items:
      - name: LaTeX
      - name: Microsoft Office

  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Owner of two dogs
      - name: Skiing
      - name: Bouldering
      - name: Chess

languages:
  - name: Luxembourgish
    percent: 100
  - name: English
    percent: 100
  - name: German
    percent: 100
  - name: French
    percent: 80

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
#awards:
#  - title: test
#    url: test
#    date: '2023-11-25'
#    awarder: test
#    summary: |
#      test
---

## About Me

Hi, I\'m Alexandre Didier, a postdoctoral researcher in the group of Prof. Dr. Melanie Zeilinger at IDSC, D-MAVT, ETH Zurich. My main research interests lie in the development of safe control algorithms, such as predictive safety filters, with application to autonomous vehicles and robots. These filters use model predictive control techniques to enhance any learning-based controller \(e.g. reinforcement learning policies) or human operators with safety guarantees. I\'m also interested in establishing relationships between online optimization and classical control theory and recently I have looked into how system theory can be used in the context of foundation models.
