---
title: 'Multi-Scale Representation Learning for Protein Fitness Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zuobai Zhang *
  - Pascal Notin *
  - Yining Huang
  - Aurélie Lozano
  - Vijil Chenthamarakshan
  - Debora Marks
  - Payel Das
  - Jian Tang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  
date: '2024-09-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems 37 (NeurIPS 2024)*
publication_short: "In *NeurIPS 2024: Conference on Neural Information Processing Systems*"

abstract: Designing novel functional proteins crucially depends on accurately modeling their fitness landscape. Given the limited availability of functional annotations from wet-lab experiments, previous methods have primarily relied on self-supervised models trained on vast, unlabeled protein sequence or structure datasets. While initial protein representation learning studies solely focused on either sequence or structural features, recent hybrid architectures have sought to merge these modalities to harness their respective strengths. However, these sequence-structure models have so far achieved only incremental improvements when compared to the leading sequence-only approaches, highlighting unresolved challenges effectively leveraging these modalities together. Moreover, the function of certain proteins is highly dependent on the granular aspects of their surface topology, which have been overlooked by prior models. To address these limitations, we introduce the Sequence-Structure-Surface Fitness (S3F) model — a novel multimodal representation learning framework that integrates protein features across several scales. Our approach combines sequence representations from a protein language model with Geometric Vector Perceptron networks encoding protein backbone and detailed surface topology. The proposed method achieves state-of-the-art fitness prediction on the ProteinGym benchmark encompassing 217 substitution deep mutational scanning assays, and provides insights into the determinants of protein function. Our code is at https://github.com/DeepGraphLearning/S3F.

# Summary. An optional shortened abstract.
summary: In this paper, we introduce the Sequence-Structure-Surface Fitness (S3F) model — a novel multimodal representation learning framework that integrates protein features across several scales.

tags:
  - Protein Engineering

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=kWMVzIdCEn'
url_code: 'https://github.com/DeepGraphLearning/S3F'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---