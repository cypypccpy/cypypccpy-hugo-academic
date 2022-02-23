---
title: SimTwin
summary: A deep reinforcement learning framework that can help directly transfer the model from simulation to reality without any real-world training. Click Video to see the Demo.
tags:
- Manipulator
date: "2021-07-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
- icon: github
  icon_pack: fab
  link: https://github.com/cypypccpy/Isaac-ManipulaRL

url_code: ""
url_pdf: "uploads/IIII.pdf"
url_slides: ""
url_video: "uploads/simtwin_cut.mp4"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

In the field of robot reinforcement learning, the reality gap has always been a problem that restricts the robustness and generalization of algorithms. We propose Simulation Twin (SimTwin) &#58 a deep reinforcement learning framework that can help directly transfer the model from simulation to reality without any real-world training. Simulation Twin consists of a reinforcement learning module and an adaptive correct module. We train the policy using the soft actor-critic algorithm only in a simulator with demonstration and domain randomization. In the adaptive correct module, we design and train a neural network to simulate the human error correction process using force feedback. Subsequently, we combine the above two modules through digital twin to control real-world robots, correct simulator parameters by comparing the difference between simulator and reality automatically, then generalize the correct action through the trained policy network without additional training. We demonstrate the proposed method in an open cabinet task, the experiments show that our framework can reduce the reality gap without any real-world training. **Click Video to see the Demo.** 
