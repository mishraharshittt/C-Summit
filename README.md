# C-Summit
Climate Summit 2025's website.
# 🌍 C-Summit 2025 Website Repository
### Creating Sustainable Bharat

Welcome to the official repository for **C-Summit 2025**, India's largest student-led Climate and Sustainability Summit, hosted at Lovely Professional University. This repository contains all source code, assets, and documentation for the **official website** of the summit.

---

## 🌿 Vision & Mission
### Vision
To create a **sustainable future** by empowering students, entrepreneurs, and climate leaders to drive eco-innovation and responsible entrepreneurship across Bharat.

### Mission
C-Summit 2025 serves as a **collaborative platform** connecting young innovators, green startups, industry leaders, policymakers, and investors to explore sustainable solutions for India's climate challenges.

---

## 🌐 Website Features
- **Dynamic Storytelling Flow** — Experience the summit's journey from idea to execution.
- **Eco-Themed Design** — Inspired by nature, using greens, earth tones, and fluid organic shapes.
- **Comprehensive Event Showcase** — Schedule, speakers, workshops, competitions, and expo details.
- **Partner & Exhibitor Section** — Highlighting collaboration opportunities.
- **Impact Dashboard** — Real-time metrics showcasing C-Summit's contribution to sustainability.
- **Media Gallery** — Photo and video highlights from pre-event campaigns to summit days.
- **Interactive Pledge Feature** — Visitors commit to personal climate actions.

---

## 🎨 Design Guidelines
### Color Palette
- **Primary**: Forest Green (#2E7D32)
- **Secondary**: Earth Brown (#8D6E63)
- **Accent**: Sky Blue (#64B5F6)
- **Background**: Off-White (#F5F5F5)
- **Text**: Charcoal Grey (#424242)

### Typography
- **Headings**: Poppins
- **Body Text**: Inter
- **Optional Accent**: Handwritten eco fonts for quotes or highlights.

---

## 🏛️ Repository Structure
```plaintext
/
├── assets/
│   ├── images/               # All website images and icons
│   ├── videos/                # Event teaser and background video (optional)
│   ├── fonts/                  # Custom fonts if not using CDN
│
├── components/                 # Reusable UI components (navbar, footer, etc.)
│
├── pages/                       # Page-level components (Home, About, Events, etc.)
│
├── styles/
│   ├── global.css               # Base styles, typography, colors
│   ├── components/              # Individual component styles
│   ├── responsive.css           # Media queries for different devices
│
├── public/                      # Static assets (favicon, OpenGraph images)
│
├── data/
│   ├── schedule.json            # Event schedule
│   ├── speakers.json            # Speaker details
│   ├── partners.json            # Partner logos & details
│
├── .env                         # Environment variables (API keys, deployment settings)
├── README.md                    # This file
├── index.html                    # Static fallback (optional if SPA)
├── package.json                  # Project dependencies
├── next.config.js                # (If using Next.js)
└── app.js / main.js              # Primary entry file
