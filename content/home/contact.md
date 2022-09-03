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
  email: leejaehyun1223@gmail.com
  # phone: x
  address:
    street: 145 Anam-ro
    city: Seoul
    region: Seongbuk-gu
    postcode: '02841'
    country: Republic of korea
    country_code: South Korea
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  directions: 301A Woojung Hall of Informatics
  office_hours:
    - 'Monday ~ Friday 10:00 to 17:00'
  
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
  #   - icon: video
  #     icon_pack: fas
  #     name: Zoom Me
  #     link: 'https://zoom.com'

design:
  columns: '2'
---
