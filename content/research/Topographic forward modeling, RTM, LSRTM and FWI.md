---
title: "Topographic forward modeling, RTM, LSRTM and FWI"
subtitle: "- 2017-09-01"
summary: An EFWI method in the curvilinear system is presented to invert velocities for areas with surface topography. This method meshes the regions near the surface topography into body-fitted grids, and areas off surface regions into rectangular grids. 
authors:
- Yingming Qu
- Zhenchun Li


doi: "10.1190/geo2016-0349.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-01"

weight: 80

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
  <img src="./Topographic forward modeling, RTM, LSRTM and FWI.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

Elastic full-waveform inversion (EFWI) attempts to find high-resolution model parameters that are able to match observed data exactly by minimizing residuals between the observed and predicted data. However, irregular surface topography can generate problematic EFWI results. To resolve this issue, an EFWI method in the curvilinear system is presented to invert velocities for areas with surface topography. This method meshes the regions near the surface topography into body-fitted grids, and areas off surface regions into rectangular grids. We derived the gradient formulas with respect to multiple parameters in the curvilinear system and developed a step-search method to calculate the corresponding step lengths. Wiener filtering is performed on a multiscale decomposition method to invert the velocity from a low to a high wavenumber. Error analysis, using a homogeneous model with a surface topography, demonstrates the accuracy and validity of our methods. Numerical experiments with an elastic hill gully surface topography model reveal that the results obtained from our method are comparable with those of the body-fitted grid method, with the notable exception of a shortened computation time for the generation of grids and simulating wavefields. The inverted results with a modified elastic Marmousi model indicate that the inverted parameters are very well-resolved after implementing the proposed EFWI on the surface topography. The sensitivity analyzes of heterogeneous near-surface media, stochastic noise, and starting velocity errors further reveal that our method has the capability of handling complex land data


A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://library.seg.org/doi/10.1190/geo2016-0349.1)