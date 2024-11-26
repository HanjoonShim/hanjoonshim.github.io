---

#-------------------------------------------------------------
title: "Precise GPS Relative Navigation for CubeSat Rendezvous"
authors:
- admin
date: "2024-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: "[Doctorial Dissertation, Seoul National University]"
publication_short: ""

abstract: "This dissertation addresses the challenge of achieving precise GPS relative navigation for CubeSat rendezvous missions. Unlike conventional methods applied to medium and large satellites, this research focuses on autonomous missions utilizing low-cost, commercially-available CubeSat platforms. In this context, the design challenges for an efficient and reliable GPS relative navigation system are redefined to include issues related to hardware performance degradation, which are directly linked to the spatial limitations of the CubeSat platform. It is found that most existing relative navigation systems for CubeSats employ GPS only as a supplementary measurement and do not resolve the carrier phase integer ambiguities, making centimeter-level accuracy difficult to achieve through real-time ambiguity resolution. 
Previous systems predominantly used algorithms that rely on electro-optical methods to recognize target satellites, often conservatively utilizing the relative position data provided by GPS receivers. By contrast, the proposed high-precision GPS relative navigation system aims to achieve real-time, centimeter-level accuracy using solely GPS receivers, thereby enhancing the operational capabilities of CubeSats in low Earth orbit (LEO). This system seeks to overcome the spatial limitations of CubeSats and fundamentally address the real-time ambiguity-fixing problems inherent in carrier phase measurements.
The approach begins with relative navigation between the chaser and target satellites using Differential GPS (DGPS), utilizing a Hatch filter to reduce noise. It then analyzes the statistical characteristics of the search space for carrier phase ambiguities derived from positional errors. However, the statistical characteristics of ambiguities based solely on DGPS are insufficient to utilize efficient search spaces such as those employed by linear combination techniques of multi-frequency carrier-phase measurements in ground-based Real-Time Kinematics (RTK) systems. Thus, the study combines these characteristics with the spatial characteristic index, Ambiguity Dilution of Precision (ADOP), to enhance the success rate of the LAMBDA method for carrier phase ambiguity resolution, thereby implementing RTK relative navigation. The LEO environment, with its many visible satellites and high-quality measurements, suggests that reliable ambiguity resolution with minimal computation is achievable–even with single-frequency measurements.
Additionally, a recursive filter for carrier phase ambiguity estimation, derived using weighted least squares from DGPS relative positions and observations, is introduced. This filter (similar to the nonlinear Kalman filter used in standard RTK) refines the ambiguity search range with updates solely from single-frequency measurements. Unlike conventional methods that rely on empirical estimates of carrier phase ambiguities through dynamic model time updates, this approach sequentially reflects the statistical characteristics of observed ambiguities from estimated initial relative positions. In this way, it is possible to narrow down the candidate search range and enhance the reliability of ambiguity resolution with minimal computational demand. Importantly, this also ensures a robust 100% success rate in resolving integer ambiguities, even with minimal satellite visibility, while minimizing residual errors and reducing the computational burden of ambiguity resolution.
Another advantage of the proposed system is its ability to detect cycle slips through the relative dynamics model between rendezvousing satellites, which facilitates the prediction of relative motion via orbit propagation–even in scenarios of communication failure. Relative accelerations derived from the linear relative motion model of closely operating CubeSats are used to determine cycle slips and predict the motion of the target satellite.
In order to demonstrate the utility of the proposed precise GPS relative navigation system, performance verification results from simulations in LEO and ground-based measurements are presented. The algorithm adapts to changes in the arrangement of GPS satellites caused by their high-speed maneuvering in orbit. Furthermore, hardware that corresponds to actual CubeSat platforms is used to predict and confirm both the resolution of ambiguities and the superior relative navigation performance–even under worst-case ground measurement scenarios. As a result, the proposed relative navigation system ensures both high accuracy of the single-frequency GPS receivers and high applicability for various missions because it is compatible with low-cost satellite platforms."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
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
url_source: 'https://snu-primo.hosted.exlibrisgroup.com/primo-explore/fulldisplay?docid=82SNU_INST51953490020002591&vid=82SNU&search_scope=ALL&tab=all&lang=ko_KR&context=L'
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
