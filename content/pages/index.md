---
type: PageLayout
title: Association CDA
colors: colors-b
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Association pour la création d'idées audiovisuelles – Hauts de France
    subtitle: ''
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
          - pb-7
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    media:
      type: VideoBlock
      title: Vidéo de promotion pour O'Tacos
      url: 'https://www.youtube.com/watch?v=HZNN1_3pPZQ'
      elementId: ''
      autoplay: false
      loop: false
      muted: false
      controls: true
      aspectRatio: '16:9'
    text: ''
  - type: CtaSection
    title: Nos réalisations
    text: >
      <ul class="wp-block-gallery columns-3 is-cropped"><figure><a
      href="https://vimeo.com/32133617"><img width="2560" height="1440"
      src="https://associationcda.wordpress.com/wp-content/uploads/2019/08/arthurgrummiaux01-4.jpg"
      alt="" sizes="(max-width: 2560px) 100vw, 2560px"></a></figure><figure><a
      href="https://www.youtube.com/watch?v=3xrVkK24kgE"><img width="1464"
      height="825"
      src="https://associationcda.wordpress.com/wp-content/uploads/2019/08/isea01.jpg"
      alt="" sizes="(max-width: 1464px) 100vw, 1464px"></a></figure><figure><a
      href="https://dai.ly/x7gxzlp"><img width="2560" height="1440"
      src="https://associationcda.wordpress.com/wp-content/uploads/2024/08/costax240-2010823314-e1722596686526.jpg"
      alt="" sizes="(max-width: 2560px) 100vw, 2560px"></a></figure><figure><a
      href="https://www.dailymotion.com/video/x5j4z2c"><img width="599"
      height="352"
      src="https://associationcda.wordpress.com/wp-content/uploads/2019/08/artsenique01-1817097966-e1722580693716.jpg"
      alt="" sizes="(max-width: 599px) 100vw, 599px"></a></figure> <figure><a
      href="https://www.dailymotion.com/video/x15rnh3"><img width="599"
      height="352"
      src="https://associationcda.wordpress.com/wp-content/uploads/2019/08/flamenco01-3921630733-e1722595989316.jpg"
      alt="" sizes="(max-width: 599px) 100vw, 599px"></a></figure> <figure><a
      href="https://www.dailymotion.com/video/xj0spx"><img width="599"
      height="352"
      src="https://associationcda.wordpress.com/wp-content/uploads/2019/08/forum2008-135064524-e1722596069568.jpg"
      alt="" sizes="(max-width: 599px) 100vw, 599px"></a></figure> </ul>
    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-16
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: flex-start
        flexDirection: col
        borderWidth: 0
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-0
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: MediaGallerySection
    title: Ils nous ont fait confiance
    subtitle: ''
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
        url: /images/iae.jpg
        altText: Logo five
        caption: Logo five
      - type: ImageBlock
        url: /images/sida-info-service-sis-19d0bf28197647d5abee605f02de7595.png
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo-maison-quartier-wazemmes-lille-mqw.jpg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/UJDhfkBn_400x400.jpg
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    colors: colors-f
    spacing: 132
    columns: 6
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-12
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
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-0
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Formulaire de contact
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: Prénom
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Nom de famille
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Site web
          isRequired: true
          width: 1/2
          type: TextFormControl
        - type: TextFormControl
          name: Texte
          label: Name
          hideLabel: false
          placeholder: Texte
          width: full
          isRequired: false
      submitLabel: Soumettre
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
