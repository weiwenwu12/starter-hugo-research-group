---
title: 'Stabilizing deep tomographic reconstruction: Part A. Hybrid framework and experimental results'
authors:
  - admin
  - Dianlin Hu 
  - Hongming Shan
  - Shaoyu Wang
  - Wenxiang Cong
  - Chuang Niu
  - Pingkun Yan
  - Hengyong Yu*
  - Varut Vardhanabhuti
  - Ge Wang*
author_notes:
  -
  - 
  -  
  -   
  -    
  -     
  -    
  - 'communication'
  - 
  - 'communication'
#  - 'Equal contribution'
date: '2022-05-13T00:00:00Z'
doi: '10.1016/j.patter.2022.100474'

# Schedule page publish date (NOT publication's date).
publishDate: '2022.05'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: A recent PNAS paper reveals that several popular deep reconstruction networks are unstable. Specifically, three kinds of instabilities were reported, (1) strong image artefacts from tiny perturbations, (2) small features missed in a deeply reconstructed image, and (3) decreased imaging performance with increased input data. Here, we propose an analytic compressed iterative deep (ACID) framework to address this challenge. ACID synergizes a deep network trained on big data, kernel awareness from compressed sensing (CS)-inspired processing, and iterative refinement to minimize the data residual relative to real measurement. Our study demonstrates that the ACID reconstruction is accurate, is stable, and sheds light on the converging mechanism of the ACID iteration under a bounded relative error norm assumption. ACID not only stabilizes an unstable deep reconstruction network but also is resilient against adversarial attacks to the whole ACID workflow, being superior to classic sparsity-regularized reconstruction and eliminating the three kinds of instabilities.


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


