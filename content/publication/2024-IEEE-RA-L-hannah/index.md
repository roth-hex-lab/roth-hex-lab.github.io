---
title: "DynaMoN: Motion-Aware Fast And Robust Camera Localization for Dynamic Neural Radiance Fields"
authors:
- Nicolas Schischka
- Hannah Schieber
- Mert Asim Karaoglu
- Melih Gorgulu
- Florian Grötzner
- Alexander Ladikos
- Nassir Navab
- Daniel Roth
- Benjamin Busam

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024"
doi: "10.1109/LRA.2024.3511399"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE RA-L*"
publication_short: "RA-L 2024"

abstract: | 
  The accurate reconstruction of dynamic scenes with neural radiance fields is significantly dependent on the estimation of camera poses. Widely used structure-from-motion pipelines encounter difficulties in accurately tracking the camera trajectory when faced with separate dynamics of the scene content and the camera movement. To address this challenge, we propose Dynamic Motion-Aware Fast and Robust Camera Localization for Dynamic Neural Radiance Fields (DynaMoN). DynaMoN utilizes semantic segmentation and generic motion masks to handle dynamic content for initial camera pose estimation and statics-focused ray sampling for fast and accurate novel-view synthesis. Our novel iterative learning scheme switches between training the NeRF and updating the pose parameters for an improved reconstruction and trajectory estimation quality. The proposed pipeline shows significant acceleration of the training process. We extensively evaluate our approach on two real-world dynamic datasets, the TUM RGB-D dataset and the BONN RGB-D Dynamic dataset. DynaMoN improves over the state-of-the-art both in terms of reconstruction quality and trajectory accuracy. We plan to make our code public to enhance research in this area.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Paper Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10777295'

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://hannahhaensen.github.io/DynaMoN/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'DynaMoN in IEEE RA-L'
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
We gratefully acknowledge funding for this study by d.hip campus.
{{% /callout %}}


