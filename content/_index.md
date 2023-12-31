---
# Leave the homepage title empty to use the site title
title: ETRiS
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        European Tsunami Risk Service
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        ETRiS is a DDSS (Data, Data products, Services, and Software) service for tsunami risk. This service is part of the candidate Thematic Core Service for tsunami and is integrated into the Integrated Core Service Data Portal of the European Plate Observing System (EPOS). The primary objective of this service is virtual access provision for DDSS for tsunami vulnerability and risk components.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---