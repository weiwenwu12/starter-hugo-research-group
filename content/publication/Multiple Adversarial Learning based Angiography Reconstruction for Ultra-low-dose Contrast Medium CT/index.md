---
title: 'Multiple Adversarial Learning based Angiography Reconstruction for Ultra-low-dose Contrast Medium CT'
authors:
  - admin
  - Hengyong Yu
  - Fenglin Liu
  - Jianjia Zhang
  - Varut Vardhanabhuti
#author_notes:
#  - 'communication'
#  - 'Equal contribution'
date: '2022-08-01T00:00:00Z'
doi: '10.1109/JBHI.2022.3213595'

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

abstract: Iodinated contrast medium (ICM) dose reduction is beneficial for decreasing potential health risk to renal-insufficiency patients in CT scanning. Due to the lowintensity vessel in ultra-low-dose-ICM CT angiography, it cannot provide clinical diagnosis of vascular diseases. Angiography reconstruction for ultra-low-dose-ICM CT can enhance vascular intensity for directly vascular diseases diagnosis. However, the angiography reconstruction is challenging since patient individual differences and vascular disease diversity. In this paper, we propose a Multiple Adversarial Learning based Angiography Reconstruction (i.e., MALAR) framework to enhance vascular intensity. Specifically, a bilateral learning mechanism is developed for mapping a relationship between source and target domains rather than the image-to-image mapping. Then, a dual correlation constraint is introduced to characterize both distribution uniformity from across-domain features and sample inconsistency with domain simultaneously. Finally, an adaptive fusion module by combining multiscale information and long-range interactive dependency is explored to alleviate the interference of high-noise metal. Experiments are performed on CT sequences with different ICM doses. Quantitative results based on multiple metrics demonstrate the effectiveness of our MALAR on angiography reconstruction. Qualitative assessments by radiographers confirm the potential of our MALAR for the clinical diagnosis of vascular diseases. The code and model are available at https://github.com/HIC-SYSU/MALAR.


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

