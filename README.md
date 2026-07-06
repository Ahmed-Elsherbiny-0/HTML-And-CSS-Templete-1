# Airport Landing Page

A landing page template built with plain HTML5 and CSS3. It's designed for a service/creative agency style business and includes a hero banner, services, portfolio, stats, testimonials, skills, pricing, and a newsletter subscribe section.

## Features

- **Sticky/overlay navigation** with logo, menu links, search icon, and a mobile hamburger menu
- **Hero/landing section** with full-screen background image, overlay, and slide bullets
- **Services section** in a 2-column responsive grid with icons
- **Design/about section** with a background image and feature list
- **Portfolio gallery** with filter tabs (All / App / Photo / Web / Print) and hover captions
- **Stats section** with icon-based counters over a background image
- **Testimonials & Skills section** with client quotes and animated progress bars
- **Pricing plans** in a 4-column responsive grid with a call-to-action button
- **Newsletter subscribe** section with an email form

## Project Structure

```
.
├── index.html      # Main HTML markup
├── style.css       # All styling and responsive rules
└── img/            # Image assets (referenced but not included)
    ├── ......

```

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — Flexbox, CSS Grid, pseudo-elements, and media queries (no frameworks or preprocessors)
- **Inline SVG** icons (no icon library dependency)

## Design System

Defined at the top of `style.css` as a reference scale:

- **Spacing:** 2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128 (px)
- **Font sizes:** 10 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98 (px)
- Base `html` font-size is set to `62.5%` so `1rem = 10px` throughout the stylesheet.
