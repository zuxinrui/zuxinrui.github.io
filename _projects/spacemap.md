---
layout: page
title: SpaceMAP
description: Visualizing high-dimensional data by space expansion (ICML 2022)
img: assets/img/spacemap-thumb.png
importance: 1
category: dimensionality reduction
related_publications: true
---

*SpaceMAP: Visualizing High-Dimensional Data by Space Expansion* — Xinrui Zu, Qian Tao. **ICML 2022.** [[Paper]](https://proceedings.mlr.press/v162/zu22a.html) · [[Code]](https://github.com/zuxinrui/SpaceMAP) · [[Video]](https://slideslive.com/38983456/spacemap-visualizing-highdimensional-data-by-space-expansion)

We propose **SpaceMAP**, a dimensionality-reduction method that visualizes data of any dimensionality on a 2-D map. Unlike previous methods, we analytically derive a transformation of distance between high- and low-dimensional spaces to match their capacity, and show that it provably reduces the intrinsic dimension of high-dimensional data within the maximum-likelihood intrinsic-dimensionality framework.

{% include figure.liquid path="assets/img/spacemap-results.png" class="img-fluid rounded z-depth-1" alt="SpaceMAP visualization results compared with other dimensionality-reduction methods." %}

<div class="caption">Result comparison with other dimensionality-reduction methods.</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/spacemap-crop.gif" class="img-fluid rounded z-depth-1" alt="SpaceMAP optimization unrolling the Swiss Roll dataset." %}
  </div>
</div>

<div class="caption">The SpaceMAP optimization process as the “unrolling” of the Swiss Roll dataset.</div>
