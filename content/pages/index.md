---
title: Home
sections:
  - type: hero_section
    title: Hello there! My name is Malvika Dusowoth.
    subtitle: >-
      I am a current Grade 12 student at Bluevale Collegiate Institute and I
      will be pursing post-secondary education in the Fall of 2022. This website
      was created by me to give you a better insight into my life and to show
      you why I am the perfect candidate to be selected into the University of
      Waterloo's Computer Science Co-op program.
    actions: []
    image: images/hero.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: secondary
    background_image: /images/cs.jpg
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 30
  - type: features_section
    features:
      - actions: []
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: References
    grid_items:
      - content: |
          **Kathy Duncan** (*volunteering*),

          Phone Number: 519-502-5252

          Email Address: kateyduncan@gmail.com
        image_position: left
        image_width: twenty-five
      - content: |
          **Ilana Arnold** (*volunteering*),

          Phone Number: 519-743-0271

          Email Address: Ilana.Arnold@kpl.org
        image_position: left
        image_width: twenty-five
      - content: |
          **Christina Harnack** (*teacher*),

          Email Address: christina_harnack@wrdsb.ca
        image_position: left
        image_width: twenty-five
      - content: |
          **Brittany Parkes** (*teacher*),

          Email Address: brittany_parkes@wrdsb.ca
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
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
