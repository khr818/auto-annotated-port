---
type: PageLayout
title: Info page- KAYAL
sections:
  - type: HeroSection
    title: I'm KAYAL FROM MHDPA((K)M)2
    subtitle: >-
      This is my info — I'm sharing it all this with ya'll to impress you with
      all the hard work I've done in the past few years. Once you're impressed,
      you can continue to scroll down to see more details and credentials about
      me.
    text: >
      I'M JUST A SMALL GIRL AND I'M ACCOUNT MANEGER IN MHDPA WHICH MEANS I HAVE
      THE TOTAL CONTROL AMONG ACCOUNTS . 
    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    media:
      type: ImageBlock
      url: /images/KAYAL.jpg
      altText: KAYAL
      caption: Caption of the image
      elementId: ''
  - type: ContactSection
    title: Got an interesting project? Tell me more...
    text: ''
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          width: 1/2
          isRequired: false
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          width: 1/2
          isRequired: false
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
      submitLabel: "Submit \U0001F680"
      elementId: sign-up-form
      styles:
        submitLabel:
          textAlign: center
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
