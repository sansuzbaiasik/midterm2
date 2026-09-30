# Steppe & Mountains — Central Asia Travel Club

**Project Theme:** Multipage responsive travel club website (author's tours across Kyrgyzstan, Kazakhstan, Uzbekistan, and Tajikistan).

## Team Members

- Sansyzbay Assylkhan
- Muktar Aikorkem
- Kapessova Danaiym

## Brief Description

"Steppe & Mountains" is an educational travel club website consisting of five pages. The site introduces tour destinations, the team, and club values; it includes a price list for the season, a photo gallery, and an application form. The design is executed in a warm "earthy" palette (cream, terracotta, sage, coral) with editorial typography.

## Website Structure

| Page | File | Content |
|---|---|---|
| Home | `index.html` | Hero block, destinations, statistics, CTA |
| About Us | `about.html` | Club history, principles, team |
| Tours & Prices | `services.html` | What's included in the tour + price list table |
| Gallery | `portfolio.html` | Photo gallery (CSS Grid) + blog notes |
| Contacts | `contact.html` | Feedback form + contact information |

## Implemented Features

- 5 pages connected by common navigation; `<header>`, `<main>`, `<footer>` on every page
- HTML5 semantic tags: `header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `footer`, `table`, `form`
- External stylesheet `css/style.css` (no inline or internal styles)
- CSS variables in `:root` (colors, fonts, sizes, radiuses)
- Google Fonts: Playfair Display (headings) + Manrope (text)
- Layouts based on Flexbox (header, footer, CTA) and CSS Grid (hero, cards, gallery)
- Positioning: `sticky` header, `absolute` badges and photo captions, rotated label on the "About Us" page
- Pseudo-classes `:hover` and `:focus` for links, buttons, and form fields
- `:nth-child()` for table "zebra", card accents, list of principles, and gallery rhythm
- Table (price list) and HTML form (request on the contacts page)
- `loading="lazy"` attribute for all images below the first screen
- Bootstrap 5: grid (`container`, `row`, `col-*`) and utilities (`py-5`, `g-4`, `text-center`, `d-flex`, `h-100`, forms)
- Custom media queries for tablets (≤ 991.98px) and mobile devices (≤ 575.98px): vertical header, single-column grid restructuring
- Generated branded images in the `img/` folder

## Technologies Used

- HTML5 (semantic markup)
- CSS3 (variables, Flexbox, Grid, positioning, pseudo-classes, media queries)
- Bootstrap 5.3 (grid and utility classes)
- Google Fonts (Playfair Display, Manrope)

## Team Contributions

- **Sansyzbay Assylkhan** — *(placeholder: e.g., home page and main CSS)*
- **Muktar Aikorkem** — *(placeholder: e.g., About Us and Gallery pages)*
- **Kapessova Danaiym** — *(placeholder: e.g., Tours & Prices, Contacts, responsiveness)*

## Published Website

🔗 GitHub Pages / Netlify Link: *(insert link after publishing)*