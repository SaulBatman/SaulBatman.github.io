---
title: Hindsight Experience Replay in Robotics Manipulation
summary: Sample-efficient!
tags:
  - Deep Learning
  - Robotics
date: '2022-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
url_code: ''
url_pdf: 'uploads/RL_final_report.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In goal-conditioned reinforcement learning
problems, the sample efficiency is often a drawback that
most of the explorations are not consider as very useful
experience because they are failure episodes, which makes
low sample efficiency. In this paper, we implemented a
module of Hindsight Experience Replay (HER) in several
goal-conditioned environments, to discover its utility of
improving sample efficiency. Based on Deep Deterministic
Policy Gradient (DDPG), the experiments showed that the
HER module helps the agent learn much faster with more
robustness. We then discussed about the limitation of HER
and how hyper parameters effects its performance.

