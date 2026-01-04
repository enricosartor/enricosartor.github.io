---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: 'Research Focus'
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      css_class: hero-tight
      spacing:
      # Top, Right, Bottom, Left
        padding: ['10px', '0', '10px', '0']
      columns: '1'
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: 'About Me'
      subtitle: ''
      text: |-
        I am Enrico Sartor, a PhD student in Applied Mathematics at the École Doctorale Jacques Hadamard (EDMH), hosted at the Laboratoire des Signaux et Systèmes (L2S). My research focuses on partially observable stochastic control. More broadly, I am interested in optimal control for PDEs and SDEs, and in its connections with optimal transport and Wasserstein geometry (e.g., mean-field optimal control). I am also interested in the mathematical foundations of machine learning, especially neural networks and reinforcement learning.

        Before starting my PhD, from November 2024 to August 2025, I worked as a research assistant under the supervision of Prof. Enrique Zuazua at the Chair for Dynamics, Control, Machine Learning and Numerics at Friedrich-Alexander-Universität Erlangen–Nürnberg, on optimal control of coagulation–fragmentation equations.

        I obtained my Master’s degree in Mathematics from the University of Udine in October 2024 (110/110 cum laude). During my Master’s, I spent six months as a visiting student at ETH Zürich in the research group of Prof. Florian Dörfler, working on my thesis “A Pontryagin minimum principle for sparse optimal control in the Wasserstein space”. I received my Bachelor’s degree in 2022 from the University of Udine, with a thesis on the improbability of collisions in the $N$-body problem.

        In March 2025, I also completed the diploma of the Scuola Superiore Universitaria di Toppo Wassermann, a merit-based honors program offering advanced coursework and research training alongside university studies.

    design:
      columns: '1'
      css_class: about-wide

  - block: collection
    id: news
    content:
      title: "News"
      count: 5
      filters:
        folders:
          - news
        kinds:
          - page
---