---
title: ws
slug: /
sections:
  - subtitle: ''
    text: >+
      Troszczymy się o zdrowie i dobre samopoczucie całej rodziny.
      Specjalizujemy się w fizjoterapii ortopedycznej, terapii manualnej,
      fizjoterapii stomatologicznej, pediatrycznej oraz w uroginekologicznej. 


      Każda wizyta to indywidualne podejście, dostosowane do potrzeb pacjenta,
      bo wierzymy, że każdy Pacjent zasługuje na troskliwą opiekę.


      Pomagamy odzyskać sprawność po urazach, wspieramy w radzeniu sobie z bólem
      oraz dbamy o prawidłowy rozwój dzieci i komfort kobiet na różnych etapach
      życia. Stawiamy na nowoczesne metody terapii, profesjonalizm i przyjazną
      atmosferę, aby każda wizyta była krokiem ku lepszemu zdrowiu. Zapraszamy!

    actions:
      - label: Zarejestruj wizytę
        url: www.strefafizjoterapii.boooksy.com
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/Main Logo.png
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: Dbamy o zdrowie całej rodziny
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - subtitle: Gabinet Fizjoterapii
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: Twoje imię
          label: Twoje imię
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Nasz adres
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
