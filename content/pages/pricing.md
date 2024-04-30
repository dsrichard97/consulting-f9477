---
title: Pricing
slug: pricing
sections:
  - type: CarouselSection
    subtitle: ''
    items: []
    variant: dots-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: flex-end
        padding:
          - pb-0
      subtitle:
        textAlign: center
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/csu1.jpeg
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
      styles:
        self:
          textAlign: center
    posts: []
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: big-list
    colors: bg-light-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: STATISTICAL CONSULTING
        tagline: This is the tagline
        subtitle: MATHEMATICS & STATISTICS DEPARTMENT
        text: |
          Innovating research, recommendations, and project deployment.
        image:
          type: ImageBlock
          url: /images/csu1.jpeg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: flex-end
        margin:
          - mb-0
        padding:
          - pt-5
      subtitle:
        textAlign: center
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Graduate Research Lead
        tagline: Feature 1
        subtitle: STAT 544 - Statistical Consulting
        text: >
          All projects are driven through the department that get approved and
          become viable to graduate students.
        image:
          type: ImageBlock
          url: /images/Screenshot 2024-04-08 at 10.18.23 PM Small.jpeg
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-1
              - pb-1
              - pl-9
              - pr-9
            textAlign: center
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        padding:
          - pt-1
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Key Benefits
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Data Driven
    items:
      - type: FeaturedItem
        title: 10k+
        subtitle: Reports Done
        text: >
          We excel in crafting detailed, actionable reports tailored to business
          contexts, enabling you to make informed decisions that drive success
          and efficiency in your operations.
        image:
          type: ImageBlock
          url: /images/rp.png
          altText: Lightning bolt symbol on red background
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: 2x
        subtitle: Automated workflows
        text: >
          Automated systems reduce the risk of human error in calculations and
          data processing, ensuring that the results are reliable and
          reproducible.
        image:
          type: ImageBlock
          url: /images/am.jpeg
          altText: Featured icon two
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
      - type: FeaturedItem
        title: Research
        subtitle: Thesis
        text: >
          We specialize in transforming complex data and research into
          accessible insights, helping you not only achieve publication but also
          extend your academic influence.
        image:
          type: ImageBlock
          url: /images/p1.jpeg
          altText: Featured icon three
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: >-
          https://docs.google.com/forms/d/e/1FAIpQLSfG3uy5tFItDy0iIR3b3g9244SEI7y99Wn3OND9WzE0tVUErw/viewform?usp=sharing
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: small-list
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-0
          - pt-0
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: ImageGallerySection
    subtitle: Our clients
    images:
      - type: ImageBlock
        url: /images/a.png
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        url: /images/lbs.png
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/nv.png
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        url: /images/va.jpeg
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/az.png
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-neutral-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
