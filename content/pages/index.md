---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Cindy. I help you get...'
    subtitle: >-
      Clarity. Motivation. Enhanced focus. Sustainable changes. Better
      relations. Sounds good? It's your life - let's level up!
    actions:
      - label: Book here - 1st session is free (30 min)
        url: /contact
        style: primary
    image: images/RightSizePic.png
    image_alt: A smiling woman
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    background_image: images/Cindy-Legarth-black-letters-cropped.png
  - type: grid_section
    title: Testimonials
    subtitle: What My Clients Say
    grid_items:
      - content: >
          Cindy is a passionate and inspiring coach. You can sense her eagerness
          to help and support you towards your goals. She helped my prioritize
          my goals for my company and what profiles to hire. Cindy challenged me
          on my current level of comfort and how to take it up a level. We
          worked together over a period of two months and it won't be the last
          time.


          **T.,** *CEO*
        image: images/joe-shields-dLij9K4ObYY-unsplash(1).jpg
        image_position: left
        image_width: twenty-five
      - content: >
          We chose Cindy as our relationship coach to gain clarity on where we
          wanted our relationship to go next. Cindy was very tentative, listened
          and guided us through the process - even when emotions ran high. We
          ended the conversation with an accountability assignment designed to
          manifest our goals for the future. We will be hiring Cindy again and
          would strongly recommend anyone who needs a push to act on their goals
          to do the same.


          **T. & G**., *a couple stuck in everyday gridlock*
        image: images/engin-akyurt-hIRK2fwo1Sc-unsplash.jpg
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: >
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Cindy.dk - Level up
  description: Clarity. Motivation. Enhanced focus. Sustainable changes. Better relations!
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Cindy.dk - Level up
      keyName: property
    - name: 'og:description'
      value: >-
        Clarity. Motivation. Enhanced focus. Sustainable changes. Better
        relations.
      keyName: property
    - name: 'og:image'
      value: /_static/app-assets/RightSizePic.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Cindy.dk - Level up
    - name: 'twitter:description'
      value: >-
        Clarity. Motivation. Enhanced focus. Sustainable changes. Better
        relations.
    - name: 'twitter:image'
      value: /_static/app-assets/RightSizePic.png
      relativeUrl: true
layout: advanced
---
