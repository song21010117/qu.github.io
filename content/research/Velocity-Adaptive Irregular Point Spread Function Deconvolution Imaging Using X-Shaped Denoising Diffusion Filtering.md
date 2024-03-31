---
title: "Velocity-Adaptive Irregular Point Spread Function Deconvolution Imaging Using X-Shaped Denoising Diffusion Filtering"
subtitle: "- 2023-08-07"
summary: To accurately calculate the inverse of the Hessian matrix, solve the PSF sparsity selection problem, and eliminate migration noise, we propose a velocity-adaptive irregular PSF deconvolution imaging using a Gaussian smoothing X-shaped denoising diffusion filtering operator. 
authors:
- Yixin Wang
- Chongpeng Huang
- Yingming Qu


doi: "10.1109/TGRS.2023.3303184"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-07"

weight: 100 .

# Publication name and optional abbreviated publication name.
publication: IEEE
publication_short: IEEE 

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
  <img src="./Velocity-Adaptive Irregular Point Spread Function Deconvolution Imaging Using X-Shaped Denoising Diffusion Filtering.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

Most least-squares migration (LSM) imaging methods use iterative gradient update methods to approximate the inverse of the Hessian matrix, but such approximations are not accurate and require a large amount of computational time. The point spread function (PSF) is an optical imaging method, defined as the response of an imaging system to a point source of light. In optics, the image of a complex object is considered to be a degenerate result obtained by convolving the PSF with the real object, which is analogous to the definition of seismic imaging using the Hessian operator. To accurately calculate the inverse of the Hessian matrix, solve the PSF sparsity selection problem, and eliminate migration noise, we propose a velocity-adaptive irregular PSF deconvolution imaging using a Gaussian smoothing X-shaped denoising diffusion filtering operator. The velocity-adaptive irregular grid selection strategy allows for adaptive selection of the grid size based on the velocity of the different layers, ensuring maximum imaging accuracy and avoiding the risk of interference among PSFs. The Gaussian smoothing X-shaped denoising diffusion filtering operator eliminates migration noise and also prevents the introduction of deconvolution noise. We use the Marmousi model and a field dataset to compare the performance of our proposed method with other common methods, demonstrating that our proposed method has clearer seismic events, more balanced amplitude, higher resolution, and higher signal-to-noise ratio than others.


A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://ieeexplore.ieee.org/document/10210619)