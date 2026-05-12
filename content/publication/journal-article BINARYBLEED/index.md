---
title: "Binary Bleed: Fast Distributed and Parallel Method for Automatic Model Selection"
authors:
- Ryan Barron
- Maksim E. Eren
- Manish Bhattarai
- Ismael Boureima
- Cynthia Matuszek
- Boian S. Alexandrov
date: "2024-01-01T00:00:00Z"
doi: "10.1109/HPEC62836.2024.10938517"
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]
# Publication name and optional abbreviated publication name.
publication: "*2024 IEEE High Performance Extreme Computing Conference (HPEC)*"
publication_short: ""
abstract: In several Machine Learning (ML) clustering and dimensionality reduction approaches, such as non-negative ma- trix factorization (NMF), RESCAL, and K-Means clustering, users must select a hyper-parameter k to define the number of clusters or components that yield an ideal separation of samples or clean clusters. This selection, while difficult, is crucial to avoid overfitting or underfitting the data. Several ML applications use scoring methods (e.g., Silhouette and Davies Boulding scores) to evaluate the cluster pattern stability for a specific k. The score is calculated for different trials over a range of k, and the ideal k is heuristically selected as the value before the model starts overfit-ting, indicated by a drop or increase in the score resembling an elbow curve plot. While the grid-search method can be used to accurately find a good k value, visiting a range of k can become time-consuming and computationally resource-intensive. In this paper, we introduce the Binary Bleed method based on binary search, which significantly reduces the k search space for these grid-search ML algorithms by truncating the target k values from the search space using a heuristic with thresholding over the scores. Binary Bleed is designed to work with single-node serial, single-node multi-processing, and distributed computing resources. In our experiments, we demonstrate the reduced search space gain over a naive sequential search of the ideal k and the accuracy of the Binary Bleed in identifying the correct k for NMFk, K-Means pyDNMFk, and pyDRESCALk with Silhouette and Davies Boulding scores. We make our implementation of Binary Bleed for the NMF algorithm available on GitHub.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
# tags:
# - Source Themes
# featured: false
# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1109/HPEC62836.2024.10938517'
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
