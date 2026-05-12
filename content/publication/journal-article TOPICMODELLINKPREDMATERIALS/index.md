---
title: "Topic Modeling and Link-Prediction for Material Property Discovery"
authors:
- Ryan C. Barron
- Maksim E. Eren
- Valentin Stanev
- Cynthia Matuszek
- Boian S. Alexandrov
date: "2025-01-01T00:00:00Z"
doi: "10.1145/3704268.3748680"
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]
# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2025 ACM Symposium on Document Engineering*"
publication_short: ""
abstract: Link prediction is a key network analysis technique that infers missing or future relations between nodes in a graph, based on observed patterns of connectivity. Scientific literature networks and knowledge graphs are typically large, sparse, and noisy, and often contain missing links, potential but unobserved connections, between concepts, entities, or methods. Here, we present an AI-driven hierarchical link prediction framework that integrates matrix factorization to infer hidden associations and steer discovery in complex material domains. Our method combines Hierarchical Nonnegative Matrix Factorization (HNMFk), Boolean matrix factorization (BNMFk) with automatic model selection. These discrete factors are then fused with Logistic matrix factorization (LMF), we use to construct a three-level topic tree from a 46,862-document corpus focused on 73 transition-metal dichalcogenides (TMDs). This class of materials has been studied in a variety of physics fields and has a multitude of current and potential applications.An ensemble BNMFk + LMF approach fuses discrete interpretability with probabilistic scoring. The resulting HNMFk clusters map each material onto coherent research themes, such as superconductivity, energy storage, and tribology, and highlight missing or weakly connected links between topics and materials, suggesting novel hypotheses for cross-disciplinary exploration. We validate our method by removing publications about superconductivity in well-known superconductors, and demonstrate that the model correctly predicts their association with the superconducting TMD clusters. This highlights the ability of the method to find hidden connections in a graph of material to latent topic associations built from scientific literature. This is especially useful when examining a diverse corpus of scientific documents covering the same class of phenomena or materials but originating from distinct communities and perspectives. The inferred links generating new hypotheses, produced by our method, are exposed through an interactive Streamlit dashboard, designed for scientific discovery.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
# tags:
# - Source Themes
# featured: false
# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1145/3704268.3748680'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
# url_slides: './'
url_source: ''
url_video: ''
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false
# Associated Projects (optional).
projects: []
# Slides (optional).
# slides: example
---
<!-- {%/* callout note */%}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{%/* /callout */%}
Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
