---
title: "GBOT: Graph-Based 3D Object Tracking for Augmented Reality-Assisted Assembly Guidance"
authors:
- Shiyu Li
- Hannah Schieber
- Niklas Corell
- Bernhard Egger
- Julian Kreimeier
- Daniel Roth

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-01-01T00:00:00Z"
doi: "10.1109/VR58804.2024.00072"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Conference on Virtual Reality and 3D User Interfaces 2024*"
publication_short: "IEEE VR 2024"

abstract: |
  Guidance for assemblable parts is a promising field for augmented reality. Augmented reality assembly guidance requires 6D object poses of target objects in real time. Especially in time-critical medical or industrial settings, continuous and markerless tracking of individual parts is essential to visualize instructions superimposed on or next to the target object parts. In this regard, occlusions by the user's hand or other objects and the complexity of different assembly states complicate robust and real-time markerless multi-object tracking. To address this problem, we present Graph-based Object Tracking (GBOT), a novel graph-based single-view RGB-D tracking approach. The real-time markerless multi-object tracking is initialized via 6D pose estimation and updates the graph-based assembly poses. The tracking through various assembly states is achieved by our novel multi-state assembly graph. We update the multi-state assembly graph by utilizing the relative poses of the individual assembly parts. Linking the individual objects in this graph enables more robust object tracking during the assembly process. For evaluation, we introduce a synthetic dataset of publicly available and 3D printable assembly assets as a benchmark for future work. Quantitative experiments in synthetic data and further qualitative study in real test data show that GBOT can outperform existing work towards enabling context-aware augmented reality assembly guidance. Dataset and code will be made publically available 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Paper Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://ieeexplore.ieee.org/document/10494181


url_pdf: ''
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
  caption: ''
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


<br>

{{% callout note %}}
We gratefully acknowledge funding for this work by BMBF (project KARVIMIO, grant number 16SV8973).
{{% /callout %}}
