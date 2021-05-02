---
title: Contact
sections:
  - type: hero_section
    title: Get in touch
    subtitle: >-
      Have a question? Send us a note using the form below and we will be in
      touch soon.
    align: center
    padding_top: small
    padding_bottom: small
    has_border: true
    background_color: none
  - title: Questions?
    subtitle: Contact us!
    title_align: left
    content: |
      Fill up the form and you'll get a response within 12 hours.
    content_align: left
    form_position: bottom
    form_width: fifty
    form_layout: stacked
    enable_card: false
    form_id: contact-form
    form_action: 'mailto:carameloproperties@gmail.com'
    form_fields:
      - input_type: text
        name: full-name
        label: Full Name
        default_value: Maria Dela Cruz
        options: []
        is_required: true
        type: form_field
      - input_type: email
        name: email
        label: Email Address
        default_value: carameloproperties@gmail.com
        options: []
        is_required: true
        type: form_field
      - input_type: textarea
        name: message
        label: Message
        default_value: 'Questions, concerns, or any relevant message.'
        options: []
        is_required: true
        type: form_field
      - input_type: text
        name: messenger-link
        label: Messenger Link for faster communication (optional)
        default_value: m.me/CarameloProperties
        options: []
        is_required: false
        type: form_field
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
  - type: grid_section
    grid_items:
      - title: Announcements & promos on Facebook
        title_align: center
        content: >
          Like and follow our [Facebook page](fb.com/carameloproperties) for
          more updates on COVID-19 protocols around our properties (as mandated
          by LGUs), announcements and launches, and **promos**/sales!!
        content_align: center
        actions:
          - label: Like us on Facebook
            url: 'https://fb.com/carameloproperties'
            style: secondary
            has_icon: true
            icon: facebook
            icon_position: left
            no_follow: true
            new_window: true
        actions_align: center
        image: images/facebook.svg
        image_alt: Partnering and sponsorships icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Help & Support
        title_align: center
        content: >
          For faster communication, message us on [FB
          Messenger](m.me/CarameloProperties). **Get a response as soon as
          possible**, or within 1 hour from 9 AM to 6 PM.
        content_align: center
        actions:
          - label: Message us
            url: 'https://m.me/CarameloProperties'
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
            no_follow: true
            new_window: true
        actions_align: center
        image: images/messenger.svg
        image_alt: Help and support icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Other Queries
        title_align: center
        content: >
          For further questions and details, email us directly at
          carameloproperties@gmail.com
        content_align: center
        actions:
          - label: Email Us
            url: /contact
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
            new_window: true
            no_follow: true
        actions_align: center
        image: images/gmail.svg
        image_alt: Other queries icon
        image_position: top
        image_align: center
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: true
    align: center
    padding_top: large
    padding_bottom: large
    background_color: primary
    title: Social Media
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
