---
title: 'Non-local low-rank cube-based tensor factorization for Spectral CT reconstruction'
authors:
  - Weiwen Wu
  - Fenglin Liu
  - Yanbo Zhang
  - Qian Wang
  - Hengyong Yu
author_notes:
  -
  - 'communication'
  -
  -
  - 'communication'
#  - 'Equal contribution'
#  - 'communication'
#  - 'Equal contribution'
date: '2018-10-26T00:00:00Z'
doi: '10.1109/TMI.2018.2878226'

# Schedule page publish date (NOT publication's date).
publishDate: '2018.10'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Spectral computed tomography (CT) reconstructs material-dependent attenuation images with the projections of multiple narrow energy windows, it is meaningful for material identification and decomposition. Unfortunately, the multi-energy projection dataset always contains strong complicated noise and result in the projections has a lower signal-noise-ratio (SNR). Very recently, the spatial-spectral cube matching frame (SSCMF) was proposed to explore the non-local spatial-spectrum similarities for spectral CT. The method constructs such a group by clustering up a series of non-local spatial-spectrum cubes. The small size of spatial patch for such a group make SSCMF fails to encode the sparsity and low-rank properties. In addition, the hard-thresholding and collaboration filtering operation in the SSCMF are also rough to recover the image features and spatial edges. While for all steps are operated on 4-D group, we may not afford such huge computational and memory load in practical. To avoid the above limitation and further improve image quality, we first formulate a non-local cube-based tensor instead of the group to encode the sparsity and low-rank properties. Then, as a new regularizer, Kronecker-Basis-Representation (KBR) tensor factorization is employed into a basic spectral CT reconstruction model to enhance the ability of extracting image features and protecting spatial edges, generating the non-local low-rank cube-based tensor factorization (NLCTF) method. Finally, the split-Bregman strategy is adopted to solve the NLCTF model. Both numerical simulations and realistic preclinical mouse studies are performed to validate and assess the NLCTF algorithm. The results show that the NLCTF method outperforms the other competitors.

#tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
#url_pdf: http://arxiv.org/pdf/1512.04133v1
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
