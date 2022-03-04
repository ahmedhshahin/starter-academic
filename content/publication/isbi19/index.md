---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Deep Convolutional Encoder-Decoders with Aggregated Multi-Resolution Skip Connections for Skin Lesion Segmentation'
subtitle: ''
summary: ''
authors:
- admin
- Karim Amer
- Mustafa A. Elattar
tags:
- skin lesions
- segmentation
- melanoma
- convolutional neural networks
- pyramid pooling modules

categories: []
date: '2019-07-11'
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-02-28T16:59:59.637688Z'
publication_types:
- '1'
abstract: 'The prevalence of skin melanoma is rapidly increasing as well as the recorded death cases of its patients. Automatic image segmentation tools play an important role in providing standardized computer-assisted analysis for skin melanoma patients. Current state-of-the-art segmentation methods are based on fully convolutional neural networks, which utilize an encoder-decoder approach. However, these methods produce coarse segmentation masks due to the loss of location information during the encoding layers. Inspired by Pyramid Scene Parsing Network (PSP-Net), we propose an encoder-decoder model that utilizes pyramid pooling modules in the deep skip connections which aggregate the global context and compensate for the lost spatial information. We trained and validated our approach using ISIC 2018: Skin Lesion Analysis Towards Melanoma Detection grand challenge dataset. Our approach showed a validation accuracy with a Jaccard index of 0.837, which outperforms U-Net. We believe that with this reported reliable accuracy, this method can be introduced for clinical practice.'
publication: 'In International Symposium on Biomedical Imaging (ISBI)'
url_pdf: /publication/isbi19/paper.pdf
---
