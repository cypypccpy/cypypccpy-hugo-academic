---
title: "Generalizing Object Manipulation through End-to-End Visual Affordance Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yiran Geng
- Boshi An
- admin
- Haoran Geng
- Hongcheng Wang
- Yan Zhao
- Yaodong Yang
- Hao Dong

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-11"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Under review*
# publication_short: In *ICW*

abstract: Learning to manipulate 3D articulated objects in an interactive environment has been challenging in reinforcement learning (RL) studies. It is hard to train a policy that can generalize over different objects with vast semantic categories, diverse shape geometry, and versatile functionality. Visual affordance provides object-centric information priors that offer actionable semantics for objects with movable parts. For example, an effective policy should know the pulling force on the handle to open a door. Nevertheless, how to learn affordance in an end-to-end fashion within the RL process is unknown. In this study, we fill such a research gap by designing algorithms that can automatically learn affordance semantics through a contact prediction process. The contact predictor allows the agent to learn the affordance information (i.e., where to act for the robot arm on the object) from previous manipulation experience, and such affordance semantics then helps the agent learn effective policies through RL updates. We use our framework on several downstream tasks. The experimental result and analysis demonstrate the effectiveness of end-to-end affordance learning.


# Summary. An optional shortened abstract.
summary: We propose an end-to-end affordance learning framework for training a policy with generalization in manipulating 3D articulated objects.

tags: [Reinforcement Learning, Object Manipulation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'An overview of SafeAIJ'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- SafeAIJ

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: SafeAIJ
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
