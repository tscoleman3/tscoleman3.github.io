---
title: "Tour"
date: 2024-10-24
type: landing

# Top: Visual slider (quick hits)
sections:
  - block: slider
    content:
      slides:
        - title: "From Data to Decisions"
          content: "Field observations transformed into quantitative insight across scales."
          align: right
          background:
            image:
              filename: tour-field.jpg      # <-- add to assets/media/
              filters: { brightness: 0.7 }
            position: center
            color: "#333"
        - title: "Applied Science for Action"
          content: "Turning analytics into guidance for conservation, restoration, and policy."
          align: left
          background:
            image:
              filename: tour-management.jpg  # <-- add to assets/media/
              filters: { brightness: 0.65 }
            position: center
            color: "#222"
        - title: "Coupled Systems, Real Solutions"
          content: "Integrating people and ecosystems to reveal the dynamics that shape our world."
          align: right
          background:
            image:
              filename: tour-chans.jpg       # <-- add to assets/media/
              filters: { brightness: 0.65 }
            position: center
            color: "#222"
        - title: "Mentorship and Impact"
          content: "Empowering students with the tools to design studies, analyze data, and drive change."
          align: center
          background:
            image:
              filename: tour-mentorship.jpg  # <-- add to assets/media/
              filters: { brightness: 0.65 }
            position: center
            color: "#222"
    design:
      slide_height: ""     # auto height
      is_fullscreen: true
      loop: false
      interval: 2500

  # Middle: 4 pillars as visual cards
  - block: features
    content:
      title: "What You'll See"
      items:
        - icon: flask
          icon_pack: fas
          name: "Field → Data → Decisions"
          description: "From sampling plans and QA/QC to tidy data pipelines that drive management."
        - icon: chart-line
          icon_pack: fas
          name: "Quantitative Ecology"
          description: "Statistical modeling, forecasting, and decision-support tools."
        - icon: users
          icon_pack: fas
          name: "CHANS Perspective"
          description: "Coupled human–natural systems as the default lens for aquatic science."
        - icon: graduation-cap
          icon_pack: fas
          name: "Mentorship"
          description: "Hands-on field skills, reproducible analysis, and clear communication."
    design:
      columns: 2

  # Impact banner (one distilled line)
  - block: hero
    content:
      title: "Impact"
      text: "We connect rigorous science with management, restoration, and communities to safeguard aquatic ecosystems."
      buttons:
        - label: "Explore Research"
          url: "/publications/"
          style: primary
        - label: "Meet the Team"
          url: "/people/"
          style: outline
    design:
      background:
        image:
          filename: tour-impact.jpg   # make sure this exists in assets/media/
          filters: { brightness: 0.55 }
        color: "#111"
        text_color_light: true
---