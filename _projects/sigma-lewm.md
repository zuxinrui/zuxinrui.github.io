---
layout: page
title: Σ-LeWM
description: Learning world models via S-information for robot control (2026 preprint)
img: assets/img/publication_preview/sigma-lewm.svg
importance: 0
category: robot learning
permalink: /projects/sigma-lewm/
---

**Σ-LeWM: Learning World Models via S-Information for Robot Control** — Xinrui Zu, Michael Przystupa, Zhao Yang, Shujian Yu, and Kevin Sebastian Luck. **Preprint, 2026.**

[Project website](https://zuxinrui.github.io/sigma-lewm/) · [Code](https://github.com/zuxinrui/sigma-lewm) · [Hugging Face](https://huggingface.co/zuxinrui/sigma-lewm)

Σ-LeWM learns a latent world model through **three views of a transition**: predicting the next state, explaining the current state from the next state and action, and recovering the action between consecutive states. Together, forward, backward, and inverse dynamics encourage representations that preserve the structure needed for robot control.

<div style="max-width: 600px; margin: 24px auto;">
{% include figure.liquid loading="eager" path="assets/img/publication_preview/sigma-lewm.svg" class="img-fluid rounded" alt="Σ-LeWM method: forward, backward, and inverse dynamics share a latent representation for robot control." %}
</div>

The two auxiliary predictors are used during training. At test time, the model retains LeWM's forward dynamics and CEM planner. We evaluate control performance and planning efficiency on Push-T, TwoRoom, Reacher, OGBench-Cube, and OGBench-Scene, alongside Gear-Assembly and Cube-Stacking in IsaacSim.

The arXiv-version main table reports **94.5%** success on Push-T and **80.7%** on OGBench-Scene, compared with **90.0%** and **57.7%** for LeWM. These are means over 3 training seeds × 5 evaluation seeds × 50 episodes; the full table includes standard deviations and all baselines.

[Explore the results, robot demonstrations, and ablations →](https://zuxinrui.github.io/sigma-lewm/)
