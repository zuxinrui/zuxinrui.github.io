---
layout: page
title: robots
permalink: /robots/
description: Hardware I've designed and built from scratch — manipulators, vehicles, and the sensors that drive them.
nav: true
nav_order: 4
---

Before (and alongside) the math, I build the machines. A running list of robots and sensor systems I've designed and built by hand — mechanics, electronics, firmware, and control.

<hr>

### SmartArm — reconfigurable modular manipulator

<div class="row align-items-center">
  <div class="col-md-7 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline>
      <source src="{{ 'assets/video/smartarm2.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>
  <div class="col-md-5 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline>
      <source src="{{ 'assets/video/smartarm2_tra.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>
</div>

A series of modular arms with full closed-loop perception control, reaching the repeatability of far more expensive manipulators. ROS Noetic middleware, a custom asynchronous `MoveIt!` pipeline that re-plans on the fly, and an adaptive feedforward dynamic controller. <a href="{{ '/projects/smartarm/' | relative_url }}">Details →</a>

<hr>

### Tyrion — a 6-DOF arm that fits on a desk

{% include figure.liquid path="assets/img/tyrion.png" class="img-fluid rounded z-depth-1" alt="Tyrion, a tiny 6-DOF desktop industrial manipulator." %}

An extremely tiny 6-DOF industrial manipulator — desktop-sized, built to industrial-style precision. <a href="{{ '/projects/tyrion/' | relative_url }}">Details →</a>

<hr>

### Ultrasonic localization system

<div class="row align-items-center">
  <div class="col-md-7 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline>
      <source src="{{ 'assets/video/sonic-local.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>
  <div class="col-md-5 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/sonic.png" class="img-fluid rounded z-depth-1" alt="Ultrasonic localization sensor hardware." %}
  </div>
</div>

Ultrasound fused with an IMU via an Extended Kalman Filter — ~0.5 mm accuracy in xyz, ~0.01 rad in rotation, at 1000 Hz on an STM32. <a href="{{ '/projects/ultrasonic-localization/' | relative_url }}">Details →</a>

<hr>

### ROS autonomous vehicle

<div class="row align-items-center">
  <div class="col-md-5 mt-3 mt-md-0">{% include figure.liquid path="assets/img/ros-v.jpg" class="img-fluid rounded z-depth-1" alt="ROS autonomous vehicle." %}</div>
  <div class="col-md-7 mt-3 mt-md-0">{% include figure.liquid path="assets/img/ros-2.png" class="img-fluid rounded z-depth-1" alt="Map built by the ROS vehicle using Gmapping SLAM." %}</div>
</div>

A SLAM-capable vehicle running ROS on a Raspberry Pi, with a custom STM32 low-level controller for the IMU and motors, mapping via Gmapping. <a href="{{ '/projects/ros-vehicle/' | relative_url }}">Details →</a>

<hr>

### 3Arobot — 3D-printed manipulators

{% include figure.liquid path="assets/img/3a.png" class="img-fluid rounded z-depth-1" alt="3Arobot 3D-printed robotic manipulators." %}

A series of 3D-printed manipulators with competitive accuracy — they write, draw, and (with a heating extruder) double as 3D printers. <a href="{{ '/projects/3arobot/' | relative_url }}">Details →</a>

<hr>

### Teaching robots — Fudan Science Camp

{% include figure.liquid path="assets/img/camp1.png" class="img-fluid rounded z-depth-1" alt="Fudan science camp robotics workshop." %}

I built a ROS + lidar mobile platform and used it to teach 100 high-school students the basics of SLAM and ROS programming. <a href="{{ '/projects/science-camp/' | relative_url }}">Details →</a>
