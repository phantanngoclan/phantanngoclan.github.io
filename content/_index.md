---
title: "Home"
date: 2026-01-01
type: landing

design:
  spacing: "4rem"

sections:
  # =========================
  # HERO (big image + title)
  # =========================
  - block: hero
    content:
      title: 'Organics Materials for Next Innovations'
      text: "Exploring novel materials towards advanced disciplinary applications"
      primary_action:
        text: "Research"
        url: "/research/"
        icon: beaker
      secondary_action:
        text: "Publications"
        url: "/publication/"
        icon: document-text
    design:
      css_class: "dark"
      # add `min-h-screen` if you want full screen hero
      # css_style: "min-height: 80vh;"
      background:
        color: "black"
        image:
          filename: "lab-hero.jpg"
          filters:
            brightness: 0.45
          size: cover
          position: center
          parallax: false

  # ===== ABOUT =====
  - block: markdown
    content:
      title: ""
      text: |
        **We design and study organic electronic & functional soft materials** spanning OMIECs, conjugated polymers, mixed ionic–electronic transport, and molecular engineering.
    
        Our lab combines **molecular design**, **simulation**, and **device-oriented characterization** to understand structure–property–function relationships.

  # ===== FOCUS AREAS =====
  - block: features
    content:
      title: "Research Areas"
      items:
        - name: "Molecular design"
          icon: sparkles
          description: "Rational backbone and side-chain engineering."
        - name: "Simulation"
          icon: cpu-chip
          description: "DFT, force-field development, and MD simulations."
        - name: "OMIECs"
          icon: bolt
          description: "Structure–property relations under electrochemical doping."
        - name: "Thin films"
          icon: squares-2x2
          description: "Morphology, aggregation, and processing effects."
    design:
      css_class: "home-wide"

  # ===== CTA =====
  - block: cta-card
    content:
      title: "Join or collaborate with us"
      text: "We welcome motivated students and collaborators."
      button:
        text: "Contact"
        url: "/contact/"
---
