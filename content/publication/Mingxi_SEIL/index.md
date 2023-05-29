---
title: 'SEIL: Simulation-augmented Equivariant Imitation Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mingxi Jia*
  - Dian Wang*
  - Guanang Su
  - David Klee
  - Xupeng Zhu
  - Robin Walters
  - Robert Platt

# Author notes (optional)
author_notes:
  - 

date: '2023-01-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA 2023* (also presented CoRL 2022 Workshop on Sim-to-Real Robot Learning).

abstract: In robotic manipulation, acquiring samples is extremely expensive because it often requires interacting with the real world.  Traditional image-level data augmentation has shown the potential to improve sample efficiency in various machine learning tasks. However, image-level data augmentation is insufficient for an imitation learning agent to learn good manipulation policies in a reasonable amount of demonstrations. We propose Simulation-augmented Equivariant Imitation Learning (SEIL), a method that combines a novel data augmentation strategy of supplementing expert trajectories with simulated transitions and an equivariant model that exploits the O(2) symmetry in robotic manipulation. Experimental evaluations demonstrate that our method can learn non-trivial manipulation tasks within ten demonstrations and outperforms the baselines with a significant margin.

# Summary. An optional shortened abstract.
summary: Simulation-augmented Equivariant Imitation Learning (SEIL) combines a novel data augmentation strategy of supplementing expert trajectories with simulated transitions and an equivariant model

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- name: Code available!
  url: https://github.com/SaulBatman/SEIL
url_pdf: 'https://arxiv.org/pdf/2211.00194'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://saulbatman.github.io/project/seil/'
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/A9gJZWZO7Og'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - 'SEIL'

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<meta http-equiv = "refresh" content = " 0.01 ; url = https://saulbatman.github.io/SEIL_site/"/>
<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->


# Authors
Mingxi Jia, Dian Wang, Guanang Su, David Klee, Xupeng Zhu, Robin Walters, Robert Platt

# Abstract
In robotic manipulation, acquiring samples is extremely expensive because it often requires interacting with the real world.  Traditional image-level data augmentation has shown the potential to improve sample efficiency in various machine learning tasks. However, image-level data augmentation is insufficient for an imitation learning agent to learn good manipulation policies in a reasonable amount of demonstrations. We propose Simulation-augmented Equivariant Imitation Learning (SEIL), a method that combines a novel data augmentation strategy of supplementing expert trajectories with simulated transitions and an equivariant model that exploits the $\mathbf{O}(2)$ symmetry in robotic manipulation. Experimental evaluations demonstrate that our method can learn non-trivial manipulation tasks within ten demonstrations and outperforms the baselines with a significant margin.

# Approach
Please refer to the [project page](https://saulbatman.github.io/project/seil/) for more details!

# Citation
```
@article{jia2022seil,
  title={SEIL: Simulation-augmented Equivariant Imitation Learning},
  author={Jia, Mingxi; Wang, Dian; Su, Guanang; Klee, David; Zhu, Xupeng; Walters, Robin; Platt, Robert},
  journal={arXiv preprint arXiv:2211.00194},
  year={2022}
}
```