---

#-------------------------------------------------------------
title: "Verification of Space GPS Receiver Navigation Performance Using a Cube Satellite"
authors:
- Sunkyoung Yu
- O-Jong Kim
- admin
- Yonghwan Bae
- Changdon Kee
- Hakdu Kim
- Jungchul Lee
- Jinhee Han
- Sanghyuck Han
- Yeonju Choi
- Wonsup Choi
date: "2020-01-21T00:00:00Z"
doi: "https://doi.org/10.33012/2020.17174"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2020 International Technical Meeting of The Institute of Navigation*, San Diego, California, January 2020, pp. 736-744"
publication_short: ""

abstract: SNUGLITE(Seoul National University GNSS Laboratory Satellite) is 2U-size Low Earth Orbit (LEO) CubeSat (U-class spacecraft). Attitude Determination and Control System (ADCS) of CubeSat is designed to maintain its attitude at the Earth pointing. For determining satellite's attitude, Extended Kalman Filter (EKF) and Linear Quadratic Gaussian (LQG) algorithm were applied. Specifically, multiple sensors - dual frequency GPS receiver, 3-axis gyroscope, magnetometer and sun sensors - were used with models Jet Propulsion Laboratory sun reference Development Ephemeris (JPL DE405) and International Geomagnetic Reference Field (IGRF12). Moreover, 3-axis magnetorquer was used as a single actuator. Generally, the verification of ADCS algorithm starts from software-in-the-loop simulation (SILS) developed and verified in software tools such as MATLAB. After verification of SILS, Processor-in-the-Loop simulation (PILS) is required to verify the ADCS algorithm implementing in the processor of On Board Computer (OBC) in C-language. Finally, satellite’s ADCS algorithm is needed to be verified experimentally by hardware-in-the-loop simulation (HILS) in the space-like environment under a ground-based setting using a massive simulator. Most of satellite attitude HILS is composed of sensors such as air-bearings, Helmholtz coil, and array sun sensors. In this paper, to verify ADCS algorithm in HILS, the precise attitude estimation, modeling and calibration of sensors (magnetometer, gyroscope and coarse sun sensor) are presented. In addition, a low-cost single-axis HILS verification method is proposed using simple testbed hanging CubeSat with a wire. By using the Earth’s magnetic field on the ground and the light from Halogen lamp, the space environment has been implemented on the ground in order to verify attitude determination and control performance in a single axis. In conclusion, the results of the HILS ensure that the performance of the proposed algorithm meets the estimation and the control requirements of the SNUGLITE.


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
