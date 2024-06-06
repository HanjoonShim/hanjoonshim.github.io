---

#-------------------------------------------------------------
title: "Verification of Space GPS Receiver Navigation Performance Based on Full-Orbit Navigation Solutions of CubeSat"
authors:
- Jaeuk Park
- admin
- Yonghwan Bae
- Changdon Kee
- Sunkyoung Yu
date: "2023-01-24T00:00:00Z"
doi: "https://doi.org/10.33012/2023.18600"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2023 International Technical Meeting of The Institute of Navigation*, Long Beach, California, January 2023, pp. 252-261"
publication_short: ""

abstract: This study verifies navigation performance of in-house developed space GPS receiver using full-orbit onboard navigation solutions of CubeSat called Seoul National University GNSS Laboratory satellite-II (SNUGLITE-II). SNUGLITE-II has been orbiting at an altitude of 700 km since its launch on June 21, 2022. The primary mission of SNUGLITE-II is real-time attitude determination using GPS only. For this mission, it is equipped with second generation of in-house developed GPS receiver which awarded flight heritage by SNUGLITE-I in 2018. This paper validates navigation performance of this second-generation receiver using orbit determination method and SNUGLITE-II data. Unlike ordinary CubeSats, beacon of SNUGLITE-II includes navigation solutions. Until communication was lost on July 13, navigation solutions in beacon data had been collected by tracking of ground stations and playback data. Since none of pseudorange or carrier phase observables were obtained, only navigation solutions are available for verification of receiver performance. While tracking from ground stations lasts about 10 minutes per pass, playback data provide full-orbit onboard navigation solutions. This new data provide wider visibility of the orbit and enabled m-level accuracy orbit determination with shorter observation time compared to the case of SNUGLITE-I where only ground-based data were available. With these navigation solutions, SNU Precise Orbit Determination (SNUPOD) tool is used to generate reference orbit for verification. Verification is performed by two type of test overlap test and middle arc test. In overlap test, reference orbits from different datasets are compared in overlapping interval to check the quality of them and then navigation solutions were evaluated by them. In middle arc test, intermediate data are excluded in reference orbit generation for independence and evaluated by the generated reference orbit. Results of two tests confirm that navigation performance of space GPS receiver on SNUGLITE-II is less than 10 m level.

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
projects: [SNUGLITE-II]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
