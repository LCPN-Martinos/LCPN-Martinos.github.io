---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Labratory for Computational Perinatal Neuroimaging
      image:
        filename: lab_pic_early2025.jpg
      text: |
        <br>
        
        The **LCPN** is a subgroup within the Labratory for Computational Neuroimaging at the Athinoula A. Martinos Center at MGH. We are focused on
        the design and development of computational tools that are capable of processing and exploring perinatal neurodevelopment.
  
  - block: collection
    content:
      title: Recent Publications
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: card
      columns: '1'

  - block: slider
    content:
      slides:
      - title: Support Our Mission 
        content: 
        align: center# right
        background:
          image:
            filename: donate.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: gift
          icon_pack: fas
          text: Donate
          url: https://giving.massgeneral.org/donate?is_designation=1&designation=Lilla%20Zollei
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '50vh'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 10000
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
