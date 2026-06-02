---
layout: page
title: Ultrasonic Localization System
description: Sub-millimeter end-effector localization fusing ultrasound and IMU
img: assets/img/sonic.png
importance: 4
category: hardware & robots
---

An ultrasonic localization system fused with an IMU via an **Extended Kalman Filter**, reaching roughly **0.5 mm** accuracy in xyz and ~0.01 rad in the three rotation axes.

<div class="row">
  <div class="col-sm-5 mt-3 mt-md-0">{% include figure.liquid path="assets/img/sonic.png" class="img-fluid rounded z-depth-1" alt="Ultrasonic localization sensor system." %}</div>
  <div class="col-sm-7 mt-3 mt-md-0">{% include figure.liquid path="assets/img/sonic-local.gif" class="img-fluid rounded z-depth-1" alt="Ultrasonic localization tracking in real time." %}</div>
</div>

The system uses an **STM32F103RCT6** as the control unit, with DMA and hardware acceleration for faster sensor processing at a 1000 Hz sampling rate.
