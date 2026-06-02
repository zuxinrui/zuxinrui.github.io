---
layout: page
title: SmartArm
description: A reconfigurable modular robotic manipulator, built from scratch
img: assets/img/smartarm-poster.jpg
importance: 1
category: hardware & robots
---

**SmartArm** is a series of reconfigurable modular robotic manipulators that use full closed-loop perception control and adaptive control to reach the repeatability of far more expensive arms. Built entirely by hand, it runs ROS Noetic as middleware, with structure designed in Fusion 360. [[Project page]](https://github.com/zuxinrui/Smartarm)

<div class="row">
  <div class="col-sm-6 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline alt="SmartArm end-effector tracking with its ultrasonic localization system.">
      <source src="{{ 'assets/video/smartarm2.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline alt="SmartArm motion planning and execution with MoveIt!.">
      <source src="{{ 'assets/video/smartarm2_tra.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>
</div>

<div class="caption">Left: end-effector tracking via the onboard ultrasonic localization system. Right: motion planning &amp; execution with a custom asynchronous <code>MoveIt!</code> pipeline that re-plans trajectories on the fly.</div>

Combined with a custom ultrasonic localization system, SmartArm runs a full closed-loop controller with two end-effector localization modes — fast-response and smooth-response. I am also developing a real-time dynamic controller using adaptive feedforward control to learn the manipulator's dynamic parameters.
