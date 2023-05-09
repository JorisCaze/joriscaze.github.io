---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: C / C++
          description: ''
          icon: code
          icon_pack: fas
        - name: Git
          description: ''
          icon: code-branch
          icon_pack: fas
        - name: Bash / Python
          description: ''
          icon: terminal
          icon_pack: fas
        - name: Docker / Slurm / Open-MPI
          description: ''
          icon: server
          icon_pack: fas
        - name: Gmsh / PointWise / Salome
          description: ''
          icon: shapes
          icon_pack: fas
        - name: ParaView
          description: ''
          icon: photo-video
          icon_pack: fas
        - name: Compressible flows
          description: ''
          icon: tint
          icon_pack: fas
        - name: Heat transfer / Phase change
          description: ''
          icon: fire
          icon_pack: fas
        - name: Numerical methods
          description: ''
          icon: desktop
          icon_pack: fas

  - block: experience
    id: experiences
    content:
      title: Experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Temporary research associate
          company: Aix-Marseille Université
          company_url: 'https://www.univ-amu.fr/'
          company_logo: amu
          location: 'Marseille'
          date_start: '2022-10-01'
          date_end: ''
          description: |2-
            * Development of the numerical scheme of the open-source CFD solver [ECOGEN](https://code-mphi.github.io/ECOGEN/) at 2nd order on unstructured meshes (C/C++).
            * Hardware & software configuration of new team servers with RAID management + backup.
            * Migration of team GitLab repository and CI/CD update.
            * Teaching of mechanics courses at the Aix-Marseille university.
            
        - title: PhD Student
          company: CNES
          company_url: 'https://cnes.fr/fr/'
          company_logo: cnes
          location: Marseille
          date_start: '2019-10-01'
          date_end: '2022-09-30'
          description: |2-
              Simulation of multiphase flows within spacecraft turbopumps under the supervision of Eric Daniel and Fabien Petitpas.
              Topics of work include:

              * Contribution to the development in C/C++ of compressible single-phase/two-phase flow models in the open-source computationnal software [ECOGEN](https://code-mphi.github.io/ECOGEN/). ([article](https://hal.archives-ouvertes.fr/hal-03387818))
              * Management of GitLab/[GitHub](https://github.com/code-mphi/ECOGEN) team repositories.
              * Setup and management of team HPC servers (Open-MPI, Slurm, disk-quota).
              * Simulation of the cavitation phenomenon within turbopumps using diffuse interface two-phase flow models ([thesis](https://www.theses.fr/2022AIXM0360)).
              * Adaptation of a two-phase flow model in mechanical equilibrium to take into account the movement of pump blades using the moving reference frame method. ([article](https://doi.org/10.1115/GT2022-78025))
              * Teaching of phase change and computationnal fluid dynamics at the Polytech Marseille engineering school.

        - title: Trainee Engineer (3rd year engineering school)
          company: IUSTI Laboratory
          company_url: 'https://iusti.cnrs.fr'
          company_logo: iusti
          location: 'Marseille'
          date_start: '2019-02-01'
          date_end: '2019-07-31'
          description: |2-
            Simulation of fluid flows within turbopumps.

            * Simulation of the fluid flow within a dynamic seal of a pump using the open-source solver [ECOGEN](https://code-mphi.github.io/ECOGEN/).
            * Development of a C++ [tool](https://github.com/code-mphi/NASG-EOS_Calibration) to calibrate liquid/vapor equation of state parameters with experimental data.

        - title: Trainee Engineer (2nd year engineering school)
          company: 'CEA'
          company_url: 'http://cadarache.cea.fr/cad'
          company_logo: cea
          location: 'Cadarache'
          date_start: '2018-06-04'
          date_end: '2018-08-10'
          description: |2-
            Creation of a dataset for the simulation of sodium slick fires in a reactor vessel during a severe accident in a sodium-cooled Fast Neutron Reactor. 
            * Scientific computing tool used: CONTAIN-LMR.

        - title: 'Trainee Engineer (1st year engineering school)'
          company: 'Process Poudres Innovations'
          company_url: 'https://www.ppinnov.com/'
          company_logo: ppi
          location: 'Peypin'
          date_start: '2017-06-01'
          date_end: '2017-06-30'
          description: |2-
            Assembly of transfer and dosing machines for powders and granules of the food and pharmaceutical industries.
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: compact

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: joris.caze[at]gmail.com
      address:
        street: 5 Rue Enrico Fermi
        city: Marseille
        region: 
        postcode: '13013'
        country: France
        country_code: FR
      coordinates:
        latitude: '43.344470'
        longitude: '5.437420'
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/in/joris-caze/'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
