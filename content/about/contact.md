---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
subtitle: Contact me on social media, or in the form below.
social:
  - icon: envelope
    icon_pack: fas
    link: about/#contact
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/NeuroNick_
    display:
      header: true
  - icon: researchgate
    icon_pack: ai
    link: https://www.researchgate.net/profile/Nicholas-Everett?ev=hdr_xprf
    display:
      header: true
  - display:
      header: true
    link: https://scholar.google.com.au/citations?user=0YMPyM4AAAAJ&hl=en
    icon_pack: ai
    icon: google-scholar

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

design:
  columns: '1'
---
