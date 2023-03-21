
---
title: 'Kernel-based feature aggregation framework in point cloud networks'
authors:
  - Jianjia Zhang
  - Zhenxi Zhang
  - Lei Wang
  - Luping Zhou
  - Xiaocai Zhang
  - Mengting Liu
  - Weiwen Wu
author_notes:
  -
  -
  -
  -
  -
  -
  - 'communication'
#  - 'communication'
#  - 'Equal contribution'
date: '2023-02-20T00:00:00Z'
doi: '10.1016/j.patcog.2023.109439'

# Schedule page publish date (NOT publication's date).
publishDate: '2023.02'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Various effective deep networks have been developed for analysis of 3D point clouds. One key step in these networks is to aggregate the features of orderless points into a compact representation for the cloud. As a typical order-invariant aggregation method, max-pooling has been widely applied. However, while enjoying simplicity and high efficiency, max-pooling does not fully exploit the feature information since it not only ignores the non-maximum elements in each feature dimension but also neglects the interactions between different dimensions. These drawbacks of max-pooling motivate us to explore advanced feature aggregation methods for 3D point cloud analysis. The desired advanced method should be capable of modeling richer information between the point features than max-pooling, and, at the same time, it can readily replace max-pooling without the need to modify other parts of the existing network architecture. To this end, this paper proposes a novel kernel-based feature aggregation framework for 3D point cloud analysis for the first time. The proposed method effectively considers all the elements in each dimension and models the nonlinear interactions between feature dimensions as complementary information to max-pooling. In addition, it is a plug-in module that can be integrated to many common networks as a replacement of max-pooling. Comprehensive experiments are conducted to demonstrate the consistently superior performance and high generality of the proposed method over max-pooling. Specifically, the proposed kernel-based feature aggregation framework consistently improves the max-pooling with three representative backbones of PointNet, DGCNN and PCT across four 3D point cloud based analysis tasks, including supervised 3D object classification, 3D part segmentation, indoor semantic segmentation and one additional unsupervised place retrieval task. Especially, it shows remarkable performance improvement over max-pooling in the unsupervised retrieval task, demonstrating its advantage in forming 3D point cloud representation.


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
