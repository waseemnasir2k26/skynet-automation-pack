# Skynet Automation Pack — 20 free n8n workflows

20 production-grade n8n automations for agencies, solo founders, SaaS, and e-commerce teams. Each ships with:

- **5-page setup PDF** in `pdfs/` — what it does, why, stack costs, prereqs, step-by-step wiring
- **Importable n8n JSON** in `n8n/` — paste into n8n → Workflows → Import from Clipboard
- **Social carousel HTML** in `carousels-html/` — 10-slide 1080×1350 lead-magnet templates

Built by [Waseem Nasir](https://waseemnasir.com) / [SkynetLabs](https://skynetjoe.com).

---

## The 20 automations

| # | Automation | PDF | n8n JSON |
|---|---|---|---|
| 01 | LinkedIn DM ICP Scorer | [pdf](pdfs/01-linkedin-dm-icp-scorer.pdf) | [json](n8n/01-linkedin-dm-icp-scorer.json) |
| 02 | Inbound Form AI Qualifier | [pdf](pdfs/02-inbound-form-ai-qualifier.pdf) | [json](n8n/02-inbound-form-ai-qualifier.json) |
| 03 | Cold Email Warm-up + Reply Detector | [pdf](pdfs/03-cold-email-warmup-reply-detector.pdf) | [json](n8n/03-cold-email-warmup-reply-detector.json) |
| 04 | LinkedIn Comment → DM Auto-Trigger | [pdf](pdfs/04-linkedin-comment-dm-trigger.pdf) | [json](n8n/04-linkedin-comment-dm-trigger.json) |
| 05 | Voice-Note Follow-up (ElevenLabs) | [pdf](pdfs/05-voice-note-followup-elevenlabs.pdf) | [json](n8n/05-voice-note-followup-elevenlabs.json) |
| 06 | AEO Citation Monitor (4 LLMs) | [pdf](pdfs/06-aeo-citation-monitor-4llm.pdf) | [json](n8n/06-aeo-citation-monitor-4llm.json) |
| 07 | Competitor Blog → My-Angle Draft | [pdf](pdfs/07-competitor-blog-my-angle-draft.pdf) | [json](n8n/07-competitor-blog-my-angle-draft.json) |
| 08 | YouTube Transcript → 9 Assets | [pdf](pdfs/08-youtube-transcript-9-assets.pdf) | [json](n8n/08-youtube-transcript-9-assets.json) |
| 09 | GSC Anomaly Bot | [pdf](pdfs/09-gsc-anomaly-bot.pdf) | [json](n8n/09-gsc-anomaly-bot.json) |
| 10 | FAQ → Schema → WP REST Inject | [pdf](pdfs/10-faq-schema-wp-rest-inject.pdf) | [json](n8n/10-faq-schema-wp-rest-inject.json) |
| 11 | Receipt OCR → Sheets → Tax | [pdf](pdfs/11-receipt-ocr-sheets-tax.pdf) | [json](n8n/11-receipt-ocr-sheets-tax.json) |
| 12 | Meeting → Action Items → ClickUp | [pdf](pdfs/12-meeting-action-items-clickup.pdf) | [json](n8n/12-meeting-action-items-clickup.json) |
| 13 | Calendly Dossier (LI + X + Company) | [pdf](pdfs/13-calendly-dossier-li-twitter-company.pdf) | [json](n8n/13-calendly-dossier-li-twitter-company.json) |
| 14 | Loom Auto-Doc → Slack | [pdf](pdfs/14-loom-auto-doc-slack.pdf) | [json](n8n/14-loom-auto-doc-slack.json) |
| 15 | Async Standup Bot | [pdf](pdfs/15-async-standup-bot.pdf) | [json](n8n/15-async-standup-bot.json) |
| 16 | Abandoned Cart → WA Voice Note | [pdf](pdfs/16-abandoned-cart-wa-voice-note.pdf) | [json](n8n/16-abandoned-cart-wa-voice-note.json) |
| 17 | Negative Review → AI Reply Draft | [pdf](pdfs/17-negative-review-ai-reply-draft.pdf) | [json](n8n/17-negative-review-ai-reply-draft.json) |
| 18 | VIP Cohort Detector → WA Congrats | [pdf](pdfs/18-vip-cohort-detector-wa-congrats.pdf) | [json](n8n/18-vip-cohort-detector-wa-congrats.json) |
| 19 | Real Estate Listing → 5 Platforms | [pdf](pdfs/19-real-estate-listing-5-platforms.pdf) | [json](n8n/19-real-estate-listing-5-platforms.json) |
| 20 | Clinic Missed-Call → WA → Recovery | [pdf](pdfs/20-clinic-missed-call-wa-recovery.pdf) | [json](n8n/20-clinic-missed-call-wa-recovery.json) |

---

## How to use

1. Open the PDF for the automation you want.
2. Skim the stack table + prereqs.
3. Copy the n8n JSON from this repo (or the GitHub button on page 4 of the PDF).
4. In your n8n instance: **Workflows → Import from Clipboard** → paste.
5. Bind credentials marked `REPLACE_ME` in each node.
6. Execute once manually to verify, then activate.

Most workflows run in 45-90 minutes from cold start. Stack costs land between $20-150/mo.

---

## Need it wired for you?

Three paths:

- **Fiverr ($297-997 per flow):** [fiverr.com/agencies/skynetjoellc](https://www.fiverr.com/agencies/skynetjoellc)
- **Free 20-min audit:** [waseem@skynetjoe.com](mailto:waseem@skynetjoe.com)
- **Monthly retainer ($1.5K-5K/mo) — full stack, multi-workflow agency:** same email

---

## License

MIT. Fork, remix, ship. Attribution appreciated but not required.

---

## Stack philosophy

- **n8n** over Zapier/Make: self-hosted = no per-task tax, full code escape hatch.
- **Claude / GPT-4 / Sonar / Gemini** depending on task. Most flows are LLM-agnostic.
- **Real APIs over scrapers** where available. Unipile for LinkedIn, Twilio for SMS/WA, Shopify/Woo native.
- **REPLACE_ME credential markers** in every JSON — no leaked tokens, ever.

Each workflow has been built to import cleanly and run end-to-end on a fresh n8n. If anything breaks, [open an issue](https://github.com/waseemnasir2k26/skynet-automation-pack/issues).
