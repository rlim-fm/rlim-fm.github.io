---
title: "Length-OOD Generalization and Transfer Learning Limits on Dynamic Programming Problems"
date: 2026-09-01
venue: "Preprint"
advisors:
  - name: "Ruriko Yoshida, Ph.D."
    url: "https://polytopes.net/"
collaborators: []
# TODO: add a representative image
# image: /images/pubs/length-ood.png
# image_alt: "Tropical hypersurface of a shortest-path polynomial"
# TODO: add links as they become available
# links:
#   paper:
#   arxiv:
#   code:
#   poster:
#   slides:
#   bibtex:
---

Visiting researcher at the [Naval Postgraduate School](https://nps.edu/). Dynamic programming
problems—shortest paths, scheduling, sequential resource allocation—are central to operations
research. However, they are notoriously hard for machine learning models: they must train on small
examples and generalize to large ones. Why do we have countless algorithms to solve these problems,
but none that teach machines to? We formalize this difficulty with a no free lunch theorem and
examine how the algebraic structure of these problems demands specialized architectures to make it
possible. In particular, we use the well-known connection to the max-plus (tropical) algebra and
geometry to specify what symmetries a model must enforce to learn an algorithm instead of memorizing
answers.
