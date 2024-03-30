---
title: "Attenuation compensation in anisotropic LSRTM and FWI"
subtitle: " - 2020-01-09"
summary: we compensate for the attenuation during source wavefield forward propagation and receiver backward propagation, and we introduce a regularization operator to automatically eliminate the exponential high-frequency noise during the attenuation compensation process. 
authors:
- Yingming Qu
- Jinli Li

doi: "10.1190/geo2019-0237.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-09"

weight: 100

# Publication name and optional abbreviated publication name.
publication: Geophysics
publication_short: Geophysics 

tags: [Imaging]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
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

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<div style="text-align: center;">
  <img src="./Attenuation compensation in anisotropic LSRTM and FWI.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

Compared to primary arrivals, multiples have longer propagation paths and smaller reflection angles, leading to a wider illumination area in the horizontal direction and higher resolution in the vertical direction. Hence, it is better to make full use of the multiples rather than suppressing them. However, seismic attenuation exists widely in the subsurface medium, especially directly below the deep sea bottom. Therefore, to compensate for the attenuation effect during multiple imaging, we have developed a viscoacoustic reverse time migration (RTM) method of different-order multiples. Following the multiple propagation paths, we compensate for the attenuation during source wavefield forward propagation and receiver backward propagation, and we introduce a regularization operator to automatically eliminate the exponential high-frequency noise during the attenuation compensation process. Taking advantage of the full wavefield information, we jointly use the different-order multiples and primaries when implementing viscoacoustic RTM. In numerical examples, we validate the viscoacoustic RTM of different-order multiples in a three-layer attenuation model and an attenuating Sigsbee2B model. Our results suggest that our method can image the models using different-order multiples separately, which suppresses crosstalk artifacts, balances energy, raises resolution, and improves subsalt images dramatically.

A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://pubs.geoscienceworld.org/geophysics/article-abstract/85/2/S71/580898/Viscoacoustic-reverse-time-migration-of-joint)