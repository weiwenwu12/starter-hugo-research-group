---
title: 'Temporally downsampled cerebral CT perfusion image restoration using deep residual learning'
authors:
  - Haichen Zhu
  - Dan Tong
  - Lu Zhang
  - Shijie Wang
  - Weiwen Wu
  - Hui Tang
  - Yang Chen
  - Limin Luo
  - Jian Zhu
  - Baosheng Li
author_notes:
  - 
  - 
  - 
  - 
  - 
  - 
  - 'communication'
#  - 'Equal contribution'
date: '2019-10-31T00:00:00Z'
doi: '10.1007/s11548-019-02082-1'

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

abstract: Purpose. Acute ischemic stroke is one of the most causes of death all over the world. Onset to treatment time is critical in stroke diagnosis and treatment. Considering the time consumption and high price of MR imaging, CT perfusion (CTP) imaging is strongly recommended for acute stroke. However, too much CT radiation during CTP imaging may increase the risk of health problems. How to reduce CT radiation dose in CT perfusion imaging has drawn our great attention.Methods. In this study, the original 30-pass CTP images are downsampled to 15 passes in time sequence, which equals to 50% radiation dose reduction. Then, a residual deep convolutional neural network (DCNN) model is proposed to restore the downsampled 15-pass CTP images to 30 passes to calculate the parameters such as cerebral blood flow, cerebral blood volume, mean transit time, time to peak for stroke diagnosis and treatment. The deep restoration CNN is implemented simply and effectively with 16 successive convolutional layers which form a wide enough receptive field for input image data. 18 patients CTP images are employed as training set and the other six patients CTP images are treated as test dataset in this study.Results. Experiments demonstrate that our CNN can restore high-quality CTP images in terms of structural similarity index (SSIM) and peak signal-to-noise ratio (PSNR). The average SSIM and PSNR for test images are 0.981 and 56.25, and the SSIM and PSNR of regions of interest are 0.915 and 42.44, respectively, showing promising quantitative level. In addition, we compare the perfusion maps calculated from the restored images and from the original images, and the average perfusion results of them are extremely close. Areas of hypoperfusion of six test cases could be detected with comparable accuracy by radiologists.Conclusion. The trained model can restore the temporally downsampled 15-pass CTP to 30 passes very well. According to the contrast test, sufficient information cannot be restored with, e.g., simple interpolation method and deep convolutional generative adversarial network, but can be restored with the proposed CNN model. This method can be an optional way to reduce radiation dose during CTP imaging.

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
