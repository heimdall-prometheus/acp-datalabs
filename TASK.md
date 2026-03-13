Build a complete, production-grade single-page website for "ACP Data Labs" — a Surgical Outcomes Analytics firm. Output: one self-contained `index.html` file (all CSS/JS inline, saved at /home/reisig/.openclaw/workspace/projects/acp-datalabs/index.html).

## Strategic Context
ACP Data Labs is the firm of Dr. Adriana C. Panayi, M.D., Ph.D. (Harvard Medical School, Brigham & Women's Hospital, 304 publications, 6,257 citations). The site will be viewed by Hikma Pharmaceuticals executives (Medical Affairs, BD, EVP Strategy) who received a cold email and are doing a 45-second credibility check. The site must scream "serious research firm" not "startup" or "consulting agency".

## Design Direction
- **Aesthetic:** Refined luxury scientific. Think Nature journal meets Goldman Sachs. NOT pharma stock photos, NOT startup gradients.
- **Color:** Deep Navy (#0F1F3D) dominant, Warm White (#FAFAF7) backgrounds, Gold (#C9A84C) for accents/highlights only
- **Typography:** Libre Baskerville (serif, headlines) + Source Sans Pro (body) from Google Fonts
- **Feel:** Prestigious, data-driven, European academic with US commercial edge
- **Motion:** Subtle fade-ins on scroll, number counter animation for the stats, NO flashy effects

## Page Structure (exact order):

### 1. NAV (sticky, minimal)
- Logo: "ACP Data Labs" in gold
- Right: "Request a Briefing" button (gold border, on hover fills gold)

### 2. HERO SECTION
- Full-height, dark navy background
- Small tag above headline: "Surgical Outcomes Intelligence" (gold, letter-spaced)
- Main headline (large, serif, white): "From Population Data to Clinical Adoption"
- Subline (smaller, muted white): "We translate large-scale surgical registry analyses into actionable pharmaceutical strategy."
- CTA button: "Request a Briefing" (gold filled)
- Below CTA, 3 stats in a row:
  - "945,505" | "Surgical Patients Analyzed"
  - "Lancet Regional Health" | "Americas, 2026"
  - "Harvard · Heidelberg · BG Klinik" | "Institutional Affiliations"

### 3. WHAT WE DO (3 pillars, white background)
Section heading: "Our Work"
Three cards side by side:
1. **Evidence Architecture** — Procedure-specific analytics from peer-reviewed surgical registries (ACS-NSQIP, NIS, SEER), translated into procedure-level evidence packages for pharmaceutical strategy.
2. **Clinical Translation** — We convert population-level outcomes data into implementable clinical intelligence — protocol frameworks, prescribing pattern analysis, and hospital adoption roadmaps.
3. **Scientific Partnership** — Long-term research collaboration with pharmaceutical partners: real-world evidence development, regulatory support packages, and KOL network engagement.

### 4. FEATURED PUBLICATION (dark navy section)
Heading: "Featured Research"
One prominent publication card:
- Journal badge: "The Lancet Regional Health — Americas · 2026"
- Title: "Post-Surgical Opioid Prescribing in the United States: A National NSQIP Analysis"
- Authors: "Adriana C. Panayi, M.D., Ph.D. · Prof. Gabriel Hundeshagen, M.D."
- N= stat: "N = 945,505 Surgical Patients"
- Two key findings:
  - "72.3% of surgical patients discharged with opioid prescriptions across 11 specialties"
  - "Procedure-specific analysis across ACS-NSQIP 2024 — the largest published analysis of its kind"
- Keep it scientific, no commercial framing here

### 5. FOR PHARMACEUTICAL PARTNERS (white section)
Heading: "For Pharmaceutical Partners"
Intro: "ACP Data Labs works with pharmaceutical companies developing non-opioid analgesics to build the evidence base, identify high-value hospital targets, and design clinical adoption programs."
Three deliverables:
- Evidence Packages — Procedure-specific opioid prescribing data, addressable patient volumes, and clinical differentiation frameworks tailored to your product.
- Hospital Target Intelligence — Named facility-level analysis with decision-maker pathways: CMO, Pharmacy Director, ERAS Coordinator, Department Chair.
- Evidence-to-Protocol Packages — Implementation-ready clinical protocol templates for P&T Committee and Quality Committee submissions.
Below: "Engagements available on a project or retainer basis. References available upon request."
CTA: "Request a Briefing"

### 6. LEADERSHIP (light section)
Heading: "Scientific Leadership"
Two people:

**Dr. Adriana C. Panayi, M.D., Ph.D.**
Role: Founder & Principal Investigator
- Plastic Surgery Resident, BG Klinik Ludwigshafen / Heidelberg University
- Formerly: Harvard Medical School · Brigham & Women's Hospital
- 304 peer-reviewed publications · 6,257 citations
- First Author, Lancet Regional Health — Americas (2026)
- Links: Google Scholar (https://scholar.google.com) and LinkedIn (placeholder #)

**Prof. Dr. Gabriel Hundeshagen, M.D.**
Role: Scientific Advisor
- Chief, Plastic, Reconstructive & Hand Surgery
- BG Klinik Ludwigshafen · Heidelberg University
- Corresponding Author, Lancet Regional Health — Americas (2026)

### 7. COMPLIANCE NOTE (subtle, small, centered)
"All analyses conducted using de-identified, publicly available research datasets in compliance with applicable data use agreements. ACP Data Labs does not hold, process, or distribute individually identifiable patient data."

### 8. FOOTER (dark navy)
Left: "ACP Data Labs Ltd." with sub-text: "Nicosia, Cyprus · Founded by Dr. Adriana C. Panayi"
Center: contact@acpdatalabs.com
Right: Privacy Policy link | copyright 2026 ACP Data Labs Ltd.

## Technical Requirements
- Single index.html, all CSS in style tag, minimal vanilla JS
- Google Fonts: Libre Baskerville + Source Sans Pro
- Fully responsive, mobile-first
- No external JS dependencies
- "Request a Briefing" opens a modal with fields: Name, Company, Title, Email, Message — submits via mailto:contact@acpdatalabs.com
- Smooth scroll, sticky nav with opacity change on scroll
- IntersectionObserver counter animation on the 3 stats
- Privacy Policy: inline modal with GDPR placeholder text

When completely finished, run: openclaw system event --text "Done: ACP Data Labs website built" --mode now
