---
title: 'Explainable Parallel RCNN with Novel Feature Representation for Time Series Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jimeng Shi
  - admin
  - Vitalii Stebliankin
  - Azam Shirali
  - Giri Narasimhan

# Author notes (optional)
author_notes:
  - 'Corresponding Author'
  - ''
  - ''
  - ''
  - ''

date: '2023-12-20T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*International Workshop on Advanced Analytics and Learning on Temporal Data*"
publication_short: "*ECML-PKKD AALTD Workshop, 2023*"

abstract: Accurate time series forecasting is a fundamental challenge in data science, as it is often affected by external covariates such as weather or human intervention, which in many applications, may be predicted with reasonable accuracy. We refer to them as predicted future covariates. However, existing methods that attempt to predict time series in an iterative manner with auto-regressive models end up with exponential error accumulations. Other strategies that consider the past and future in the encoder and decoder respectively limit themselves by dealing with the past and future data separately. To address these limitations, a novel feature representation strategy - shifting - is proposed to fuse the past data and future covariates such that their interactions can be considered. To extract complex dynamics in time series, we develop a parallel deep learning framework composed of RNN and CNN, both of which are used in a hierarchical fashion. We also utilize the skip connection technique to improve the model's performance. Extensive experiments on three datasets reveal the effectiveness of our method. Finally, we demonstrate the model interpretability using the Grad-CAM algorithm.

# Summary. An optional shortened abstract.
summary: We address limitations in time-series forecasting when external covariates and predicted future covariates are available by introducing a "shifting" feature representation that fuses past observations with predicted future covariates so their interactions are modeled directly. We build a parallel, hierarchical deep architecture that combines RNN and CNN blocks with skip connections and validate our approach on three datasets.

tags:
  - Time Series Prediction
  - Flood Mitigation
  - AI for Science

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-031-49896-1_5

# Custom links
# links:
#   - type: pdf
#     url: ""
#   - type: code
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: dataset
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: slides
#     url: https://www.slideshare.net/
#   - type: source
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!-- 
> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
