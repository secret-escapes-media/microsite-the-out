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
      label: Are you a UK resident and over the age of 25?
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
      label: Do you agree to receive emails from THE OUT?
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
    - id: phone-type
      type: radio
      label: What type of phone do you use?
      required: true
      options:
        - id: phone-iphone
          label: 'iPhone'
          value: 'iphone'
        - id: phone-android
          label: 'Android'
          value: 'android'
        - id: phone-other
          label: 'Other'
          value: 'other'
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition
---