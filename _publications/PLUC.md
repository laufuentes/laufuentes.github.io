---
title: 'Policy learning under constraint: Maximizing a primary outcome while controlling an adverse event'
collection: publications
category: manuscripts
permalink: /publication/PLUC
authors: Laura Fuentes-Vicente, Mathieu Even, Gaelle Dormion, Julie Josse, Antoine Chambaz. 
date: 2026-01-29
venue: 'preprint'

---

## Abstract 

A medical policy aims to support decision-making by mapping patient characteristics to individualized treatment recommendations. Standard approaches typically optimize a single outcome criterion. For example, recommending treatment according to the sign of the Conditional Average Treatment Effect (CATE) maximizes the policy "value" by exploiting treatment effect heterogeneity. This point of view shifts policy learning towards the challenge of learning a reliable CATE estimator. However, in multi-outcome settings, such strategies ignore the risk of adverse events, despite their relevance. PLUC (Policy Learning Under Constraint) addresses this challenges by learning an estimator of the CATE that yields smoothed policies controlling the probability of an adverse event in observational settings. Inspired by insights from EP-learning, PLUC involves the optimization of strongly convex Lagrangian criteria over a convex hull of functions. Its alternating procedure iteratively applies the Frank-Wolfe algorithm to minimize the current criterion, then performs a targeting step that updates the criterion so that its evaluations at previously visited landmarks become targeted estimators of the corresponding theoretical quantities. An R package PLUC-R provides a practical implementation. We illustrate PLUC's performance through a series of numerical experiments.

[Download pdf](https://arxiv.org/abs/2601.22717)


citation: 'Fuentes-Vicente, L., Even, M., Dormion, G., Josse, J., & Chambaz, A. (2026). Policy learning under constraint: Maximizing a primary outcome while controlling an adverse event. arXiv preprint arXiv:2601.22717.'
