---
title: Publications
date: 2026-01-01
type: landing

design:
  css_class: "nio-pubs"
  spacing:
    padding: [0, 0, 0, 0]

sections:
  - block: hero
    content:
      title: Publications
      text: "Selected and full publications from OMNI-Lab."
      # primary_action:
      #   text: Google Scholar
      #   url: https://scholar.google.com/...
      # secondary_action:
      #   text: ORCID
      #   url: https://orcid.org/...
    design:
      background:
        color: "#0b1220"
        gradient_start: "#0b1220"
        gradient_end: "#111827"
        text_color_light: true
      spacing:
        padding: [60, 0, 40, 0]

  - block: collection
    id: pubs
    content:
      title: ""
      text: ""
      collection: publications
      count: 1000
      sort_by: date
      sort_ascending: false

      filter_default: 0
      filter_show_count: true
      filter_show_search: true
      filter_show_sort: true
      filter_show_year: true
      filter_show_type: true
      group_by: year

      filters:
        - name: All
          tag: "*"
        - name: OMIECs
          tag: OMIEC
        - name: n-Type
          tag: n-type
        - name: Device
          tag: OECT
        - name: Simulation
          tag: simulation

    design:
      view: citation
      columns: "1"
      spacing:
        padding: [10, 0, 70, 0]

  - block: markdown
    content:
      title: ""
      text: |
        <div class="pubs-note">
        **Tip:** Add publications by creating files under `content/publication/` (one per paper)  
        or import from BibTeX (recommended) and let the page render automatically.
        </div>
    design:
      spacing:
        padding: [0, 0, 30, 0]
---

