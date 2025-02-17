---
title: Careers
slug: careers
sections:
  - title:
      text: A team that works closely together
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Section subtitle
    text: >
      There are many variations of passages of Lorem Ipsum available, but the
      majority have suffered alteration in some form, by injected humour, or
      randomised words which don't look even slightly believable. If you are
      going to use a passage of Lorem Ipsum, you need to be sure there isn't
      anything embarrassing hidden in the middle of text.
    actions:
      - label: See open positions
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Meet The Team
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Featured items section subtitle
    items:
      - type: FeaturedItem
        title: Sacha Hutson
        tagline: ''
        subtitle: Co-Founder
        text: >
          The inspiration for this project came during the Christmas season of
          2024, when God placed a deep conviction on my heart to help a young
          man who was homeless. Initially, I hesitated at the thought of giving
          him £20, but the Holy Spirit gently but firmly convicted me, urging me
          to act in obedience. I committed to ensuring that, when I next saw
          him, I would give him that £20. However, God had far more in store
          than I could have ever imagined. Not only did I have the privilege of
          giving, but I also had the opportunity to minister to this young man,
          building a meaningful rapport and offering support in whatever way I
          could. This experience filled me with indescribable joy, knowing that
          through my obedience, I was able to serve God by helping someone in
          need and, most importantly, sharing the hope of Jesus with him. It was
          a powerful reminder of God's love and provision, and it ignited a
          passion within me to do more for others. To Him be all the glory for
          this journey. He is the true source of this mission, and it is only by
          His grace and guidance that I am able to step into this calling.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder image
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
            flexDirection: col
      - type: FeaturedItem
        title: Ifeatu Okafor
        tagline: ''
        subtitle: Co-Founder
        text: |
          Follow the tutorial to build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
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
            flexDirection: col
    actions: []
    variant: two-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Meet The Team
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person2.json
      - content/data/person1.json
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
  - title:
      text: Get Involved
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Subtitle goes here
    items:
      - title: Volunteer Worker
        subtitle: On-site Volunteer
        text: >
          Do you want to make an impact in our society? Join us as a hands-on
          volunteer.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Open Source Engineer
        subtitle: Marketing
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    actions:
      - label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
