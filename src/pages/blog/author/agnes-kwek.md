---
title: Agnes-Kwek
sections:
  - type: hero_section
    title: Agnes Kwek
    subtitle: Posts authored by Agnes Kwek
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    author: src/data/team/agnes-kwek.yaml
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - title: Stay updated
    title_align: center
    content: |
      Subscribe to our newsletter to make sure you don't miss anything.
    content_align: center
    form_position: bottom
    form_width: fourty
    form_layout: inline
    enable_card: false
    form_id: subscribeForm
    form_fields:
      - input_type: email
        name: email
        default_value: Your email address
        options: []
        is_required: true
        type: form_field
        label: Email
    submit_label: Subscribe
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: secondary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
    form_action: /thank-you
  - title: Let's talk
    content: >
      Unlike other consultants, we love to understand your context first before
      offering any advice or service. This way we can be sure you get what you
      truly need, tailored to you.
    actions:
      - label: Get in touch now
        url: /contact
        style: primary
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
    actions_position: right
    actions_width: fourty
    align: left
    padding_top: large
    padding_bottom: large
    has_border: false
    background_color: primary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: cta_section
seo:
  type: stackbit_page_meta
  title: Posts by Agnes Kwek
  description: This is the author archive page of posts authored by Agnes Kwek
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Posts by Dianne Ameter
      keyName: property
    - name: 'og:description'
      value: This is the author archive page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Posts by Dianne Ameter
    - name: 'twitter:description'
      value: This is the author archive page
    - name: 'twitter:image'
      value: images/classic/post-5.png
      relativeUrl: true
template: advanced
---
