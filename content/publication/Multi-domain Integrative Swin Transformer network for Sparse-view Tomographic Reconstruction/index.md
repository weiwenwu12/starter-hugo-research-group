---
title: 'Multi-domain Integrative Swin Transformer network for Sparse-view Tomographic Reconstruction'
authors:
  -  Jiayi Pan
  -  Heye Zhang
  -  Weifei Wu
  -  Zhifan Gao
  -  Weiwen Wu*
#author_notes:
#  - 'communication'
#  - 'Equal contribution'
date: '2022-06-10T00:00:00Z'
doi: '10.1016/j.patter.2022.100498'

# Schedule page publish date (NOT publication's date).
publishDate: '2022.06'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Decreasing projection views to a lower X-ray radiation dose usually leads to severe streak artifacts. To improve image quality from sparse-view data, a multi-domain integrative Swin transformer network (MIST-net) was developed and is reported in this article. First, MIST-net incorporated lavish domain features from data, residual data, image, and residual image using flexible network architectures, where a residual data and residual image sub-network was considered as a data consistency module to eliminate interpolation and reconstruction errors. Second, a trainable edge enhancement filter was incorporated to detect and protect image edges. Third, a high-quality reconstruction Swin transformer (i.e., Recformer) was designed to capture image global features. The experimental results on numerical and real cardiac clinical datasets with 48 views demonstrated that our proposed MIST-net provided better image quality with more small features and sharp edges than other competitors



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
