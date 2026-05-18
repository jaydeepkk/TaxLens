# TaxLens

**UK Tax-Awareness Simulator** — taxlens.io

A guided journey calculator for UK PAYE earners. Plain English tax explanations, real-time calculations, and the UK's first tax position heat map.

---

## What it is

TaxLens helps UK PAYE employees understand their tax position through a guided seven-step journey — not a wall of numbers. Every technical term is explained in plain English. Every insight is personalised to the user's specific inputs.

**Not financial advice. Educational simulations only. Based on publicly available 2025/26 HMRC rules.**

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Homepage — landing page, teaser calculator with heat map, waitlist, legal docs |
| `calculator.html` | Full guided journey calculator — 7 steps, results, scenario cards |
| `sample-report.html` | Sample PDF report preview — blurred sections showing what the paid report contains |
| `sitemap.xml` | XML sitemap for search engines |
| `robots.txt` | Robots file |

---

## Key features

- **Real-time tax position heat map** — unique visual showing where the user sits on the tax spectrum, shifting from green to red as salary rises, back to green as pension increases
- **Seven-step guided journey** — salary, region, pension, student loan, NI, child benefit, bonus
- **Plain English explanations** — every technical term explained at the point of use
- **Pro tips** — insider knowledge on pension relief, salary sacrifice, bonus sacrifice
- **£100k trap detection** — automatic detection with plain English explanation and visual meter
- **Full calculation chain** — shows exactly where every pound goes on the results page
- **Tax-awareness scoring** — 0-100 score based on identified gaps, with transparent breakdown
- **Scenario cards** — tap to see plain English explanation of each pension scenario
- **NI gap guidance** — updated for April 2026 rule changes (Class 2 abolished, Class 3 rises)

---

## Tech stack

- Pure HTML, CSS, JavaScript — no frameworks, no dependencies
- All calculations run client-side — no salary data sent to any server
- Google Fonts (DM Sans, DM Serif Display)
- Tabler Icons webfont
- Formspree for form submissions (endpoint: https://formspree.io/f/xvzyplbz)

---

## Deployment

Hosted on Hostinger. Files deploy directly from this repository via GitHub integration.

| Environment | URL |
|-------------|-----|
| Production | https://taxlens.io |
| Calculator | https://taxlens.io/calculator.html |
| Sample report | https://taxlens.io/sample-report.html |

### Deploy process
1. Push to `main` branch
2. Hostinger auto-deploys from GitHub
3. Changes live within ~60 seconds

---

## Calculations covered

- Income tax — England, Wales, NI (3 bands) and Scotland (5 bands) — 2025/26
- Personal allowance taper — £100,000 to £125,140
- Employee NI — 8% main rate, 2% upper rate — State Pension age exemption
- Employer NI — 15% above £5,000 (shown for context, not deducted)
- Student loan — Plans 1, 2, 4, 5 and Postgraduate
- Pension — salary sacrifice and relief at source
- Child benefit high income charge — £60,000 to £80,000 taper
- Bonus — cash vs pension sacrifice comparison
- Adjusted net income — used for trap detection and child benefit charge

---

## Regulatory positioning

TaxLens is an educational simulation platform. All outputs are illustrative estimates. TaxLens is **not** FCA-authorised and does **not** provide financial, investment, tax or regulated advice.

Every output is labelled as illustrative. No "guaranteed", "you should", "recommended" or "apply" language is used anywhere in the product.

---

## Operated by

Jaydeep Karkare trading as TaxLens  
hello@taxlens.io  
privacy@taxlens.io  
taxlens.io
