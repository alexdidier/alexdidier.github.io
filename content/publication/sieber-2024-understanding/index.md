---
title: 'Understanding the differences in Foundation Models: Attention, State Space
  Models, and Recurrent Neural Networks'
authors:
- Jerome Sieber
- Carmen Amo Alonso
- admin
- Melanie N. Zeilinger
- Antonio Orvieto
date: '2024-05-24'
publishDate: '2024-08-27T16:57:05.756163Z'
publication_types:
- article
publication: '*arXiv preprint arXiv:2405.15731*'
featured: true
summary: Discover how a dynamical system theoretic approach can be used to provide insights into foundation models.
abstract: 'Softmax attention is the principle backbone of foundation models for various artificial intelligence applications, yet its quadratic complexity in sequence length can limit its inference throughput in long-context settings. To address this challenge, alternative architectures such as linear attention, State Space Models (SSMs), and Recurrent Neural Networks (RNNs) have been considered as more efficient alternatives. While connections between these approaches exist, such models are commonly developed in isolation and there is a lack of theoretical understanding of the shared principles underpinning these architectures and their subtle differences, greatly influencing performance and scalability. In this paper, we introduce the Dynamical Systems Framework (DSF), which allows a principled investigation of all these architectures in a common representation. Our framework facilitates rigorous comparisons, providing new insights on the distinctive characteristics of each model class. For instance, we compare linear attention and selective SSMs, detailing their differences and conditions under which both are equivalent. We also provide principled comparisons between softmax attention and other model classes, discussing the theoretical conditions under which softmax attention can be approximated. Additionally, we substantiate these new insights with empirical validations and mathematical arguments. This shows the DSFs potential to guide the systematic development of future more efficient and scalable foundation models.'
image:
  caption: 'Performance comparison of softmax attention and linear attention with increasing state expansion n.'
  focal_point: ""
  preview_only: false
---
