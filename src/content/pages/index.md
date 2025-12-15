---
_schema: default
title: Astro Component Library
pageSections:
  - _component: page-sections/heroes/hero-split
    eyebrow:
    heading: Technology-Driven & Outcome Focused
    subtext: >-
      LENDEM Solutions is a data-centered, decision management technology firm that delivers unparalleled results to its clients by transforming data into sound business decisions.
    imageSource: /src/assets/images/home/tech-driven.jpg
    imageAlt: Astro Component Library
    imageAspectRatio:
    imageFlare: dots-bg
    imageHeight: 460
    imageMaxWidth: 439
    paddingVertical: 6xl
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Learn more
        link: "#learn-more"
        iconName: ""
        iconPosition: before
        hideText: false
        variant: primary
        size: md
    reverse: false
    colorScheme: contrast
    backgroundColor: wave
  - _component: page-sections/features/feature-split
    eyebrow:
    heading: LENDEM Solutions
    subtext: >-
      At LENDEM Solutions, we empower lenders with intelligent systems to turn complex data into a strategic advantage – but what truly sets us apart is how deeply we engage. We don't just provide solutions; we embed alongside your team, aligning our systems and expertise with your goals. Whether you're scaling operations, refining credit strategies, or enhancing customer engagement, our focus remains the same: what matters to you, matters to us. Your success is our metric.
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Learn What Makes Us Different ›
        link: "/about-us/"
        iconName: ""
        iconPosition: before
        hideText: false
        variant: text
        size: md
    imageSource: /src/assets/images/home/laptop.jpg
    imageAlt: Website Feature
    imageAspectRatio: none
    imageRounded: true
    imageFlare: squares-1-bg
    imageHeight: 470
    imageMaxWidth: 523
    splitWidth: 554
    reverse: true
    colorScheme: default
    backgroundColor: base
  - _component: page-sections/features/feature-grid
    eyebrow:
    heading: Innovative Solutions
    subtext: We deliver value to our clients through proprietary valuation algorithms designed to drive volume and financial performance – amplified by our extensive network of relationships in the marketplace.
    gap: xl
    minItemWidth: 280
    maxItemWidth: 360
    features:
      - _component: page-sections/features/feature-grid/feature-item
        title: Decisioning
        description: >-
          Through data analytics and our proprietary scoring of hundreds of unique data points, we are able to help you immediately mitigate fraud as well as assess risk of non-payment leading to higher ROI.
        iconName: lendem/shield
        iconColor:
      - _component: page-sections/features/feature-grid/feature-item
        title: Omni-Channel Customer Acquisition
        description: >-
          With our vast experience in Ping Tree Maximization, Digital Advertising and Direct Mail, we are able to make split-second decisions to help our clients maximize the lifetime value of their consumers.
        iconName: lendem/network
        iconColor:
      - _component: page-sections/features/feature-grid/feature-item
        title: Vintage Maximization
        description: >-
          LENDEM has experience with several unique consumer products such as multi-payment installment and lines of credit giving our clients the flexibility to provide products that match the consumer's need.
        iconName: lendem/arrow-up
        iconColor:
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: See How Smart Data Drives Better Decisions ›
        link: "/solutions/"
        iconName: ""
        iconPosition: before
        hideText: false
        variant: text
        size: md
    colorScheme: default
    backgroundColor: surface
    align: center
  - _component: page-sections/features/benefit-grid
    eyebrow: How You Will Benefit
    heading: Cutting-Edge Technology
    subtext: We obsess over creating elegant technology solutions using data analytics tools and marketing pathways to grow our clients' businesses with robust and scalable solutions.
    gap: xl
    minItemWidth: 280
    maxItemWidth: 360
    features:
      - _component: page-sections/features/feature-grid/feature-item
        title: Customer Acquisition
        description: >-
          We help clients scale high-performance customer acquisition through proprietary valuation algorithms and deep marketplace relationships—built for efficiency, even at high volume.
        imageSource: /src/assets/images/home/customer-aquisition.png
        imageAlt: Customer Aquisition
      - _component: page-sections/features/feature-grid/feature-item
        title: Security
        description: >-
          We prioritize security at every level — leveraging authentication, encryption, fraud prevention, and data privacy. Our approach evolves with changing regulations and technology to help clients earn and maintain customer trust.
        imageSource: /src/assets/images/home/security.png
        imageAlt: Security
      - _component: page-sections/features/feature-grid/feature-item
        title: Scoring Model Development
        description: >-
          Our scoring models span credit risk, fraud, conversion, and lifetime value—flexible to match each client’s risk profile and performance goals. Whether targeting growth, efficiency, or long-term value, we align with your strategy.
        imageSource: /src/assets/images/home/scoring.png
        imageAlt: Scoring
    buttonSections:
    colorScheme: default
    backgroundColor: base
    paddingVertical: 6xl
    align: center
  - _component: page-sections/ctas/cta-small
    heading: Join our team that’s redefining what’s possible.
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Join our team
        link: "/careers/"
        iconName: ""
        iconPosition: before
        hideText: false
        variant: primary
        size: md
    colorScheme: default
    backgroundColor: base
    rounded: false
---
