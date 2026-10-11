# Changelog

All notable changes to this project are documented in this file.

## [2026.10] - 2026-10-12

- skynet-automation-pack is a public, MIT-licensed free pack of 20 n8n automations, each with an importable workflow JSON, a 5-page setup PDF, a carousel and rendered PNG slides.
- Reviewed October 2026: tree re-checked; README links (skynetjoe.com, waseemnasir.com, Fiverr agency, repo issues) returned HTTP 200. No workflow, PDF or carousel change.
- Known gaps: workflow JSONs are a May 2026 snapshot and were not re-validated against a current n8n version; each needs credentials wired after import; no CI workflow and no package manifest.
- Release housekeeping only: Status line, changelog and the 'Need it wired for you?' links updated to the Fiverr, Upwork and Calendly URLs.

## [2026.09] - 2026-09-16

- Maintenance review of skynet-automation-pack — a free lead-magnet pack of 20 production-grade n8n automations for agencies, solo founders, SaaS and e-commerce teams, published by SkynetLabs.
- Status: each of the 20 automations ships as an importable n8n workflow JSON in `n8n/`, a 5-page setup PDF in `pdfs/`, a 10-slide 1080×1350 carousel in `carousels-html/`, and 200 pre-rendered slide PNGs in `carousels-png/` (20 slugs × 10 slides). MIT licensed. Topics run from LinkedIn DM ICP scoring and inbound form qualification through AEO citation monitoring, GSC anomaly alerts, receipt OCR and clinic missed-call recovery.
- Reviewed September 2026: docs refreshed, CHANGELOG started, released as v2026.09. No workflow JSON, PDF, carousel or PNG changes.
- Known gaps: the workflow JSONs are a 2026-05 snapshot and have not been re-validated against a current n8n version in this release; each still needs credentials wired locally after import, as the per-automation PDFs describe.
- Repo hygiene: LICENSE present, but no CHANGELOG before this release and no CI workflow under `.github/`. No package manifest, so there is no machine-readable version to bump.
