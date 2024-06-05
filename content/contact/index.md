---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: hero
    content:
      image:
        filename: welcome.png
      text: |-
        <br>

        **Where to find us**:

        To reach the lab, across the road from the University North Gate, enter the Psychology building from the Pritchatts Road 52 parking lot. Looking at the Cafe 52, take the elevators on the left to the 4th floor. Exit the elevator on the left and follow the corridor.
  - block: contact
    content:
      title: Get in touch
      text: |-
        To get in touch and for information on how to use the lab, please fill in the form below. You will be given access to the Lab CODA where you will find all details. The lab is located in the Gisbert Kapp building. Entrance is via Pritchatts Road 52. Visitor parking is possible at the nearby multi-storey North East car park.
      address:
        street: Pritchatts Road 52
        postcode: "B15 2SA"
        city: Birmingham
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: "52.45321698704788"
        longitude: "-1.927825815563642"
      directions: Floor 4 in the Gisbert Kapp Building
      office_hours:
        - Monday - Friday 10:00 to 16:00

      # Automatically link email and phone or display as text?
      autolink: true

      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: "1"

  - block: markdown
    content:
      title:
      subtitle: ""
      text:
    design:
      columns: "1"
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
        padding: ["20px", "0", "20px", "0"]
      css_class: fullscreen
---
