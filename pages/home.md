---
name: Button Kin Games
permalink: /
layout: design-system-base.html
meta_title: "Button Kin Games | Indie TTRPG Studio | Manchester, UK"
meta_description: "Button Kin Games is a one-woman indie TTRPG studio from Yvris Burke, home to whimsical and strange tabletop roleplaying games with unusual themes."
header_image: src/images/brand/button_kin_header_banner.jpg
eleventyNavigation:
  key: Home
  order: 1
redirect_from:
  - /oh-my-stars/
  - /tags/press-kit/
blocks:
  - type: hero
    name: Button Kin Games
    lead: A One-Woman Games Studio from Yvris Burke
  # Intro — split image with a photo of Yvris
  - type: split-image
    content: |
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
      ## The Custom of the Sea

      The Custom of the Sea is Yvris' in-development Regency horror TTRPG. You'll play as a castaway, one of several from all levels of society shipwrecked and stranded with His Royal Highness the Prince Regent. You find yourselves on a mysterious island governed by a malevolent intelligence which wants to corrupt or destroy you. Will you hold strong to propriety or indulge your animal instincts to survive?
    button:
      text: Join a Play Test
      href: https://tickets.buttonkin.com/events
      variant: primary
    figure_src: /games/the-custom-of-the-sea/thumb.jpg
    figure_alt: The Custom of the Sea title image, white text on a blue and brown background showing an oil painting of ships in a storm

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
