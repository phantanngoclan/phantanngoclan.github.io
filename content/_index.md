---
title: "Home"
date: 2026-01-01
type: landing

design:
  spacing: "5rem"

sections:
  # ===== HERO =====
  - block: hero
    content:
      title: |
        <div class="hero-title-wrap">
          <div class="hero-acronym">
            <span class="omni">
              <span class="blink b1">O</span>
              <span class="blink b2">M</span>
              <span class="blink b3">N</span>
              <span class="blink b4">I</span>
            </span>
          </div>
          <div class="hero-fullname">
            Organics Materials for Next Innovations
          </div>
        </div>
      text: |
        We design, simulate, and characterize organic (opto)electronic materials—linking molecular design to device performance.
      primary_action:
        text: "Research"
        url: "/research/"
        icon: beaker
      secondary_action:
        text: "Publications"
        url: "/publication/"
      announcement:
        text: "Open positions: PhD / MS / Interns"
        link:
          text: "See details"
          url: "/join/"
    design:
      css_class: "dark home-hero-wide"
      background:
        color: "black"
        image:
          filename: "lab-hero.jpg"
          filters:
            brightness: 0.35
          size: cover
          position: center
          parallax: false

  # ===== QUICK INTRO =====
  - block: markdown
    content:
      title: "About"
      text: |
        **OMNI** is focused on organic semiconductors and mixed ionic–electronic conductors (OMIECs),
        spanning **molecular design → simulations → thin films/devices**.

        - **Computational design:** DFT/MD/ML-enabled screening and mechanistic understanding  
        - **Materials:** conjugated polymers, n-type acceptors, macrocycles  
        - **Applications:** OECTs, photovoltaics, sensors, energy storage

        👉 If you’re interested in collaborating, please reach out via the **Contact** page.
    design:
      css_class: "home-wide"

  # ===== FOCUS AREAS =====
  - block: features
    content:
      title: "Focus areas"
      text: ""
      items:
        - name: "Molecular design"
          icon: sparkles
          description: "Backbone/side-chain engineering for stability, transport, and ion uptake."
        - name: "Multiscale simulation"
          icon: cpu-chip
          description: "DFT → force fields → MD films/solutions to connect structure and function."
        - name: "OMIECs & devices"
          icon: bolt
          description: "From morphology and swelling to electronic performance in OECT-relevant conditions."
        - name: "Structure–property"
          icon: chart-bar
          description: "Quantify how packing, planarity, and disorder impact transport and doping."
        - name: "Thin-film morphology"
          icon: squares-2x2
          description: "Annealing, solvent effects, aggregation pathways, and phase behavior."
        - name: "Open science"
          icon: code-bracket
          description: "Reusable workflows, scripts, and reproducible simulation pipelines."
    design:
      css_class: "bg-gray-50 dark:bg-gray-950 home-wide"

  # ===== CTA =====
  - block: cta-card
    content:
      title: "Want to work with us?"
      text: "We welcome collaborations and motivated students."
      button:
        text: "Join / Contact"
        url: "/contact/"
    design:
      card:
        css_class: "bg-primary-300"
---
