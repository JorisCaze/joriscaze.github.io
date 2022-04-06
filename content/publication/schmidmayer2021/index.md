---
title: "Modelling interactions between waves and diffused interfaces"
authors:
- Kevin Schmidmayer
- admin
- Fabien Petitpas
- Eric Daniel
- Nicolas Favrie
date: "2021-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal for Numerical Methods in Fluids"
publication_short: ""

abstract: When simulating multiphase compressible flows using the diffuse-interface methods, the test cases presented in the literature to validate the modellings with regard to interface problems are always textbook cases, interfaces are sharp and the simulations therefore easily converge to the exact solutions. In real problems, it is rather different because the waves encounter moving interfaces which consequently have already undergone the effects of numerical diffusion. Numerical solutions resulting from the interactions of waves with diffused interfaces have never been precisely investigated and for good reasons, the results obtained are extremely dependent on the model used. Precisely, well-posed models present similar and important issues when such an interaction occurs, coming from the appearance of a wave-trapping phenomenon. To circumvent those issues, we propose to use a thermodynamically-consistent pressure-disequilibrium model with finite, instead of infinite, pressure-relaxation rate to overcome the difficulties inherent in the computation of these interactions. Because the original method to solve this model only enables infinite relaxation, we propose a new numerical method allowing infinite as well as finite relaxation rates. Solutions of the new modelling are examined and compared to literature, in particular we propose the study of a shock on a water--air interface, but also for problems of helium--air and water--air shock tubes, spherical and non-spherical bubble collapses.

# Summary. An optional shortened abstract.
summary: A new pressure-relaxation is proposed to circumvent wave propagation issues of diffuse-interface methods in the context of multiphase compressible flows.

tags:
- Diffuse-interface method
- Compressible multiphase flows
- Relaxation

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://hal.archives-ouvertes.fr/hal-03387818/document
url_code: 'https://code-mphi.github.io/ECOGEN/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Propagation of a shock into a diffused interface'
  focal_point: ""
  preview_only: false
---
