---
title: Home
sidebar:
  entries:
  - title: Nouveautés
    url: "#intro"
    is_primary: true
  - title: L'Association
    url: "#one"
    is_primary: false
  - title: Le Parc
    url: "#two"
    is_primary: false
  - title: Accès
    url: "#three"
    is_primary: false
  - title: Contact
    url: "#four"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Nouveautés
  subtitle: "Cras aliquam amet adipiscing nibh faucibus suscipit ut Parturient  \ncol
    accumsan est arcu donec sed Eleifend Integer."
  section_id: intro
  background_style: style1
  actions:
  - label: Learn more
    url: "#one"
    is_scrolly: true
    is_primary: false
  component: intro.html
- type: spotlights
  template: spotlights
  title: L'association
  section_id: one
  background_style: style2
  component: spotlights.html
- type: features
  template: features
  title: Les Installations
  subtitle: Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis
    mauris, eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget hendrerit
    bibendum, urna est aliquam sem, sit amet imperdiet est velit quis lorem.
  section_id: two
  background_style: style3
  features_list:
  - title: Lorem ipsum amet
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-code
  - title: Aliquam sed nullam
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-lock
  - title: Sed erat ullam corper
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-cog
  - title: Veroeros quis lorem
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-desktop
  - title: Urna quis bibendum
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-chain
  - title: Aliquam urna dapibus
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-diamond
  actions:
  - label: Learn more
    url: "/generic"
    is_scrolly: false
    is_primary: false
  component: features.html
- template: contact
  title: Contact
  section_id: four
  background_style: style1
  component: contact.html
  type: contact
  text: ''
  contact_list:
  - text: ''
    url: ''
    title: Email
  social:
    title: ''
    social_icons: []
- template: intro
  title: Accès
  section_id: intro
  background_style: style1
  component: intro.html
  type: intro
  subtitle: ''
  actions: []
layout: home
menu:
  main:
    weight: 1

---
