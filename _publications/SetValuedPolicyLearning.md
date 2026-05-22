---
title: 'Set-Valued Policy Learning'
collection: publications
category: manuscripts
permalink: /publication/SetValuedPolicyLearning
authors: Laura Fuentes-Vicente, Mathieu Even, Gaelle Dormion, Antoine Chambaz, Uri Shalit, Julie Josse. 
date: 2026-05-20
venue: 'preprint'

---

## Abstract 

Conventional treatment policies map patient covariates to a single recommended intervention in order to maximize expected clinical outcomes. Although a rich body of causal inference methods has been developed to estimate such policies, point-valued recommendations can be highly sensitive to estimation uncertainty, model specification, and finite-sample variability, while typically providing little guidance about how confident one should be in the recommended action. In this work, we propose a set-valued policy learning paradigm for the multiple-treatment setting, in which policies output a set of plausible treatments rather than a single recommendation. This formulation enables intrinsic uncertainty
quantification, with the size of the predicted set reflecting the degree of decision ambiguity. We extend the learning-to-defer framework to multiple treatments via
a novel greatest Lower Bound method, and introduce conformal policy learning, which bridges the gap between unobserved ground-truth optimal treatments and
estimated optimal treatment rules. Drawing on insights from the noisy-label literature, we develop a randomness-injection approach that guarantees marginal coverage without requiring assumptions on underlying black-box optimal treatment
rules. Through experiments on synthetic data and a real-world application to In-Vitro Fertilization (IVF), we demonstrate that our methods produce robust and actionable policies that naturally incorporate clinical considerations while effectively balancing performance and reliability.

[Download pdf](https://arxiv.org/pdf/2605.19830)


citation: 'Fuentes-Vicente, L., Even, M., Dormion, G., Chambaz, A., Uri Shalit & Josse, J. (2026). Set-Valued Policy Learning. arXiv preprint arXiv:2605.19830.'

