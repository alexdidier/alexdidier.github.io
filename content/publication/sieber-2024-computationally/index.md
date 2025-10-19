---
title: Computationally Efficient System Level Tube-MPC for Uncertain Systems
authors:
- Jerome Sieber
- admin
- Melanie N. Zeilinger
date: '2025-01-18'
publishDate: '2025-01-27T16:57:05.762070Z'
publication_types:
- article-journal
publication: '*Automatica*'
abstract: 'Tube-based model predictive control (MPC) is the principal robust control technique for constrained linear systems affected by additive disturbances. While tube-based methods that compute the tubes online have been successfully applied to systems with additive disturbances, their application to systems affected by additional model uncertainties is challenging. This paper introduces a new tube-based MPC method - named filter-based system level tube-MPC (SLTMPC) - which overapproximates both uncertainties with an online optimized disturbance set, while simultaneously computing the tube controller online. Extending prior work, we generalize the method to polytopic disturbance sets and for the first time provide rigorous closed-loop guarantees for the receding horizon controller. These guarantees are obtained by virtue of a new terminal controller design and an online optimized terminal set. To reduce the computational complexity of the proposed method, we additionally introduce an asynchronous computation scheme that separates the optimization of the tube controller and the nominal trajectory. Finally, we provide a comprehensive numerical evaluation of the proposed methods to demonstrate their effectiveness.'
url_pdf: https://www.sciencedirect.com/science/article/pii/S0005109825003607
url_code: https://github.com/IntelligentControlSystems/filter-sltmpc
links:
- name: Preprint
  url: https://arxiv.org/abs/2406.12573
---
