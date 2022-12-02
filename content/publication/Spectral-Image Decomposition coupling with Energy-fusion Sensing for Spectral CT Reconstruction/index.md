---
title: 'Spectral-Image Decomposition coupling with Energy-fusion Sensing for Spectral CT Reconstruction'
authors:
  - Shaoyu Wang
  - Haijun Yu
  - Yarui Xi
  - Changcheng Gong
  - admin"*"
  - Fenglin Liu*
#author_notes:
#  - 'communication'
#  - 'Equal contribution'
date: '2021-05-10T00:00:00Z'
doi: '10.1109/TIM.2021.3078555'

# Schedule page publish date (NOT publication's date).
publishDate: '2021.05'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Spectral-computed tomography (CT) has been demonstrating its great advantages in lesion detection, tissue characterization, and material decomposition. However, the quality of images is often significantly corrupted with various noises, which brings a great challenge for its applications. Because the channel-wise images from different energy interval share similar structure and physical message, the spatial sparsity, global correlation across the spectrum (GCS), and nonlocal self-similarity (NSS) as three important characteristics are employed to spectral CT reconstruction. In this study, we propose a spectral-image decomposition with energy-fusion sensing (SIDES) reconstruction method, which encourages to obtain better quality spectral images and material decomposition results by establishing a unified tensor decomposition model. First, considering the noise distribution in channel-wise and the difference of linear attenuation coefficients within channel-cross, an adaptive weighted full-spectrum prior image as additional supervised information is incorporated to formulate a new weighted prior image-based tensor. Cooperating with original image tensor, they fully explore the spatial sparsity, GCS, and NSS properties. Then, we formulate nonlocal similar patch-based tensor groups to encode the NSS property from image-domain and residual-image-domain (which is expanded by prior-image and image-self). Next, low-rank regularized Tucker tensor decomposition is employed to fully explore the intrinsic knowledge with the help of prior-image supervision. Finally, the relaxed convex optimization model is optimized by dividing reconstruction model into several subproblem using split-Bregman method. Numerical simulations and real experiments are designed to validate and evaluate the SIDES method and the results demonstrate that the SIDES reconstruction outperforms the state-of-the-art.


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
