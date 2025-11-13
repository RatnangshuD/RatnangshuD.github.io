---
layout: page
title: "Approximation-Free Control for STL Specifications Using STTs"
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
        {% include figure.liquid path="assets/img/STT-STT/STT.png" title="Spatiotemporal Tube illustration" class="img-fluid rounded z-depth-1" %}
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

# Related Publication

**Approximation-Free Control for Signal Temporal Logic Specifications Using Spatiotemporal Tubes**  
R. Das, S. Choudhury, P. Jagtap  
IEEE Control Systems Letters (L-CSS), 2025

[Read the paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11036802)

---
