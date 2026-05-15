---
name: Button Kin Games
permalink: /
layout: design-system-base.html
meta_title: "Button Kin Games | Indie TTRPG Studio | Manchester, UK"
meta_description: "Button Kin Games is a one-woman indie TTRPG studio from Yvris Burke, home to whimsical and strange tabletop roleplaying games with unusual themes."
eleventyNavigation:
  key: Home
  order: 1
redirect_from:
  - /oh-my-stars/
  - /tags/press-kit/
blocks:
  # Intro — split image with a photo of Yvris
  - type: split-image
    content: |
      ## A One-Woman Games Studio from Yvris Burke

      Established in 2020 by game designer, writer, and web developer Yvris
      Burke, Button Kin Games is home to whimsical and strange TTRPGs with
      unusual themes, and a smattering of D&D 5e content.

      Check out the [About](/about/) section to learn more about Yvris, or
      the [blog](/blog/) to catch up on recent happenings.
    button:
      text: More about Yvris
      href: /about/
      variant: secondary
    figure_src: images/alex.jpg
    figure_alt: Yvris Burke at a TTRPG convention

  # New game ad — hero banner promoting the latest release
  - type: split-image
    reverse: true
    content: |
      ## Jude's World

      A plucky preteen struggles to reunite their separating parents in this
      solo, tarot-based journaling TTRPG. Take on the role of 12-year-old Jude
      and steer them through a complicated time in their young life.
    button:
      text: Read More
      href: /releases/judes-world/
      variant: primary
    figure_src: /games/judes-world/thumb.png
    figure_alt: Jude's World Front Cover

  # Featured releases
  - type: items
    intro_content: |
      ## The Buttonkin Games Catalogue
    collection: games
    filter:
      property: data.featured
      equals: "true"

  # Newsletter signup
  - type: snippet
    reference: newsletter

  # Recent blog posts
  - type: snippet
    reference: recent-blog-posts

  # Upcoming events
  - type: snippet
    reference: upcoming-events
---
