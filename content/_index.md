---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="drawings" >}}
    design:
      columns: '1'
  - block: markdown
    id: gallery2
    content:
      title: Gallery2
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
- block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Thank your for your interest. I am happy to hear from you!
      # Contact (add or remove contact options as necessary)
      email: constance1@web.de
      phone: (+49) 176 3163 4154
      address:
        street:
        city: Delft
        region:
        postcode: 2623LN
        country: The Netherlands
        country_code:
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
