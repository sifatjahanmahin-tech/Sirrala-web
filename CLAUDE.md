# SirraLa Cleaning Services – Website Workspace

## Project Overview
Single-page marketing website for **SirraLa Cleaning Services** (Baniyachong Ventures LLC).
Serves the San Fernando Valley & Woodland Hills area of Los Angeles, CA.

## Tech Stack
- Pure HTML5 / CSS3 / Vanilla JS — **no build step, no frameworks**
- All code lives in one file: `index.html`
- EmailJS for contact form (service: `service_qy2l9yf`)
- Google Tag Manager (`GTM-P8SBCWDF`) for analytics
- Google Maps embed for service area
- Font Awesome 6.5.1 (CDN), Google Fonts: Playfair Display + DM Sans

## Color Palette
| Variable | Hex | Use |
|---|---|---|
| `--primary` | `#1a5c3a` | Forest green – main brand color |
| `--primary-light` | `#257c4f` | Hover states |
| `--secondary` | `#f5c842` | Warm gold – CTAs & accents |
| `--bg-light` | `#faf8f0` | Soft cream background |
| `--text-dark` | `#1a1a1a` | Body text |

## Key Sections (in order)
1. Header / sticky nav
2. Hero – headline + review card
3. Trust bar – stats (500+, 5-star, 100%, Locally Owned)
4. Services – 4 service cards + add-ons
5. How It Works – 3 steps
6. Promo banner – $100 OFF offer
7. Pricing – 3 tiers + add-on table
8. Testimonials – 3 client reviews
9. FAQ accordion
10. About – company story
11. Contact & Booking form (EmailJS)
12. Footer

## Business Info
- Phone: +1 (747) 365-6868
- Email: info@sirrala.com
- Hours: 7 Days/Week 8AM–6PM
- Facebook: profile.php?id=61579489464371
- Instagram: @sirralacleaning

## Development Notes
- No npm, no bundler — open `index.html` directly in browser
- Reveal animations use IntersectionObserver (`.reveal`, `.reveal-left`, `.reveal-right` → `.active`)
- Counter animation targets use `data-target` + `data-suffix` attributes
- FAQ accordion: `.faq-item.open` class toggled by JS
- Testimonials: existing 3-column grid, arrow + dot controls on mobile
