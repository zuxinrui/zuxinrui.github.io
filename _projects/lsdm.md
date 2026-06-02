---
layout: page
title: LSDM (MSc Thesis)
description: Fast and precise lung CT image generation via diffusion models
img: assets/img/lsdm.png
importance: 3
category: generative models
---

My MSc thesis introduces the **Latent Semantic Diffusion Model (LSDM)** for fast and precise lung CT image generation from sketches. [[Thesis]](https://essay.utwente.nl/95061/)

{% include figure.liquid path="assets/img/lsdm.png" class="img-fluid rounded z-depth-1" alt="Overview of the Latent Semantic Diffusion Model (LSDM)." %}

<div class="caption">Overview of the proposed LSDM.</div>

{% include figure.liquid path="assets/img/r2-best.png" class="img-fluid rounded z-depth-1" alt="Lung CT generation compared with SPADE; note the detail at the lobe boundaries." %}

<div class="caption">Generation comparison against the popular SPADE model — note the detail at the lobe boundaries.</div>

A proposed **inpainting classifier guidance** makes the synthesis controllable: the guidance scale tunes the malignancy of the generated CT scans.

{% include figure.liquid path="assets/img/r4-classifier-scales.png" class="img-fluid rounded z-depth-1" alt="Controllable CT synthesis across inpainting classifier guidance scales." %}
