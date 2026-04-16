---
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
      ## Events

      PLACEHOLDER TEXT — where you can find Button Kin next.

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

  - type: cta
    title: Want to host Button Kin at your event?
    description: PLACEHOLDER TEXT
    button:
      text: Get in touch
      href: /contact/
      variant: secondary
      size: lg
---
