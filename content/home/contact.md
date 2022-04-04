---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

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
  email: rrghosh.biet@gmail.com
  phone: (+91) 7549010609
  address:
    street: Hauz Khas
    city: New Delhi
    region: Delhi
    postcode: '110016'
    country: India
    country_code: IND
  coordinates:
    latitude: '28.5457'
    longitude: '77.1928'
  directions: Enter Block II (Academics building) and take the stairs to room no. 312 on Floor 2
  # office_hours:
   #  - 'Monday 10:00 to 13:00'
   #  - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/home?lang=en'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://us05web.zoom.us/profile'

design:
  columns: '2'
---
