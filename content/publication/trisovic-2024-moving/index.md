---
title: Moving horizon estimation for simultaneous localization and mapping with robust estimation error bounds
authors:
- Jelena Trisovic
- admin
- Simon Muntwiler
- Melanie N. Zeilinger
date: '2024-11-21'
publishDate: '2024-11-21T10:06:05.762070Z'
publication_types:
- article
publication: '*arXiv preprint arXiv:2411.13310*'
abstract: 'This paper presents a robust moving horizon estimation (MHE) approach with provable estimation error bounds for solving the simultaneous localization and mapping (SLAM) problem.  We derive sufficient conditions to guarantee robust stability in ego-state estimates and bounded errors in landmark position estimates, even under limited landmark visibility which directly affects overall system detectability. This is achieved by decoupling the MHE updates for the ego-state and landmark positions, enabling individual landmark updates only when the required detectability conditions are met. The decoupled MHE structure also allows for parallelization of landmark updates, improving computational efficiency. We discuss the key assumptions, including ego-state detectability and Lipschitz continuity of the landmark measurement model, with respect to typical SLAM sensor configurations, and introduce a streamlined method for the range measurement model. Simulation results validate the considered method, highlighting its efficacy and robustness to noise.'
links:
- name: Preprint
  url: https://arxiv.org/abs/2411.13310
---