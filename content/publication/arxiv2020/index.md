---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'FAIRS: Soft Focus Generator and Attention for Robust Object Segmentation from Extreme Points'
subtitle: ''
summary: ''
authors:
- admin
- Prateek Munjal
- Ling Shao
- Shadab Khan
tags:
- deep learning
- computer vision
- extreme points
- segmentation

categories: []
date: '2020-04-04'
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
- '3'
abstract: "Semantic segmentation from user inputs has been actively studied to facilitate interactive segmentation for data annotation and other applications. Recent studies have shown that extreme points can be effectively used to encode user inputs. A heat map generated from the extreme points can be appended to the RGB image and input to the model for training. In this study, we present FAIRS -- a new approach to generate object segmentation from user inputs in the form of extreme points and corrective clicks. We propose a novel approach for effectively encoding the user input from extreme points and corrective clicks, in a novel and scalable manner that allows the network to work with a variable number of clicks, including corrective clicks for output refinement. We also integrate a dual attention module with our approach to increase the efficacy of the model in preferentially attending to the objects. We demonstrate that these additions help achieve significant improvements over state-of-the-art in dense object segmentation from user inputs, on multiple large-scale datasets. Through experiments, we demonstrate our method's ability to generate high-quality training data as well as its scalability in incorporating extreme points, guiding clicks, and corrective clicks in a principled manner."
publication: 'Arxiv'
url_pdf: https://arxiv.org/pdf/2004.02038.pdf
---
