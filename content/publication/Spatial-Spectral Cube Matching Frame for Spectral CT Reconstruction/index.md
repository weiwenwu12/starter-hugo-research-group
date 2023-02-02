---
title: 'Spatial-Spectral Cube Matching Frame for Spectral CT Reconstruction'
authors:
  - Weiwen Wu
  - Yanbo Zhang
  - Qian Wang
  - Fenglin Liu
  - Fulin Luo
  - Hengyong Yu
author_notes:
  -
  -
  -
  - 'communication'
  -
  - 'communication'
#  - 'communication'
#  - 'Equal contribution'
date: '2018-10-25T00:00:00Z'
doi: '10.1088/1361-6420/aad67b'

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

abstract: 'Spectral computed tomography (CT) reconstructs the same scanned object from projections of multiple narrow energy windows, and it can be used for material identification and decomposition. However, the multi-energy projection dataset has a lower signal-noise-ratio (SNR), resulting in poor reconstructed image quality. To address this thorny problem, we develop a spectral CT reconstruction method, namely spatial-spectral cube matching frame (SSCMF). This method is inspired by the following three facts: i) human body usually consists of two or three basic materials implying that the reconstructed spectral images have a strong sparsity; ii) the same basic material component in a single channel image has similar intensity and structures in local regions. Different material components within the same energy channel share similar structural information; iii) multi-energy projection datasets are collected from the subject by using different narrow energy windows, which means images reconstructed from different energy-channels share similar structures. To explore those information, we first establish a tensor cube matching frame (CMF) for a BM4D denoising procedure. Then, as a new regularizer, the CMF is introduced into a basic spectral CT reconstruction model, generating the SSCMF method. Because the SSCMF model contains an L<sub>0</sub> -norm minimization of 4D transform coefficients, an effective strategy is employed for optimization. Both numerical simulations and realistic preclinical mouse studies are performed. The results show that the SSCMF method outperforms the state-of-the-art algorithms, including the simultaneous algebraic reconstruction technique, total variation minimization, total variation plus low rank, and tensor dictionary learning.'

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
