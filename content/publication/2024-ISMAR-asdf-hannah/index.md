---
title: "ASDF: Assembly State Detection Utilizing Late Fusion by Integrating 6D Pose Estimation"
authors:
- Hannah Schieber
- Shiyu Li
- Niklas Corell
- Philipp Beckerle
- Julian Kreimeier
- Daniel Roth

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-10-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE International Symposium on Mixed and Augmented Reality (ISMAR) 2024*"
publication_short: "IEEE ISMAR 2024"

abstract: | 
  In medical and industrial domains, providing guidance for assembly processes is critical to ensure efficiency and safety. Errors in assembly can lead to significant consequences such as extended surgery times, and prolonged manufacturing or maintenance times in industry. Assembly scenarios can benefit from in-situ Augmented Reality (AR) visualization to provide guidance, reduce assembly times and minimize errors. To enable in-situ visualization 6D pose estimation can be leveraged. Existing 6D pose estimation techniques primarily focus on individual objects and static captures. However, assembly scenarios have various dynamics including occlusion during assembly and dynamics in the assembly objects appearance. Existing work, combining object detection/6D pose estimation and assembly state detection focuses either on pure deep learning-based approaches, or limit the assembly state detection to building blocks. To address the challenges of 6D pose estimation in combination with assembly state detection, our approach ASDF builds upon the strengths of YOLOv8, a real-time capable object detection framework. We extend this framework, refine the object pose and fuse pose knowledge with network-detected pose information. Utilizing our late fusion in our Pose2State module results in refined 6D pose estimation and assembly state detection. By combining both pose and state information, our Pose2State module predicts the final assembly state with precision. Our evaluation on our ASDF dataset shows that our Pose2State module leads to an improved assembly state detection and that the improvement of the assembly state further leads to a more robust 6D pose estimation. Moreover, on the GBOT dataset, we outperform the pure deep learning-based network, and even outperform the hybrid and pure tracking-based approaches.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Paper Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: 'https://arxiv.org/pdf/2403.16400'

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://hex-lab.io/asdf/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'ASDF at ISMAR'
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
We gratefully acknowledge funding for this study by d.hip campus and Bundesministerium für Bildung und Forschung (BMBF) with the grant number 16SV8973.
{{% /callout %}}


