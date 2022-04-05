# Design

## Components

- Header
  - Logo
  - CTA
- Main
  - `h1`
  - Text
  - CTA
- Phone image
- Stats
  - Three stat components, each consisting of:
    - Stat
    - Name of category
- Testimonial
  - Image
  - Arc
  - Block quote
  - Attribution
- Footer
 
## Design system

### Colors

- Gray 800
  - Header text
  - Header CTA border
  - Header CTA hover BG
  - Curve over header
  - Main header
  - Main CTA BG
  - Stat number
  - Footer logo and icons
- Gray 500
  - Text in main
  - Stat text
  - Copyright info
- Cream
  - Body text in testimonial
  - Background box at bottom
- White
  - Header and attribution for testimonial
  - Header CTA hover text
  - Main CTA text
- Lavender, pink, orange
  - Gradient for main CTA hover BG

### Typography

- Epilogue font, bold & regular
- Heading XL: Bold and regular, 72px - 78px, -1px char space
  - 38px - 44px, -0.53px on mobile
  - 56px - 64px, -0.78px on tablet
- Heading L: Bold and regular, 48px - 56px, -0.5px char space
- Heading M: Bold, 18px - 32px, -0.2px char space
- Heading S: Bold, 16px - 26px, -2.5px char space
- Quote: Regular, 20px - 35px
- Body: Regular, 18px - 32px
  - 16px - 28px on mobile and tablet
- Footer: Regular, 15px - 32px

### Active states

- Header button colors inverted on hover
- Main CTA bg gradient on hover
- Opacity 50% on social icons in footer

## Layouts

### Mobile

#### Distinguishing features

- Column with each block having its own line (except header)
- All text except in Head is center-aligned
- Testimonial fills entire width, overriding margins
- Footer is a column

#### Dimensions

- Body
  - mt-24
  - mx-16
  - Everything centered
- Header
  - mb-56
  - 'suite' 32px 32px -0.44px
  - CTA
    - 14px 24px -0.14px
    - br-6
    - px-16 py-12
- Main
  - mb-56
  - Column aligned
  - `h1`
    - mb-32
    - Arc
      - mb-8
      - 151.47 x 16.89
  - Text
    - mb-32
  - CTA
    - 18p 32px -0.18px
    - br-6
    - px-32 py-14
- Image
  - mb-56
  - 343 x 240
  - br-15
  - Landscape
- Stats
  - mb-56
  - Stat
    - mb-32
- Testimonial
  - mb-56
  - Everything centered
  - Image
    - mb-40
    - Centered
    - Jeremy small, 252 x 402
    - Blur centered horizontally behind Jeremy, at bottom
    - Comes up 180px above background
  - Arc
    - mb-36
    - 49.27 x 40
  - Quote
    - mb-40
    - x-margin in-line
    - Header
      - mb-40
      - 40px, 48px, -0.42px
  - Attribution
    - mb-64
- Footer
  - mb-80
  - Components mb-80
  - Background
    - 100% x 420
  - Icons
    - Width between 28px

### Tablet

#### Distinguishing features

- Main and image share same line, header goes into image
- Stats all on one line
- Testimonial now in line with rest of margins
- Footer all on one line

#### Dimensions

- Body
  - mt-40
  - mx-40
- Header
  - mb-80
  - CTA
    - 16px 32px -0.16px
    - br-6
    - px-24 py-12
- Main, together with image
  - mb-88
  - Column aligned
  - `h1`
    - mb-40
    - Overlaps with image
    - Arc
      - mb-16
      - 231.19 x 29
  - Text
    - mb-40
  - Image
    - mb-56
    - 343 x 240
    - br-15
    - Portrait
- Stats
  - mb-92
  - Stat
    - gap 10px
- Testimonial
  - mb-72
  - x-margin in-line
  - Quote
    - Text
      - mx-58
- Footer
  - mb-72
  - Background
    - 100% x 640

### Desktop

#### Distinguishing features

- Stats now take up column along same line as main and image
- Man in testimonial now on left instead of top

#### Dimensions

- Body
  - Max content width of 1110; outside this
  - mt-50
- Nav bar
  - mb-66
- Main, image, and stats
  - mb-144
  - Everything center-aligned vertically
  - Main
    - Arc
      - 287 x 36
    - Text
      - mb-52
  - Image
    - mr-96
    - 350 x 600
  - Stats
    - Stat
      - mb-64
      - Left-aligned
  - Main
    - mb-56
    - Column aligned
    - `h1`
      - mb-32
      - Arc
        - mb-8
        - 151.47 x 16.89
    - Text
      - mb-32
    - CTA
      - 18p 32px -0.18px
      - br-6
      - px-32 py-14
  - Image
    - mb-56
    - 343 x 240
    - br-15
  - Stats
    - mb-56
    - Stat
      - mb-32
- Testimonial
  - mb-96
  - Image
    - mr-30
    - Becomes large, 375 x 600
    - Now on left, bottom aligning with container
    - 55px above background
  - Arc
    - mr-52
    - 64.05 x 52
    - 161px from top
  - Quote
    - text left-aligned
- Footer
  - Background
    - 100% x 464