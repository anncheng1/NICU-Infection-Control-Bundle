# NICU Infection Prevention Bundle

An interactive, single-file web app for neonatal unit infection prevention education, compliance auditing, and root cause analysis (RCA).

Covers the six core bundles: **CLABSI**, **VAP**, **NEC**, **Hand Hygiene**, **Skin Care**, and **Milk Hygiene**.

## Features

- **Learn** — six evidence-based learning modules (bundle elements, rationale, cited sources) each paired with a scored knowledge check (80% to pass).
- **Audit Tools** — Yes / No / N/A compliance checklists for each bundle. Every submission is timestamped, scored, charted as a trend line, and exportable to CSV.
- **RCA Tool** — a structured root cause analysis workflow for any CLABSI, VAP, or NEC case: event timeline, 5 Whys, fishbone-style contributing-factor checklist (People / Process / Equipment / Environment / Patient), root cause statement, corrective action plan with owners and due dates, follow-up tracking, and a printable report.
- **Dashboard** — rolls up latest compliance %, quiz completion, and open RCA actions across the unit at a glance.

## Running it

No build step, no server, no dependencies. Two options:

1. **Locally** — download `index.html` and open it in any modern browser (Chrome, Edge, Safari, Firefox).
2. **Hosted** — if GitHub Pages is enabled for this repo (Settings → Pages → Source: GitHub Actions), the app is published automatically on every push to `main` at:
   `https://<your-username>.github.io/nicu-infection-prevention-bundle/`

## Data & privacy

All data you enter (quiz scores, audit results, RCA records) is stored **only in your browser's local storage** — nothing is sent to a server. This means:

- Data is specific to one browser on one device unless you export/import it.
- Use **Resources & Data → Export all data (.json)** regularly to back up records, and **Import** to restore them on another computer.
- Do not enter patient names or other identifying information in any field — use case/reference numbers only.

## Content basis

Module content and checklist items summarize published guidance, including:

- CDC/NHSN — Recommendations for Prevention and Control of Infections in NICU Patients: CLABSI (2024)
- EFCNI/ESCNH — European Standards of Care for Newborn Health: Prevention of Ventilator Associated Pneumonia
- NEC-zero scoping review and standardized feeding protocol literature
- WHO "My 5 Moments for Hand Hygiene"
- AWHONN/NANN Neonatal Skin Care Evidence-Based Clinical Practice Guideline
- CDC Breastfeeding: Breast Milk Storage and Preparation; HMBANA standards

Full citations are listed in-app under **Resources & Data**. This app is an educational summary — always defer to your institution's approved policies and clinical judgment. It has not been reviewed or endorsed by any of the cited organizations.

## License

All rights reserved — internal use only. See [LICENSE](LICENSE).
