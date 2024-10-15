---

#-------------------------------------------------------------
title: "Verification and Hardware Implementation of Single-Frequency RTK-Based Precise Relative Navigation for SNUGLITE-III CubeSat"
authors:
- admin
- Yonghwan Bae
- kee
- In Hoi Koo
date: "2024-01-23T00:00:00Z"
doi: "https://doi.org/10.33012/2024.19486"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2024 International Technical Meeting of The Institute of Navigation*, Long Beach, California, January 2024, pp. 787-798"
publication_short: ""

abstract: In this paper, we address the verification and hardware implementation challenges of real-time kinematics (RTK)-based precise relative navigation for SNUGLITE-III CubeSat, which performs autonomous formation flying and rendezvous docking in low Earth orbit (LEO). To adapt the algorithm to the CubeSat platform and apply centimeter-level relative navigation using only singlefrequency measurements commonly available in GPS receivers for CubeSat, various performance degradation issues arise due to constraints imposed by the onboard systems, such as limited power, computing resources, and redundancy assurance. Therefore, when applying GPS-based precise relative navigation to CubeSat missions for autonomous formation flying and rendezvous docking, it is essential to consider the performance impact resulting from the hardware characteristics of the onboard computer, space GPS receiver, and GPS antenna. The relative navigation algorithm used in this application is developed based on a software GPS simulator in a LEO environment. Before validating the algorithm for satellite deployment, ground validation must be prioritized. In other words, understanding the differences between the LEO and ground environments and establishing a sequential verification procedure for the relative navigation algorithm are required. For this purpose, we aim to validate the developed precision relative navigation algorithm for CubeSats incrementally using measurements collected on the ground and analyze the actual hardware characteristics to achieve algorithm verification goal. To validate the utility of the proposed technique, we first verify the effectiveness of the developed CubeSat RTK relative navigation algorithm. Here, the algorithm's validation and performance are analyzed by utilizing actual measurements with reliable high-cost GPS receivers and antennas. Subsequently, hardware characteristics and performance analysis are conducted by sequentially applying GPS patch antennas and space GPS receivers installed on the CubeSat. Through the proposed technique, we demonstrate that SNUGLITE-III CubeSat relative navigation system can provide centimeter-level performance, even when considering the hardware characteristics of the CubeSat platform.

tags:
- SNUGLITE-III
featured: false

# links:
# - name: ""
#   url: ""
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
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [SNUGLITE-III]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
