---
title: "Clustered Mini-batching and Sampling Schemes for Stochastic Optimization"
date: 2026-03-01
venue: "In preparation"
advisors:
  - name: "Jeová Farias, Ph.D."
    url: "https://jeovafarias.github.io/"
  - name: "András Benczúr, Ph.D."
    url: "https://sztaki.hun-ren.hu/en/organisation/departments/ilab/andras-benczur"
  - name: "Bálint Zoltán Daróczy, Ph.D."
    url: "https://sztaki.hun-ren.hu/en/organisation/departments/ilab/balint-zoltan-daroczy"
collaborators: []
# TODO: add a representative image
# image: /images/pubs/clustered-minibatching.png
# image_alt: ""
# TODO: add links as they become available
# links:
#   paper:
#   arxiv:
#   code:
#   poster:
#   slides:
#   bibtex:
---
In collaboration with the
[HUN-REN Institute for Computer Science and Control (SZTAKI)](https://sztaki.hun-ren.hu/en) in
Budapest, Hungary.
A growing body of work focuses on aligning losses to the local analytic geometry of target functions (Rame et al., 2023, Zha et al. 2023, Zhu et al., 2025). 
However, uniform sampling and mini-batching assumes that the global geometry does not conflict with local geometry. 
We design k-Neighborhood Aware Sampling (k-NAS), a mini-batching scheme that builds localized mini-batches controlled by a softmax temperature hyperparameter.
