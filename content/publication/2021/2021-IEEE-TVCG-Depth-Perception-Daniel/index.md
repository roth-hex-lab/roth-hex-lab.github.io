---
title: "The Impact of Focus and Context Visualization Techniques on Depth Perception in Optical See-Through Head-Mounted Displays"
authors:
- Alejandro Martin-Gomez
- Jakob Weiss
- Andreas Keller
- Ulrich Eck
- Daniel Roth
- Nassir Navab


#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-12-30T00:00:00Z"
doi: "10.1109/TVCG.2021.3079849"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Visualization and Computer Graphics (TVCG)*"
publication_short: "IEEE TVCG"

abstract: |
  Estimating the depth of virtual content has proven to be a challenging task in Augmented Reality (AR) applications. Existing studies have shown that the visual system makes use of multiple depth cues to infer the distance of objects, occlusion being one of the most important ones. The ability to generate appropriate occlusions becomes particularly important for AR applications that require the visualization of augmented objects placed below a real surface. Examples of these applications are medical scenarios in which the visualization of anatomical information needs to be observed within the patient's body. In this regard, existing works have proposed several focus and context (F+C) approaches to aid users in visualizing this content using Video See-Through (VST) Head-Mounted Displays (HMDs). However, the implementation of these approaches in Optical See-Through (OST) HMDs remains an open question due to the additive characteristics of the display technology. In this article, we, for the first time, design and conduct a user study that compares depth estimation between VST and OST HMDs using existing in-situ visualization methods. Our results show that these visualizations cannot be directly transferred to OST displays without increasing error in depth perception tasks. To tackle this gap, we perform a structured decomposition of the visual properties of AR F+C methods to find best-performing combinations. We propose the use of chromatic shadows and hatching approaches transferred from computer graphics. In a second study, we perform a factorized analysis of these combinations, showing that varying the shading type and using colored shadows can lead to better depth estimation when using OST HMDs.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Journal Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://ieeexplore.ieee.org/abstract/document/9429918'

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
  caption: "Base implementations of focus and context visualization techniques (top row) and their appearance in video- (mid row), and optical- (bottom row) see-through head-mounted displays. From left to right: Baseline overlay without contextual layer, Virtual Window, Contextual Anatomical Mimesis, and Virtual Mask. Mean and standard deviation of corresponding alignment errors of study 1 are presented in centimeters. The OST images are captured using a smartphone camera placed at the eye position. Contrast and brightness have been adjusted for a faithful impression of the overlay as observed by the user."
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

{{% callout note %}}
This work was supported in part by the Bayerische Forschungsstiftung under Grant DOK-178-17 and in part by the Deutsche Forschungsgemeinschaft under Grant NA-620/33-2. The authors would also like to thank Marc Lazarovici and the Institut für Notfallmedizin for their valuable support in conducting their user study on their premises. Alejandro Martin-Gomez and Jakob Weiss are contributed equally to this work as corresponding authors.
{{% /callout %}}



