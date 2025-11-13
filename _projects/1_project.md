---
layout: page
title: Socially Aware Multi-Agent Control using Real-Time STTs
description: Real-time spatiotemporal tubes for socially aware navigation and multi-agent coordination
img: assets/img/SocialSTT/SocialAwareness.png
importance: 1
category: research
related_publications: true
---

An autonomous vehicle delivering groceries is expected to exhibit higher social awareness (**altruistic**: more cooperative and cautious, prioritizing safety) compared to a fire-truck (**egoistic**: more goal-driven, prioritizing task completion). The fire truck may move straight ahead, while a commercial vehicle should adjust its behavior to prevent collisions. Thus, social awareness can be viewed as a personality trait, and modeling heterogeneous interactions among agents leads to a more realistic representation of such systems.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SocialSTT/SocialAwareness.png" title="Social awareness illustration" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Interaction between an egoistic (high-priority) fire truck and an altruistic (collision-avoiding) grocery vehicle.
</div>

In this project, we develop a **real-time Spatiotemporal Tube (STT) framework** that allows **socially aware, model-free, and computationally fast control** of **unknown multi-agent systems**.  
Each agent is assigned a **Social Awareness Index** that modulates its behavior: egoistic or altruistic, allowing human-like interactive behavior during navigation.

The approach combines:
- Real-time STT construction  
- Model-free closed-form control  
- Social interaction functions  
- Multi-agent safety and negotiation  
- Prescribed-time reach-avoid-stay (TRAS) guarantees  

To examine the influence of the social awareness index, we considered two scenarios with two omnidirectional robots (blue and yellow). In Case~1, the blue agent was assigned a higher social awareness index than the yellow agent. Consequently, the blue agent behaved more altruistically, showing greater flexibility and cooperation, whereas the yellow agent was more egoistic, prioritizing its goal and obstacle avoidance. In Case~2, the social awareness indices were swapped while keeping all other parameters identical, leading to the opposite behaviors compared to Case~1.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SocialSTT/hardware1.mp4" title="Hardware demonstration" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hardware demonstration of two omnidirectional robots in a cluttered dynamic environment
</div>

# Related Publication  
**Incorporating Social Awareness into Control of Unknown Multi-Agent Systems: A Real-Time Spatiotemporal Tubes Approach**  
R. Das, S. Upadhyay, P. Jagtap  
arXiv:2510.25597 (2025)

[Read the paper](https://arxiv.org/pdf/2510.25597)

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div> -->
