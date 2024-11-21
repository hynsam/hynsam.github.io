---
title: 'Augmenting Evolutionary Models with Structure-based Retrieval'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yining Huang *
  - Zuobai Zhang *
  - Jian Tang
  - Debora Susan Marks
  - Pascal Notin


# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ''
  - ''
  - ''

date: '2024-07-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In *ICML 2024: ML for Life and Material Science Workshop*"
publication_short: "In *ICML 2024: ML4LMS Workshop*"

abstract: Multiple Sequence Alignments (MSAs) are crucial in protein sequence analysis for identifying homologous proteins sharing a common evolutionary origin. However, traditional MSA search tools struggle to recover distantly related sequences that, despite low sequence similarity, exhibit high structural and functional resemblance—often missing in the so-called ‘midnight zone’ of protein similarity. To overcome these limitations, we propose the integration of structure similarity search tools to enhance the identification of homologous proteins. This approach utilizes Foldseek to search the AlphaFold database, aligning structurally similar proteins to construct Multiple Structure Alignments (MStructAs) alongside traditional MSAs. By combining these alignments, we develop family-specific generative models for protein fitness prediction, using diverse assays from the ProteinGym benchmarks. Our findings reveal that incorporating structure-based retrieval into MSAs significantly improves the performance of alignment-based methods, suggesting a robust hybrid retrieval strategy that harnesses both sequence and structure similarities.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Protein Engineering

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=rTJL3eujta'
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