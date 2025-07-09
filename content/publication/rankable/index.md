---
title: "On the rankability of visual embeddings"
authors:
- admin
- Arnas Uselis
- Seong Joon Oh
date: "2025-07-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: arXiv pre-print
publication_short: ""

abstract: "We study whether visual embedding models capture continuous, ordinal attributes along linear directions, which we term _rank axes_. We define a model as _rankable_ for an attribute if projecting embeddings onto such an axis preserves the attribute's order. Across 7 popular encoders and 9 datasets with attributes like age, crowd count, head pose, aesthetics, and recency, we find that many embeddings are inherently rankable. Surprisingly, a small number of samples, or even just two extreme examples, often suffice to recover meaningful rank axes, without full-scale supervision. These findings open up new use cases for image ranking in vector databases and motivate further study into the structure and learning of rankable embeddings."

featured: false

url_pdf: https://arxiv.org/abs/2507.03683
url_code: 'https://github.com/aktsonthalia/rankable-vision-embeddings'

# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Star domain'
  focal_point: ""
  preview_only: false

---