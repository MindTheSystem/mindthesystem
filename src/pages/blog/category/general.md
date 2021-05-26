---
title: General
sections:
  - type: hero_section
    title: General
    subtitle: Posts under the category "General"
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    category: src/data/categories/general.yaml
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    title: Stay updated
    title_align: center
    content: Subscribe to our newsletter to make sure you don't miss anything.
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
    submit_label: Subscribe
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
  - title: Let's talk
    content: >
      Unlike other consultants, we love to understand your context first before
      offering any advice or service. This way we can be sure you get what you
      truly need, tailored to you.
    actions: []
    actions_position: bottom
    actions_width: fourty
    align: left
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: cta_section
seo:
  type: stackbit_page_meta
  title: Posts in General
  description: This is the author archive page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Posts in General
      keyName: property
    - name: 'og:description'
      value: This is the author archive page
      keyName: property
    - name: 'og:image'
      value: images/classic/post-5.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Posts in General
    - name: 'twitter:description'
      value: This is the author archive page
    - name: 'twitter:image'
      value: images/classic/post-5.png
      relativeUrl: true
template: advanced
---
