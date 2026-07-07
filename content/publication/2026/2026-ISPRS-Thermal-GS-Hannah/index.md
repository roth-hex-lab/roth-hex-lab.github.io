---
title: "Supercharging Thermal Gaussian Splatting with Depth Estimation"
authors:
- Manoj Biswanath
- Chenxin Cai
- Hannah Schieber
- Daniel Roth
- Benjamin Busam

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-06-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["journal"]

# Publication name and optional abbreviated publication name.
publication: "*ISPRS Archives"
publication_short: "ISPRS Archvies"

abstract: | 
   Efficient and robust 3D scene representation is crucial in autonomous driving, robotics, and related fields. While RGB images provide valuable content for 3D reconstruction, other modalities like thermal or depth can enable additional information on the environment. Lately, novel view synthesis methods like 3D Gaussian Splatting have started using multiple modalities to further boost their performance. But fusing or combining multimodal data can make the process slower and can bring in additional challenges. Therefore, our project aims to use single modality based on thermal infrared domain, by removing the reliance on visible light as much as possible. This single modality can be expected to be faster as it does not rely on multimodal data. We propose a method, Thermal-to-Depth Gaussian Splatting (TDg), that uses only thermal images and depth estimation in its architecture to derive the radiance fields. Our TDg method outperforms the MSMG (Multiple Single-Modal Gaussians) baseline in most cases on our test datasets, RGBT-Scenes and ThermalMix. On average, the rendering quality metrics such as learned perceptual image patch similarity (LPIPS), structural similarity index measure (SSIM), and peak signal-to-noise ratio (PSNR) of TDg are 1.12%, 0.034%, and 0.01% better than the baseline MSMG values. It also reduces the training time significantly, by 12 mins 47 secs (55% improvement). Overall, our method is successful in deriving these thermal radiance fields, which can ultimately have several applications, such as identifying heat sources critical in surveillance, search or rescue operations, and industrial inspections where temperature is widely used to monitor machines.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Journal Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Arxiv
  url: 'https://arxiv.org/abs/2605.30328'
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





