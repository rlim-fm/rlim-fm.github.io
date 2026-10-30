---
title: "Length-OOD Generalization and Transfer Learning Limits on Dynamic Programming Problems"
date: 2026-09-01
venue: "NeurReps Workshop @ NeurIPS 2026"
advisors:
  - name: "Ruriko Yoshida, Ph.D."
    url: "https://polytopes.net/"
collaborators: []
# TODO: add a representative image
# image: /images/pubs/length-ood.png
# image_alt: "Tropical hypersurface of a shortest-path polynomial"
# TODO: add links as they become available
links:
#   paper:
   arxiv: https://arxiv.org/abs/2608.25034
#   code:
#   poster:
#   slides:
#   bibtex:
---

Work done at the [Naval Postgraduate School](https://nps.edu/). Length generalization is a notoriously hard problem for neural networks. 
However, [Tropical Attention](https://neurips.cc/virtual/2025/loc/san-diego/poster/120059), based in the tropical (max/min-plus) semiring, is a conspicuous exception, achieving strong length generalization on dynamic programming (DP) tasks.
We ask what is required for length generalization on DPs. 
We demonstrate that embedding DPs as a tropical polynomial is lossy and does not respect the DP's graph topology. Finally, we prove two negative results. The semiring’s two native ways to reduce dimension
(setting a variable to each identity) are neither injective nor always closed within the DP.
Series and parallel composition fail to construct all DAG topologies from
smaller sub-DAGs, and even all terminal-only operations do not capture all DP
compositions.
