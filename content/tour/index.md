---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '50vh'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 10000
  
  - block: hero
    content:
      title: |
        Labratory for Computational Perinatal Neuroimaging
      image:
        filename: welcome.jpg
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
---