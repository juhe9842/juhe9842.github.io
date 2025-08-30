---
title: 'Attention-based Map Encoding for Learning Generalized Legged Locomotion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Junzhe He
  - Chong Zhang
  - Fabian Jenelten
  - Ruben Grandia
  - Moritz BÄcher
  - Marco Hutter

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *Science Robotics*
publication_short: In *SciRob 2025*

abstract: Dynamic locomotion of legged robots is a critical yet challenging topic in expanding the operational range of mobile robots. It requires precise planning when possible footholds are sparse, robustness against uncertainties and disturbances, and generalizability across diverse terrains. Although traditional model-based controllers excel at planning on complex terrains, they struggle with real-world uncertainties. Learning-based controllers offer robustness to such uncertainties but often lack precision on terrains with sparse steppable areas. Hybrid methods achieve enhanced robustness on sparse terrains by combining both methods but are computationally demanding and constrained by the inherent limitations of model-based planners. To achieve generalized legged locomotion on diverse terrains while preserving the robustness of learning-based controllers, this paper proposes an attention-based map encoding conditioned on robot proprioception, which is trained as part of the controller using reinforcement learning. We show that the network learns to focus on steppable areas for future footholds when the robot dynamically navigates diverse and challenging terrains. We synthesized behaviors that exhibited robustness against uncertainties while enabling precise and agile traversal of sparse terrains. In addition, our method offers a way to interpret the topographical perception of a neural network. We have trained two controllers for a 12-degrees-of-freedom quadrupedal robot and a 23-degrees-of-freedom humanoid robot and tested the resulting controllers in the real world under various challenging indoor and outdoor scenarios, including ones unseen during training.

# Summary. An optional shortened abstract.
summary: 'Science Robotics 2025. In this work, we propose an attention-based map encoding method that enables legged robots walk on challenging discontinuous terrains.'

tags:
  - Legged Locomotion
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
url_source: 'https://www.science.org/stoken/author-tokens/ST-2851/full'
url_video: 'https://www.youtube.com/watch?v=GUgwB6WxcFo&t=37s'

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
#   - ame

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
