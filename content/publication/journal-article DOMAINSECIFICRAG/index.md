---
title: "Domain-Specific Retrieval-Augmented Generation Using Vector Stores, Knowledge Graphs, and Tensor Factorization"
authors:
- Ryan C. Barron
- Vesselin Grantcharov
- Selma Wanna
- Maksim E. Eren
- Manish Bhattarai
- Nicholas Solovyev
- George Tompkins
- Charles Nicholas
- Kim Ø. Rasmussen
- Cynthia Matuszek
- Boian S. Alexandrov
date: "2024-01-01T00:00:00Z"
doi: "10.1109/ICMLA61862.2024.00258"
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]
# Publication name and optional abbreviated publication name.
publication: "*2024 International Conference on Machine Learning and Applications (ICMLA)*"
publication_short: ""
abstract:  | 
    Large Language Models (LLMs) are pre-trained on large-scale corpora and excel in numerous general natural language processing (NLP) tasks, such as question answering (QA). Despite their advanced language capabilities, when it comes to domain-specific and knowledge-intensive tasks, LLMs suffer from hallucinations, knowledge cut-offs, and lack of knowledge attributions. Additionally, fine tuning LLMs’ intrinsic knowledge to highly specific domains is an expensive and time consuming process. The retrieval-augmented generation (RAG) process has recently emerged as a method capable of optimization of LLM responses, by referencing them to a predetermined ontology. It was shown that using a Knowledge Graph (KG) ontology for RAG improves the QA accuracy, by taking into account relevant sub-graphs that preserve the information in a structured manner. In this paper, we introduce SMART-SLIC, a highly domain- specific LLM framework, that integrates RAG with KG and a vector store (VS) that store factual domain specific information. Importantly, to avoid hallucinations in the KG, we build these highly domain-specific KGs and VSs without the use of LLMs, but via NLP, data mining, and nonnegative tensor factorization with automatic model selection. Pairing our RAG with a domain- specific: (i) KG (containing structured information), and (ii) VS (containing unstructured information) enables the development of domain-specific chat-bots that attribute the source of information, mitigate hallucinations, lessen the need for fine-tuning, and excel in highly domain-specific question answering tasks. We pair SMART-SLIC with chain-of-thought prompting agents. The framework is designed to be generalizable to adapt to any specific or specialized domain. In this paper, we demonstrate the question answering capabilities of our framework on a corpus of scientific publications on malware analysis and anomaly detection.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
# tags:
# - Source Themes
# featured: false
# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1109/ICMLA61862.2024.00258'
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
