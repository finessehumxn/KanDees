# KanDees Kreations LLC — Website

**Full-scope brand website for a handmade resin art and keepsakes business.**

[![Type](https://img.shields.io/badge/Type-Client%20Project-orange?style=flat)]()
[![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JavaScript-blue?style=flat)]()
[![Status](https://img.shields.io/badge/Status-Delivered-brightgreen?style=flat)]()
[![Deploy](https://img.shields.io/badge/Deploy-Netlify%20%2B%20GitHub-black?style=flat)]()

---

## Overview

KanDees Kreations LLC is a woman-owned, handmade resin art and keepsakes business based in Florida. This project is a full-scope website build covering brand identity presentation, product showcase, custom order flow, and client lead generation — deployed via GitHub and Netlify.

**Live site:** `kandeeskreations.com` *(deploy to activate)*

---

## Scope of Work

### Design
- Brand color system implementation (#8162E6 · #FE56AB · #FF814D · #5EC777)
- Rouge Script + Poppins typography pairing
- Mobile-first responsive layout
- Animated hero section with floating elements
- Gradient mesh backgrounds and glassmorphism accents
- Scroll-triggered reveal animations throughout

### Development
- Single-file HTML/CSS/JS — zero dependencies, zero build step
- Custom order modal with full form → email handler
- Contact form → email handler with field capture
- FAQ accordion (open/close toggle)
- Announcement bar with rotating text
- Mobile hamburger menu
- Wishlist heart toggle buttons
- Newsletter signup → email handler
- Smooth scroll navigation
- Intersection Observer scroll reveals

### Sections Built
1. Rotating announcement bar
2. Sticky navigation + mobile menu
3. Hero with logo, CTAs, floating dots
4. Stats strip (500+ customers, 1000+ pieces, 5★)
5. Business card banner
6. Shop by Category (6 cards)
7. Featured Products with pricing + wishlist
8. 4-Step Custom Order Process
9. About / Our Story
10. Testimonials (3 cards)
11. Social / Instagram section
12. Contact + FAQ accordion
13. Footer with newsletter

---

## How to Deploy

### Deploy to Netlify via GitHub

1. Create a new GitHub repo (e.g. `kandees-kreations`)
2. Upload `index.html` to the root of the repo
3. Go to [netlify.com](https://netlify.com) → New site → Connect GitHub repo
4. Publish directory: `/` (root)
5. Click Deploy

### Connect Custom Domain
In Netlify → Domain Management → Add `kandeeskreations.com`
Update nameservers at your domain registrar to point to Netlify.

---

## How the Forms Work

All forms use `mailto:` links — no backend or third-party service required.

When a user submits:
- **Order modal** → opens email client with pre-filled subject + order details to `kandees.kreations.llc@gmail.com`
- **Contact form** → opens email client with inquiry details
- **Newsletter** → opens email client with subscriber email

**To upgrade to a real form backend:** Replace `window.location.href = 'mailto:...'` with a [Formspree](https://formspree.io) fetch call (free tier available).

---

## What to Add Next

- [ ] Real product photos from `@kandees.kreations.llc` Instagram
- [ ] Formspree integration for form submissions without email client pop
- [ ] Calendly embed for custom order consultations
- [ ] Instagram feed widget (Behold or LightWidget, free tier)
- [ ] Google Analytics
- [ ] Shop/cart functionality (Snipcart or Shopify Buy Button)

---

## Client Info

**Business:** KanDees Kreations LLC
**Owner:** Krystal
**Email:** kandees.kreations.llc@gmail.com
**Phone:** (321) 316-0422
**Social:** @kandees.kreations

---

## Built By

**Millennials Creatives LLC** — creative and technology services for small businesses.

**L. Finesse Humxn** — AI systems engineer, full-stack developer, founder.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lfinesse---%230077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/lfinesse-)
[![Portfolio](https://img.shields.io/badge/Portfolio-finessehumxn.com-purple?style=flat)](https://finessehumxn.com)
