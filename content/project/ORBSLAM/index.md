---
title: ORBSLAM3 on iPhone
summary: Wanna try ORBSLAM3 with your iPhone? Try this!
tags:
  - Mobility
  - Robotics
date: '2022-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
url_code: 'https://gitlab.com/saulbatman/eece5554/-/tree/main/FinalProject'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In order to run our method, you should install ORBSLAM3 and Droidcam on your UBUNTU PC. And, you should install droidcam in your iPhone, which you can find in App store.
ORBSLAM3 and droidcam repositories have already been forked into our github repo. Please refer to the installation links mentioned above to download these necessary components. It is highly recommended to check the official github repo. We also get a modified version monoVO-Python here as our baseline, where we also add out kitti toolkits.
Our project is ORBSLAM3 on iPhone. The motivation is that SLAM often requires cameras like realsense, which is hard to get in daily life. So, why not use the camera in our iPhone? By using iPhone, many interesting applications can be furtherly extended, such as augmented reality, indoor localization, etc.
For now, the ORBSLAM algorithm runs on PC and the video sequence is transmitting from iPhone to PC via droidcam.

Please refer to our [project website](https://gitlab.com/saulbatman/eece5554/-/tree/main/FinalProject)!
