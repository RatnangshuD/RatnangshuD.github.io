---
layout: page
title: "STTs for Signal Temporal Logic (STL) Tasks"
description: A closed-form, model-free control framework for general STL specifications using Spatiotemporal Tubes
img: assets/img/STL-STT/STL.png
importance: 3
category: research
related_publications: true
---

Signal Temporal Logic (STL) enables rich task descriptions involving deadlines, sequencing, logical constraints, and safety requirements. However, existing STL control frameworks do not scale to complex specifications or unknown dynamics.

This project develops a **Spatiotemporal Tube (STT)-based control framework** for **general STL specifications** in unknown nonlinear systems. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/STL-STT/STL.png" title="Spatiotemporal Tube illustration" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The STT generation framework.
</div>

The method:
- reformulates STL robustness constraints as a **robust optimization problem (ROP)**,  
- converts it into a tractable **scenario optimization program (SOP)**,  
- constructs STTs ensuring **positive STL robustness**, and  
- uses an **approximation-free, closed-form controller** to keep trajectories inside the tubes.

The resulting control strategy is **model-free**, supports **general STL**, and requires **no real-time optimization**.

---

## Omnidirectional Robot

This STL task requires the robot to switch between $T_1$ and $T_2$ every 3–4 time units until time 13, reach and stay in the region $G$ from time 17 to 20, and avoid $O_1$ and $O_2$ for the first 20 time units, starting from $S$.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/STL-STT/Omni.png" title="Omnidirectional robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The robot safely reaches the target within the prescribed time while avoiding all obstacles.
</div>

---

## Rotating Rigid Spacecraft

This is a sequential STL task, in which the spacecraft, starting from $S$, must eventually reach either region $T_1$ or $T_2$ between 7 and 8 seconds. Then, it must "eventually" proceed to the goal region $G$ between 14 and 15 seconds. Additionally, the spacecraft must avoid the unsafe set $O$ at all times from 0 to 15 seconds.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/STL-STT/Spacecraft.png" title="Spacecraft" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Handles time-varying unsafe intervals while reaching the target at the specified time.
</div>

---

# Related Publication

**Approximation-Free Control for Signal Temporal Logic Specifications Using Spatiotemporal Tubes**  
R. Das, S. Choudhury, P. Jagtap  
IEEE Control Systems Letters (L-CSS), 2025

[Read the paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11036802)

---
