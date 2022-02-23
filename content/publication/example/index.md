---
title: "Zero-Shot Sim-to-Real Transfer of Reinforcement Learning Framework for Robotics Manipulation with Demonstration and Force Feedback"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuanpei Chen
- Chao Zeng
- Zhiping Wang
- Peng Lu
- Chenguang Yang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-02-23"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: In the field of robot reinforcement learning, the reality gap has always been a problem that restricts the robustness and generalization of algorithms. We propose Simulation Twin (SimTwin) &#58 a deep reinforcement learning framework that can help directly transfer the model from simulation to reality without any real-world training. Simulation Twin consists of a reinforcement learning module and an adaptive correct module. We train the policy using the soft actor-critic algorithm only in a simulator with demonstration and domain randomization. In the adaptive correct module, we design and train a neural network to simulate the human error correction process using force feedback. Subsequently, we combine the above two modules through digital twin to control real-world robots, correct simulator parameters by comparing the difference between simulator and reality automatically, then generalize the correct action through the trained policy network without additional training. We demonstrate the proposed method in an open cabinet task, the experiments show that our framework can reduce the reality gap without any real-world training.

# Summary. An optional shortened abstract.
summary: We propose Simulation Twin (SimTwin) &#58 a deep reinforcement learning framework that can help directly transfer the model from simulation to reality without any real-world training.

tags: [Sim2Real, Reinforcement Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/IIII.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'uploads/simtwin_cut.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'An overview of SimTwin'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
