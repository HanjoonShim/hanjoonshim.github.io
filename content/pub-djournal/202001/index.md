---

#-------------------------------------------------------------
title: "Single Frequency GPS Relative Navigation for Autonomous Rendezvous and Docking Mission of Low-Earth Orbit Cube-Satellites"
authors:
- admin
- O-Jong Kim
- Sunkyoung Yu
- kee
- Dong-Hyun Cho 
- Hae-Dong Kim
date: "2020-12-01T00:00:00Z"
# doi: "https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002656314​"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Positioning, Navigation, and Timing 9*, no.4, pp. 357-366. 10.11003/JPNT.2020.9.4.357"
publication_short: ""

abstract: This paper addressed a relative navigation method for autonomous rendezvous and docking of cube-satellites using single frequency Differential GPS (DGPS) under the intermittent communication between satellites. Since the ionospheric error of GPS measurement is variable depending on the visible satellites, a few meters error of relative navigation is occurred in the Low-Earth Orbit (LEO) environment. Therefore, it is essential to remove the ionospheric error to perform relative navigation. Besides, an intermittent communication period for receiving GPS measurements of the target satellite is limited for getting information every sampling time. To solve this problem, a method combining range domain DGPS and orbit propagation is proposed in this paper. The proposed method improves the performance of DGPS by using Hatch filter and solves an intermittent communication problem by estimating the relative position and velocity using Hill-Clohessy-Wiltshire Equation. Through the simulation, it is verified that the suggested algorithm provides the relative position error within RMS 0.5 m and the relative velocity error within RMS 3 cm/s. Furthermore, it has the advantage that it is suitable for real-time implementation using single-frequency GPS measurements and is computationally efficient.

tags:
- KARDSAT
featured: false

# links: 
# - name: ""
# url_pdf: https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002656314
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002656314'
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
projects: [KARDSAT]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
