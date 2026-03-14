# ACP Data Lab

**Analysis · Consulting · Prediction**

Surgical outcomes analytics and real-world evidence for the pharmaceutical industry.

🌐 **Live:** [acp-datalabs.pages.dev](https://acp-datalabs.pages.dev)

---

## Quick Start

The site is a single `index.html` file with all CSS and JavaScript inline. No build step required.

**To preview locally:**
```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deployment

**Automatic:** Every push to `main` triggers a deploy to Cloudflare Pages via GitHub Actions.

**Manual (if needed):**
```bash
npx wrangler pages deploy . --project-name acp-datalabs
```

## Project Structure

```
├── index.html              # Complete website (HTML + CSS + JS, single file)
├── assets/
│   ├── logo-acp.png        # Official logo (transparent background)
│   ├── logo-original.jpg   # Original logo file from Adriana
│   ├── logo-acp.svg        # SVG version of the logo
│   ├── adriana-profile.jpg # Dr. Panayi profile photo
│   ├── gabriel-profile.jpg # Prof. Hundeshagen profile photo
│   ├── favicon.ico         # Favicon
│   ├── favicon-16.png      # 16px favicon
│   ├── favicon-32.png      # 32px favicon
│   ├── apple-touch-icon.png# Apple touch icon
│   └── og-image.png        # OpenGraph social sharing image
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Search engine directives
├── .github/
│   └── workflows/
│       └── deploy.yml      # Auto-deploy on push to main
└── README.md
```

## Design System

| Element | Value |
|---------|-------|
| **Background** | White (`#ffffff`) |
| **Headings** | Navy (`#0F2B46`) |
| **Body text** | Dark (`#1e2d3d`) |
| **Accent** | Institutional Blue (`#165EAB`) |
| **Logo colors** | Red `#E23D38` · Blue `#2F80ED` · Yellow `#F2C94C` |
| **Font** | Source Sans Pro (body), Poppins (logo letters), Montserrat (logo wordmark) |
| **Border radius** | 4px (institutional, not rounded) |
| **Reference** | [Broad Institute](https://www.broadinstitute.org/) aesthetic |

## Logo Guidelines

- **Always use `logo-acp.png`** — do not recreate or regenerate the logo
- Resize is OK, but no cropping or editing
- The logo consists of three colored squares (red, blue, yellow) with lowercase white letters `a`, `c`, `p` and "DATA LAB" text below
- For individual letter tiles, use separate `a.png`, `c.png`, `p.png` files (when provided)
- Blue is the dominant accent color on the site; red and yellow appear only in the logo

## Content Sections

1. **Navigation** — Sticky, with logo + section links + contact CTA
2. **Affiliation Strip** — Harvard, Brigham & Women's, Zürich, Heidelberg, Cambridge, UCL, UTMB
3. **Hero** — Headline, subline, CTA, key statistics (945K+ records, 11+ specialties, 300+ publications, 11,200+ citations)
4. **Evidence Bar** — Compliance chips (de-identified data, IRB-reviewed, DUA-governed, publication-grade)
5. **About** — "Analysis. Consulting. Prediction." with ACP acronym breakdown
6. **Services** — Real-World Evidence, Market Landscape, Clinical Adoption Strategy
7. **Approach Banner** — Registry Expertise, Publication-Grade Rigor, Commercial Translation
8. **Publications** — Selected peer-reviewed publications with Google Scholar link
9. **Team** — Dr. Adriana C. Panayi (Founding Director) and Prof. Dr. Gabriel Hundeshagen (Research Associate & Senior Project Manager)
10. **Contact** — CTA + mailto form (contact@acpdatalab.com)
11. **Compliance/Footer** — Data governance statement, entity info

## Team Profiles

### Dr. Adriana C. Panayi, M.D., Ph.D.
- **Role:** Founding Director & Chair of Scientific Leadership
- **Affiliations:** Harvard Medical School · Brigham & Women's Hospital · University Hospital Zürich · UCL · University of Cambridge
- **Stats:** 7,709 citations · h-index 43 · 300+ publications

### Prof. Dr. Gabriel Hundeshagen, MMS.
- **Role at ACP:** Research Associate & Senior Project Manager
- **External:** Managing Senior Consultant, Plastic, Reconstructive & Hand Surgery, Director of Research
- **Affiliations:** UTMB Galveston · BG Klinik Ludwigshafen · Heidelberg University
- **Stats:** 3,500 citations · h-index 27 · 150+ publications

## Tech Stack

- **Hosting:** Cloudflare Pages (auto-deploy from GitHub)
- **Framework:** None — vanilla HTML/CSS/JS, single file
- **Fonts:** Google Fonts (Source Sans Pro, Poppins, Montserrat)
- **Domain:** `acpdatalab.com` (to be configured)
- **Contact:** `contact@acpdatalab.com` (mailto-based form)

## Making Changes

1. Edit `index.html` (or add/replace assets in `assets/`)
2. Commit and push to `main`
3. GitHub Actions automatically deploys to Cloudflare Pages (~30 seconds)
4. Site is live at [acp-datalabs.pages.dev](https://acp-datalabs.pages.dev)

### Font Color Consistency Rule
All text within a single element must be one color. Do not mix blue and black within the same word or number (e.g., "945K+" should be entirely one color, not "945" in blue and "K+" in black).

## License

Proprietary — ACP Data Lab Ltd., Nicosia, Cyprus.
