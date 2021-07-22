---
title: Contact
sections:
  - type: hero_section
    title: Kontakt Mig
    subtitle: >-
      Udfyld og send formularen nedenfor - så vender jeg tilbage indenfor 1
      arbejdsdag
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Navn
        default_value: Dit navn
        is_required: true
      - input_type: email
        name: Din mailadresse
        label: Email
        default_value: Din mailadresse
        is_required: true
      - input_type: textarea
        name: message
        label: Besked
        default_value: Din besked
      - input_type: checkbox
        name: Samtykke
        label: >-
          Jeg er indforstået med at formularen her giver Cindy ret til at
          kontakte mig.
        is_required: true
    submit_label: Send Besked
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
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
