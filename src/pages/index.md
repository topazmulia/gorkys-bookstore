---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/diligent-avocado.jpg
    content: |+
      # Gorky's Bookstore.
      # An all-new chapter.


    actions:
      - title: See all items
        url: /store
        arrow: true
  - type: featured_products_section
    section_id: best_sellers_section
    title: Best sellers
    icon: true
    light_title: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/novel10.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/Office.md
    title: ''
  - section_id: /testimonials
    testimonials:
      - text: >-
          Excellent service. The books were wrapped securely and arrived in
          pristine condition. I sent an email after to books arrived to ask
          about the author, and I received a prompt reply.
        author:
          name: Aureent Patron Antariksa
          location: 'Cikupa, Tangerang'
      - text: >-
          Gorky's Books went above and beyond - great and friendly customer
          service and prompt delivery of my book. I highly recommend them. Many
          thanks!
        author:
          name: Omar Syahrill
          location: 'Pancoran Mas, Depok'
    type: testimonials_section
  - section_id: /promotions
    title: 'A new books for quarantine :)'
    subtitle: from IDR 99000
    cta:
      title: Discover
      url: /store
      arrow: false
      type: action
    type: promotion_section
    image: images/polite-oak.jpg
template: home
page_css_class: ''
---
