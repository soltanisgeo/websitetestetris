---
# Leave the homepage title empty to use the site title
title: ETRiS
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      image:
        filename: one.jpg
      text: |       
        ETRiS is a DDSS (Data, Data products, Services, and Software) service for tsunami risk. This service is part of the [candidate Thematic Core Service for tsunami](https://www.tsunamidata.org) and is integrated into the [Integrated Core Service Data Portal](https://www.ics-c.epos-eu.org) of the [European Plate Observing System](https://www.epos-eu.org) (EPOS). The primary objective of this service is virtual access provision for DDSS for tsunami vulnerability and risk components.
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: about.jpg
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
        {{% cta cta_link="./people/" cta_text="About ETRiS →" %}}
    design:
      columns: '1'
---