---
title: 'An Energy Based Model for Incorporating Sequence Priors for Target-Specific Antibody Design'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yining Huang *
  - Steffanie Paul *
  - Debora Marks

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ''

date: '2023-12-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In *NeurIPS 2023: Generative AI and Biology Workshop*"
publication_short: "In *NeurIPS 2023: GenBio Workshop*"

abstract: With the growing demand for antibody therapeutics, there is a great need for computational methods to accelerate antibody discovery and optimization. Advances in machine learning on graphs have been leveraged to develop generative models of antibody sequence and structure that condition on specific antigen epitopes. However, the data availability for training models on structure (∼5k antibody binding complexes Schneider et al. [2022]) is dwarfed by the amount of antibody sequence data available (> 550M sequences Olsen et al. [2022]) which have been used to train protein language models useful for antibody generation and optimization. Here we motivate the combination of well-trained antibody sequence models and graph generative models on target structures to enhance their performance for target-conditioned antibody design. First, we present the results of an investigation into the sitewise design performance of popular target-conditioned design models. We show that target-conditioned models may not be incorporating target information into the generation of middle loop residues of the complementarity-determining region of the antibody sequence. Next, we propose an energy-based model framework designed to encourage a model to learn target-specific information by supplementing it with pre-trained marginal-sequence information. We present preliminary results on the development of this model and outline future steps to improve the model framework.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Antibody Design

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=Ejw5zOOgLp'
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