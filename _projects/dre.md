---
layout: page
title: Deep Recursive Embedding
description: Recursive representation learning for high-dimensional data embedding (IEEE TVCG 2022)
img: assets/img/dre.png
importance: 2
category: dimensionality reduction
related_publications: true
---

**Deep Recursive Embedding (DRE)** embeds high-dimensional data into low-dimensional space (typically 2D for visualization). **IEEE TVCG 2022.** [[Paper]](https://ieeexplore.ieee.org/document/9585419) · [[Code]](https://github.com/zuxinrui/DeepRecursiveEmbedding)

DRE leverages latent data representations for boosted embedding performance, maps out-of-sample data, and scales to extremely large datasets — improving both local and global structure preservation over the state of the art.

{% include figure.liquid path="assets/img/dre.png" class="img-fluid rounded z-depth-1" alt="Deep Recursive Embedding architecture." %}

<div class="row justify-content-sm-center">
  <div class="col-sm-7 mt-3 mt-md-0">{% include figure.liquid path="assets/img/MNIST-conv-2.gif" class="img-fluid rounded z-depth-1" alt="DRE optimization process embedding the MNIST dataset." %}</div>
</div>

<div class="caption">The DRE optimization process on the MNIST dataset.</div>
