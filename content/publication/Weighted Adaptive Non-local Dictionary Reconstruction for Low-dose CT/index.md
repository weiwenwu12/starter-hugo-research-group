---
title: 'Weighted Adaptive Non-local Dictionary Reconstruction for Low-dose CT'
authors:
  -  Haijun Yu
  -  Shaoyu Wang
  -  Weiwen Wu[*]
  -  Changcheng Gong
  -  Zhenzhen Pi
  -  Fenglin Liu[*]
#author_notes:
#  - 'communication'
#  - 'Equal contribution'
date: '2021-03-21T00:00:00Z'
doi: '10.1016/j.sigpro.2020.107871'

# Schedule page publish date (NOT publication's date).
publishDate: '2021.03'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Low-dose computed tomography (LDCT) image reconstruction has been attracting much attention in medical applications because it can reduce the radiation risk. Sometimes, traditional methods are difficult to reconstruct satisfying image quality from low-dose projections. It is a challenging task for LDCT reconstruction with image quality improvement. Recently, various patch-based methods including dictionary learning were developed for LDCT and have achieved promising performance. Most of these patch-based methods assume that the noise follows the uniform Gaussian distribution, while noise is much more complex than Gaussian distribution in practice. In this study, considering the varying statistics of noise in different patches, we develop a weighted adaptive non-local dictionary (WAND) method for LDCT. Concretely, instead of establishing a complex model for the noise distribution in the whole image, we iteratively characterize the noise property in each local patch during the iteration processing. Besides, we also adaptively describe the different distributions of sparse coefficients of each patch to better characterize the sparsity priors of the image. The simulated and realistic experiments have shown that WAND can achieve better image quality in terms of small details preservation and noise suppression.


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
