---
title: "Causality Detection with Matrix-based Transfer Entropy"

authors:
  - Admin
  - Shujian Yu
  - Badong Chen

date: '2022-09-17T00:00:00Z'
doi: '10.1016/j.ins.2022.09.037'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Information Sciences"
publication_short: In *Information Sciences 2022*

abstract: Transfer entropy (TE) is a powerful tool for analyzing causality between time series and complex systems. However, it faces two key challenges. First, TE is often used to quantify the pairwise causal direction; yet, in real-world applications, one is always interested in identifying more complex causal relationships, such as indirect causation, common causation, and synergistic effect. Second, the estimation of TE usually relies on probability estimation, which is particularly complicated, or even infeasible for high-dimensional data. In this work, we take TE one step further and develop a pair of measures, the matrix-based conditional transfer entropy (CTE M) and the matrix-based high-order transfer entropy (HTE M). The former can detect both indirect and common causation, while the latter can detect synergistic effect. Making use of the recently proposed matrix-based Rényi’s α-order entropy functional, CTE M and HTE M are defined on the eigenspectrum of a normalized Hermitian matrix of the projected data in kernel space, which avoids the necessity of density estimation and the curse of dimensionality. Experiments on both synthetic and real-world datasets demonstrate the effectiveness of our measures in high-dimensional space, and their superiority in recovering complex causal structures for more than two time series.

# Summary. An optional shortened abstract.
summary: 

tags: ['Causal Discovery', 'Transfer Entropy']

featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

links:
  - name: Paper
    url: https://www.sciencedirect.com/science/article/pii/S0020025522010830
    
  - name: Code
    url: https://github.com/zwq2/MTE_causal

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
