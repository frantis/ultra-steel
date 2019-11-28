---
title: Home
sections:
  - component: hero_block.html
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    section_id: hero
    title: 'Dobrý den, jak Vám můžeme pomoci?'
    type: heroblock
  - component: portfolio_block.html
    layout_style: mosaic
    num_projects_displayed: 6
    section_id: latest-projects
    subtitle: An optional subtitle of the section
    title: Dokončené projekty
    type: portfolioblock
    view_all_text: View All
    view_all_url: portfolio/index.html
  - component: services_block.html
    section_id: services
    serviceslist:
      - content: >-
          Design a výroba prototypů, produktový design, optimalizace, nebo tisk
          Vašich souborů. Vyrobíme leccos, přesně dle Vašich požadavků na
          funkční a vizuální parametry výrobku. Nabízíme i maloseriovou výrobu.
        title: 3D modelování a tisk
      - content: >-
          Kompletní řešení webové prezentace od návrhu struktury přes design po
          zajištění hostingu a provozu webu. Sledujeme trendy v oblasti
          webdesignu a naše weby jsou rychlé a bezpečné a přivedou Vám nové
          zákazníky.
        title: Tvorba statických webů
      - content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
        title: Interiérový design
      - content: >-
          Aliquam pulvinar, orci ac scelerisque tempus, felis leo sagittis
          justo, sit amet condimentum lorem nibh vel quam. Duis consectetur
          lorem ipsum, non efficitur urna viverra et.
        title: Service title
    subtitle: An optional subtitle of the section
    title: Nabízené služby
    type: servicesblock
  - component: testimonials_block.html
    section_id: testimonials
    subtitle: An optional subtitle of the section
    testimonialslist:
      - author: John Doe
        avatar: images/john_doe.jpg
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Jane Roe
        avatar: images/jane_roe.jpg
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin, vel posuere justo laoreet.
    title: Reference
    type: testimonialsblock
  - actions:
      - label: Navštívit blog
        url: blog/index.html
    component: posts_block.html
    num_posts_displayed: 2
    section_id: latest-posts
    subtitle: An optional subtitle of the section
    title: Náš blog
    type: postsblock
  - component: contact_block.html
    section_id: contact
    subtitle: An optional subtitle of the section
    title: Kontaktujte nás
    type: contactblock
menu:
  main:
    name: Domů
    weight: 1
layout: home
---

