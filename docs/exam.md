---
layout: page
title: Partiel
permalink: '/partiel'

symfony_elements:
- title: Controller
  listing:
  - label: Routage
  - label: "`Request`"
    details: Dont la gestion des paramètres en **GET** et **POST**
  - label: "`Response`"
- title: Twig
  listing:
  - label: Gestion des templates
  - label: Héritage et blocks
- title: Form
  listing:
  - label: "`data_class`"
    details: L'objet _mappé_ sur le formulaire
  - label: options
  - label: Validation
    details: Gérée par les `Constraint`s et les `Validator`s
  - label: Soumission
- title: Doctrine
  listing:
  - label: Entity et Repository
  - label: "`EntityManager`"
    details: "`persist` / `flush`"
- title: Droits d'accès
  listing:
  - label: "`security.yaml`"
  - label: "`IsGranted`"
    details: (avec éventuellement les `Voter`s)
- title: Service
  listing:
  - label: Injection
---

## Organisation

* 📆 Date : Mardi 24 juin (8h - 12h)
* 🗣️ Format : Entretien individuel
* ⏳️ Durée : 10mn
* 💯 Éléments de notation :
   - Vos connaissances et votre compréhension de Symfony (voir ci-après)
   - Votre réalisation au sein de l'application de groupe
* 📥️ Vous avez jusqu'au vendredi 20 juin 23h59 pour travailler sur votre application

## Éléments Symfony à retenir

{% include pages/exam/_elements.liquid symfony_elements=page.symfony_elements %}
