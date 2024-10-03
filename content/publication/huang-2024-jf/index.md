---
title: Augmenting Evolutionary Models with Structure-based Retrieval
authors:
- Yining Huang*
- Zuobai Zhang*
- Jian Tang
- Debora Susan Marks
- Pascal Notin
date: '2024-05-01'
publishDate: '2024-10-03T21:30:42.091443Z'
publication_types:
- paper-conference
publication: "*ICML'24 Workshop ML for Life and Material Science: From Theory to Industry
  Applications*"
abstract: Multiple Sequence Alignments (MSAs) are crucial in protein sequence analysis
  for identifying homologous proteins sharing a common evolutionary origin. However,
  traditional MSA search tools struggle to recover distantly related sequences that,
  despite low sequence similarity, exhibit high structural and functional resemblance—often
  missing in the so-called ‘midnight zone’ of protein similarity. To overcome these
  limitations, we propose the integration of structure similarity search tools to
  enhance the identification of homologous proteins. This approach utilizes Foldseek
  to search the AlphaFold database, aligning structurally similar proteins to construct
  Multiple Structure Alignments (MStructAs) alongside traditional MSAs. By combining
  these alignments, we develop family-specific generative models for protein fitness
  prediction, using diverse assays from the ProteinGym benchmarks. Our findings reveal
  that incorporating structure-based retrieval into MSAs significantly improves the
  performance of alignment-based methods, suggesting a robust hybrid retrieval strategy
  that harnesses both sequence and structure similarities.
---
