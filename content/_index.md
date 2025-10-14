---
title: ""
date: 2025-10-13
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: >-
        I’m **Hamza BOUDHAIR**, a renewable energy engineer specializing in the
        **modeling, simulation, and optimization** of photovoltaic and wind systems.
        I hold a **Master’s degree in Electronics and Materials for Renewable and
        New Energies** from the Faculty of Polydisciplinary Studies of Ouarzazate (Morocco).
        My experiences include **ENSA Agadir Energy & Environment Lab**, **ECOWATT**,
        and the **Regional Directorate of Energy**. Passionate about innovation and
        sustainability, I focus on **energy efficiency**, **hybrid storage**, and **AI-based optimization**.
      button:
        text: Download CV
        url: "https://drive.google.com/file/d/1WVR5Z5YO_u4jA9zIVkYhye9MBx3cq6_C/view?usp=sharing"
      headings:
        about: "About Me"
        education: "Education"
        interests: "Research Interests"
    design:
      avatar:
        size: large
        shape: circle

  - block: markdown
    content:
      title: "⚡ Research & Expertise"
      subtitle: ""
      text: |-
        My research focuses on **renewable energy systems**, particularly the **simulation,
        optimization, and techno-economic analysis** of solar and wind systems.

        I am also exploring the **reliability and degradation of PV modules** in desert environments,
        **hybrid energy storage** (including gravity-based systems), and **AI applications**.
    design:
      columns: "1"

  - block: collection
    id: papers
    content:
      title: "📄 Featured Publications"
      filters:
        folders: [publications]
        featured_only: true
    design:
      view: article-grid
      columns: 2

   - block: gallery
    content:
      title: "🎓 Certifications"
      subtitle: "Professional & Technical Training"
      text: "Recognized certifications demonstrating technical and analytical expertise in renewable energy and research tools."
      items:
        - image: "schneider-finance.jpg"
          caption: "Schneider Electric University — Analyse financière des projets I (2024)"
        - image: "schneider-audit.jpg"
          caption: "Schneider Electric University — Instruments de mesure pour les audits énergétiques I (2023)"
        - image: "clarivate-wos.jpg"
          caption: "Clarivate — Exploring a Research Topic with the Web of Science (2025)"
    design:
      view: masonry
      columns: 3

  - block: collection
    id: projects
    content:
      title: "🧩 Featured Projects"
      filters:
        folders: [projects]
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: "Latest Projects"
      filters:
        folders: [projects]
        exclude_featured: false
    design:
      view: card

  - block: collection
    id: news
    content:
      title: "📰 Recent News & Updates"
      page_type: blog
      count: 5
      filters:
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    content:
      title: "🌍 Let's Collaborate"
      text: |-
        I’m always open to collaborations in **renewable energy modeling, optimization,
        and AI-assisted design**. Feel free to reach out for academic or industrial projects.

        📧 **hamza.boudhair@gmail.com**  
        🔗 LinkedIn: [https://www.linkedin.com/in/hamza-boudhair](https://www.linkedin.com/in/hamza-boudhair)
      button:
        text: "Contact Me"
        url: "mailto:hamza.boudhair@gmail.com"
    design:
      card:
        css_class: "bg-primary-300"
---
