---
title: "Curing Cancer in a FLASH: A Finite-Element Computational Analysis of an Ultrasonic Detection Array Setup for Ultra-High Dose Rate (FLASH) Measurements and Absolute Dosimetry"
authors:
- me
date: "2025-08-08T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: FLASH Radiotherapy is a promising radiation therapy modality, delivering radiation dose at an ultra-high dose rate (≥40 Gy/s) compared to Conventional Radiotherapy (0.01 – 0.40 Gy/s) while minimizing irradiation damage to healthy tissue surrounding a tumor. However, existing radiation dose imaging technology using thermistors cannot determine, with significant precision and millisecond-regime time delays, whether a surface dose achieved FLASH-level dose rates. A proposed solution involves propagating an ultrasonic wave orthogonal to a radiative beam from an electron linear accelerator in a water phantom to observe potential phase modulation of the ultrasound, which can be de-modulated to determine the delivered dose rate. This investigation aims to conduct a Finite-Element Method (FEM) analysis of the ultrasonic detection array setup proposed via simulations of a complete thermoacoustic model on the COMSOL® Multiphysics 6.1 software to confirm phase modulation of the ultrasonic signal. First, a simplified water phantom was constructed, bounded by physical and material parameters and surrounded by a Perfectly Matched Layer. Then, a radiative beam was devised by applying multipulse laser machining principles to a heat flux condition. Similarly, the ultrasonic signal was adapted from a High-Intensity Focused Ultrasound (HIFU) pulse, applying diagnostic ultrasound principles to switch from HIFU’s use case as a therapeutic modality. The Pressure Acoustics and Heat Transfer modules were accordingly coupled to obtain temperature change, acoustic pressure, and phase of the ultrasonic wave upon simultaneously propagating the radiative beam and ultrasonic signal. The simulation results show a significant phase modulation of the ultrasonic signal after reaching the radiative beam. Upon interaction with the heated region (10 mK temperature difference achieved from a 40 Gy/s beam), the ultrasonic signal initially faced an increase in frequency via compression before decreasing below the original frequency. A decrease in the number of peaks was additionally observed, indicating phase modulation. Moreover, slight amplitude modulation in the heated region was observed in the transient domain. While the presence of thermoacoustic shocks may be attributed to FEM meshing, this behavior is validated by existing literature. The computational model results are also validated by preliminary results observed in experiment with close agreement. The results of this investigation may be applied in methods for Absolute Dosimetry of surface doses, Holographic Interferometry of radiotherapy beams, radiation calorimetry, and high-precision FLASH measurements to make FLASH Radiotherapy a clinical modality.

# Summary. An optional shortened abstract.
summary: This investigation aims to use a Finite-Element Method (FEM) analysis to develop a primary standard for Absolute Dosimetry and technology for real-time imaging of absorbed radiation dose.

tags:
- Radiation Physics
- Dosimetry
- Computational Physics

featured: true

hugoblox:
  ids:
    # arxiv: 1512.04133v1

links:
# - type: preprint
#   provider: arxiv
#   id: 1512.04133v1
- type: pdf
  url: V.Sundar_FEM Analysis for UHDR (FLASH) Measurements and Absolute Dosimetry_Paper.pdf
- type: poster
  url: V.Sundar_FEM Analysis for UHDR (FLASH) Measurements and Absolute Dosimetry_Poster.pdf
- type: slides
  url: V.Sundar_FEM Analysis for UHDR (FLASH) Measurements and Absolute Dosimetry_Talk_Slides.pdf
- type: custom
  label: Visual Abstract
  url: V.Sundar_FEM Analysis for UHDR (FLASH) Measurements and Absolute Dosimetry_Visual Abstract.pdf
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs. -->

<!-- > [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
