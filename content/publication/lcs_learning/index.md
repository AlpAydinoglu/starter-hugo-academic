---
title: 'Learning Linear Complementarity Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wanxin Jin
  - admin
  - Mathew Halm
  - Michael Posa

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-02-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Learning for Dynamics and Control*
publication_short: In *L4DC*

abstract: This paper investigates the learning, or system identification, of a class of piecewise-affine dynamical systems known as linear complementarity systems (LCSs). We propose a violation-based loss which enables efficient learning of the LCS parameterization, without prior knowledge of the hybrid mode boundaries, using gradient-based methods. The proposed violation-based loss incorporates both dynamics prediction loss and a novel complementarity - violation loss. We show several properties attained by this loss formulation, including its differentiability, the efficient computation of first- and second-order derivatives, and its relationship to the traditional prediction loss, which strictly enforces complementarity. We apply this violation-based loss formulation to learn LCSs with tens of thousands of (potentially stiff) hybrid modes. The results demonstrate a state-of-the-art ability to identify piecewise-affine dynamics, outperforming the clustering-based piecewise-affine regression methods and the methods which must differentiate through non-smooth linear complementarity constraints.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://arxiv.org/pdf/2109.07076.pdf

url_pdf: 'https://proceedings.mlr.press/v168/jin22a/jin22a.pdf'
url_code: 'https://github.com/DAIRLab/Learning-LCS'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
