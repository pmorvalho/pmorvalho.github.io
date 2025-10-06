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
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      # button:
        # text: Download CV
        # url: uploads/resume.pdf      
      headings:
        about: 'Bio'
        interests: 'Research Interests'
        education: ''	
    design:
      ##  Apply a gradient background
      # css_class: hbx-bg-gradient      
      # background:
      #   gradient_start: #ecf0f1
      #   gradient_end: #2980b9
      #   # The gradient angle from 0-360 degrees
      #   gradient_angle: 180
      #   # Text color (true=light, false=dark, or remove for the dynamic theme color).
      #   text_color_light: false
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      spacing:
        padding: [0px, 0, 0, 0]
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view  more info https://docs.hugoblox.com/getting-started/page-builder/#listing-view
      # view: citation
      view: date-title-summary      
      # Reduce spacing
      spacing:
        padding: [0px, 0, 0, 0]
  - block: markdown
    content:
      title: '👨‍💻 My Research 🕵️‍♂️'
      subtitle: ''
      text: |-
        My research explores the synergy between **Automated Reasoning (AR)** and **Machine Learning (ML)**, focusing on enhancing the robustness and reliability of ML Models (e.g., Large Language Models), across diverse reasoning tasks, including but not limited to code understanding.

        By integrating the mathematical rigor and precision of formal methods with the scalability and adaptability of machine learning, I strive to **develop AI systems that are both reliable and efficient**, tackling critical challenges at the frontier of trustworthy AI.

        I am always excited to explore new ideas together! 📧 **Feel free to get in touch** 📧 if you are interested in collaborating! 😃

    design:
      columns: '1'
      spacing:
        padding: [30px, 0, 0, 0]      
  - block: collection
    id: papers
    content:	
      title: Featured Publications
      count: 3
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3
      spacing:
        padding: [50px, 0, 0, 0]      
  - block: collection
    content:
      title: Recent Publications
      count: 6      
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: [50px, 0, 0, 0]
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      count: 3
      filters:
        folders:
          - events
    design:
      # more info https://docs.hugoblox.com/getting-started/page-builder/#listing-view	
      # view: article-grid
      view: date-title-summary
      columns: 3
      spacing:
        padding: [50px, 0, 0, 0]
---
