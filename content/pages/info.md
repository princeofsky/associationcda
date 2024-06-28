---
type: PageLayout
title: About
colors: colors-b
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >-
      ## Hey I’m a developer. I’ve been born and raised in the world, and that’s
      also where I’m based. I’m currently a free agent, ex-this, ex-that,
      ex-super big name. When I’m not coding, writing or creating, I eat
      cereals. I have a dog, check her out [@mygod](https://www.stackbit.com/).
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'Ils nous ont fait confiance :'
    images:
      - type: ImageBlock
        url: /images/lille-comics-festival.jpg
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/egide20logo_0.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/sida-info-service-sis-19d0bf28197647d5abee605f02de7595.png
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo-maison-quartier-wazemmes-lille-mqw.jpg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/iae.jpg
        altText: Logo five
        caption: Logo five
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
---
