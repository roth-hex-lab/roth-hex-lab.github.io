---
title: "Neural Motion Tracking: Formative Evaluation of Zero Latency Rendering"
authors:
- Daniel Roth
- Valentin Bräutigam
- Nidhi Joshi
- Constantin Kleinbeck
- Hannah Schieber
- Julian Kreimeier

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-10-10T00:00:00Z"
doi: "10.1145/3641825.3687751"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference-paper"]

# Publication name and optional abbreviated publication name.
publication: "*ACM ACM Symposium on Virtual Reality Software and Technology (VRST) 2024*"
publication_short: "ACM VRST 2024"

abstract: | 
  Low motion-to-photon latencies between physical movement and rendering updates are crucial for an immersive virtual reality (VR) experience and to avoidusers’ discomfort and sickness. Current methods aim to minimize the delay between the motion measurement and rendering at the cost of increasing technical complexity and possibly decreasing accuracy. By relying on capturing physical motion, these strategies will, by nature, not result in zero latency rendering or will be based on prediction and resulting uncertainty. This paper presents and evaluates a novel alternative and proof of principle for VR motion tracking that could enable motion-to-photon latencies of zero and below zero in time. We termed our concept Neural Motion Tracking, which we define as the sensing and assessment of motion through human neural activation of the somatic nervous system. In contrast to measuring physical activity, the key principle is that we aim to utilize the physiological timeframe between a user’s intention and the execution of motion. We aim to foresee upcoming motion ahead of the physical movement, by sampling preceding electromyographic signals before the muscle activation. The electromechanical delay (EMD) between potential change in the muscle activation and actual physical movement opens a gap in which measurement can be taken and evaluated before the physical motion. In a first proof of principle, we evaluated the concept with two activities, arm bending and head rotation, measured with a binary activation measure. Our results indicate that it is possible to predict movement and update a rendering up to 2 ms before its physical execution, which is assessed by optical tracking after approximately 4 ms. However, to make the best use of this advantage, electromyography (EMG) sensor data should be as high quality as possible (i.e., low noise and from muscle-near electrodes). Our results empirically quantify this characteristic for the first time when compared to state-of-the-art optical tracking systems for VR. We discuss our results and potential pathways to motivate further work toward marker- and latency-less motion tracking.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Paper Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://doi.org/10.1145/3641825.3687751'

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
  caption: 'Neural Motion Tracking'
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
Honorable Mention Best Paper Award
{{% /callout %}}


