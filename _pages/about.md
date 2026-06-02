---
layout: about
title: about
permalink: /
subtitle: <em>“I align the geometry of how machines perceive — and build the robots that do.”</em><br>PhD Student, <a href='https://vu.nl/en'>Vrije Universiteit Amsterdam</a> · Robot Learning · Multimodal Representation · Optimal Transport

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

**Xinrui Zu** (祖新瑞) is a PhD student at **Vrije Universiteit Amsterdam**, jointly in the [Computational Intelligence Group](https://cs.vu.nl/ci/) and the [Quantitative Data Analytics Group](https://vu-qda.github.io/), advised by Dr. [Kevin Sebastian Luck](https://kevin-luck.com/) and Dr. [Shujian Yu](https://sjyucnel.github.io/). He studies the **geometry of learned representations** — how perception is structured inside neural networks — and uses **optimal transport** to align that structure across sensory modalities (vision, force, tactile, IMU, proprioception) and across domains (medical imaging and robotics).

The same idea threads through his work: a Gromov–Wasserstein regularizer for robot perception (**UniOMA**, ICRA 2026), optimal-transport flows for medical image synthesis, and embedding methods that preserve structure under dimensionality reduction (**SpaceMAP**, ICML 2022; **Deep Recursive Embedding**, IEEE TVCG 2022). Before his PhD he was a research assistant at [TU Delft, Imaging Physics](https://www.tudelft.nl/tnw/over-faculteit/afdelingen/imphys) with Dr. [Qian Tao](https://www.tudelft.nl/tnw/over-faculteit/afdelingen/imphys/about-the-department/tao-qian), earned an MSc in Robotics & Mechatronics at the [University of Twente](https://www.ram.eemcs.utwente.nl), and a BSc in Theoretical & Applied Mechanics at [Fudan University](https://en.wikipedia.org/wiki/Fudan_University). And because alignment shouldn’t stay theoretical, he also **builds the robots** — modular manipulators, autonomous vehicles, and the sensors they learn from.

Feel free to reach out for collaborations or a chat about optimal transport, multimodal robot learning, or generative models.

<br>

#### 🤖 Featured — UniOMA (ICRA 2026)

{% include figure.liquid loading="eager" path="assets/img/unioma/vip.jpg" class="img-fluid rounded z-depth-1" alt="UniOMA real-robot setup: vision, IMU and proprioception drive frozen encoders to predict end-effector position on a 6-DoF arm." %}

<div class="caption">
  <strong>UniOMA</strong> uses Gromov–Wasserstein optimal transport to align the <em>structure</em> of heterogeneous robot sensors into a shared representation space — improving robustness when sensors drop out. <a href="{{ '/projects/unioma/' | relative_url }}">Read more →</a>
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
  "headline": "UniOMA: Unified Optimal-Transport Multi-Modal Structural Alignment for Robot Perception",
  "author": { "@id": "https://zuxinrui.github.io/#person" },
  "datePublished": "2026",
  "publisher": { "@type": "Organization", "name": "IEEE ICRA 2026" },
  "about": ["Optimal Transport", "Gromov-Wasserstein", "Robot Perception", "Multimodal Alignment"],
  "url": "https://openreview.net/forum?id=rcc5qZ6CtV"
}
</script>
