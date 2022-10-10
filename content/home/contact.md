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
  email: amirmahdi.namjoo1@gmail.com
  
  contact_links:
    - icon: github
      icon_pack: fab
      name: GitHub (titansarus)
      link: 'https://github.com/titansarus'
    - icon: linkedin
      icon_pack: fab
      name: LinkedIn
      link: 'https://www.linkedin.com/in/amirmahdi-namjoo-23b4b9192/'
    - icon: telegram
      icon_pack: fab
      name: Telegram
      link: 'https://t.me/amir_astrophysics'

design:
  columns: '2'
---
