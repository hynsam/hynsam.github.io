---
title: 'How to Go With the Flow: an Analysis of Flow Matching Molecular Docking Performance With Priors of Varying Information Content'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dina A. Sharon *
  - Yining Huang *
  - Motolani Oyewole
  - Sammy Mustafa

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ''
  - ''

date: '2024-04-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In *ICLR 2024: Generative and Experimental Perspectives for Biomolecular Design Workshop*"
publication_short: "In *ICLR 2024: GEM Workshop*"

abstract: Predicting molecular docking poses with flow matching algorithms represents both a promising opportunity and a challenging task. Recently, a flow matching algorithm, HarmonicFlow, has been reported to yield encouraging molecular docking results. The method employs a harmonic prior to make initial predictions. In light of the importance of long-range information for molecular structure, we sought to understand the consequences of the harmonic prior for docking results. We found that the most-recent-at-the-time-of-our-initial-writing method often provides compressed poses, and there is some correlation between this compression and docking performance (though results changed with a newer version). We retrained the method to use a prior incorporating information from a molecular conformation, to determine whether a prior with more comprehensive structural detail would provide better performance. Performance did not improve with this new prior, whether the exact long-range information was used or whether noise was added. This finding suggests that further prior development is unlikely to improve performance, implying perhaps advances in the neural network could be another avenue to consider. Therefore, we discuss some possible ways to leverage local and long-range structural information in the neural network. By understanding chemical features associated with docking performance, investigating results with a more chemically-informed prior, and suggesting possible neural network advances, this work enhances the molecular machine learning community's grasp of the repertoire of opportunities available to improve docking performance.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Flow Matching
  - Docking

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=FGwGt9XWO4'
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