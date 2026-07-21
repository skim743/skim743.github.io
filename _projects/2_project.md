---
layout: page
title: Building a Robotarium
description: Full-stack development of a remotely accessible multi-robot research testbed at Georgia Tech
img:
importance: 2
category: work
related_publications: true
---

The Robotarium is a remotely accessible, multi-robot research testbed at Georgia Tech that lets researchers and students run swarm-robotics experiments on real hardware from anywhere. I worked across the full stack of the testbed — from robot design and firmware to the software framework that keeps it running autonomously.

A core contribution was **GTernal**, a robot designed for the autonomous operation of the testbed, with onboard collision avoidance based on control barrier functions and time-of-flight sensors {% cite Kim2024GTernal %}. I led the production of 40 GTernals to replace the previous GritsBot X robots, and led the transition of the Robotarium's publish–subscribe framework from MQTT to ROS2 — spanning the Python/MATLAB backend, robot firmware, and motion-capture interface. I also built a mobile version of the Robotarium using a laptop and a webcam-based tracking system (ArUco tags).

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/X4MpRk02QDE" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Building a Robotarium.
</div>
