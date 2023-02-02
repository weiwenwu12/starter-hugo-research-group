---
title: 'Locally linear transform based three-dimensional gradient L0-norm minimization for spectral CT reconstruction'
authors:
  - Qian Wang
  - Weiwen Wu
  - Shiwo Deng
  - Yining Zhu
  - Hengyong Yu
author_notes:
  - 
  - 
  - 
  - 
  - 'communication'
#  - 'Equal contribution'
date: '2020-08-25T00:00:00Z'
doi: '10.1002/mp.14420'

# Schedule page publish date (NOT publication's date).
publishDate: '2020.08'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Purpose. Spectral computed tomography (CT) is proposed by extending the conventional CT along the energy dimension. One newly implementation is to employ an energy-discriminating photon counting detector (PCD), which can distinguish photon energy and divide a whole x-ray spectrum into several energy bins with appropriate post-processing steps. The state-of-the-art PCD-based spectral CT has superior energy resolution and material distinguishability, and it further has a great potential in both medical and industrial applications. To improve the reconstruction quality and decomposition accuracy, in this work, we propose an optimization-based spectral CT reconstruction method with an innovational sparsity constraint. Methods. We first employ a locally linear transform to the reconstructed channel images, and the structural similarity along the spectral dimension is effectively converted to a one-dimensional (1D) gradient sparsity. Then, combining the prior knowledge of piecewise constant in the spatial domain (e.g., a two-dimensional (2D) gradient sparsity feature), we unify both spectral and spatial dimensions and establish a joint three-dimensional (3D) gradient sparsity. In addition, we use the L<sub>0</sub> -norm to measure the proposed sparsity and incorporate it as a smoothness constraint to concretize a general optimization framework. Furthermore, we develop the corresponding iterative algorithm to solve the optimization problem.Results. Both visual results and quantitative indexes of numerical simulations and phantom experiments demonstrate the proposed method outperform the conventional filtered backprojection (FBP), total variation (TV), 2D L<sub>0</sub> -norm (L<sub>0</sub> ), and TV with low rank (TVLR)-based methods. From the image and ROI comparisons, we find the proposed method performs well in noise suppression, detail maintenance, and decomposition accuracy. However, the FBP suffers severe noise, the TV and L<sub>0</sub> are difficult to work consistently among different energy bins, and the TVLR fails to avoid gray value shift. The image quality assessments, such as peak signal-to-noise ratio (PSNR), normal mean absolute deviation (NMAD). and structural similarity (SSIM), also consistently indicate the proposed method can effectively removing noise and keeping fine structures in both channel-wise reconstructions and material decompositions.Conclusions. By employing a locally linear transform, the structural similarity among spectral channel images is converted to a 1D gradient sparsity and the gray value shift is effectively avoided when the difference measurement is minimized. The 3D L<sub>0</sub> -norm jointly and uniformly measures the gradient sparsity in both spectral and spatial dimensions. The cooperation of locally linear transform and 3D L<sub>0</sub> -norm well reinforces the global sparse features and keeps the correlation along spectral dimension without bringing gray-value distortions. The corresponding constraint optimization model is fast and stably solved by using an alternative direction technique. Both numerical simulations and phantom experiments confirm the superior performance of the proposed method in noise suppression, structure maintenance, and accurate decomposition.


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
