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
      text: "Selected and full publications from OMNI-Guy."
    design:
      background:
        color: "#0d3b66"
        gradient_start: "#0b1220"
        gradient_end: "#111827"
        text_color_light: true
      spacing:
        padding: [60, 0, 40, 0]

  - block: collection
    id: pubs
    content:
      # Render from content/publication/
      collection: publications
      count: 1000
      sort_by: date
      sort_ascending: false

      # Built-in UI controls (safe across recent Hugo Blox versions)
      filter_show_count: true
      filter_show_search: true
      filter_show_sort: true
      filter_show_year: true
      filter_show_type: true

      # NOTE: Do NOT add `filters:` here unless you match the exact schema
      # expected by your theme version. A wrong schema causes build failure.

    design:
      view: citation
      columns: "1"
      spacing:
        padding: [10, 0, 70, 0]

  - block: markdown
    content:
      text: |
        <div class="pubs-note">
        **Tip:** Add publications by creating files under `content/publication/` (one per paper)  
        or import from BibTeX and let this page render automatically.
        </div>
    design:
      spacing:
        padding: [0, 0, 30, 0]
---

