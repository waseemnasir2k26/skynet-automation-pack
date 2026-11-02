# skynet-automation-pack

Twenty n8n workflows for agencies, founders, SaaS and e-commerce teams, each with importable JSON, a setup PDF and a 10-slide carousel template. Lead scoring, form qualification, cold-email reply detection, AEO citation monitoring, voice-note follow-up and more.

## What is in it

- `n8n/` - 20 importable workflow files.
- `pdfs/` - one setup PDF per workflow: what it does, stack, prerequisites, wiring steps.
- `carousels-html/` and `carousels-png/` - a 10-slide 1080x1350 carousel per workflow, as HTML and rendered PNG.

| #   | Workflow                              | #   | Workflow                                 |
| --- | ------------------------------------- | --- | ---------------------------------------- |
| 01  | LinkedIn DM ICP scorer                | 11  | Receipt OCR to Sheets and tax            |
| 02  | Inbound form AI qualifier             | 12  | Meeting action items to ClickUp          |
| 03  | Cold email warm-up and reply detector | 13  | Calendly dossier (LinkedIn, X, company)  |
| 04  | LinkedIn comment to DM trigger        | 14  | Loom auto-doc to Slack                   |
| 05  | Voice-note follow-up (ElevenLabs)     | 15  | Async standup bot                        |
| 06  | AEO citation monitor (4 LLMs)         | 16  | Abandoned cart to WhatsApp voice note    |
| 07  | Competitor blog to my-angle draft     | 17  | Negative review AI reply draft           |
| 08  | YouTube transcript to 9 assets        | 18  | VIP cohort detector to WhatsApp congrats |
| 09  | GSC anomaly bot                       | 19  | Real estate listing to 5 platforms       |
| 10  | FAQ to schema to WP REST inject       | 20  | Clinic missed call to WhatsApp recovery  |

Files are named `NN-<slug>.json` and `NN-<slug>.pdf`; browse the folders for the exact names.

## Quickstart

1. Open the PDF for the workflow you want and read the stack table and prerequisites.
2. In n8n: Workflows, Import from File (or paste the JSON with Import from Clipboard).
3. Replace every `REPLACE_ME` credential marker with your own credentials in n8n.
4. Run once manually, check the output, then activate.

## For you if

You run your own n8n and want a starting point per use case rather than a blank canvas.

## Status and limits

- Starting points, not finished products. Expect to adjust prompts, mappings and credentials for your stack.
- Several flows depend on paid third parties (LLM APIs, ElevenLabs, WhatsApp or SMS providers, a LinkedIn data provider). Those costs are yours.
- The WhatsApp and outreach flows send messages. Check platform rules and consent requirements first; these flows have no built-in compliance layer (see `n8n-whatsapp-compliant-agent` for one).
- Not re-tested against every n8n release. Try them on a copy first.
- The JSON files carry `REPLACE_ME` markers and no live credentials.

## License

MIT, see [LICENSE](LICENSE).

---

Built by SkynetLabs. Contact: waseem@skynetjoe.com

Need this wired into your business? SkynetLabs builds voice agents, n8n back offices and sites that convert → https://skynetjoe.com
