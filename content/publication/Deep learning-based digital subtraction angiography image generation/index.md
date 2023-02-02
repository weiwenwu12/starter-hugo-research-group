---
title: 'Deep learning-based digital subtraction angiography image generation'
authors:
  -  Yufeng Gao
  -  Yu Song
  -  Xiangrui Yin
  -  Weiwen Wu
  -  Lu Zhang
  -  Yang Chen
  -  Wanyin Shi
author_notes:
  -
  -
  -
  -
  -
  - 'communication'
#  - 'communication'
#  - 'Equal contribution'
date: '2019-10-14T00:00:00Z'
doi: '10.1007/s11548-019-02040-x'

# Schedule page publish date (NOT publication's date).
publishDate: '2019.10'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: 'Purpose: Digital subtraction angiography (DSA) is a powerful technique for diagnosing cardiovascular disease. In order to avoid image artifacts caused by patient movement during imaging, we take deep learning-based methods to generate DSA image from single live image without the mask image.
Methods: Conventional clinical DSA datasets are acquired with a standard injection protocol. More than 600 sequences obtained from more than 100 subjects were used for head and leg experiments. Here, the residual dense block (RDB) is adopted to generate DSA image from single live image directly, and RDBs can extract high-level features by dense connected layers. To obtain better vessel details, a supervised generative adversarial network strategy is also used in the training stage.
Results: The human head and leg experiments show that the deep learning methods can generate DSA image from single live image, and our method can do better than other models. Specifically, the DSA image generating with our method contains less artifact and is suitable for diagnosis. We use metrics including PSNR, SSIM and FSIM, which can reach 23.731, 0.877 and 0.8946 on the head dataset and 26.555, 0.870 and 0.9284 on the leg dataset.
Conclusions: The experiment results show the model can extract the vessels from the single live image, thus avoiding the image artifacts obtained by subtracting the live image and the mask image. And our method has a better performance than other methods we have tried on this task.'

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
