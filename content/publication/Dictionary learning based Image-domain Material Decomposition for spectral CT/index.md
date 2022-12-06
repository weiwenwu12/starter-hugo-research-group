---
title: 'Dictionary learning based Image-domain Material Decomposition for spectral CT'
authors:
  - admin
  - Haijun Yu
  - Peijun Chen
  - Fulin Luo
  - Fenglin Liu
  - Qian Wang
  - Yining Zhu
  - Yanbo Zhang
  - Jian Feng
  - Hengyong Yu
author_notes:
  - 
  - 
  - 
  - 
  - 'communication'
  - 
  - 
  - 
  - 
  - 'communication'
#  - 'Equal contribution'
date: '2020-05-26T00:00:00Z'
doi: '10.1109/TRPMS.2020.2997880'

# Schedule page publish date (NOT publication's date).
publishDate: '2020.05'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: The spectral computed tomography (CT) has huge advantages by providing accurate material information. Unfortunately, due to the instability or overdetermination of the material decomposition model, the accuracy of material decomposition can be compromised in practice. Very recently, the dictionary learning-based image-domain material decomposition (DLIMD) can obtain high accuracy for material decompositions from reconstructed spectral CT images. This method can explore the correlation of material components to some extent by training a unified dictionary from all material images. In addition, the dictionary learning-based prior as a penalty is applied on material components independently, and many parameters would be carefully elaborated in practice. Because the concentration of contrast agent in clinical applications is low, it can result in data inconsistency for dictionary-based representation during the iteration process. To avoid the aforementioned limitations and further improve the accuracy of materials, we first construct a generalized DLIMD (GDLIMD) model. Then, the material tensor image is unfolded along the mode-1 to enhance the correlation of different materials. Finally, to avoid the data inconsistency of low iodine contrast, a normalization strategy is employed. Both physical phantom and tissue-synthetic phantom experiments demonstrate the proposed GDLIMD method outperforms the DLIMD and direct inversion (DI) methods.

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
