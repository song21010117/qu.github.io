---
title: "AI for seismic velocity building"
subtitle: "- 2023-11-03"
summary: We present a multiscale fusion network with shot record attention (MFNSR) module, which can construct velocity models directly from the original seismic record. The proposed network can obtain fine-grained complete semantic information in the shot record by multilayer fusion operation. 
authors:
- Jing Lu
- Chunlei Wu
- Yingming Qu



doi: "10.1109/TGRS.2023.3329932"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-03"

weight: 80

# Publication name and optional abbreviated publication name.
publication: IEEE
publication_short: IEEE 

tags: [AI]

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
  <img src="./AI for seismic velocity building.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

Seismic velocity is crucial for seismic waveform inversion in geological exploration. An accurate velocity model is a key prerequisite for reverse time migration and other high-resolution seismic imaging techniques. Traditional methods perform well in seismic wave velocity modeling, but there are issues, such as lack of low-frequency components, low computational efficiency, and subjective factors, which result in low accuracy in modeling seismic wave velocity containing noise. In addition, mid-to-low frequency data are crucial for velocity model inversion, but existing methods often overlook this. In this article, we present a multiscale fusion network with shot record attention (MFNSR) module, which can construct velocity models directly from the original seismic record. The proposed network can obtain fine-grained complete semantic information in the shot record by multilayer fusion operation. Shot record attention (SR-attention) is proposed to reveal the medium-to-low frequency information in the shot record. The proposed random noise block enables better generalization of the model and higher accuracy in modeling the shot record speed of the entrained noise. The results of extensive numerical experiments on synthetic models show that our method acquires outstanding performance, which verifies the positive effect of MFNSR on the inversion of medium-to-low frequency data. The visualizations of outputs show that the proposed method can obtain more accurate velocity models.


A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://ieeexplore.ieee.org/document/10308616)