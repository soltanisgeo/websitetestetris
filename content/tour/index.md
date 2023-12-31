---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Maps 
        content: 'Maps for data and data products from past Tsunami events'
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon:
          icon_pack: fas
          text: Maps
          url: 'https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/etris_geodata.shp' 
      - title: Data and Data products
        content: 'For Tsunami risk assessment'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon:
          icon_pack: fas
          text: Data & Data products
          url: 'https://github.com/eurotsunamirisk/etris_data_and_data_products/tree/main/etris_data_products'
      - title: Software
        content: 'The Tsunami risk modeller toolkit'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: 
          icon_pack: fas
          text: Software
          url: 'https://github.com/eurotsunamirisk/trmtk'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
