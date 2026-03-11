---
title: "MultiCam: On-the-fly Multi-Camera Pose Estimation Using Spatiotemporal Overlaps of Known Objects"
authors:
- Shiyu Li
- Hannah Schieber
- Kristoffer Waldow
- Benjamin Busam
- Julian Kreimeier
- Daniel Roth

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-03-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-03-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["journal-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Conference on Virtual Reality and 3D User Interfaces (VR) 2026*"
publication_short: "IEEE VR 2026"

abstract: | 
  Multi-camera dynamic augmented Reality (AR) applications require a camera pose estimation to leverage individual information from each camera in one common system. This can be achieved by combining contextual information, such as markers or objects, across multiple views. While commonly cameras are calibrated in an initial step or updated through the constant use of markers, another option is to leverage information already present in the scene, like known objects. Another downside of marker-based tracking is that  markers have to be tracked inside the field-of-view (FoV) of the cameras.
  To overcome these limitations, we propose a constant dynamic camera pose estimation leveraging spatiotemporal FoV overlaps of known objects on the fly. To achieve that, we enhance the state-of-the-art object pose estimator to update our spatiotemporal scene graph, enabling a relation even among non-overlapping FoV cameras. To evaluate our approach, we introduce a multi-camera, multi-object pose estimation dataset with temporal FoV overlap, including static and dynamic cameras. Furthermore, in FoV overlapping scenarios, we outperform the state-of-the-art on the widely used YCB-V and T-LESS dataset in camera pose accuracy. Our performance on both previous and our proposed datasets validates the effectiveness of our marker-less approach for AR applications. 
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Paper Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://ieeexplore.ieee.org/document/10972879'

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
  caption: 'Extended Reality Teleconsultation for Medical Interventions: State of the Art and Perspectives'
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



