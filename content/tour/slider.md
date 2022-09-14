---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Welcome to the HKUST-GZ
      content: 'Look more about our school: HKUST-GZ!'
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: Two Campuses_1.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Click here
        url: https://hkust-gz.edu.cn/
    - title: Bioinformatics
      content: 'The science of collecting and analysing complex biological data such as genetic codes!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: bioinformatics.jpg
    - title: Tang lab- HKUST Bioinformatics
      content: 'Welcom to join us!!!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
