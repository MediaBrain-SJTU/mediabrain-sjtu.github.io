---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 
        content: 
        align: center
        background:
          image:
            filename: new-p1.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: 
        content: 
        align: center
        background:
          image:
            filename: new-p2.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: 
        content: 
        align: center
        background:
          image:
            filename: new-p3.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: 
        content: 
        align: center
        background:
          image:
            filename: new-p4.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: Open Position!
        content: 
        align: right
        background:
          image:
            filename: new-p1.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../recruit/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 1000
  - block: hero
    content:
      title: |
        Research Scope
      # image:
      #   filename: new-p2.jpg
      text: |
        <br>
        We develop advanced methodologies and systems to better process multimedia, analyze social media, and understand human.
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---