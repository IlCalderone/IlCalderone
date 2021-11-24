---
title: Home
sections:
  - type: hero_section
    title: Benvenuti sul Calderone
    subtitle: un Blog Personalissimo
    content: |
      Hei! Come tu ci sia capitato qui è un mistero.
      Ma se ci sei, prenditi un momento per scoprire cosa bolle in pentola.
    actions:
      - label: Link utili
        url: 'https://beacons.ai/ilcalderone'
        style: primary
    image: images/2E4C7246-57A3-4FB2-B9C3-308B208726922021-11-14_21-14-56_295.jpeg
    image_alt: Hero section placeholder image
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/966BC436-1640-4764-BAED-987DE1908C322021-11-21_16-12-57_907.jpeg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 20
    has_border: true
  - type: blog_feed_section
    title: Ultimi Articoli
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 6
    show_image: true
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
  - type: grid_section
    title: Subscribe
    grid_items:
      - title: Apple Podcasts
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-1.svg
        image_alt: Apple Podcasts icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Spotify
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-2.svg
        image_alt: Spotify icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Overcast
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-3.svg
        image_alt: Overcast icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: lorem-ipsum
        subtitle: lorem-ipsum
        title_align: left
        content: >-
          ## Lorem ipsum


          Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua.


          - Lorem ipsum

          - dolor sit amet
        content_align: left
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: false
    align: center
    padding_top: large
    padding_bottom: large
    has_border: true
    background_color: secondary
    background_image: images/2021-03-13 18.28.16.jpeg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: form_section
    content: >-
      ## Ask A Question

      I'm OK with any kind of questions and will answer as many as I possibly
      can.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
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
        label: Question
        default_value: Your question
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
seo:
  title: Stackbit Podcaster Theme
  description: The preview of the Podcaster theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Podcaster Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Podcaster theme
      keyName: property
    - name: 'og:image'
      value: images/hero.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Podcaster Theme
    - name: 'twitter:description'
      value: The preview of the Podcaster theme
    - name: 'twitter:image'
      value: images/hero.png
      relativeUrl: true
template: advanced
---
