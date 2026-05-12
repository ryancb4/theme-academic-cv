---
title: "HEAL}: Hierarchical Embedding Alignment Loss for Improved Retrieval and Representation Learning"
authors:
- Manish Bhattarai
- Ryan Barron
- Maksim Eren
- Minh Vu
- Vesselin Grantcharov
- Ismael Boureima
- Valentin Stanev
- Cynthia Matuszek
- Vladimir Valtchinov
- Kim Rasmussen
- Boian Alexandrov
date: "2025-01-01T00:00:00Z"
doi: "10.18653/v1/2025.knowledgenlp-1.19"
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]
# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 4th International Workshop on Knowledge-Augmented Methods for Natural Language Processing*"
publication_short: ""
abstract: Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by integrating external document retrieval to provide domain-specific or up-to-date knowledge. The effectiveness of RAG depends on the relevance of retrieved documents, which is influenced by the semantic alignment of embeddings with the domain{'}s specialized content. Although full fine-tuning can align language models to specific domains, it is computationally intensive and demands substantial data. This paper introduces Hierarchical Embedding Alignment Loss (HEAL), a novel method that leverages hierarchical fuzzy clustering with matrix factorization within contrastive learning to efficiently align LLM embeddings with domain-specific content. HEAL computes level/depth-wise contrastive losses and incorporates hierarchical penalties to align embeddings with the underlying relationships in label hierarchies. This approach enhances retrieval relevance and document classification, effectively reducing hallucinations in LLM outputs. In our experiments, we benchmark and evaluate HEAL across diverse domains, including Healthcare, Material Science, Cyber-security, and Applied Maths.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
# tags:
# - Source Themes
# featured: false
# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.18653/v1/2025.knowledgenlp-1.19'
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
