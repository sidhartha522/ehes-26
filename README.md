# HSS 2026 — Hyderabad Startup Summit

Official website for the **Hyderabad Startup Summit 2026**, organized by the Hyderabad Entrepreneurs Club.  
A premium dark-themed, static HTML website designed to inform, convert, and onboard attendees and exhibitors.

---

## 🗓 Event Details

| Field | Info |
|---|---|
| **Date** | April 19th, 2026 |
| **Venue** | Shubham Convention Centre, Nagole, Hyderabad — 500068 |
| **Expected Attendance** | 1500+ |
| **Organized By** | Hyderabad Entrepreneurs Club (Ekthaa) |

---

## 📄 Pages

### `index.html` — Main Landing Page
The primary event landing page covering:
- **Hero** — Summit branding with CTA to tickets & schedule
- **About** — Mission and stats (100+ VC meetings, 24H networking)
- **Power Panels** — Founder, Tech, Creator, Branding, and VC panels
- **Featured Ecosystem Builders** — Makers of Milkshakes, Flashshoot, BKP Homes
- **Summit Schedule** — Full day timeline from 10:00 AM to 3:00 PM+
- **Tickets** — Attendee Pass (₹499) and Pro Pass (₹1,999) via BookMyShow
- **Location** — Embedded Google Maps for Shubham Convention
- **Stalls CTA** — Promo card linking to the stalls booking page

### `stalls.html` — Stall Booking Page
Dedicated page for startups and food vendors wanting to exhibit:
- **Hero** — April 19 date, venue, 1500+ audience size
- **Who You'll Reach** — 6 audience types (founders, investors, students, etc.)
- **Stall Packages** — Small (₹5K), Big (₹10K), Food (₹10K+) cards
- **Important Guidelines** — What is/isn't provided; participant responsibilities
- **Why Take a Stall** — 4 benefit cards (leads, live demo, visibility, connections)
- **Contact** — WhatsApp deep-links to Vanshika & Saiteja

---

## 🗂 File Structure

```
ehes-26/
├── index.html          # Main event landing page
├── stalls.html         # Stall booking page
├── image.png           # Flashshoot / organizer logo
├── ekthaa (1).png      # Ekthaa logo
├── stalls-hss.pdf      # Source PDF for stall page content
├── render.yaml         # Render.com deployment config
└── README.md           # This file
```

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Markup** | HTML5 |
| **Styling** | Tailwind CSS (via CDN) + custom CSS |
| **Fonts** | Plus Jakarta Sans, Inter (Google Fonts) |
| **Icons** | Material Symbols Outlined (Google Fonts) |
| **Maps** | Google Maps Embed API |
| **Ticketing** | BookMyShow deep-link |
| **Deployment** | Render.com (static site) |

### Design System
- **Theme:** Dark glassmorphism
- **Background:** `#0A0F1C` (Deep Midnight)
- **Primary:** `#3B82F6` (Electric Blue)
- **Secondary:** `#6366F1` (Indigo/Purple)
- **Typography:** Plus Jakarta Sans (headlines) + Inter (body)
- **Components:** Glass cards, gradient CTAs, ambient glows, micro-animations

---

## 🚀 Deployment

The site is deployed as a **static site on [Render.com](https://render.com)**.

```yaml
# render.yaml
services:
  - type: web
    name: ehes-26
    env: static
    buildCommand: ""
    staticPublishPath: .
```

No build step required — all assets are served directly from the repository root.

---

## 📞 Contact

| Name | Phone | Role |
|---|---|---|
| **Vanshika** | [9032305209](https://wa.me/919032305209) | Stall Bookings |
| **Saiteja** | [9390771123](https://wa.me/919390771123) | Stall Bookings |
| **Email** | sidhartha@ekthaa.app | General Enquiries |
| **Instagram** | [@hyderabad.entrepreneurs.summit](https://instagram.com/hyderabad.entrepreneurs.summit) | Social |

---

© 2026 Hyderabad Startup Summit. All rights reserved.