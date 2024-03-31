---
title: "Acoustic-elasticviscoelastic forward modeling, RTM, LSRTM and FWI"
subtitle: "- 2020-03-22"
summary: We develop a 2D curvilinear-grid-based fluid-solid separated-wavefield EFWI (CFS-SEFWI) method. Numerical examples that include an anomaly model and a modified Marmousi II model demonstrate that CFS-SEFWI overcomes the influence of the irregular fluid-solid interface and efficiently reduces crosstalk effects. 
authors:
- Yingming Qu
- Zhe Guan


doi: "10.1190/geo2018-0743.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-22"

weight: 80

# Publication name and optional abbreviated publication name.
publication: Geophysics
publication_short: Geophysics 

tags: [Inversion]

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
  <img src="./Acoustic-elasticviscoelastic forward modeling, RTM, LSRTM and FWI.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

Marine seismic exploration with ocean-bottom cable technology is able to record P- and S-wave information simultaneously. Elastic full-waveform inversion (EFWI) uses P- and S-waves to invert multiple parameters with adequate amplitude information and complete illumination of the subsurface. To calculate the wavefield within EFWI, we use different formats of wave equations in fluid and solid mediums and an appropriate boundary condition to convert waves on the interface. This partitioned simulation scheme is more stable and efficient than the traditional integrated simulation scheme. However, if the fluid-solid coupled medium has an extremely irregular interface, the conventional finite-difference method with rectangular grids cannot obtain accurate source and receiver wavefields. We use the curvilinear coordinates to overcome this limitation. In the curvilinear coordinates, the irregular interface can be transformed into a horizontal interface. To reduce the crosstalk of inverted P- (⁠⁠) and S-velocities (⁠⁠), we derive the gradient formulas of and based on P- and S-wave mode separation in the curvilinear coordinates, and, finally, we develop a 2D curvilinear-grid-based fluid-solid separated-wavefield EFWI (CFS-SEFWI) method. Numerical examples that include an anomaly model and a modified Marmousi II model demonstrate that CFS-SEFWI overcomes the influence of the irregular fluid-solid interface and efficiently reduces crosstalk effects between and ⁠. Our results also demonstrate that this method is less sensitive to noise compared to the conventional CFS FWI method without separating wave modes.


A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://pubs.geoscienceworld.org/geophysics/article-abstract/85/3/R113/583054/Fluid-solid-coupled-full-waveform-inversion-in-the)