# Golden Crust Bakery (WEDE5020 POE)

Website for Golden Crust Bakery, Riverdale (Proposal 1 from Part 1).
Student: Sibusiso Khoza | ST10532951 | Rosebank International

## Project structure
- `index.html`, `about.html`, `products.html`, `enquiry.html`, `contact.html`
- `css/style.css` (single external stylesheet linked on every page)
- `images/` (hero images used with `picture`, `srcset` and `sizes`)

## Design decisions (Part 2)
- Palette: cream `#fbf3e4`, golden brown `#c98a2b`, dark brown `#6b3f12`, burgundy `#8c2f39` (from the Part 1 proposal).
- Fonts: Fraunces (serif headings) and Work Sans (body), loaded from Google Fonts.
- Layout: Flexbox for header, nav and hero; CSS Grid for card sections.
- Breakpoints: desktop above 64em, tablet 40em to 64em (2 columns), mobile below 40em (1 column).
- Units: `rem`/`em` for type and spacing, `%` and `fr` for widths.
- Interaction: `:hover`, `:focus-visible` and `:active` on links, buttons, cards and form fields.

## Changelog
| Date | File | Change | Reason |
|------|------|--------|--------|
| 2026-08-21 | Proposal | Part 1 proposal submitted | Initial submission |
| 2026-__-__ | Proposal / HTML | **Add each Part 1 feedback correction here, one row per change, with the lecturer's comment** | Feedback from Part 1 |
| 2026-__-__ | css/style.css | Created external stylesheet with CSS reset and base styles (font, colours, margin/padding) | Part 2 requirement 2.1 and 2.2 |
| 2026-__-__ | css/style.css | Added typography styles (font-family, size, weight, line-height, letter-spacing) | Requirement 2.3 |
| 2026-__-__ | css/style.css | Built Flexbox header/hero and Grid card layout | Requirement 2.4 |
| 2026-__-__ | css/style.css | Added colours, borders, box-shadows and hover/focus/active states | Requirement 2.5 |
| 2026-__-__ | css/style.css | Added tablet and mobile media queries and relative units | Requirement 3.1 and 3.2 |
| 2026-__-__ | index.html | Added `picture` element with `srcset` and `sizes` for the hero image | Requirement 3.3 |
| 2026-__-__ | all pages | Linked `css/style.css` and added viewport meta tag | Requirement 2.1 |

## Screenshot evidence
Add your own screenshots from browser DevTools (F12, then device toolbar):
- Desktop (1440px): `screenshots/desktop.png`
- Tablet (iPad, 820px): `screenshots/tablet.png`
- Mobile (iPhone, 390px): `screenshots/mobile.png`

![Desktop](screenshots/desktop.png)
![Tablet](screenshots/tablet.png)
![Mobile](screenshots/mobile.png)

## References
Google Fonts (2026) Google Fonts. Available at: https://fonts.google.com (Accessed: 20 August 2026).
MDN Web Docs (2026) CSS: Cascading Style Sheets. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 20 August 2026).
MDN Web Docs (2026) Responsive images. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_images (Accessed: 20 August 2026).
MDN Web Docs (2026) Using media queries. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries (Accessed: 20 August 2026).
