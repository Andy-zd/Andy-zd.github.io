---
layout: about
title: about
permalink: /
subtitle: Ph.D. student, Georgia Institute of Technology

profile:
  align: right
  image: me.JPG
  image_circular: false # crops the image to make it circular
  address: >
      Atlanta, GA

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. student at the Georgia Institute of Technology, advised by [Jiachen Li](https://jiachenli94.github.io/). Before moving to Georgia Tech, I began my Ph.D. at the University of California, Riverside. I worked as a research assistant in the [Zhang Vision Group](https://fudan-zvg.github.io/) during my master's study and spent four months as a visiting graduate researcher at the University of California, Los Angeles, advised by [Bolei Zhou](https://boleizhou.github.io/). I received my B.S. and M.S. degrees from the School of Mathematical Sciences at Fudan University in 2021 and 2024.

## research

### Spatial Intelligence for Embodied Intelligence

My research studies how embodied agents can perceive, reconstruct, reason about, and act in the 3D and 4D physical world. I develop geometry-aware representations and generative world models that connect pixels and language to metric space, dynamics, and actions. The central goal is to build spatially consistent world representations that are precise enough for control while remaining general across scenes, viewpoints, tasks, and embodiments.

**Autonomous driving.** I work on neural reconstruction and simulation, realistic multimodal sensor synthesis, structured urban-scene generation, and world-grounded vision-language-action planning. This line includes [S-NeRF](https://ziyang-xie.github.io/s-nerf/), [NeRF-LiDAR](https://github.com/fudan-zvg/NeRF-LiDAR), [UrbanDiffusion](https://metadriverse.github.io/urbandiff/), [S-NeRF++](https://arxiv.org/abs/2402.02112), [uncertainty-aware 3D scene refinement](https://arxiv.org/abs/2503.15742), and [VLM-3R](https://vlm-3r.github.io/). My current project, **Driving in 4D: A World-Grounded Vision-Language-Action Model for End-to-End Autonomous Driving**, investigates how frozen visual geometry and VLM semantics can be aligned through a compact spatial interface for motion planning.

**Robot manipulation.** I explore spatially grounded VLA policies through explicit camera-pose and coordinate conditioning, instruction-aligned 3D reasoning, scalable procedurally generated environments, reinforcement-learning post-training, and video/point-flow world models for physical interaction. Together, the driving and manipulation directions ask the same question: how can an embodied agent preserve the geometry, semantics, and dynamics needed to turn visual understanding into reliable action?

