---
title: "Trustworthy Domain-Specific AI for Structured Knowledge Retrieval and Reasoning"
authors:
- Ryan C. Barron
date: "2025-01-01T00:00:00Z"
doi: ""
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]
# Publication name and optional abbreviated publication name.
publication: "*ProQuest Dissertations and Theses*"
publication_short: ""
abstract: This dissertation presents a production-ready architecture that addresses the challenge of transforming vast volumes of unstructured, domain-specific text into structured and actionable knowledge representations that enable both retrieval and reasoning. Traditional pipelines for knowledge discovery remain fragmented, relying on brittle keyword extraction, ad hoc topic modeling, and disconnected reasoning modules. In response, this work proposes an integrated architecture that unifies semi-automatic corpus curation, semantic structuring, and retrieval systems into a scalable, interpretable pipeline. The research introduces two novel techniques, Binary Bleed, an adapted binary search method that significantly reduces low-rank search complexity, particularly useful in Non-negative Matrix Factorization (NMF), and based on it, Hierarchical NMF (HNMF) with automatic selection of the number of latent features (HNMFk), a depth-adaptive topic modeling method that produces interpretable, Subject Matter Expert (SME) guided taxonomies. These representations are simultaneously instantiated as a typed, structured-based Knowledge Graph and a semantically aligned Vector Store, which includes the extracted latent features and is synchronized via an event-driven substrate. To perform contextual information access, the research introduces a new form of Retrieval-Augmented Generation (RAG), named Tensor-Structured RAG (T-SRAG), capable of dynamically routing queries across retrieval paths. The system improves semantic fidelity and reduces hallucinations by incorporating a contrastive loss alignment technique that maps both document and query embeddings to hierarchical topic structures. Beyond retrieval, the framework introduces a new Artificial Intelligence (AI) reasoning by identifying and completing missing links in the knowledge graph through tensor-based link prediction. This enables inferential responses grounded in citation structure rather than generative hallucination from a Large Language Model (LLM). The presented applications show validation across cybersecurity, law, materials science, and healthcare, demonstrating significant improvements in retrieval precision, early trend detection, as well as AI hypotheses generation and hallucination mitigation at scale. Overall, the dissertation delivers a new deployable, modular foundation for domain-specific, trustworthy AI systems capable of both retrieving and reasoning over structured knowledge.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
# tags:
# - Source Themes
# featured: false
# links:
# - name: ""
#   url: ""
url_pdf: ''
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
