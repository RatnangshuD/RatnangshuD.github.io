---
layout: page
title: Spatiotemporal Tubes for Temporal Reach–Avoid–Stay (T-RAS) Tasks
description: A sampling-based STT framework with closed-form control for unknown nonlinear systems
img: assets/img/TRAS-STT/TRAS.png
importance: 2
category: research
related_publications: true
---

Temporal Reach–Avoid–Stay (T-RAS) tasks appear across robotics and safety-critical autonomous systems: reach a target set within a desired time while avoiding unsafe regions and remaining in a safe state space. Classical tools such as Hamilton–Jacobi reachability or control barrier functions struggle with **scalability**, **model uncertainty**, or **online computation costs**.

This project develops a **sampling-based Spatiotemporal Tube (STT) framework** with an **approximation-free, closed-form controller** that allows unknown nonlinear systems to satisfy general T-RAS specifications.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/TRAS-STT/TRAS.png" title="Spatiotemporal Tube illustration" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The STT generation framework.
</div>

---

## Omnidirectional Robot — Safe Navigation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/TRAS-STT/Omni.gif" title="Omnidirectional robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The robot safely reaches the target within the prescribed time while avoiding all obstacles.
</div>

---

## Magnetic Levitator — Time-Varying Unsafe Sets

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/TRAS-STT/MagLevSTT.png" title="Magnetic levitation system STT" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/TRAS-STT/MagLev.gif" title="Magnetic levitation system" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Handles time-varying unsafe intervals while reaching the target at the specified time.
</div>

---

# Related Publication

**Spatiotemporal Tubes for Temporal Reach–Avoid–Stay Tasks in Unknown Systems**  
R. Das, A. Basu, P. Jagtap  
IEEE Transactions on Automatic Control (TAC), 2025  

[Read the paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11096612)

---

