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
  <!-- form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true -->

  # Contact details (edit or remove options as required)
  # email: ""
  # phone: 888 888 88 88
  address:
    street: Homi Bhabha Road
    city: Mumbai
    region: MH
    postcode: '400005'
    country: India
    country_code: IN
  coordinates:
    latitude: '18.9078922'
    longitude: '72.8081678'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/vidur_sa1'
    - icon: linkedin
      icon_pack: fab
      name: Connect with me
      link: 'https://www.linkedin.com/in/vidursa/'

design:
  columns: '2'
---
