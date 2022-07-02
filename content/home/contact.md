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
  email: wuye@njust.edu.cn
  phone: 133-289-19503
  address:
    street: 200 Xiaolingwei Street
    city: Nanjing
    region: Jiangsu
    postcode: '210094'
    country: China
    country_code: CN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter CS Building and take the stairs to Office 4048 on Floor 4
  office_hours:
    - 'Monday - Friday 08:30 to 22:00'
    - 'Saturday - Sunday 09:00 to 18:00'
  appointment_url: 'https://calendly.com/wuye'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: @wuye4567
      link: 'https://twitter.com/wuye4567'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
