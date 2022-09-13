---
title: 'Stabilization of Complementarity Systems via Contact-Aware Controllers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Philip Sieg
  - Victor M. Preciado
  - Michael Posa

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Robotics*
publication_short: In *TRO* <span style="color:green"> **(Best Paper Finalist, TC on Model-Based Optimization for Robotics)** </span>

abstract: We propose a control framework which can utilize tactile information by exploiting the complementarity structure of contact dynamics. Since many robotic tasks, like manipulation and locomotion, are fundamentally based in making and breaking contact with the environment, state-of-the-art control policies struggle to deal with the hybrid nature of multi-contact motion. Such controllers often rely heavily upon heuristics or, due to the combinatorial structure in the dynamics, are unsuitable for real-time control. Principled deployment of tactile sensors offers a promising mechanism for stable and robust control, but modern approaches often use this data in an ad hoc manner, for instance to guide guarded moves. This framework can close the loop on tactile sensors and it is non-combinatorial, enabling optimization algorithms to automatically synthesize provably stable control policies. We demonstrate this approach on multiple numerical examples, including quasi-static friction problems and a high dimensional problem with ten contacts. We also validate our results on an experimental setup and show the effectiveness of the proposed method on an underactuated multi-contact system.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2109.07076.pdf

url_pdf: 'https://arxiv.org/pdf/2008.02104.pdf'
url_code: 'https://github.com/AlpAydinoglu/cdesign'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/fZiJh7coMXc'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ''


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
