---

#-------------------------------------------------------------
title: "Precise in-orbit relative navigation technique for rendezvous mission of CubeSats using only GPS receivers"
authors:
- admin
- O-Jong Kim
- Sunkyoung Yu
- Changdon Kee
- Dong-Hyun Cho
- Hae-Dong Kim
date: "2023-04-08T00:00:00Z"
doi: "https://doi.org/10.1007/s12567-023-00488-x"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*CEAS Space Journal, Vol. 16*, 117-137"
publication_short: ""

abstract: This paper proposes a global positioning system (GPS) based relative navigation algorithm for CubeSats that perform autonomous rendezvous and docking missions. To realize precise relative navigation using only GPS, an algorithm is developed to improve the differential GPS (DGPS) performance by reducing the integer ambiguity search space of carrier-phase DGPS. To this end, a Hatch filter is used to improve the pseudorange noise performance, and range-domain DGPS-based single-frequency relative navigation is realized. Because GPS measurements are transmitted intermittently using an inter-satellite link, orbit propagation is performed using the Hill–Clohessy–Wiltshire equation. Moreover, to improve the performance of the propagation error accumulated over time, an in-orbit velocity moving average filter is incorporated. Because the rate change of relative motion in the local-vertical-local-horizontal coordinate system on the orbit is small, the noise level for the relative velocity and overall relative navigation system performance are improved. To demonstrate the usefulness of the proposed method, software-in-the-loop simulation and processor-in-the-loop simulation-based real-time implementation is realized on the onboard computer of a reference CubeSat (SNUGLITE-III A, target) and thruster-equipped CubeSat (SNUGLITE-III B, chaser), and their performances are evaluated.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- KARDSAT
- SNUGLITE-III
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1007/s12567-023-00488-x
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
projects: [KARDSAT]

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
