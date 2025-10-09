---
title: "Multi-Layer Gaussian Splatting for Immersive Anatomy Visualization"
authors:
- Constantin Kleinbeck
- Hannah Schieber
- Klaus Engel
- Ralf Gutjahr
- Daniel Roth

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-03-10T00:00:00Z"
doi: "10.1109/TVCG.2025.3549882"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Visualization and Computer Graphics*"
publication_short: "IEEE TVCG"

abstract: |
  In medical image visualization, path tracing of volumetric medical data like computed tomography (CT) scans produces lifelike three-dimensional visualizations. Immersive virtual reality (VR) displays can further enhance the understanding of complex anatomies. Going beyond the diagnostic quality of traditional 2D slices, they enable interactive 3D evaluation of anatomies, supporting medical education and planning. Rendering high-quality visualizations in real-time, however, is computationally intensive and impractical for compute-constrained devices like mobile headsets. We propose a novel approach utilizing Gaussian Splatting (GS) to create an efficient but static intermediate representation of CT scans. We introduce a layered GS representation, incrementally including different anatomical structures while minimizing overlap and extending the GS training to remove inactive Gaussians. We further compress the created model with clustering across layers. Our approach achieves interactive frame rates while preserving anatomical structures, with quality adjustable to the target hardware. Compared to standard GS, our representation retains some of the explorative qualities initially enabled by immersive path tracing. Selective activation and clipping of layers are possible at rendering time, adding a degree of interactivity to otherwise static GS models. This could enable scenarios where high computational demands would otherwise prohibit using path-traced medical volumes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Journal Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://ieeexplore.ieee.org/document/10919012

url_pdf: ''
url_code: 'https://github.com/roth-hex-lab/Multi-Layer-Gaussian-Splatting-for-Immersive-Anatomy-Visualization'
url_dataset: 'https://osf.io/tuwh5/'
url_poster: ''
url_project: 'https://hex-lab.io/Multi-Layer-Gaussian-Splatting-for-Immersive-Anatomy-Visualization/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Pipeline from CT rendering to reconstruction to visualization in VR'
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

Presented at IEEE VR 2025 in St.Malo, France. See the video below for a quick visual introduction.

{{< video src="Constantin/Multi-Layer_Anatomy_GS_Teaser.mp4" controls="yes" >}}

<br>

{{% callout note %}}
All code, trained models and datasets are available online. See the linked project page for further information.
{{% /callout %}}


