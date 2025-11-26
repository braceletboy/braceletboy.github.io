---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-11-26
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
      button:
        text: Resume
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown2
    id: research
    content:
      title: '📚 Research'
      subtitle: ''
      text: |-
        My research develops principled, actionable, and broadly applicable AI explanations grounded in clear mathematics. The work investigates how explanations should behave across model families. From protein-folding systems like AlphaFold2 to vision transformers and multimodal models, I focus on designing tools for AI explainability and fairness.

        This research combines rigorous theory (game-theoretic reasoning, sensitivity analysis) with empirical evaluation on realistic tasks and datasets. Prior work includes two publications on South Florida flood mitigation offering actionable guidance for planners. Recent efforts include a paper on the limits of XAI for AlphaFold2 and related architectures, and a preprint proposing a mathematically grounded framework for Vision Transformers that yields stable, faithful attributions. Throughout, the emphasis remains on theoretical soundness, real-world evaluation, open-source releases, and reproducibility.

        The goal is to create impact along three dimensions: clarifying what explanation methods can guarantee; delivering practical tools and benchmarks for trustworthy deployment; and bringing these methods into real-world use in scientific and safety-critical domains. Future directions include extending methods to text and multimodal models, building standardized XAI evaluation suites, and releasing toolkits for robust explanations.

    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
