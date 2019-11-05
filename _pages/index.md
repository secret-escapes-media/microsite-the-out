---
layout: competition
id: competition

title: Competition
long-title: Win your very own luxury escape
enter-cta: Enter Now


features:

  - id: stay
    title: The Stay
    description: The Poets House Hotel perfectly marries country charms with contemporary style. The turn-of-the-century listed building houses rooms fit for a glamorous sojourn, with copper baths perfect for long evening soaks with fizz in hand. This is your chance to indulge in the better life, gazing at gorgeous country views before discovering the Cambridgeshire countryside.

  - id: car
    title: The Car
    description: The new Range Rover Evoque R-Dynamic is packed with modern, bold design cues, innovative technology and new levels of refinement. Delivered to your door, step inside for a truly five-star adventure. It’s yours for the duration; where will the Evoque take you?


competition-form:
  id: comp
  post-url: "#getFormUrl"
  expiry-date: 2050-01-01
  fields:
    - id: name
      type: text
      label: Name
      required: true
    - id: email
      type: email
      label: Email
      required: true
    - id: qualify
      type: radio
      label: Are you a UK resident and over the age of 18?
      required: true
      options:
        - id: qualify-true
          label: 'Yes'
          value: 'yes'
        - id: qualify-false
          label: 'No'
          value: 'no'
          invalid: true
    - id: opt-in
      type: radio
      label: Would you like to receive emails from our Partner brand?
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
    - id: storytime
      type: text-long
      label: Tell us about your favourite travel experience
      required: true
    - id: eggs
      type: select
      label: What is your favourite continent?
      required: true
      options:
        - label: Africa
          value: africa
        - label: Antarctica
          value: antarctica
        - label: Asia
          value: asia
        - label: Europe
          value: europe
        - label: North America
          value: north-america
        - label: Oceania
          value: oceania
        - label: South America
          value: south-america
    - id: contact
      type: checkbox
      label: Do you have a preference on how we should contact you?
      required: true
      options:
        - id: contact-email
          label: Email
          value: email
        - id: contact-post
          label: Post
          value: post
        - id: contact-phone
          label: Phone
          value: phone
    - id: week
      type: select
      label: What is your favourite day of the week?
      options:
        - label: Monday
          value: mon
        - label: Tuesday
          value: tue
        - label: Wednesday
          value: wed
        - label: Thursday
          value: thur
        - label: Friday
          value: fri
        - label: Saturday
          value: sat
        - label: Sunday
          value: sun
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition
---