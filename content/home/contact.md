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
  email: bastien.chaudet@unige.ch
  phone: +41 22 379 11 54
  address:
    street: Rue du Conseil Général 7-9
    city: Geneva
    region: GE
    postcode: '1205'
    country: Switzerland
    country_code: CH

design:
  columns: '2'
---
