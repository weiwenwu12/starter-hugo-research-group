---
title: 'IMD-MTFC: Image-domain Material Decomposition via Material-image Tensor Factorization and Clustering for Spectral CT'
authors:
  - Shaoyu Wang
  - Ailong Cai
  - Weiwen Wu
  - Tao Zhang
  - Fenglin Liu
  - Hengyong Yu

author_notes:
  -
#  - 'Equal contribution'
#  - 'communication'
#  - 'Equal contribution'
date: '2023-01-06T00:00:00Z'
doi: '10.1109/TRPMS.2023.3234613'

# Schedule page publish date (NOT publication's date).
publishDate: '2023.01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: 'Spectral computed tomography (CT) provides multispectral X-ray information that can be used for quantitative material-specific imaging compared to the conventional CT. However, the low-count photon rate in a single energy bin may lead to highly noisy measurements with compromised material contrast and accuracy. Moreover, the complicated material decomposition process is an ill-posed inverse problem, which is sensitive to noise. In this work, we develop an image-domain material decomposition method via material-image tensor factorization and clustering (IMD-MTFC) for spectral CT to obtain high-precision material-specific images. Specifically, a set of image patches are extracted from the normalized material-specific image tensors decomposed by the direct inversion (DI). Then, each of them is clustered in a given nonlocal neighboring area to explore the nonlocal self-similarity of material-specific images. Furthermore, the low-rank regularized Kronecker-basis-representation tensor factorization is employed to incorporate the sparsity and redundant correlation across the material-specific images. The split-Bregman is employed to optimize the model by dividing it into several subproblems. The performance of our method is validated with numerically simulated mouse projections, physical phantom and preclinical experiments. The results confirm that the IMD-MTFC method outperforms other state-of-the-art competing methods.'

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
