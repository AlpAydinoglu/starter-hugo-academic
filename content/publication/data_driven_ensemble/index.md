---
title: 'Data-driven Stabilization of Nonlinear Systems via Tree-Based Ensemble Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Cassiano O. Becker
  - Victor M. Preciado

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2019-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Decision and Control*
publication_short: In *CDC*

abstract: We present an approach for the stabilization of an unknown nonlinear dynamical system when only data samples from its dynamics are available. Our approach is based on approximating the system dynamics with an ensemble of regression trees. As a result of our approximation, we obtain a model that is a piecewise-affine dynamical system defined over a partition of the state space. In general, the stabilization of the resulting piece-wise affine system requires, in the worst case, solving an exponential number of linear matrix inequalities (with respect to the state dimension). To overcome this computational limitation, we propose a stabilization procedure having a complexity that grows linearly with the number of partitions. This stabilization procedure explicitly exploits the fact that our model is described via an ensemble of regression trees. In addition, we derive probabilistic conditions under which the stabilization of the model implies that the original nonlinear system is also stabilized. Finally, we validate our approach by performing numerical simulations over trajectories of two coupled Van der Pol oscillators.


# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2109.07076.pdf

url_pdf: 'https://arxiv.org/pdf/1909.11221.pdf'
url_code: 'https://github.com/AlpAydinoglu/cdesign'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/0ey439i4Jbk'

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
