---
title: "Do Deep Neural Network Solutions Form a Star Domain?"
authors:
- admin
- Alexander Rubinstein
- Ehsan Abbasnejad
- Seong Joon Oh
date: "2024-03-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Entezari et al. (2022) conjectured that neural network solution sets reachable via stochastic gradient descent (SGD) are convex, considering permutation invariances. This means that two independent solutions can be connected by a linear path with low loss, given one of them is appropriately permuted. However, current methods to test this theory often fail to eliminate loss barriers between two independent solutions (Ainsworth et al., 2022; Benzing et al., 2022). In this work, we conjecture that a more relaxed claim holds: the SGD solution set is a star domain that contains a star model that is linearly connected to all the other solutions via paths with low loss values, modulo permutations. We propose the Starlight algorithm that finds a star model of a given learning task. We validate our claim by showing that this star model is linearly connected with other independently found solutions. As an additional benefit of our study, we demonstrate better uncertainty estimates on Bayesian Model Averaging over the obtained star domain."

featured: false

url_pdf: https://arxiv.org/abs/2403.07968
url_code: 'https://github.com/aktsonthalia/starlight'

# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Star domain'
  focal_point: ""
  preview_only: false

---