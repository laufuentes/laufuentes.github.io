---
title: "Talk EuroCIM 2026"
collection: talks
type: "Talk"
permalink: /presentations/talks/Talk_EuroCIM26
venue: "Oxford University"
date: 2026-04-15
location: "Oxford, UK"
---

I had the pleasure to present my publication, "Policy learning under constraint: Maximizing a primary outcome while controlling an adverse event" at EuroCIM 2026.  

Abstract: A medical policy aims to support decision-making by mapping patient characteristics to individualized treatment recommendations. Standard approaches optimize a single outcome criterion. For example, recommending treatment based on the sign of the CATE maximizes the policy “value” by exploiting treatment effect heterogeneity. This shifts policy learning towards the challenge of learning a reliable CATE estimator. However, in multi-outcome settings, such strategies ignore the risk of adverse events, despite their relevance. PLUC (Policy Learning Under Constraints) addresses this challenge by learning an estimator of the CATE that yields smoothed policies controlling the probability of an adverse event. Inspired by insights from EP-learning, PLUC involves the optimization of strongly convex Lagrangian criteria over a convex hull of functions. Its alternating procedure iteratively applies the Frank-Wolfe algorithm to minimize the current criterion, then performs a targeting step that updates the criterion so that its evaluations at previously visited landmarks become targeted estimators of the corresponding theoretical quantities. We illustrate PLUC’s performance through numerical experiments and an in-vitro fertilization case study.

[Download slides](http://laufuentes.github.io/files/PLUC_LFV.pdf)