---
title: Home
sidebar:
  entries:
  - title: News
    url: "#intro"
    is_primary: true
  - title: L'Association
    url: "#one"
    is_primary: false
  - title: Nos installations
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
  title: News
  subtitle: "_Hiver 2020_\n\nPensez à vous équiper en fonction des conditions météo
    ! \n\nPour les extérieurs à l'association, le Parc est ouvert, sur réservation,
    les week-end de 10h à 17h.\n\nPour les membres, sur réservation, tous les jours
    de 10h à 17h."
  section_id: intro
  background_style: style1
  actions: []
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
  - title: Plein de cibles 3D
    text: Réparties sur 1 hectare et placées stratégiquement
    icon: fa-route
  - title: Pas de tir
    text: Pour une séance
    icon: fa-hourglass-half
  - title: Pour tous
    text: Toutes les cibles 3D du parc diposent de différents pas de tir. Plus besoin
      de se séparer pour tirer en groupe, quelque soit votre niveau !
    icon: fa-map-signs
  - title: Veroeros quis lorem
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-desktop
  actions: []
  component: features.html
- template: intro
  title: Accès
  section_id: three
  background_style: style1
  component: intro.html
  type: intro
  subtitle: ''
  actions: []
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
layout: home
menu:
  main:
    weight: 1

---
