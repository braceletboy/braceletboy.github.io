---
title: "Deep Learning Models for Water Stage Predictions in South Florida"
authors:
- Jimeng Shi
- Zeda Yin
- admin
- Khandker Ishtiaq
- Anupama John,
- Jayantha Obeysekera,
- Arturo Leon,
- Giri Narasimhan

author_notes:
- "Equal contribution, Corresponding Author"
- "Equal contribution"

date: "2025-07-18T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Water Resources Planning and Management, 151(10)*"
publication_short: ""

abstract: Simulating and predicting the water level/stage in river systems is essential for flood warnings, hydraulic operations, and flood mitigations. Physics-based detailed hydrological and hydraulic computational tools, such as the Hydrologic Engineering Center’s River Analysis System (HEC-RAS), MIKE, and the storm water management model, can be used to simulate a complete watershed and compute the water stage at any point in the river system. However, these physics-based models are computationally intensive, especially for large watersheds and for longer simulations, since they use detailed grid representations of terrain elevation maps of the entire watershed and solve complex partial differential equations for each grid cell. To overcome this problem, we train several deep learning (DL) models for use as surrogate models to rapidly predict the water stage. A portion of the Miami River in South Florida was chosen as a case study for this paper. Extensive experiments show that the performance of various DL models (MLP, RNN, CNN, LSTM, and RCNN) is significantly better than that of the physics-based model, HEC-RAS, even during extreme precipitation conditions (i.e., tropical storms), and with speedups exceeding 500×. To predict the water stages more accurately, our DL models use both measured variables of the river system from the recent past and covariates for which predictions are typically available for the near future.

# Summary. An optional shortened abstract.
summary: Physics-based hydraulic models like HEC‑RAS, MIKE, and SWMM can accurately simulate river stages but are computationally costly for large watersheds and long runs because they solve detailed PDEs on high‑resolution grids. To address this, we train deep‑learning surrogate models to predict water stage rapidly using recent measured river variables plus near‑future covariates. The DL surrogates not only achieve better accuracy than HEC‑RAS—even during extreme precipitation events, but also run more than 500× faster.

tags:
  - Time Series Prediction
  - Flood Mitigation
  - AI for Science
  - HEC-RAS

featured: false

hugoblox:
  ids:
    doi: 10.1061/JWRMD5.WRENG-6194

# links:
#   - type: pdf
#     url: http://arxiv.org/pdf/1512.04133v1
#   - type: code
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: dataset
#     url: ""
#   - type: poster
#     url: ""
#   - type: project
#     url: ""
#   - type: slides
#     url: https://www.slideshare.net/
#   - type: source
#     url: ""
#   - type: video
#     url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!-- 
> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
