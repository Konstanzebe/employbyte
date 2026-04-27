# Employbyte — Project Context

## What is Employbyte
AI business consultancy that builds custom AI employees for companies and startups.
A Maxitory company (maxitory.com) — operated by Konstanze Beiner.

## Business Model
Boutique & premium service. Process:
Inquiry → Discovery Call → Proposal → Build → Delivery & Handover

## Top 5 Verticals (by market demand)
1. Customer Support Agent
2. Sales Development Rep (SDR)
3. Social Media Manager
4. Finance & Accounting Assistant
5. HR & Recruitment Assistant

## Website Stack
- Pure HTML + CSS + JS (no framework, no build step)
- Bilingual: EN / DE (toggle in nav + footer)
- Fonts: Poppins (headings, weight 500) + DM Sans (body, weight 400)
- Google Fonts CDN

## Design DNA — exact Maxitory (maxitory.com)
| Token | Value |
|---|---|
| Background | #FFFFFF |
| Primary/Accent | #B69974 (gold) |
| Primary Warm | #FFBC7D (amber hover) |
| Dark | #232323 (charcoal) |
| Body Text | #4A4A4A |
| Muted | #888888 |
| Beige sections | #ECE8E0 |
| Border | #E0DAD0 |
| Container max-width | 1200px |

## Files
- index.html — main landing page
- style.css — all styles
- script.js — language toggle, mobile nav, scroll animations
- impressum.html — imprint page (German legal)
- impressum.css — imprint page styles
- images/ — all images pulled from maxitory.com
- CNAME — employbyte.com (GitHub Pages)

## Images (images/)
- ai-illustration.png → Hero right column (woman at laptop)
- hero-bg-2.png → Concept section (two women collaborating)
- hero-bg-3.png → Process banner (AI presentation to team)
- case-2.png → Customer Support case card
- case-1.png → Sales case card
- case-3.png → Finance case card
- ai-banner.png → CTA section background
- about.png → Maxitory logo in footer

## Page Sections (top → bottom)
1. Fixed nav — logo, links, EN/DE toggle, Calendly CTA
2. Hero — split layout (text left, photo right)
3. Stats bar — dark strip, 4 numbers
4. Concept — two-column, image + cards
5. Process banner — full-width photo with overlay text
6. Process — 4 steps with timeline
7. Why Employbyte — dark section, 4 value props
8. Case Studies — 3 cards with images (placeholders)
9. CTA section — gold bg with team photo overlay → Calendly
10. Footer — Maxitory logo, EN/DE toggle, legal links

## CTA / Booking
Calendly: https://calendly.com/k-beiner-maxitory/30min

## Hosting
- GitHub repo: https://github.com/Konstanzebe/employbyte.com
- Default branch: employbyte.com (renamed from main by GitHub Pages)
- GitHub Pages enabled, source: employbyte.com branch / root
- Custom domain: employbyte.com
- DNS: IONOS.de — 4 A records (@) + CNAME (www → konstanzebe.github.io)

## To deploy changes
git add . && git commit -m "your message" && git push

## Still TODO
- [ ] Add real case studies when available (replace placeholders)
- [ ] Add real client logos
- [ ] Create Datenschutz (Privacy Policy) page
- [ ] Add Employbyte logo/favicon
- [ ] English version of imprint (imprint.html)
- [ ] Enable HTTPS enforcement once SSL cert is issued by GitHub
