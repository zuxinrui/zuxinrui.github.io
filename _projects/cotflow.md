---
layout: page
title: COT Flow
description: Contrastive Optimal Transport Flow for fast, editable generation (under review)
img: assets/img/COT/cotflow-i2i-h2s.gif
importance: 1
category: generative models
---

**Contrastive Optimal Transport Flow (COT Flow)** is a generative framework that achieves fast, high-quality generation with improved zero-shot editing flexibility compared to previous diffusion models. *(Under review.)*

Unpaired image-to-image translation:

<div class="row">
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/COT/cotflow-i2i-h2s.gif" class="img-fluid rounded z-depth-1" alt="COT Flow image-to-image translation (horse to zebra)." %}</div>
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/COT/cotflow-i2i-m2f.gif" class="img-fluid rounded z-depth-1" alt="COT Flow image-to-image translation." %}</div>
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/COT/cotflow-i2i-o2c.gif" class="img-fluid rounded z-depth-1" alt="COT Flow image-to-image translation." %}</div>
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/COT/cotflow-i2i-e2m.gif" class="img-fluid rounded z-depth-1" alt="COT Flow image-to-image translation." %}</div>
</div>

Zero-shot image editing — image composition, stroke–texture coupling, and augmentation:

<div class="row justify-content-sm-center">
  <div class="col-sm-5 mt-3 mt-md-0">{% include figure.liquid path="assets/img/COT/cotflow-composition-1.gif" class="img-fluid rounded z-depth-1" alt="COT Flow zero-shot image composition." %}</div>
  <div class="col-sm-5 mt-3 mt-md-0">{% include figure.liquid path="assets/img/COT/cotflow-coupling-1.gif" class="img-fluid rounded z-depth-1" alt="COT Flow stroke-texture coupling." %}</div>
</div>
