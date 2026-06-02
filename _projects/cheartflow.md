---
layout: page
title: cHeartFlow
description: Synthesizing cardiac MR images from sketches (MIDL 2024)
img: assets/img/Fig1_v4.png
importance: 2
category: generative models
related_publications: true
---

*cHeartFlow: Synthesizing Cardiac MR Images from Sketches* — Xinrui Zu, Qian Tao. **MIDL 2024.** [[Paper]](https://openreview.net/forum?id=orIWvvBK2v)

We present **contrastive HeartFlow (cHeartFlow)**, a generative framework that synthesizes cardiac magnetic resonance (CMR) images from simple sketches by training on contrastive pairs of images and sketches.

{% include figure.liquid path="assets/img/Fig1_v4.png" class="img-fluid rounded z-depth-1" alt="cHeartFlow generation compared with GAN-based and diffusion-based models." %}

<div class="caption">cHeartFlow generation compared with popular GAN-based and diffusion-based models.</div>

Zero-shot MRI registration with cHeartFlow trades off registration accuracy (faithfulness) against image quality (realism). Below: (1) original MRI cycle, then registration at control parameter t = 0.25 / 0.5 / 0.75.

<div class="row">
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/original.gif" class="img-fluid rounded z-depth-1" alt="Original MRI cycle." %}</div>
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/seg-t0.25.gif" class="img-fluid rounded z-depth-1" alt="Registration at t=0.25." %}</div>
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/seg-t0.5.gif" class="img-fluid rounded z-depth-1" alt="Registration at t=0.5." %}</div>
  <div class="col-sm-3 mt-3 mt-md-0">{% include figure.liquid path="assets/img/seg-t0.75.gif" class="img-fluid rounded z-depth-1" alt="Registration at t=0.75." %}</div>
</div>
