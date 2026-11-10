---
layout: about
title: about
permalink: /
subtitle: PhD Student, <a href='https://vu.nl/en'>Vrije Universiteit Amsterdam</a> · Robot Learning · Multimodal Representation · Optimal Transport

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Amsterdam, the Netherlands</p>
    <p>Computational Intelligence Group</p>
    <p>Quantitative Data Analytics Group</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

<div class="intro" markdown="1">

**Xinrui Zu** (祖新瑞) is a PhD student at **Vrije Universiteit Amsterdam**, jointly in the [Computational Intelligence Group](https://cs.vu.nl/ci/) and the [Quantitative Data Analytics Group](https://vu-qda.github.io/), advised by Dr. [Kevin Sebastian Luck](https://kevin-luck.com/) and Dr. [Shujian Yu](https://sjyucnel.github.io/). He studies the **geometry of learned representations** — how perception is structured inside neural networks — and uses **optimal transport** to align that structure across sensory modalities (vision, force, tactile, IMU, proprioception) and across domains (medical imaging and robotics).

The same idea threads through his work: a Gromov–Wasserstein regularizer for robot perception (**UniOMA**, ICRA 2026), optimal-transport flows for medical image synthesis, and embedding methods that preserve structure under dimensionality reduction (**SpaceMAP**, ICML 2022; **Deep Recursive Embedding**, IEEE TVCG 2022). Before his PhD he was a research assistant at [TU Delft, Imaging Physics](https://www.tudelft.nl/tnw/over-faculteit/afdelingen/imphys) with Dr. [Qian Tao](https://www.tudelft.nl/tnw/over-faculteit/afdelingen/imphys/about-the-department/tao-qian), earned an MSc in Robotics & Mechatronics at the [University of Twente](https://www.ram.eemcs.utwente.nl), and a BSc in Theoretical & Applied Mechanics at [Fudan University](https://en.wikipedia.org/wiki/Fudan_University). And because alignment shouldn’t stay theoretical, he also **builds the robots** — modular manipulators, autonomous vehicles, and the sensors they learn from.

Feel free to reach out for collaborations or a chat about optimal transport, multimodal robot learning, or generative models.

</div>

<br>

#### Featured — Σ-LeWM (2026)

<div style="max-width: 600px; margin: 20px auto;">
{% include figure.liquid loading="eager" path="assets/img/publication_preview/sigma-lewm.svg" class="img-fluid rounded" alt="Σ-LeWM: forward, backward, and inverse dynamics jointly structure the latent world model for robot control." %}
</div>

<div class="caption">
  <strong>Σ-LeWM: Learning World Models via S-Information for Robot Control</strong> combines forward, backward, and inverse dynamics to learn structured latent representations, improving robot control and planning efficiency. <a href="https://zuxinrui.github.io/sigma-lewm/">Explore the project →</a>
</div>

###### What does Xinrui Zu work on?

Xinrui Zu develops optimal-transport methods — primarily Gromov–Wasserstein — that align the **structure** of different robot sensor modalities rather than matching them point-to-point, improving robustness when sensors fail or drop out. His broader interests span generative models for medical imaging and dimensionality reduction for high-dimensional data visualization.

<!-- Structured data for search engines and AI assistants (schema.org) -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "@id": "https://zuxinrui.github.io/#person",
  "name": "Xinrui Zu",
  "alternateName": ["祖新瑞", "zuxinrui"],
  "url": "https://zuxinrui.github.io",
  "image": "https://zuxinrui.github.io/assets/img/prof_pic.jpg",
  "jobTitle": "PhD Student",
  "affiliation": {
    "@type": "CollegeOrUniversity",
    "name": "Vrije Universiteit Amsterdam",
    "url": "https://vu.nl/en"
  },
  "alumniOf": [
    { "@type": "CollegeOrUniversity", "name": "University of Twente" },
    { "@type": "CollegeOrUniversity", "name": "Fudan University" }
  ],
  "knowsAbout": [
    "Robot Learning", "Multimodal Representation Learning", "Optimal Transport",
    "Gromov-Wasserstein", "Robot Perception", "Generative Models for Medical Imaging",
    "Dimensionality Reduction"
  ],
  "sameAs": [
    "https://scholar.google.com/citations?user=t7rNKqEAAAAJ",
    "https://orcid.org/0000-0002-0924-4904",
    "https://github.com/zuxinrui",
    "https://www.linkedin.com/in/zuxinrui",
    "https://x.com/zu_xinrui",
    "https://openreview.net/profile?id=~Xinrui_Zu1"
  ]
}
</script>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ScholarlyArticle",
  "headline": "Σ-LeWM: Learning World Models via S-Information for Robot Control",
  "author": [
    {
      "@type": "Person",
      "name": "Xinrui Zu"
    },
    {
      "@type": "Person",
      "name": "Michael Przystupa"
    },
    {
      "@type": "Person",
      "name": "Zhao Yang"
    },
    {
      "@type": "Person",
      "name": "Shujian Yu"
    },
    {
      "@type": "Person",
      "name": "Kevin Sebastian Luck"
    }
  ],
  "datePublished": "2026",
  "about": [
    "World Models",
    "S-Information",
    "Robot Control",
    "Representation Learning"
  ],
  "url": "https://zuxinrui.github.io/sigma-lewm/"
}
</script>

<style>
/* Larger intro/bio paragraphs on the homepage (one size up) */
.post .intro p { font-size: 1.15rem; line-height: 1.7; }

/* Enlarge selected-publication preview thumbnails (~2x) for a stronger first impression */
@media (min-width: 576px) {
  ol.bibliography .row > .col-sm-2.abbr { flex: 0 0 32%; max-width: 32%; }
  ol.bibliography .row > .col-sm-2.abbr abbr.badge { max-width: 130px; }
}
</style>
