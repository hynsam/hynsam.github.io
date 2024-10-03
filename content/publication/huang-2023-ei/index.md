---
title: An Energy Based Model for Incorporating Sequence Priors for Target-Specific
  Antibody Design
authors:
- Yining Huang*
- Steffanie Paul*
- Debora Marks
date: '2023-10-01'
publishDate: '2024-10-03T21:30:42.077968Z'
publication_types:
- paper-conference
publication: "*Neurips'23: Workshop on Generative AI and Biology*"
abstract: 'With the growing demand for antibody therapeutics, there is a great need
  for computational methods to accelerate antibody discovery and optimization. Advances
  in machine learning on graphs have been leveraged to develop generative models of
  antibody sequence and structure that condition on specific antigen epitopes. However,
  the data availability for training models on structure (∼5k antibody binding complexes
  Schneider et al. [2022]) is dwarfed by the amount of antibody sequence data available
  (> 550M sequences Olsen et al. [2022]) which have been used to train protein language
  models useful for antibody generation and optimization Here we motivate the combination
  of well-trained antibody sequence models and graph generative models on target structures
  to enhance their performance for target-conditioned antibody design. First, we present
  the results of an investigation into the sitewise design performance of popular
  target-conditioned design models. We show that target-conditioned models may not
  be incorporating target information into the generation of middle loop residues
  of the complementarity-determining region of the antibody sequence. Next, we propose
  an energy-based model framework designed to encourage a model to learn target-specific
  information by supplementing it with pre-trained marginal-sequence information.
  We present preliminary results on the development of this model and outline future
  steps to improve the model framework.  '
---
