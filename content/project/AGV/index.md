---
title: AGV
summary: Improved Localization system of Automated Guided Vehicle. Click Video to see the Demo.
tags:
- AGV
date: "2021-07-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](uploads/AGV_Demo.mp4)'
  focal_point: ""
  preview_only: false

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
- icon: github
  icon_pack: fab
  link: https://github.com/cypypccpy/rmua_scut

url_code: ""
url_pdf: ""
url_slides: ""
url_video: "uploads/AGV_Demo.mp4"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
This project is an upgrade of the AGV localization system for the ICRA 2021 DJI RoboMaster
AI Challenge. After realizing a Lidar based navigation using ROS Navigation Stack, I found that
AMCL algorithm for localization have a low accuracy. Therefore, I separated the pure localization
module of a SLAM algorithm, Cartographer, used it for localization and published odom and pose
topic for navigation in ROS, greatly improving the accuracy. 
**Click Video to see the Demo.** 

