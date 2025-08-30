---
title: 'DTC: Deep Tracking Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Fabian Jenelten  
  - Junzhe He
  - Farbod Farshidian
  - Marco Hutter

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *Science Robotics*
publication_short: In *SciRob 2024*

abstract: Legged locomotion is a complex control problem that requires both accuracy and robustness to cope with real-world challenges. Legged systems have traditionally been controlled using trajectory optimization with inverse dynamics. Such hierarchical model-based methods are appealing because of intuitive cost function tuning, accurate planning, generalization, and, most importantly, the insightful understanding gained from more than one decade of extensive research. However, model mismatch and violation of assumptions are common sources of faulty operation. Simulation-based reinforcement learning, on the other hand, results in locomotion policies with unprecedented robustness and recovery skills. Yet, all learning algorithms struggle with sparse rewards emerging from environments where valid footholds are rare, such as gaps or stepping stones. In this work, we propose a hybrid control architecture that combines the advantages of both worlds to simultaneously achieve greater robustness, foot-placement accuracy, and terrain generalization. Our approach uses a model-based planner to roll out a reference motion during training. A deep neural network policy is trained in simulation, aiming to track the optimized footholds. We evaluated the accuracy of our locomotion pipeline on sparse terrains, where pure data-driven methods are prone to fail. Furthermore, we demonstrate superior robustness in the presence of slippery or deformable ground when compared with model-based counterparts. Last, we show that our proposed tracking controller generalizes across different trajectory optimization methods not seen during training. In conclusion, our work unites the predictive capabilities and optimality guarantees of online planning with the inherent robustness attributed to offline learning. Trajectory optimization and reinforcement learning are combined for versatile and robust perceptive legged locomotion.

# Summary. An optional shortened abstract.
summary: Science Robotics 2024. In this work, we propose a hybrid control architecture that combines the advantages of both model-based and learning-based methods to simultaneously achieve greater robustness, foot-placement accuracy, and terrain generalization.

tags:
  - Legged Locomotion
  - MPC
  - Reinforcement Learning

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
url_source: 'https://www.science.org/doi/10.1126/scirobotics.adh5401'
url_video: 'https://www.youtube.com/watch?v=nipH-yl8lR0'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - dtc

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
