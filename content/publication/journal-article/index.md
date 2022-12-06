---
title: 'Spectral CT reconstruction via Spectral-Image Tensor and Bidirectional Image-gradient minimization'
authors:
  - admin
  - Hengyong Yu
  - Lieza Vanden Broeke
  - Fenglin Liu
  - Jianjia Zhang
  - Varut Vardhanabhuti
author_notes:
  - 
  - 
  - 
  - 
  - 'communication'
  - 'communication'
#  - 'Equal contribution'
date: '2022-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.compbiomed.2022.106080'

# Schedule page publish date (NOT publication's date).
publishDate: '2022.09'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: It is challenging to obtain good image quality in spectral computed tomography (CT) as the photon-number for the photon-counting detectors is limited for each narrow energy bin. This results in a lower signal to noise ratio (SNR) for the projections. To handle this issue, we first formulate the weight bidirectional image gradient with L0-norm constraint of spectral CT image. Then, as a new regularizer, bidirectional image gradient with L0-norm constraint is introduced into the tensor decomposition model, generating the Spectral-Image Tensor and Bidirectional Image-gradient Minimization (SITBIM) algorithm. Finally, the split-Bregman method is employed to optimize the proposed SITBIM mathematical model. The experiments on the numerical mouse phantom and real mouse experiments are designed to validate and evaluate the SITBIM method. The results demonstrate that the SITBIM can outperform other state-of-the-art methods (including TVM, TV + LR, SSCMF and NLCTF).
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
