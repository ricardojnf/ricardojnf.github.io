---
title: "CLASP: An online learning algorithm for Convex Losses And Squared Penalties"
collection: publications
permalink: /publication/2026-clasp
excerpt: ''
date: 2026-07-04
paperurl: ''
citation: 'R. N. Ferreira, J. Xavier, and C. Soares, "CLASP: Online learning algorithms for Convex Losses And Squared Penalties," accepted at the International Conference on Machine Learning, 2026.'
paperoglink: 'https://icml.cc/virtual/2026/poster/61649'
---

Abstract 
--------

Addressing Constrained Online Convex Optimization (COCO), we introduce CLASP (Convex Losses And Squared Penalties), a framework that minimizes cumulative loss together with squared constraint violations. We propose two variants of CLASP, CLASP-I and CLASP-F, allowing for a joint or separate handling of the static decision set and the time-varying constraints, a decoupling flexibility that affords simpler implementations when projections onto the static decision set are easy. Our theoretical analysis departs from prior work by fully leveraging the variety of cutter operators, and contraction properties such as the strongly quasi-nonexpansiveness, a proof strategy not previously applied in this setting. For convex losses, both CLASP algorithms achieve regret $O\left(T^{\max\{\beta,1-\beta\}}\right)$ and cumulative squared penalty $O\left(T^{1-\beta}\right)$ for any $\beta \in (0,1)$. Most importantly, for strongly convex problems, we provide the first logarithmic guarantees on both regret and cumulative squared penalty: In the strongly convex case, both CLASP algorithms guarantee that the regret is upper bounded by $O( \log T )$ and the cumulative squared penalty is also upper bounded by $O( \log T )$. 