---
layout: page
title: ROS Autonomous Vehicle
description: A SLAM-capable autonomous vehicle with a custom STM32 low-level controller
img: assets/img/ros-v.jpg
importance: 4
category: hardware & robots
---

An autonomous vehicle running **ROS (Noetic)** on a Raspberry Pi, with a custom **STM32** low-level controller driving both the IMU and the motors.

<div class="row">
  <div class="col-sm-5 mt-3 mt-md-0">{% include figure.liquid path="assets/img/ros-v.jpg" class="img-fluid rounded z-depth-1" alt="ROS autonomous vehicle." %}</div>
  <div class="col-sm-7 mt-3 mt-md-0">{% include figure.liquid path="assets/img/ros-2.png" class="img-fluid rounded z-depth-1" alt="Map built by the ROS vehicle using Gmapping SLAM." %}</div>
</div>

I built the ROS packages and deployed them to the Raspberry Pi Ubuntu system, using the **Gmapping** SLAM algorithm to construct maps.
