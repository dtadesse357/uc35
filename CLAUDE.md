# UC35 — Project Bible

## What Is UC35
UC35 is a solo web design agency specializing in building
professional websites for construction businesses. Services
target contractors, roofers, HVAC companies, plumbers,
electricians, painters, and general construction trades across
the United States.

**Tagline:** Built to Win Contracts
**Owner:** Ayyub
**Business Model:** Cold outreach → client intake → site build →
delivery → maintenance retainer
**Status:** Active — in growth phase

---

## Figma Make Workflow

UC35 uses Figma Make as the primary rapid site generation tool.

### How It Works
1. Find a target business on Google with no website
2. Copy their full Google Business Profile listing text
3. Paste into Figma Make — full site generates automatically
4. Light refinement and cleanup
5. Send preview link to business owner as cold outreach
6. If they say yes — collect deposit then move to delivery

### Delivery Decision
- Starter $299 → deliver refined Figma Make version
- Standard $499 → deliver refined Figma Make version
- Premium $799 → always rebuild in Antigravity as clean HTML
- Client requests code ownership → rebuild in Antigravity

### Why This Works
Showing a business owner their own business looking
professional is more powerful than any sales pitch.
The preview link IS the pitch.

---

## File Structure.
~/Documents/UC35/
├── CLAUDE.md               → This file. Read first every session.
├── index.html              → UC35 agency portfolio page
├── steele-and-sons.html    → Sample site 1
├── ironridge-roofing.html  → Sample site 2
├── peakline-hvac.html      → Sample site 3
├── clients/                → One folder per live client
│   └── [client-name]/
│       └── index.html
├── agents/                 → Agent instruction files
│   ├── builder.md
│   ├── copy.md
│   ├── outreach.md
│   └── review.md
└── skills/                 → Reusable skill instruction files
├── new-client-site.md
├── generate-copy.md
├── deploy-checklist.md
├── swap-colors.md
└── add-testimonials.md
---

## Tech Stack — Non-Negotiable Rules
- Single file HTML/CSS/JS per site — everything in one .html file
- No CSS frameworks — no Bootstrap, no Tailwind, no Bulma
- No JS frameworks — no React, no Vue, no Angular
- Google Fonts allowed — Inter or Barlow preferred
- GSAP allowed — use for scroll animations and entrance effects
- CSS used for hover effects, transitions, and micro-interactions
- All sites must be fully mobile responsive (320px → 1440px)
- No placeholder lorem ipsum — all copy must be real and purposeful
- Forms do not need backend — functional appearance is sufficient
  unless explicitly told otherwise
- Host on Vercel — one folder per client site

---

## Design System — Apply to Every Site Built

### Color Palette (Default Construction Theme)
- Background dark: #0D0D0D
- Background card: #1A1A1A
- Primary text: #FFFFFF
- Secondary text: #A0A0A0
- Default accent: #E87722 (orange) — swap per client
- Border: #2A2A2A

### Typography
- Primary font: Inter (Google Fonts)
- Fallback: Barlow, sans-serif
- Hero headline: 56px bold
- Section headline: 36px bold
- Card title: 20px semibold
- Body: 16px regular, 1.6 line height

### Component Rules
- Buttons: solid fill with accent color, 4px border radius,
  uppercase tracking on text, smooth hover lift effect
- Cards: dark background #1A1A1A, 1px border #2A2A2A,
  hover border glows with accent color
- Sections: 80px padding top and bottom
- Navigation: sticky, dark background with blur on scroll
- All images: use CSS gradients or dark overlays —
  no external image URLs unless client provides them

---

## Standard Site Structure
Every client site must follow this section order:

1. Sticky navigation — logo left, links right
2. Hero — headline, subheadline, two CTAs
   (Get a Free Quote + View Our Work)
3. Services — 3 service cards with icon, title, description
4. About — company bio + 3 stat boxes
5. Testimonials — 2 client quotes with name and location
6. Contact form — Name, Phone, Email, Service dropdown, Message
7. Footer — name, phone, email, copyright

---

## Pricing Tiers

### Starter — $299
- 3 pages: Home, About, Contact
- Mobile responsive
- Contact form
- Google Maps embed
- Delivered in 5 business days
- 2 rounds of revisions

### Standard — $499
- 5 pages + everything in Starter
- SEO meta tags, page titles, descriptions
- Social media links
- Photo gallery section
- Delivered in 5 business days
- 2 rounds of revisions

### Premium — $799
- Everything in Standard
- Logo design (Canva-based)
- Google Business Profile setup guidance
- 1 month of post-delivery edits included
- Delivered in 3 business days
- 2 rounds of revisions

### Maintenance Retainer — $75/month
- Hosting management
- Small content edits
- Monthly health check
- Push this on every client after delivery

---

## Payment Structure
- Platform: Zelle (preferred)
- Structure: 50% deposit before any work begins,
  50% on final delivery
- Never begin building without deposit received
- No refunds after delivery of preview link

---

## Client Communication
- Email: uc35agency@gmail.com
- Phone: available (SMS preferred for contractors)
- Response time target: within 4 hours during business hours
- Tone: professional, confident, brief — contractors are busy

---

## Revision Policy
- 2 rounds of revisions included in all packages
- Revisions must be submitted in writing (email or text)
- Changes to core structure or content after delivery
  are billed at $50/hour
- Scope creep is not tolerated — new pages = new invoice

---

## Agents (in ~/Documents/UC35/agents/)
These are specialized instruction sets Claude Code activates
for specific tasks:

- **builder.md** — builds full client site from intake info
- **copy.md** — writes all website copy from business details
- **outreach.md** — generates cold outreach messages per business
- **review.md** — audits finished site before client delivery

To activate an agent, read its .md file then execute the task.

---

## Skills (in ~/Documents/UC35/skills/)
Reusable task instructions for repeatable operations:

- **new-client-site.md** — full workflow to build a new client site
- **generate-copy.md** — generate all copy for a given business
- **deploy-checklist.md** — pre-delivery quality checklist
- **swap-colors.md** — rebrand template to new client colors
- **add-testimonials.md** — add or update testimonials section

To use a skill, read its .md file then follow its instructions.

---

## What Good Looks Like
- Site loads fast — no heavy assets
- Looks legitimate enough that a contractor would pay $499 for it
- Mobile experience is as good as desktop
- Copy speaks directly to the client's customers
  (homeowners, businesses needing construction work)
- Clear call to action above the fold
- Contact info visible without scrolling

## What to Avoid
- Generic stock-photo placeholder URLs that break
- Lorem ipsum anywhere on the page
- Overly complex animations that slow the site
- Frameworks — they add bloat for single-file sites
- Vague copy like "We are the best" without specifics
- Breaking the single-file rule — everything in one .html

---

## Session Protocol
Every time a new Claude Code session opens on UC35:
1. Read CLAUDE.md first
2. Confirm understanding of the project
3. Ask what the task is for this session
4. Execute — do not deviate from the rules above without
   explicit instruction from Ayyub

---
*UC35 Project Bible — keep this file updated as the
project evolves*
