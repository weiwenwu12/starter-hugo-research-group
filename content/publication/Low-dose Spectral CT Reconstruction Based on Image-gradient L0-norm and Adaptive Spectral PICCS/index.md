---
title: 'Low-dose Spectral CT Reconstruction Based on Image-gradient L0-norm and Adaptive Spectral PICCS'
authors:
  - Shaoyu Wang
  - admin
  - Jian Feng
  - Fenglin Liu
  - Hengyong Yu
#author_notes:
#  - 'communication'
#  - 'Equal contribution'
date: '2020-12-01T00:00:00Z'
doi: '10.1088/1361-6560/aba7cf'

# Schedule page publish date (NOT publication's date).
publishDate: '2020.12'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: The photon-counting detector based spectral computed tomography (CT) is promising for lesion detection, tissue characterization, and material decomposition. However, the lower signal-to-noise ratio within multi-energy projection dataset can result in poorly reconstructed image quality. Recently, as prior information, a high-quality spectral mean image was introduced into the prior image constrained compressed sensing (PICCS) framework to suppress noise, leading to spectral PICCS (SPICCS). In the original SPICCS model, the image gradient L1-norm is employed, and it can cause blurred edge structures in the reconstructed images. Encouraged by the advantages in edge preservation and finer structure recovering, the image gradient L0-norm was incorporated into the PICCS model. Furthermore, due to the difference of energy spectrum in different channels, a weighting factor is introduced and adaptively adjusted for different channel-wise images, leading to an L0-norm based adaptive SPICCS (L0-ASPICCS) algorithm for low-dose spectral CT reconstruction. The split-Bregman method is employed to minimize the objective function. Extensive numerical simulations and physical phantom experiments are performed to evaluate the proposed method. By comparing with the state-of-the-art algorithms, such as the simultaneous algebraic reconstruction technique, total variation minimization, and SPICCS, the advantages of our proposed method are demonstrated in terms of both qualitative and quantitative evaluation results.

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
