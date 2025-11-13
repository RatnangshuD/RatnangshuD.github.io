---
layout: page
title: Socially Aware Multi-Agent Control using Real-Time STTs
description: Real-time spatiotemporal tubes for socially aware navigation and multi-agent coordination
img: assets/img/projects/SocialAwareness-bg.jpg   # background image for project card
importance: 1
category: research
related_publications: true
---

This project develops a **real-time Spatiotemporal Tube (STT) framework** that allows **socially aware, disturbance-robust, and collision-free control** of **unknown multi-agent systems**.  
Each agent is assigned a **Social Awareness Index (SAI)** that modulates its behavior: egoistic or altruistic, allowing human-like interactive behavior during navigation.

The approach combines:
- Real-time STT construction  
- Model-free closed-form control  
- Social interaction functions  
- Multi-agent safety and negotiation  
- Temporal reach-avoid-stay (TRAS) guarantees  

It scales to dozens of agents, works under unknown disturbances, and supports real-time deployment.

---

# 🎥 Hardware Demonstration (GIF)
<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hardware.gif" title="Hardware demonstration" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hardware experiment: Two omnidirectional robots performing socially aware negotiation and collision avoidance.
</div>

---

# Related Publication  
**Incorporating Social Awareness into Control of Unknown Multi-Agent Systems: A Real-Time Spatiotemporal Tubes Approach**  
R. Das, S. Upadhyay, P. Jagtap  
arXiv:2510.25597 (2025)

[Read the paper](https://arxiv.org/pdf/2510.25597)

---

<!-- # Code Snippet (Optional)
Here’s an example of a 2/3 + 1/3 image layout as used above:

{% raw %}
```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/hardware.gif" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/simulation3d.gif" %}
  </div>
</div> -->
