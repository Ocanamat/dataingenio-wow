---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Insightful Data Science
      content: Machine Learning / Deep Learning / Optimization / Citizen DataSci
      #position: top
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.5
        media: slider.png
        fit: cover
        #overlay_filter : 0.6
---