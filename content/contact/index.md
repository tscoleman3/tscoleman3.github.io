---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: ""
      email: tscoleman3@gmail.com
      address:
        street: 808 N Pine St
        city: Hammond
        region: LA
        postcode: '70401'
        country: United States
        country_code: US
      coordinates:
        latitude: '30.51075'
        longitude: '-90.46649'
      directions: Thelma Ryan Hall (Biology) Room 159
      office_hours:
        - 'Thursday 2:00 to 4:00 PM'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
