---
title: "Four component imaging method for OBN data"
subtitle: "- 2024-02-26"
summary: We propose an ocean bottom dual-sensor viscoacoustic and separated-viscoelastic coupled Q-compensated least-squares reverse time migration (OBD-VSV-QLSRTM) in curvilinear coordinates. In this method, to solve the Q-compensated elastic inverse problem, we jointly use the recorded acoustic pressure and elastic multicomponent seismic data from the OBD observation system. 
authors:
- Jinli Li
- Yingming Qu


doi: "10.1190/geo2023-0433.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-26"

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
  <img src="./Four component imaging method for OBN data.assets/image.png" alt="Image Alt Text" style="max-width: 100%; height: auto;">
</div>
<br />

The ocean bottom dual-sensor (OBD) observation system places water detectors (pressure sensors) and land detectors on the irregular seabed interface to receive acoustic pressure fields and elastic wavefields, respectively. These data are usually applied to effectively remove ghost waves and ringing interference in the seawater layer, rather than being jointly used for migration. We propose an ocean bottom dual-sensor viscoacoustic and separated-viscoelastic coupled Q-compensated least-squares reverse time migration (OBD-VSV-QLSRTM) in curvilinear coordinates. In this method, to solve the Q-compensated elastic inverse problem, we jointly use the recorded acoustic pressure and elastic multicomponent seismic data from the OBD observation system. A new misfit function in the sense of least-squares inversion is constructed based on viscoacoustic and separated viscoelastic wavefields. Acoustic and separated viscoelastic equations are used to describe the acoustic wavefield in the acoustic medium and the Q-compensated P and S wavefields in the underlying viscoelastic medium, respectively. On the acoustic-viscoelastic interface, we implement a stable governing equation to ensure continuous and steady transmission of Q-compensated stresses in the subseabed and pressure in the seawater. To address the irregular seabed problem, we mesh the acoustic-viscoelastic models onto curvilinear grids and apply coordinate transformations to map the models and equations to a new curvilinear coordinate system. We derive viscoacoustic and separated-viscoelastic coupled adjoint and demigration operators in the curvilinear coordinates, enabling linear acoustic-viscoelastic modeling and stable receiver-side back-propagated wavefield continuation. Numerical examples conducted on two typical acoustic-viscoelastic models demonstrate that our proposed OBD-VSV-QLSRTM in curvilinear coordinates can produce highly accurate P- and S-wave images efficiently.


A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://library.seg.org/doi/10.1190/geo2023-0433.1)