---
title: "1.58-b FeFET-Based Ternary Neural Networks: Achieving Robust Compute-In-Memory With Weight-Input Transformations"
authors:
- Imtiaz Ahmed
- Akul Malhotra
- admin
- Sumeet K Gupta

author_notes:

date: "2025-10-14T00:00:00Z"
doi: "https://doi.org/10.1109/JXCDC.2025.3621160"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-25-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal on Exploratory Solid-State Computational Devices and Circuits"
publication_short: "IEEE JxCDC"

abstract: >-
   Ternary weight neural networks (TWNs), with weights quantized to three states, have emerged as promising solutions for resource-constrained edge artificial intelligence (AI) platforms due to their high energy efficiency with acceptable inference accuracy. Further energy savings can be achieved with TWN accelerators utilizing techniques such as compute-in-memory (CiM) and scalable technologies such as ferroelectric transistors (FeFETs). Although the standard 1T-FeFET CiM design offers high density with its compactness and multilevel storage, its CiM performance in deeply scaled technology is prone to hardware nonidealities. This requires design modifications such as 2T-FeFET bitcells, offering high CiM robustness due to their differential nature at the cost of area. In this work, we conduct a design space exploration of FeFET-based TWN-CiM solutions. By utilizing FeFETs storing 1 bit (two levels) and 1.58 ( log23 ) bits (three levels), we design three flavors of ternary CiM arrays: 1) 1T design based on 1.58-b FeFET (1T); 2) 2T differential (2T-diff) design; and 3) 2T pull-up-pull-down (2T-PUPD) design. Additionally, to increase the computational robustness of the 1T design, we propose static-weight transformation (WT) and static-weight input transformation (WIT). We then comparatively evaluate the inference accuracy and energy–area tradeoffs of these designs. For this, we use phase-field models to capture the multidomain physics and a rigorous inference simulator accounting for hardware nonidealities. Our analysis for ResNet18 trained on the CIFAR100 dataset shows that 1.58-b 1T-bitcell with WT and WIT techniques yield significant improvement in inference accuracy (73.61%) compared to the standard 1T design (i.e., without WIT). This accuracy is comparable to the 2T-diff design (76.4%), with 1.98× and 1.91× reduction in overall area and CiM energy, respectively.

# Summary. An optional shortened abstract.
summary: 
tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/11202915
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
