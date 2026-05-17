---
name: Events
permalink: /events/
layout: design-system-base.html
meta_title: "Events | Button Kin Games"
meta_description: Upcoming conventions, online games, and community events featuring Button Kin Games.
eleventyNavigation:
  key: Events
  order: 5
blocks:
  - type: section-header
    intro: |-
      # Events

      Games, conventions, and play tests

  - type: snippet
    reference: upcoming-events

  - type: section-header
    intro: |-
      ## Recent Past Events

      A look back at the last few events Button Kin attended. See the full
      [past events archive](/events/past/) for more.

  - type: items
    collection: pastEvents
    horizontal: true

  - type: contact-form
    intro_content: |
      ## Do you want Button Kin at your event? Get in Touch
---
