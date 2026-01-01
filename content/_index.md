---
title: "Home"
type: landing

design:
  spacing: "5rem"

sections:
  # ===== HERO =====
  - block: hero
    content:
      title: "OMNI"
      subtitle: "Organics Materials for Next Innovations"
      text: |
        We design, simulate, and understand organic (opto)electronic materials,
        connecting **molecular structure** to **device performance**.
      primary_action:
        text: "Research"
        url: "/research/"
        icon: beaker
      secondary_action:
        text: "Publications"
        url: "/publication/"
    design:
      css_class: "home-hero-wide dark"
      background:
        color: "black"

  # ===== ABOUT =====
  - block: markdown
    content:
      title: "About"
      text: |
        **OMNI Lab** focuses on organic semiconductors and mixed ionic–electronic
        conductors (OMIECs), spanning:

        - Molecular & side-chain design  
        - Multiscale simulations (DFT → MD)  
        - Thin films, morphology, and devices  
        - OECTs, photovoltaics, and energy materials
    design:
      css_class: "home-wide"

  # ===== FOCUS AREAS =====
  - block: features
    content:
      title: "Research focus"
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
