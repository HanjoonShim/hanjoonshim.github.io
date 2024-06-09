---

#-------------------------------------------------------------
title: "Real-time Software Verification Technique of Attitude Determination and Control System for CubeSat"
authors:
- admin
- Yonghwan Bae
- kee
date: "2023-03-01T00:00:00Z"
doi: "https://doi.org/10.5139/JKSAS.2023.51.3.207​"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of the Korean Society for Aeronautical & Space Sciences, Vol. 51*, Issue 3, pp. 207-216"
publication_short: ""

abstract: This paper presents a real-time software verification technique for the attitude determination and control system (ADCS) of CubeSats. The on-board computer (OBC) of the CubeSat is equipped with a single core and limited redundancy, making it essential for reliable software to be installed. In consideration of cost, development time, resources, and manpower, an accessible software verification method is necessary. Based on this point of view, this paper first performs a model-in-the-loop simulation (MILS) using MATLAB, a commonly used software in educational institutions for ADCS design. Based on the designed model, software verification is performed by separating the space environment simulator, which provides dynamic models and sensor measurements, and the ADCS module. RS-232 communication is used for data input and output between these modules, and MATLAB-based software-in-the-loop simulation (SILS) and OBCbased processor-in-the-loop simulation (PILS), which is implemented in a real-time operating system (RTOS), are performed. The validity of the implemented software is verified by comparing the results. The proposed technique was validated by presenting the numerical errors of the SILS and PILS results of the SNUGLITE-II CubeSat ADCS.

tags:
- SNUGLITE-II
featured: false

# links: 
# - name: 511007.pdf
url_pdf: uploads/pub-dj-202301.pdf
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
