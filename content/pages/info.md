---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >
      ## WELOCME TO TAI INFO PAGE HERE AS YOU CAN SEE WE ARE A GROUP HAS TWO
      SEPARATIONS TAI/MHDPA(KM)<sup>2 </sup>HERE I AM THEIR FOUNDER KHR AND
      THEIR OTHER ROLES ARE  [@TAI](https://www.stackbit.com/)


      ### FROM TAI


      SAI SUDARSAN S - CO - FOUNDER(TAI),DIRECTOR


      SRIAKLESH M - CO FOUNDER(TAI),CEO


      DAYA SANKARA B - CO FOUNDER(TAI),DIRECTOR


      KHR - CHAIRMAN,FOUNDER(TAI,RACE,MHDPA(KM)<sup>2</sup>


      ## FROM MHDPA(KM)<sup>2</sup>


      K HARSHAN RAGHAV - SENIOR PRESIDENT


      MUTHUKRISHNAN P - CHAIRMAN


      ANUDANVIKA L - PRESIDENT


      DHANUSHKASRI B - VICE-PRESIDENT


      MITHUN PRABHU B - CHIEF MANAGER


      KRITHVI R\*/ - DEPUTY MANAGER


      KAYAL K\* - ASST. MANAGER | [@KAYAL](/kayal)


      MAGILA\* - P.A. (KRITHVI)


      PIRTHIUV M - EDITOR(PHOTOGRAPHER YT)
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
    media:
      type: ImageBlock
      url: /images/Absolute_Infinity.webp
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
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
    subtitle: OUR OWN CLUBS✔️
    images:
      - type: ImageBlock
        url: /images/Screenshot 2024-09-22 175922.png
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/Screenshot 2024-09-22 180136.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/Absolute_Infinity.webp
        altText: TAI
        caption: TAI
      - type: ImageBlock
        url: /images/Screenshot 2024-09-22 180316.png
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/Screenshot 2024-09-22 180429.png
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
  - type: ContactSection
    backgroundSize: full
    title: JOIN OUR CLUB NOW
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: TAI
          label: TAI
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
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
