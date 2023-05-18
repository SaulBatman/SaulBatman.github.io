---
title: "SEIL: Simulation-augmented Equivariant Imitation Learning"
summary: ICRA 2023
tags:
  - Deep Learning
  - Robotics
date: '2022-08-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
- name: Paper
  url: 'https://arxiv.org/pdf/2211.00194'
- name: Code available!
  url: https://github.com/SaulBatman/SEIL
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/A9gJZWZO7Og'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
# Authors
Mingxi Jia, Dian Wang, Guanang Su, David Klee, Xupeng Zhu, Robin Walters, Robert Platt

# Abstract
In robotic manipulation, acquiring samples is extremely expensive because it often requires interacting with the real world.  Traditional image-level data augmentation has shown the potential to improve sample efficiency in various machine learning tasks. However, image-level data augmentation is insufficient for an imitation learning agent to learn good manipulation policies in a reasonable amount of demonstrations. We propose Simulation-augmented Equivariant Imitation Learning (SEIL), a method that combines a novel data augmentation strategy of supplementing expert trajectories with simulated transitions and an equivariant model that exploits the $\mathbf{O}(2)$ symmetry in robotic manipulation. Experimental evaluations demonstrate that our method can learn non-trivial manipulation tasks within ten demonstrations and outperforms the baselines with a significant margin.

# Approach
## 1. Equivariant Behavioral Cloning
  <img src="./img/equivariant.gif" alt="drawing" width="900"/>

## 2. Transition Simulation
  <img src="./img/TS.gif" alt="drawing" width="900"/>

# Results
* Simulation results
  
  <!-- ![Sim Results](./img/sim_result.png) -->
  <img src="./img/sim_result.png" alt="drawing" width="900"/>
* Real-world results
 
  <img src="./img/real_result.png" alt="drawing" width="1000"/>
# Experiments
## Real-world tasks
* Block in Bowl
  <img src="./img/bowl.gif" alt="drawing" width="1000"/>
* Trash Tidying
  <img src="./img/trash3.gif" alt="drawing" width="1000"/>
* Shoe Packing
  <img src="./img/shoe.gif" alt="drawing" width="1000"/>
* Drawer Opening
  <img src="./img/drawer.gif" alt="drawing" width="1000"/>

## Interactive close-loop behavior
* Interactive Drawers
  <img src="./img/Drawer_interactive.gif" alt="drawing" width="1000"/>
* Interactive "Trash Tidying"
  <img src="./img/Trash3_interactive.gif" alt="drawing" width="1000"/>

# Citation
```
@article{jia2022seil,
  title={SEIL: Simulation-augmented Equivariant Imitation Learning},
  author={Jia, Mingxi; Wang, Dian; Su, Guanang; Klee, David; Zhu, Xupeng; Walters, Robin; Platt, Robert},
  journal={arXiv preprint arXiv:2211.00194},
  year={2022}
}
```