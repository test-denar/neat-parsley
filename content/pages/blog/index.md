---
title: Blog
layout: PageLayout
sections:
  - type: FeaturedPostsSection
    variant: variant-a
    colors: colors-e
    bottomGap: none
    width: wide
    contentAlignHoriz: center
    title: Blog
    textAlign: center
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
  - elementId: ''
    colors: colors-a
    width: wide
    height: tall
    topGap: medium
    bottomGap: medium
    contentWidth: large
    contentAlignHoriz: left
    contentAlignVert: middle
    textAlign: left
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: Latest news
    subtitle: Featured blog posts section example
    actions:
      - type: Button
        label: View all
        url: /
        style: primary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    type: FeaturedPostsSection
  - elementId: ''
    colors: colors-h
    width: wide
    height: short
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: lorem-ipsum
    subtitle: lorem-ipsum
    testimonials:
      - type: Testimonial
        quote: >-
          “It’s great to see someone taking action while still maintaining a
          sustainable fish supply to home cooks.”
        name: Johnna Doe
        title: Product Marketing Manager at Acme
        image:
          type: ImageBlock
          url: /images/dianne-ameter.jpg
          altText: Product Marketing Manager
    type: TestimonialsSection
---
