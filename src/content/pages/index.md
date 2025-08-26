---
_schema: page
title: Home
seo:
  page_description: >-
    Tom Richardson's personal portfolio. Tom is a web developer, specialising in static sites and SSG's.
  canonical_url:
  featured_image:
  featured_image_alt:
  open_graph_type:
  no_index: false
content_blocks:
  - _bookshop_name: hero
    text_color: "#333232"
    background_color: "#ffffff"
    heading: Tom Richardson
    subheading: Web Developer
  - _bookshop_name: left-right
    block_id:
    text_color: "#333232"
    background_color: "#ffffff"
    heading: I make static sites
    text_content: >-
      I’m a full stack web developer, trained in a React focused bootcamp, now
      specialising in static site generators - particularly Astro, Eleventy,
      Hugo, and Jekyll.


      I work as a Solutions Architect for CloudCannon, a git-based content
      management system for managing static sites.
    image:
      image_path: /images/square-portrait.png
      image_alt: A portrait of Tom Richardson in the CloudCannon offices
    flipped: true
  - _bookshop_name: left-right-form
    block_id: contact
    heading: Contact Me
    text_color: "#333232"
    background_color: "#ffffff"
    form:
      form_id: contact-form
      form_fields:
        - input_type: text
          label: Name
          required: true
        - input_type: email
          label: Email
          required: true
        - input_type: textarea
          label: Message
          required: true
---
