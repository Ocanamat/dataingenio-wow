---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: reach me!
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

  # Contact details (edit or remove options as required)
  email: info@dataingenio.com
  address:
    street: Plaza de Luceros 2
    city: Alicante
    region: Comunitat Valenciana
    postcode: '03005'
    country: Spain
    country_code: ES
  coordinates:
    latitude: '38.345972'
    longitude: '-0.490312'
  appointment_url: 'https://calendly.com/tama-francisquez'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Ocanamat'
    - icon : skype
      icon_pack : fab
      name: Skype Me
      link: 'skype:tamanaco.francisquez?call'

design:
  columns: '2'
---
