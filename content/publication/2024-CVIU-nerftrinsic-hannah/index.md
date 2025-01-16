---
title: "Indoor synthetic data generation: A systematic review"
authors:
- Hannah Schieber
- Fabian Deuser
- Bernhard Egger
- Norbert Oswald
- Daniel Roth

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024"
doi: "10.1016/j.cviu.2024.104206"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Vision and Image Understanding*"
publication_short: "CVIU"

abstract: |
  Novel view synthesis using neural radiance fields (NeRF) is the state-of-the-art technique for generating high-quality images from novel viewpoints. Existing methods require a priori knowledge about extrinsic and intrinsic camera parameters. This limits their applicability to synthetic scenes, or real-world scenarios with the necessity of a preprocessing step. Current research on the joint optimization of camera parameters and NeRF focuses on refining noisy extrinsic camera parameters and often relies on the preprocessing of intrinsic camera parameters. Further approaches are limited to cover only one single camera intrinsic. To address these limitations, we propose a novel end-to-end trainable approach called NeRFtrinsic Four. We utilize Gaussian Fourier features to estimate extrinsic camera parameters and dynamically predict varying intrinsic camera parameters through the supervision of the projection error. Our approach outperforms existing joint optimization methods on LLFF and BLEFF. In addition to these existing datasets, we introduce a new dataset called iFF with varying intrinsic camera parameters. NeRFtrinsic Four is a step forward in joint optimization NeRF-based view synthesis and enables more realistic and flexible rendering in real-world scenarios with varying camera parameters.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Journal Publication
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://pdf.sciencedirectassets.com/271018/1-s2.0-S1077314224X00107/1-s2.0-S107731422400287X/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLWVhc3QtMSJHMEUCIA%2F02dxNdxOaajn1D%2BeMyvk47m1zXRCuEaoV%2FVqUoUoBAiEA0QdIX5%2F8zH3dDwUlTqWtP2tR0HcuNUcOYlLu9B8MFVcqsgUIQhAFGgwwNTkwMDM1NDY4NjUiDLq%2BHIaMVNsE%2BbSL3SqPBbryg0rjYok2IWkzszTuS8S3pBbmdQ163OpeqMYNDm%2BEf1wiX2znn5ZpSey7cBuaFn1MgtPnO8P4z4CeLxwrfiBRU6Dy1TywCdkLuWydNUsmJoVh7bIGgiQxH6V8cJlopIzAuk5wmOLi3uLeS%2B3XSAKgq29GzfhBbKWlvXX0SjHUp90uK1aN0Zc2kofNGB6M6vt5IzVSXK8xgMejpngW7Gw7OGIDURQJUk8WXCfiZZ%2BrEYBtMM07ncvof9E2WTYGeqFKvA9yMRljZjitj7pPErQpRtiTGuALnTVaAq6dr%2BDA%2BdKWjRqSWq8fa7H53ufVvdNda4ShhSe2u28pK3YWxbyQrrFIOl1TTCLV2Zm4%2BNcaisn%2BvdeahBimvzYqZAh1h2CnYCqhSCSJgLPdhobuYXp6UifoBE93J1TP7uiUZK3fhXVRGnUVM8pttX4a6kKEXWK4k64yuvQAh49tlNtJgN9PVU5gQMWBRb2EqmKautwIyCWqTdodSpi%2FprUJR55e5qGqSYQ%2B1MlZ%2BxcOl94tSWxS%2BSVw7I%2FCx7rk0T9UCXE7lqpMjPVeZ63ZNIf3PhngzgTDj0T2wTaEKkJ6ElddPQk9G%2BTJsOtlW0RewoXPIGFdHjO9rna5Fo89nD2mIIKkmN%2Fzaj8ZsNze%2Fp5mUl1wPJYA6iJjyfpc8jnekM9hYtfYjEwXBBojYcALdaFhAM0AO7HeaurtSpnOAN36tebNc0x5N61%2BGURNfwI6ycqtyfvEuSr0d0NbH2zG60l%2BDPQS%2Fu1rxuZlwkgjtxnKK8p3r4Zm%2FrOnQPDjYz%2BpUbj3ljFA6PD%2Fu6ezqb6wRRQaR1edtoqz8WhPem7rlbkrV87Tx0qSW4WSHC%2FsBexs1H8CQKcw0YujvAY6sQHhuCrdcHk1GfbgIle%2FQb13JW6f0VQgLcRqQJH1OzWQomO1MMEEiADGS13526u9eLyEIsz24sqd3sBzejyIM%2BK4iQ8j5hBaZAra1idPGdN%2BwTnAH2nHPk7rBQBRaFkKB59C8rI4gNCwWCNbX15KO6u4juik4XdOq2tOCTeA3nhsMMBhHZ5aINBwK8J56ONRj48l96%2Ffp6yUGVlrcjjkAeWf%2B5U%2FCfx5XMpmx4S3B9hr4hw%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250116T094015Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY5YM4XVED%2F20250116%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e5b317a3d3f1c25f64f76b1eb18efa3197100cad4840aa5a98f7e312bd714c74&hash=a53923dbf56f00a4b6539e5b956f559e9bbf32c7ed3fb23ecb5720fe75091a10&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S107731422400287X&tid=spdf-5324ad37-1498-4768-b94b-78308212a15d&sid=b406ecf88a4cd443788b41a518b620170edfgxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=02055f5454065d515a07&rr=902d249d7a5ddc96&cc=de


url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://hannahhaensen.github.io/nerftrinsic_four/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Example renderings from the same scene using approaches.'
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


