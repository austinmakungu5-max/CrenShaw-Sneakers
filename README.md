# CrenShaws Sneakers — Website Project

## Project Title
CrenShaws Sneakers Website (WEDE5020 POE — Part 2)

## Student Information
- Name: Austin Makungu
- Student Number: ST10517674
- Group: 2

## Project Overview
A five-page website for CrenShaws Sneakers, a sneaker studio offering new
drops, cleaning and restoration, fit consultations, and authentication
services. The site introduces the brand, showcases its offering, and
allows visitors to send an enquiry or get in touch.

## Website Goals and Objectives
- Generate leads through an online enquiry form.
- Present the brand and its services clearly to potential customers.
- Provide easy-to-find contact information and studio location.
- KPI: number of enquiry form submissions per month.
- KPI: contact page to enquiry page conversion rate.

## Key Features and Functionality
- Homepage with hero introduction and a featured product.
- About Us page with brand story, mission, vision, and team.
- Services page detailing all four core services.
- Enquiry page with an embedded Google Form for enquiries (name, contact
  details, interest, and message collected via the form itself).
- Contact page with studio location (embedded Google Map) and contact details.
- Consistent navigation menu across all five pages.

## Timeline and Milestones
| Milestone | Target |
|---|---|
| Website Project Proposal | 12 August  |
| HTML structure (all 5 pages) | 14 August|
| CSS styling and responsive design | 18 September |
| JavaScript functionality and SEO | 18 October |

## Part 1 Details
This submission (Part 1) includes:
- The initial HTML structure for all 5 required pages.
- Basic CSS styling (colour scheme and typography).
- Folder structure: root HTML files, with `css/`, `js/`, and `images/` subfolders.

## Part 2 Details
This submission (Part 2) includes:
- A single external stylesheet (`css/style.css`) linked from every page
  (previously only one page linked to a stylesheet, and it pointed to a
  file that didn't exist — this has been corrected).
- A CSS reset, base typography, and colour scheme applied site-wide.
- Decorative, typographic, and layout styling for the desktop solution,
  using CSS Grid for the homepage hero and the product/service card grids.
- Interactive states (`:hover`, `:focus`, `:active`) on links, buttons,
  and form fields, plus `box-shadow` for depth on cards, images, and buttons.
- Full responsive design: breakpoints at 768px (tablet) and 480px
  (mobile) implemented with `@media screen and (max-width: ...)` —
  the `.container` grids drop from 3 columns to 2 to 1, and the
  navigation stacks vertically on smaller screens.
- Navigation restructured to a `nav > ul > li > a` pattern (previously
  plain `<a>` tags with no list), styled with `nav ul`/`nav ul li a`.
- Card/team/gallery layouts now use a single reusable `.container` /
  `.container div` pattern instead of separate `.cards`/`.card` classes
  — any `div` placed inside `.container` is styled automatically.
- Added a "Style Inspiration" gallery on the homepage using this same
  `.container` pattern, showing six promotional-style sneaker images
  for visual inspiration (clearly labelled as inspiration, not exact
  current stock, since some of the source images feature other brands'
  products).
- Relative units (`rem` for type, `%`/`vw` for layout and image sizing)
  used throughout instead of fixed pixel values.
- Responsive images: `srcset`/`sizes` used on the hero and featured
  product images so the browser loads an appropriately sized file
  (480w/800w/1200w) per screen size.
- Fixed broken navigation on the homepage (all links previously pointed
  to `#` instead of the other pages).
- Added real content to the About, Services, Enquiry, and Contact pages,
  which were previously empty shells with no `<main>` content.
- Renamed `enquries.html` to `enquiry.html` (spelling) and updated all
  navigation links accordingly.
- Removed unused/missing image references (`brand1-logo.jpg` through
  `brand5-logo.jpg`, `product4.jpg` through `product8.jpg`) that pointed
  to files which didn't exist in the project.
- Screenshot evidence of the desktop, tablet, and mobile views has been
  added to `/screenshots` and is referenced below.

### Screenshot Evidence
| Page | Desktop | Tablet | Mobile |
|---|---|---|---|
| Home | `screenshots/home-desktop.png` | `screenshots/home-tablet.png` | `screenshots/home-mobile.png` |
| About | `screenshots/about-desktop.png` | `screenshots/about-tablet.png` | `screenshots/about-mobile.png` |
| Services | `screenshots/services-desktop.png` | `screenshots/services-tablet.png` | `screenshots/services-mobile.png` |
| Get in Touch | `screenshots/enquiry-desktop.png` | `screenshots/enquiry-tablet.png` | `screenshots/enquiry-mobile.png` |
| Contact | `screenshots/contact-desktop.png` | `screenshots/contact-tablet.png` | `screenshots/contact-mobile.png` |

Part 3 (JavaScript functionality and SEO) will follow in a future
submission/edit.

## Sitemap
```
Home (index.html)
├── About Us (about.html)
├── Services (services.html)
├── Get in Touch (enquiry.html)
└── Contact (contact.html)
```
All pages are on the same level and are reachable from the main
navigation menu on every page.

## Changelog

### Part 1
- 9 August 2026 — Initial HTML structure created for all 5 pages.
- 13 August 2026 — Basic CSS styling applied (colour palette, typography, layout).

### Part 2
- 25 August 2026 — Fixed broken homepage navigation (links previously all
  pointed to `#`).
- 25 August 2026 — Linked a single external stylesheet (`css/style.css`) from
  every page; removed the reference to a non-existent `css/style.css`
  on the old Contact page and the unlinked pages.
- 25 August 2026 — Added real `<main>` content to About, Services, Enquiry, and
  Contact pages (previously empty).
- 25 August 2026 — Renamed `enquries.html` to `enquiry.html` and corrected all
  navigation links referencing it.
- 28 August 2026 — Removed image references to files that didn't exist in the
  project (`brand1-logo.jpg`–`brand5-logo.jpg`, `product4.jpg`–`product8.jpg`).
- 1 September 2026 — Added `box-shadow` to cards, hero images, and the primary
  button for visual depth.
- 1 September 2026 — Added `:focus` and `:active` states to nav links, the
  button, and form inputs (previously only `:hover` was styled) for
  better accessibility and interactivity feedback.
- 9 September 2026 — Added `letter-spacing` to header text and the button for
  refined typography.
- 10 September 2026 — Restructured product/service listings into a `.cards` CSS
  Grid container.
- 10 September 2026 — Implemented responsive design: added `@media screen and
  (max-width: ...)` breakpoints at 768px (tablet) and 480px (mobile);
  `.container` grids collapse from 3 to 2 to 1 columns; navigation
  stacks vertically on mobile.
- 15 September 2026 — Restructured navigation to a `nav > ul > li > a` pattern on
  all 5 pages.
- 15 September 2026 — Replaced `.cards`/`.card` with a reusable `.container` /
  `.container div` pattern; applied it to the homepage featured drop,
  the new Style Inspiration gallery, the Services cards, and the About
  page team cards.
- 15 September 2026 — Added six promotional-style images to a new "Style
  Inspiration" gallery on the homepage, each with `srcset` for
  responsive loading.
- 15 September 2026 — Generated multiple image resolutions (480w/800w/1200w) and
  added `srcset`/`sizes` to the hero and featured product images for
  responsive, bandwidth-friendly image loading.
- 18 September 2026 — Added screenshot evidence of desktop/tablet/mobile views to
  the README.
- 18 September 2026 — Removed macOS system files (`__MACOSX/`, `._*`) from the
  project folder before packaging for submission.

## References
- MDN Web Docs — CSS Grid Layout: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- MDN Web Docs — Using media queries: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- MDN Web Docs — Responsive images (`srcset`/`sizes`/`picture`):
  https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images
- MDN Web Docs — CSS pseudo-classes (`:hover`, `:focus`, `:active`):
  https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes
- Google Maps embed used on the Contact page: https://www.google.com/
