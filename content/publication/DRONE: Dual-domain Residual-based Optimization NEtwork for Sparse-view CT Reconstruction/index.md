---
title: 'DRONE: Dual-domain Residual-based Optimization NEtwork for Sparse-view CT Reconstruction'
authors:
  - Weiwen Wu
  - Dianlin Hu
  - Chuang Niu
  - Hengyong Yu*
  - Varut Vardhanabhuti* 
  - Ge Wang*
#author_notes:
#  - 'communication'
#  - 'Equal contribution'
date: '2021-05-06T00:00:00Z'
doi: '10.1109/TMI.2021.3078067'

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

abstract: Deep learning has attracted rapidly increasing attention in the field of tomographic image reconstruction, especially for CT, MRI, PET/SPECT, ultrasound and optical imaging. Among various topics, sparse-view CT remains a challenge which targets a decent image reconstruction from very few projections. To address this challenge, in this article we propose a Dual-domain Residual-based Optimization NEtwork (DRONE). DRONE consists of three modules respectively for embedding, refinement, and awareness. In the embedding module, a sparse sinogram is first extended. Then, sparse-view artifacts are effectively suppressed in the image domain. After that, the refinement module recovers image details in the residual data and image domains synergistically. Finally, the results from the embedding and refinement modules in the data and image domains are regularized for optimized image quality in the awareness module, which ensures the consistency between measurements and images with the kernel awareness of compressed sensing. The DRONE network is trained, validated, and tested on preclinical and clinical datasets, demonstrating its merits in edge preservation, feature recovery, and reconstruction accuracy.

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
