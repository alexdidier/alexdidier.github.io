---
title: Moving horizon estimation for simultaneous localization and mapping with robust
  estimation error bounds
authors:
- Jelena Trisovic
- admin
- Simon Muntwiler
- Melanie N Zeilinger
date: '2024-11-21'
publishDate: '2025-01-21T09:29:10.099013Z'
publication_types:
- paper-conference
publication: '*2025 European Control Conference (ECC)*'
abstract: 'This paper presents a robust moving horizon estimation (MHE) approach with provable estimation error bounds for solving the simultaneous localization and mapping (SLAM) problem.  We derive sufficient conditions to guarantee robust stability in ego-state estimates and bounded errors in landmark position estimates, even under limited landmark visibility which directly affects overall system detectability. This is achieved by decoupling the MHE updates for the ego-state and landmark positions, enabling individual landmark updates only when the required detectability conditions are met. The decoupled MHE structure also allows for parallelization of landmark updates, improving computational efficiency. We discuss the key assumptions, including ego-state detectability and Lipschitz continuity of the landmark measurement model, with respect to typical SLAM sensor configurations, and introduce a streamlined method for the range measurement model. Simulation results validate the considered method, highlighting its efficacy and robustness to noise.'
url_pdf: https://ieeexplore.ieee.org/abstract/document/11187277 
links:
- name: Preprint
  url: https://arxiv.org/abs/2411.13310
---
