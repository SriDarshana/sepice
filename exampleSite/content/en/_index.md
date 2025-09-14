---
author: Mark Dumay
title: Welcome to SÉPICE!
description: Sépice - Bringing the world's finest spices to your kitchen. We meticulously source rare single-origin, high-quality, authentic spices and craft unique blends to unlock new depths of flavor in your cooking. Discover new flavors and elevate your home cooking with our curated selection. Shop our full range online and have premium spices delivered right to your door.
content_blocks:
  - _bookshop_name: hero
    heading:
      title: Welcome to SÉPICE!
      content: |-
        Sépice - Bringing the world's finest spices to your kitchen.
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/sunrise.jpg
      ratio: 16x9
    width: 8
    links:
      - title: About
        url: about
        icon: fas chevron-right
    orientation: horizontal
    justify: center

  - _bookshop_name: articles
    heading:
      title: Blog
      align: start
    input:
      section: blog
      reverse: true
      sort: date
      keywords: featured
    hide-empty: false
    header-style: none
    more:
      title: More Posts
    padding: 0
    limit: 3
    class: border-0 card-zoom card-body-margin

  - _bookshop_name: articles
    heading:
      title: Projects
      align: start
    background:
      background: body-tertiary
    hide-empty: false
    input:
      section: projects
      reverse: false
      sort: date
    more:
      title: More articles
    cols: 1
    padding: 4
    limit: 2
    icon-style: fa-5x
    header-style: none
    footer-style: tags
    orientation: horizontal-sm
    class: border-1 card-emphasize
---
