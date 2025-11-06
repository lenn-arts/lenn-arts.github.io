---
layout: page
title: Build a walking quadruped robot from scratch
description: I design, manufacture, and control a four-legged robot to walk.
img: assets/img/metalhead_thumbnail_vertical.jpg
importance: 1
category: project
---

Built a four-leg walking robot from scratch. Performed concept sketch, CAD design, manufacturing (3D printing, lasercutting), electronics integration, gait design and optimization. Achieved top speed of 30cm/s. 

Watch the full engineering journey from start to end:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="800" height="450" src="https://www.youtube-nocookie.com/embed/gTV5YUqbgmM?si=86GznT94GUoocRxH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
</div>

The robot is consistent between CAD, real world manufacture, and simulation, allowing to run design optimization as well as gait optimization and learning.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/metalhead_cad_real_sim.jpg" title="Metalhead CAD design, built in the real-world, and digital twin in simulation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Metalhead CAD design, built in the real-world, and digital twin in simulation
</div>

We get the robot to walk fast by deploying a short cyclical gait for the 8 servos that is inspired by the result of evolutionary algorithms.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/metalhead_gait_plot.png" title="Metalhead optimal gait" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Metalhead optimal sinusoidal gait for 8 servo motors.
</div>
