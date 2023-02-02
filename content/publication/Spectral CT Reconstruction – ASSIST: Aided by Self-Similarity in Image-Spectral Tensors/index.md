---
title: 'Spectral CT Reconstruction – ASSIST: Aided by Self-Similarity in Image-Spectral Tensors'
authors:
  - Wenjun Xia
  - Weiwen Wu
  - Fenglin Liu
  - Hengyong Yu
  - Ge Wang
  - Yi Zhang
author_notes:
  -
  -
  -
  -
  -
  - 'communication'
#  - 'communication'
#  - 'Equal contribution'
date: '2019-03-10T00:00:00Z'
doi: '10.1109/TCI.2019.2904207'

# Schedule page publish date (NOT publication's date).
publishDate: '2019.03'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: 'Spectral computed tomography (CT) reconstructs multienergy images from data in different energy bins. However, these reconstructed images can be contaminated by noise due to the limited numbers of photons in the corresponding energy bins. In this paper, we propose a spectral CT reconstruction method aided by self-similarity in image-spectral tensors, which utilizes the selfsimilarity of patches in both spatial and spectral domains. Patches with similar structures identified by a joint spatial and spectral searching strategy form a basic tensor unit, and can be utilized to improve image quality. Specifically, each tensor is decomposed into a low-rank component and a sparse component, which respectively represent the stable structures and feature differences across different energy bins. The augmented Lagrange method is applied to optimize the proposed objective function. To validate the performance of the proposed method, several simulated clinical and real data experiments are performed. The qualitative and quantitative results demonstrate that the proposed method outperforms several representative state-of-the-art algorithms in terms of preserving image details and reducing artifacts.'
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
