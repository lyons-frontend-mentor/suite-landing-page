# Typemaster pre-launch landing page solution

## Overview

### The challenge

Create a responsive landing page based on the given Figma designs.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- HTML
- CSS

## Reflection

In my previous challenge, I developed a strategy whereby I carefully inspect each of the designs and write up notes (in `design.md`) before beginning to code. I chose this challenge because it's very similar to the previous one (another landing page), so that I could practice accounting for design changes between layouts. As a result, I mainly focused on refining my existing skills rather than discovering new ones. For example, in my CSS I decided to have four main styling sections:

1. General formatting, for styles applicable to all layouts (e.g. colors of text, buttons, etc.);
2. Mobile;
3. Tablet;
4. Desktop.

This change mainly helped me organize my CSS, as in retrospect combining the mobile and general formatting would achieve the same effect due to how I set up my media queries (only using minimum screen widths, rather than using both min and max). 

I'm not yet sure whether I want to continue using only minimum screen widths in the media queries, or whether I want to implement ranges. On the one hand, using only minimum screen widths allows the code to stack on top of each other (e.g. when margins/padding don't change). On the other hand, I found myself needing to negate old rules when the layout changed, especially for margins. For example, I needed to `unset` a lot of my old margins on the Jeremy image in the testimonial. While it was manageable in this challenge, I imagine it could become unsustainable for larger projects.

### Continued development

For future challenges I want to continue using this approach. However, I'd also like to consider whether I could use certain properties more cleverly. For example, a lot of people praise CSS Grid for eliminating the need for media queries. While I certainly need *some* media queries in this project (to use larger images as the screen size gets larger), perhaps a certain CSS Grid layout would allow the content prior to the testimonial to automatically adjust to the larger screen sizes. Peraps it could be something like this:

- The text component, the image, and each of the stats gets their own cells, for 5 cells total.
- Some sort of `auto-fill`/`auto-flow` property would allow the text and image to occupy the same line when possible.
- Perhaps choosing the track widths and heights appropriately would allow the stats to switch from taking up a column for the mobile/desktop layouts, to taking up a row for the tablet layout. 

On this last point, I'm not so sure, but this is certainly something to try in the future.
