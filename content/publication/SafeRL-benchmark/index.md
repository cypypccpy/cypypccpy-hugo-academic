---
title: "Benchmarking Safe Policy Optimization for Constrained Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jiamg Ji
- Long Yang
- Shangding Gu
- admin
- Zhouchen Lin
- Yaodong Yang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-12"
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

abstract: Safe reinforcement learning (safe RL) tackles decision making problems with safety constraints. Despite the influx of attention in this field, there is a lack of commonly recognized safe RL benchmark. This is partly because the code of many safe RL methods is unavailable and also because new methods often come with new testing tasks.  As a result, researchers suffer from incorrect implementations, unfair comparisons, and misleading conclusions.  In this study, we offer a solid safe RL benchmark---(\texttt{SafePO})---which benchmarks popular safe policy learning algorithms across a list of common environments. Specifically, we start by standardizing the problem of safe exploration via solving constrained Markov decision processes (CMDP). Then, we provide implementations for CMDP solutions, covering both constrained policy optimization type methods and Lagrangian type methods.  Our implementations in SafePO are highly efficient in the sense that learners can collect samples in parallel and synchronize their policy gradients on different physical CPU cores. We test them on four types of safety-aware robot learning tasks. Based on the benchmark results, we derive new insights by disclosing the interplay of different attributes on safety performance and illustrating the difficulty of safety learning on the sparse cost. Furthermore, to consider the safe RL problem in multi-agent settings, we introduce new tasks based on the DexterousHands environment and report comparison results for both single-agent and multi-agent safe RL algorithms. Our project is released at&#58 \url{https://github.com/PKU-MARL/Safe-Policy-Optimization}.


# Summary. An optional shortened abstract.
summary: We provide a solid safe RL benchmark along with new testing environments.

tags: [Benchmarking Safe Policy Optimization for Constrained Reinforcement Learning]

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
