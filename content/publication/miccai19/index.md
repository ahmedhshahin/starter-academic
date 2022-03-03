---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Extreme Points Derived Confidence Map as a Cue for Class-Agnostic Interactive Segmentation Using Deep Neural Network'
subtitle: ''
summary: ''
authors:
- admin
- Shadab Khan
- Javier Villafruela
- Jianbing Shen
- Ling Shao
author_notes:
- "Equal contribution"
- "Equal contribution"

tags:
- deep learning
- extreme points
- interactive segmentation

categories: []
date: '2019-10-10'
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
abstract: 'To automate the process of segmenting an anatomy of interest, we can learn a model from previously annotated data. The learning-based approach uses annotations to train a model that tries to emulate the expert labeling on a new data set. While tremendous progress has been made using such approaches, labeling of medical images remains a time-consuming and expensive task. In this paper, we evaluate the utility of extreme points in learning to segment. Specifically, we propose a novel approach to compute a confidence map from extreme points that quantitatively encodes the priors derived from extreme points. We use the confidence map as a cue to train a deep neural network based on ResNet-101 and PSP module to develop a class-agnostic segmentation model that outperforms state-of-the-art method that employs extreme points as a cue. Further, we evaluate a realistic use-case by using our model to generate training data for supervised learning (U-Net) and observed that U-Net performs comparably when trained with either the generated data or the ground truth data. These findings suggest that models trained using cues can be used to generate reliable training data.'
publication: 'In International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)'
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-32245-8_8
url_code: https://github.com/ahmedshahin9/AssistedAnnotator
---
