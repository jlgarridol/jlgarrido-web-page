---
title: "Semi-supervised classification with pairwise constraints: A case study on animal identification from video"
authors:
- Ludmila I. Kuncheva
- admin
- Ismael Ramos-Pérez
- Samuel L. Hennessey
- Juan J. Rodríguez
author_notes: 
-
-
-
-
- Corresponding author
date: "2024-04-01"
doi: "10.1016/j.inffus.2023.102188"

# Publication type.
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Information Fusion* 104: 102188"
publication_short: "Inf Fusion"

abstract: "Mainstream semi-supervised classification assumes that part of the available data are labelled. Here we assume that, in addition to the labels, we have pairwise constraints on the unlabelled data. Each constraint links two instances, and is one of Must Link (ML, belong to the same class) or Cannot Link (CL, belong to different classes). We propose an approach that uses the labelled data to train a classifier and then applies the ML and CL constraints in subsequent labelling. In our approach, a set of instances are labelled at the same time. Our case study is on animal re-identification. The dataset consists of five free-camera video clips of animals (koi fish, pigeons and pigs), annotated with bounding boxes and animal identities. The proposed approach combines the representations or classifiers predictions from the bounding boxes of consecutive frames. We demonstrate that our approach outperforms standard classifiers, constrained clustering, as well as inductive and transductive semi-supervised learning, using five feature representations."
summary: "This study introduces a novel semi-supervised classification method that incorporates automatically generated pairwise constraints—Must Link (ML) and Cannot Link (CL)—from video data to improve animal re-identification accuracy. By applying these constraints frame-by-frame and combining them with standard classifiers, the proposed methods significantly outperform traditional classifiers, constrained clustering, and other semi-supervised learning approaches across five animal video datasets."

tags: [Animal re-identification, Classification, Computer vision, Semi-supervised learning]
featured: true

url_pdf: "https://www.sciencedirect.com/science/article/pii/S1566253523005043/pdfft?md5=7f6c6bb13b4c98fcce8c8a05bd1e696f&pid=1-s2.0-S1566253523005043-main.pdf"
url_code: "https://github.com/admirable-ubu/semi-supervised-animal-re-identification"
url_dataset: "https://doi.org/10.5281/zenodo.7322820"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
