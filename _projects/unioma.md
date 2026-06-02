---
layout: page
title: UniOMA
description: Gromov–Wasserstein structural alignment for multimodal robot perception (ICRA 2026)
img: assets/img/unioma/vip.jpg
importance: 1
category: robot learning
permalink: /projects/unioma/
related_publications: true
---

*UniOMA: Unified Optimal-Transport Multi-Modal Structural Alignment for Robot Perception* — Xinrui Zu, Kevin Sebastian Luck, Shujian Yu. Accepted to **ICRA 2026 Late-Breaking Results** and the ICRA 2026 *“From Data to Decisions”* workshop (Poster Session 2). [[Paper]](https://openreview.net/forum?id=rcc5qZ6CtV)

Contrastive losses learn **which** sensor readings correspond across modalities, yet stay blind to the internal geometry each modality carries. **UniOMA** closes this *structural alignment gap* with a geometry-aware **Gromov–Wasserstein (GW)** regularizer that augments any contrastive multimodal objective with structural alignment.

{% include figure.liquid loading="eager" path="assets/img/unioma/vip.jpg" class="img-fluid rounded z-depth-1" alt="UniOMA real-robot setup: vision, IMU and proprioception drive frozen encoders to predict the end-effector position on a 6-DoF arm." %}

<div class="caption">
  UniOMA in the wild: vision, IMU, and proprioception drive frozen encoders to predict the end-effector position on a real 6-DoF arm — one of five robotic benchmarks.
</div>

Standard InfoNCE-style losses align instance-level correspondence — which sample matches which — but remain invariant to transforms that distort each modality's internal relational geometry. UniOMA encodes each sensor's intra-modality similarity structure and uses a Gromov–Wasserstein distance to draw every modality toward a dynamically learned consensus geometry, or *barycenter*. The regularizer is plug-and-play across InfoNCE, Symile, GRAM, and related objectives, scales linearly to three or more modalities, and targets robot perception with underexplored modalities — force, tactile, IMU, proprioception — where sample density varies widely across sensors. Across five robotic benchmarks, including a new real-robot Vision–IMU–Proprioception dataset, UniOMA consistently improves state regression, classification, and cross-modal retrieval.

{% include figure.liquid loading="eager" path="assets/img/unioma/overview.png" class="img-fluid rounded z-depth-1" alt="UniOMA method overview: Stage 1 estimates a structural-consensus barycenter; Stage 2 aligns each encoder's embedding geometry to it via Gromov-Wasserstein; the end-to-end RL panel shows robustness to modality dropout." %}

<div class="caption">
  UniOMA at a glance: (Stage 1) estimate a structural-consensus barycenter from per-modality similarity kernels; (Stage 2) align each encoder's embedding geometry to it via Gromov–Wasserstein, on top of the contrastive loss; and (right) the payoff in end-to-end reinforcement learning, where alignment keeps a Unitree Go1 policy robust when a sensor modality is dropped.
</div>

As a byproduct, the learned barycenter weights yield a label-free per-modality **structural-importance ranking**, surfacing which sensor most shapes a given task — proprioception in one setting, depth in another — without task labels or repeated retraining.
