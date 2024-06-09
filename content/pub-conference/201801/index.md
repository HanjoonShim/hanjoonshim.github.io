---

#-------------------------------------------------------------
title: "Development and Verification of Attitude Determination and Control Algorithm for SNUGLITE Cube Satellite"
authors:
- Minkyu Choi
- Sunkyoung Yu
- O-Jong Kim
- Heekwon No
- admin
- kee
date: "2018-01-29T00:00:00Z"
doi: "https://doi.org/10.33012/2018.15534​"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: |-
    *Proceedings of the 2018 International Technical Meeting of The Institute of Navigation*, Reston, Virginia, Jan 2018, pp. 56-71.
    <span style="background-color: grey; font-weight: bold; color: white;">&nbsp;As Speaker&nbsp;</span>

publication_short: ""

abstract: This study demonstrates the validation of the in-house developed space GPS receiver using a cube satellite called Seoul National University GNSS satelLITE (SNUGLITE). SNUGLITE is orbiting at an altitude of 575km since its launch date Dec. 4th, 2018. The main mission of SNUGLITE is to verify the space GPS receiver. This paper validated the performance of space GPS receiver to clarify the mission success using SNUGLITE data and orbit determination method. SNUGLITE broadcasts its navigation solutions using a beacon, every 10 seconds, but none of the pseudo-range or carrier phase observations are transmitted because of the failure of the communication receiver part. Therefore, only navigation solutions could be used to verify space receiver performance. Onboard navigation solutions are collected during antenna tracking by stations and the tracking lasts about 10 minutes per each station. Despite the data environment, an orbit could be determined in m-level accuracy using data of a few arcs and the SNU Precise Orbit Determination (SNUPOD) tool. In the verification method, the verification was performed by selecting one arc within the dataset and excluding it from the creation of the reference orbit so that the arc and the reference orbit had an independent relationship. A simulation was conducted to show the feasibility of the verification process and real data experiments were assessed the accuracy of SNUGLITE navigation data. The result shows that the verification process is enough to validate m-level accuracy and SNUGLITE space GPS receiver performance is about 6 m. In conclusion, it is confirmed that SNUGLITE satisfies the requirements of its main mission.


tags:
- SNUGLITE-I
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
projects: [SNUGLITE-I]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
