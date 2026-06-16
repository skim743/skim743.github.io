---
layout: page
title: Advanced Robotic Manipulation Lab
description: An educational robot-arm testbed at Georgia Tech for hands-on manipulation research and coursework
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

The Advanced Robotic Manipulation (ARM) Lab is an educational robotic testbed at Georgia Tech, built around multiple robot-arm stations that let students and researchers move from algorithms to real hardware. I established the lab end to end — from budget planning, procurement, and layout design through system installation, hardware calibration, and software integration.

To make the testbed reliable and reproducible at scale, I developed custom hardware emergency-stop buttons (physical switches driven by a custom-programmed microcontroller) integrated into the robot SDK, containerized the entire software stack for consistency across stations, and built a fleet-management framework supporting remote power control, over-the-air (OTA) updates, teleoperation, and centralized data collection. The lab also hosts course projects spanning simulation and hardware, covering point-cloud registration, pick-and-place, torque control, gravity compensation, hybrid force–position control, and imitation learning.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/iEGV_zJChFA" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Advanced Robotic Manipulation Teaser.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/9Fe_vq2uovM" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Advanced Robotic Manipulation Teaser.
</div>
