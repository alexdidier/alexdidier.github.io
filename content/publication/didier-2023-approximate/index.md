---
title: 'Approximate predictive control barrier functions using neural networks: A
  computationally cheap and permissive safety filter'
authors:
- admin
- Robin C. Jacobs
- Jerome Sieber
- Kim P. Wabersich
- Melanie N. Zeilinger
date: '2023-07-17'
publishDate: '2024-08-27T16:57:05.750183Z'
publication_types:
- paper-conference
publication: '*2023 European Control Conference (ECC)*'
featured: true
summary: Find out how we can use neural networks for approximating predictive safety filters while analysing closed-loop guarantees.
image:
  caption: 'Illustration of the proposed approximation scheme'
  focal_point: ""
  preview_only: false
abstract: 'A predictive control barrier function (PCBF) based safety filter is a modular framework to verify safety of a control input by predicting a future trajectory. The approach relies on the solution of two optimization problems, first computing the minimal state constraint violation given the current state in the form of slacks on the constraint, and then computing the minimal deviation from a proposed input given the previously computed minimal slacks. This paper presents an approximation procedure that uses a neural network to approximate the optimal value function of the first optimization problem, which defines a control barrier function (CBF). By including this explicit approximation in a CBF-based safety filter formulation, the online computation becomes independent of the prediction horizon. It is shown that this approximation guarantees convergence to a neighborhood of the feasible set of the PCBF safety filter problem with zero constraint violation. The convergence result relies on a novel class K lower bound on the PCBF decrease and depends on the approximation error of the neural network. Lastly, we demonstrate our approach in simulation for an autonomous driving example and show that the proposed approximation leads to a significant decrease in computation time compared to the original approach.'
url_pdf: https://ieeexplore.ieee.org/abstract/document/10178263
url_code: https://gitlab.ethz.ch/ics/approximate-predictive-control-barrier-functions
links:
- name: Preprint
  url: https://arxiv.org/abs/2211.15104
---
