---
layout: page
title: DiFine UI
description: A web platform for controllable medical image synthesis
img: assets/video/draw.png
importance: 3
category: generative models
---

**DiFine UI** is a web-based medical image synthesis platform built on the [LSDM](/projects/lsdm/) model. Users can draw medical images from sketches and control the synthesis by adjusting diagnosis parameters through a proposed inpainting classifier guidance. It is built with [Uvicorn](https://www.uvicorn.org/) and [FastAPI](https://fastapi.tiangolo.com/).

DiFine UI has three modes — *drawing*, *controlling*, and *diagnosis training* (an educational mode to practice diagnosis on synthesized images).

<div class="row">
  <div class="col-sm-6 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" controls muted playsinline poster="{{ 'assets/video/draw.png' | relative_url }}">
      <source src="{{ 'assets/video/draw.MP4' | relative_url }}" type="video/mp4">
    </video>
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" controls muted playsinline poster="{{ 'assets/video/control.png' | relative_url }}">
      <source src="{{ 'assets/video/control.MP4' | relative_url }}" type="video/mp4">
    </video>
  </div>
</div>

<div class="caption">Left: drawing mode. Right: controlling the synthesis via diagnosis parameters.</div>
