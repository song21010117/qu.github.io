---
title: "Target-oriented seismic interferometric imaging method"
subtitle: "- 2023-12-01"
summary: To address this limitation, we propose a new approach called stained least-squares RTM (ST-LSRTM) that enhances the gradient through the integration of the staining algorithm. 
authors:
- Chang Liu
- Yingming Qu


doi: "10.1016/j.jappgeo.2023.105243"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01"

weight: 80

# Publication name and optional abbreviated publication name.
publication: Journal of Applied Geophysics
publication_short: JAG

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
  <img src="./Target-oriented seismic interferometric imaging method.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

The staining algorithm-based reverse time migration (RTM) technique has shown promise in improving imaging results for certain complex structures, such as subsalt and steeply dipping layers, by incorporating the complex domain. However, RTM suffers from low-resolution images as it utilizes the adjoint of the forward modeling operator rather than its inverse operator. To address this limitation, we propose a new approach called stained least-squares RTM (ST-LSRTM) that enhances the gradient through the integration of the staining algorithm. In ST-LSRTM, we first develop the wave equation and Born approximation, transitioning from the real to the complex domains. To simplify the linear perturbation operator, we constrain the magnitude of the imaginary velocity. Next, we compute the gradient in the complex domain. The enhanced gradient is obtained by replacing the traditional gradient with the normalized stained gradient within the stained region. Finally, we construct a misfit function based on the L2 norm and calculate the step size and gradient direction using the conjugate gradient method. Model tests demonstrate that ST-LSRTM achieves high-resolution imaging results even when the stained area is imprecise. Comparisons of waveform curves and normalized residual curves confirm that ST-LSRTM approaches true reflection coefficient model more closely compared to traditional LSRTM.


A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://www.sciencedirect.com/science/article/abs/pii/S092698512300321X)