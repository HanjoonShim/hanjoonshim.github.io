---

#-------------------------------------------------------------
title: "Single Frequency RTK Relative Navigation for Autonomous Formation Flying Mission of SNUGLITE-III CubeSat"
authors:
- admin
- Yonghwan Bae
- Jae Woong Hwang
- Changdon Kee
- In Hoi Koo
date: "2023-09-11T00:00:00Z"
doi: "https://doi.org/10.33012/2023.19371"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: |-
  *Proceedings of the 36th International Technical Meeting of the Satellite Division of The Institute of Navigation (ION GNSS+ 2023)*, Denver, Colorado, September 2023, pp. 1474-1486.
  <span style="background-color: red; font-weight: bold;">&nbsp;Best&nbsp;Presentation&nbsp;</span>
publication_short: ""

abstract: This study addresses the challenge of real-time kinematics (RTK) relative navigation for CubeSats engaged in autonomous formation flying within low Earth orbit (LEO). Considering the operational limitations and hardware characteristics of CubeSat platforms, we present an effective approach to achieving precise centimeter-level relative navigation using only single-frequency GPS measurements. Capitalizing on the strengths of the number of GPS-visible satellites in LEO and the small error factors in measurement values, our proposed methodology eliminates the need for additional sensors such as cameras, LIDAR, and lasers. To accomplish this, we begin by employing the range-domain DGPS technique to enhance the accuracy of pseudoranges through the application of a Hatch Filter. Subsequently, we compute the float solution and covariance of the double-difference integer ambiguities from the DGPS relative position without the filters. For RTK relative navigation, then, we can determine the integer ambiguities using the LAMBDA technique epoch-by-epoch, allowing efficient computation. To confirm the performance of the proposed method, we analyze the performance of RTK relative navigation through simulation in LEO.

tags:
- SNUGLITE-II
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
