---
title: "SEvaluating Cutout Rendering Techniques for Pass-Through Embodiment Using a Real-Mirror Metaphor"
authors:
- Kristoffer Waldow
- Arnulph Fuhrmann
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
publication_types: ["workshop-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Conference on Virtual Reality and 3D User Interfaces (VR) 2026*"
publication_short: "IEEE VR 2026"

abstract: | 
    A convincing sense of embodiment in virtual reality (VR) is crucial for creating immersive and engaging experiences, as
    it shapes how users perceive and interact with their virtual bodies. The sense of embodiment is thereby, among others, affected by
    the shape, appearance, and fidelity of the virtual body. However, achieving convincing avatar appearance remains a challenge for
    VR applications. One promising solution is Pass-Through Embodiment (PTE), which enables users to see their real bodies in VR.
    PTE combines depth-based segmentation with the pass-through video stream of video-see-through displays to effectively visualize
    photon-captured representations of their own bodies. Despite the source-fidelity of the representation, the resolution of integrated depth
    sensors in Head Mounted Displays (HMD) can produce artifacts at segmentation boundaries, leading to visible aliasing. The perceptual
    impact of these artifacts on the VR experience remains unexplored. Therefore, in this paper we compare three edge-rendering
    techniques designed to reduce artifacts without compromising performance. Aside from a soft gradient, we introduce two new methods
    with a hard and dithered edge. The latter aims to balance the sharpness of hard masks with the smoothness of gradient transitions,
    without relying on alpha blending. To evaluate those methods in a PTE context, we conducted a within-subjects study that introduces
    a novel real-mirror paradigm, using an actual physical mirror as reference for reflection. We found significant results in measured
    presence and embodiment. Subsequent analysis revealed that our dithered cutout approach significantly outperforms hard masks,
    while no significant difference was found between soft condition. These results suggest a perceptual continuum where dithering and
    soft blending both effectively reduce visual artifacts through gradient representation. Together with high overall ratings on presence and
    embodiment across all conditions, these findings confirm PTE as a robust method for supporting embodiment and presence, while
    highlighting the potential of dithering as a computationally efficient yet perceptually comparable alternative to smooth blending.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Paper Publication
featured: true

# Custom links (uncomment lines below)
links:
# - name: Paper
#  url: 'https://ieeexplore.ieee.org/document/10972879'
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



