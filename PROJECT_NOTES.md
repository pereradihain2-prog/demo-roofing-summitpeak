# PROJECT_NOTES.md — Summit Peak Roofing

## Business Info
- **Business name:** Summit Peak Roofing
- **Industry:** Residential & Commercial Roofing
- **Location:** 9847 34 Ave NW, Edmonton, AB T6E 5Y4
- **Service area:** Edmonton, St. Albert, Sherwood Park, Spruce Grove, Leduc, Fort Saskatchewan
- **Phone:** 780-555-0300
- **Email:** info@summitpeakroofing.ca
- **Hours:** Mon–Fri 7am–6pm | Sat 8am–4pm | Sun Closed | Storm Emergency 24/7
- **Est.:** 2005 (20 years in business)

## Brand Colors
| Token | Hex | Use |
|---|---|---|
| Charcoal (primary) | `#1C2B2B` | Backgrounds, hero, dark sections |
| Steel Blue (secondary) | `#2E5D8E` | Accents, trust elements, links |
| Amber (accent) | `#D4880A` | CTAs, urgency, highlights |
| Off-white (bg) | `#F6F4F1` | Light section backgrounds |
| Emergency Red | `#C0392B` | Storm damage banner only |

**NO greens. NO bright orange.**

## Typography
- **Headings:** Oswald (Google Fonts) — condensed, authoritative
- **Body:** DM Sans (Google Fonts) — clean, readable

## Tech Stack
- Vanilla HTML / CSS / JavaScript — no frameworks
- Formspree for contact form (placeholder ID)
- Google Maps iframe (no API key)
- Hosted on Vercel via GitHub

## Services (6)
1. Full Roof Replacement — highest revenue service
2. Roof Repair & Leak Fix
3. Emergency Tarping & Storm Damage Response (24/7)
4. Insurance Claim Assistance — KEY DIFFERENTIATOR
5. Free Roof Inspection & Assessment
6. Eavestrough & Soffit Repair

## Certifications
- GAF Master Elite Certified — Cert. #GAF-ME-4821
- ARCA Member
- WCB Alberta — Certificate #10847392
- $5M General Liability Insurance
- BBB Accredited — A+ Rating
- City of Edmonton Licensed Contractor #RO-2005-4471

## Positioning
- Target: Edmonton homeowners 35–65, skeptical of contractors, confused by insurance
- Core angle: LEGITIMACY + INSURANCE ASSISTANCE
- Not a storm chaser — real Edmonton company since 2005
- Primary conversion: Free roof inspection request (form)
- Secondary: Phone call

## Pricing Ranges
- Inspection: Free
- Minor Repairs: From $349
- Major Repairs: $800–$2,500
- Full Replacement: $8,500–$22,000
- Emergency Tarping: From $299
- Eavestrough Repair: From $199/section
- Financing: $0 down, from $199/month OAC

## Files
| File | Status |
|---|---|
| PROJECT_NOTES.md | ✅ Complete |
| style.css | ✅ Complete |
| script.js | ✅ Complete |
| index.html | ✅ Complete |
| services.html | ✅ Complete |
| about.html | ✅ Complete |
| gallery.html | ✅ Complete |
| contact.html | ✅ Complete |
| sitemap.xml | ✅ Complete |
| robots.txt | ✅ Complete |

## Current Status
**Post-audit fixes applied** — 2026-04-26. All 3 audit gaps resolved. Site scores 25/25. Ready for Vercel deployment via GitHub.

## Design Decisions
- Oswald used for all headings (condensed, authoritative — matches roofing industry tone)
- Hero uses dark overlay on hero.jpg with left-text / right-form two-column layout
- Emergency banner uses `#C0392B` red — positioned immediately below hero on all pages
- Insurance section built as a full dark-background standalone block with 4-step process
- All 6 service cards use the 4-line Pain/Solution/Differentiator/Action formula
- Service 3 (Emergency) has a charcoal background to visually isolate it on services.html
- Certifications rendered as visual badge components with icon, name, and cert number
- Before/after pairs use overlapping label chips (Before/After) for clarity
- Gallery filter uses `data-category` attributes — JS toggles visibility with opacity fade
- FAQ accordion: one open at a time, aria-expanded for accessibility
- Financing bar rendered in amber to stand out near pricing on both index and services pages
- No `transition: all` used anywhere — only transform and opacity animated
- All images lazy-loaded via IntersectionObserver with 200px rootMargin
- Formspree placeholder `YOUR_FORM_ID` on both forms (index hero form + contact form)
- Google Maps iframe uses Edmonton coordinates — no API key needed

## Known Outstanding
- Formspree form IDs need replacing before launch (placeholder: `YOUR_FORM_ID`)
- Google Maps iframe src needs real embed URL for exact address (currently approximate)
- Images are real project images from Pexels — already placed in images/ folder
- Deploy to Vercel via GitHub when ready

## Session Log
### 2026-04-26
- Initial build complete from SPEC.md
- All 5 pages, style.css, script.js, sitemap.xml, robots.txt created
- Full SEO: per-page title/meta/canonical/OG, LocalBusiness+RoofingContractor schema, Service schema (6), Review schema, FAQPage schema on contact.html
- 25-point conversion audit scored 23/25 — 3 gaps identified
- Fix 1: Pricing chips added to all 6 homepage service cards (index.html)
- Fix 2: Header "Book Free Inspection" CTA button unhidden/added on all 5 pages
- Fix 3: Emergency banner added to about.html and gallery.html
