---
title: Contact
sections:
  - type: hero_section
    title: Contact
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
    content: |+
      ##### Call: 0448740025 / 0792210293

      Email:  drgertcloete@gmail.com

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
    title: Fill out the form below and I will get in touch you.
    section_id: contact-form
  - actions: []
    grid_items:
      - title_align: center
        content: |
          George Practice:
          Fairview office park nr.2

          Cnr. Of Knysna road and 1st avenue

          Dr. Gert Cloete
        content_align: center
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        title: George Practice
      - title: Mossel Bay Practice
        title_align: center
        content: |
          Mosselbay golf club suit: 2

          21st Avenue Mosselbay

          Dr Inge van der Vyver
        content_align: center
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
      - title_align: left
        content_align: center
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: cloete chiropractic office
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        image: /images/IMG_20211117_072204 (1).jpg
      - title_align: left
        content_align: left
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: cloete chiroptactic office photo
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        image: /images/IMG_20211117_072248.jpg
    grid_cols: two
    grid_gap_vert: small
    grid_gap_horiz: small
    enable_cards: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: secondary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: grid_section
    section_id: office
    title: Location
    subtitle: where to find us
seo:
  title: Contact Us | Cloete Chiropractic
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
  description: >-
    Contact us to make a booking for our George or Mossel Bay practice. Or fill
    in a form and we will contact you.
layout: advanced
---
