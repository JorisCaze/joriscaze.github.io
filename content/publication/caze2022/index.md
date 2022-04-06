---
title: "Modeling and simulation of a turbopump flow: a multiphase approach"
authors:
- admin
- Fabien Petitpas
- Eric Daniel
- Sébastien Le Martelot
- Matthieu Queguineur
date: "2022-06-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ASME Turboexpo 2022 - Turbomachinery Technical Conference and Exposition"
publication_short: "ASME Turboexpo 2022"

abstract: In this study, cryogenic flows in rocket engine that may undergo a phase change because of a loss of pressure in pump, or any depressurization process are considered. We proposed a well-posed mathematical representation for this kind of flow as well as the numerical model for seeking the solutions. The two important points addressed in this study are the compressibility of the phases and the use of a rotating reference frame. The compressibility effects are quite essentials to obtain a physical and realistic cavitation model through the equation of state of the fluids (liquid and vapor), while the moving reference frame being the way we chose to model the pump motion. The model we develop is based on conservation equations of mass, momentum and energy for each phase plus a non-conservative equation evolution for the volume fraction. The description of the flow is based on the diffuse interface method, the interfaces appear naturally in the flow (interfaces between vapor and liquid for example) and do not require any interface tracking method. The phase change process is based on a stiff relaxation procedure using thermodynamic equilibrium considerations. Results related to a pump application are then presented using the open-source platform ECOGEN where the present numerical method is implemented. The model is able to produce a quite realistic pump characteristic curve where the relationship between the pump overpressure and its operating mass flow rate is expressed. In these first calculations it will be shown that cavitation may occur in some regions of the flow and that the multiphase approach is suited for this study.

# Summary. An optional shortened abstract.
summary: Cavitation within spacecraft turbopumps is studied using diffuse-interface multiphase model for which blades rotation is taken into account by use of the Moving Reference Frame method.

tags:
- Diffuse-interface method
- Compressible multiphase flows
- Moving Reference Frame
- Phase change

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: '#'
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
  caption: 'Cavitation on a three blades inducer'
  focal_point: ""
  preview_only: false
---
