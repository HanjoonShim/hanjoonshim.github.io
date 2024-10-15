---

#-------------------------------------------------------------
title: "HILS Verification of Low Earth Orbit Cube-Satellite Attitude Determination and Control System Using Helmholtz Cage"
authors:
- admin
date: "2019-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: "[Master's Thesis, Seoul National University]"
publication_short: ""

abstract: In this thesis, Hardware-In-the-Loop Simulation (HILS) verification of attitude determination and control system (ADCS) is addressed for low earth orbit cube-satellite equipped with a magnetorquer only. Unlike ordinary satellites equipped with reaction wheels, only a magnetorquer is mounted on cube-satellite due to spatial constraints. It is a simple, low-weight, and low-power consumption actuator that enables efficient operation of cube-satellite and aims to maintain nadir-pointing control. In order to achieve the objective of the proposed system, firstly, the equations of motion for the cube-satellite is expressed in terms of the gravity gradient torque, and the input torque calculated from the dipole moment of the magnetorquer and geomagnetic field. Then, a linear system model is obtained by interpreting the uncertainty flowing into the system as noise sources. In addition, extended Kalman filter equations are derived to estimate the attitude of the cube-satellite by defining the reference vector from the sun and magnetic field model, and fusing the sun sensor, magnetometer, and gyroscope measurements. Then, LQR controller can be designed to maintain nadir-pointing by calculating the optimal solution from the cost function composed of a given linear system and input. In order to verify the performance of the proposed system, HILS should be performed considering various constraints of the ground environment. However, it is difficult to verify the above-described system in a ground environment due to limitations in the performance of magnetorquer such as small input torque effected by the magnitude of the geomagnetic field, and decoupled input control. So far, it has been studied that the verification of cube-satellite ADCS for the stabilization of angular velocity, the passive control method which depends on geomagnetic field alignment, and HILS using reaction wheels. HILS of ADCS using only magnetorquer also has been proposed, but the performance analysis was limited due to the constraints of the ground environment. In contrast, the proposed HILS is aimed at verifying magnetorquer mounted cube-satellite ADCS that solves the limitations from unknown error factors of the ground environment. Therefore, in this thesis, HILS verification of cube-satellite ADCS using Helmholtz cage is proposed. It is focused on output characteristics proportional to the magnitude of the external magnetic field of the magnetorquer. In other words, it is solved by controlling the magnetic field vector generated from Helmholtz cage that is the degradation of the estimation performance due to the magnetic field including the statistical error characteristic in the indoor environment and the control performance deterioration due to the small input torque of the magnetorquer which is vulnerable to the disturbance. To construct a magnetic field vector from Helmholtz cage, it is designed using the Biot-Savat law to model the current-magnetic field relationship. Also, it is designed to have a size enough to ensure the magnetic field uniformity of the space including the cube-satellite. The magnetic field vector controller of Helmholtz cage can be easily designed by approximating the transfer function from the derived current-magnetic field equation and using the classical control technique. In this case, cube-satellite is suspended in the inner space of Helmholtz cage to perform single axis HILS verification of ADCS. Since the GPS measurement value cannot be calculated in the indoor experiment environment, the nadir-pointing reference vectors are redefined by the mean measurement values of the simulated sunlight and the magnetic field generated from Helmholtz cage. Then, by defining a coordinate system based on the Helmholtz cage in the proposed HILS environment, nadir-pointing control performance can be expected by the computer simulation. Based on these simulation results, the proposed system can be verified by comparison with actual experimental results. To demonstrate the validity of the proposed method, a single axis HILS verification of ADCS using SNUGLITE cube-satellite is presented. The proposed method can verify the performance of nadir-pointing control on the ground by using only the magnetorquer which is typically installed in cube-satellite. It is also confirmed that the estimation performance and the control reliability of ADCS can be verified effectively compared with the method which does not utilize Helmholtz cage. The proposed HILS verification technique is expected to be used for verification of cube-satellite ADCS for various tasks due to its simplicity and practicality.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://s-space.snu.ac.kr/handle/10371/150647'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
