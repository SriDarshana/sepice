---
title: Welcome to SÉPICE!
description: Sépice - Bringing the world's finest spices to your kitchen. We meticulously source rare single-origin, high-quality, authentic spices and craft unique blends to unlock new depths of flavor in your cooking. Discover new flavors and elevate your home cooking with our curated selection. Shop our full range online and have premium spices delivered right to your door.
content_blocks:
  - _bookshop_name: hero
    heading:
      title: 
      content: |-
        🚚.......... Free Islandwide Delivery on oders over LKR.2500 !!!
      width: 12 #6
    background:
      color: danger #primary, danger, info, success, warning
      subtle: true
    justify: end

  - _bookshop_name: hero
    heading:
      title: Welcome to SÉPICE
      content: |-
        Sépice - Bringing the world's finest spices to your kitchen. We meticulously source rare single-origin, high-quality, authentic spices and craft unique blends to unlock new depths of flavor in your cooking. Discover new flavors and elevate your home cooking with our curated selection. Shop our full range online and have premium spices delivered right to your door.
      width: 5 #6
    background:
      color: info #primary, danger, info
      subtle: true
    illustration:
      image: /img/wcgirl_new3.png
      ratio: 4x3 #16*9
    width: 12 #12
    links:
      - title: Place an order
        url: https://wa.me/message/WMM6S3FQUT3PB1
        icon: fas chevron-right
    orientation: horizontal
    justify: center

  - _bookshop_name: articles
    heading:
      title: Offers
      align: start
    input:
      section: offer
      reverse: true
      sort: date
    hide-empty: false
    header-style: none
    cols: 3
    more:
      title: See more
    padding: 5
    limit: 3
    class: border-0 card-zoom card-body-margin

  - _bookshop_name: video-message
    heading:
      # preheading: Preheading
      # title: Heading
      content: ~ THE SOUL OF CEYLON FLAVOR ~
      # align: start
    background:
      color: primary
      subtle: true
    orientation: horizontal
    icon-style: fa-lg
    video:
      # provider: vimeo
      # media-id: "55073825"
      provider: youtube
      media-id: "qWQoYJlJfdk"
      autoplay: false
      color: black
    # messages:
      # - title: SÉPICE
        # icon: fas 1
      # - title: THE SOUL OF CEYLON FLAVOR
        # icon: fas 2
      # - title: Third Message
        # icon: fas 3
      justify: center
      padding: 5
        
  - _bookshop_name: articles
    heading:
      title: News
      align: end
    background:
      color: info #primary, danger, info
      subtle: true
      backdrop: /img/sunset.jpg
    input:
      section: news
      reverse: true
      sort: date
    hide-empty: false
    header-style: none
    cols: 3
    more:
      title: See more
    padding: 5
    limit: 3
    class: border-0 card-zoom card-body-margin

---
{{< carousel id="carousel-21x9" ratio="21x9" class="col-lg-12 col-lg-8 mx-auto **bg-transparent**">}}
  {{< img src="img/showcase01.jpg" caption="Welcome to SÉPICE" >}}
  {{< img src="img/showcase03.jpg" caption="" >}}
  {{< img src="img/showcase05.jpg" caption="" >}}
  {{< img src="img/bundle_offer01.png" caption="" >}}
{{< /carousel >}}

