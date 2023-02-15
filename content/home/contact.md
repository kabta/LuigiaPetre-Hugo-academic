---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 160

title: Contact
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
      captcha: false

  # Contact details (edit or remove options as required)
  email: luigia.petre@abo.fi
  address:
    street: Vesilinnantie 5
    city: Turku
    postcode: '20500'
    country: Finland
    country_code: Fin
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building Agora and take the stairs or lift to Office 3401 on Floor 3
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter 
      link: 'https://twitter.com/luigia_petre'
    - icon: video
      icon_pack: fas
      name: Zoom 
      link: 'https://zoom.com'

design:
  columns: '2'
---
