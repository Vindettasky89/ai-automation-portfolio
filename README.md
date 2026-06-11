# MARRØW DIVISION — AI Automation Portfolio

> 20+ years music production meets modern AI-agent engineering.
> Every workflow here is built, tested, and verified to work.

## What This Repo Contains

```
.
├── README.md                    ← You're here. Start here.
├── workflows/
│   ├── ai-email-agent/         ← Flagship showcase workflow
│   │   ├── workflow.json        ← Importable n8n workflow
│   │   ├── README.md            ← How it works, how to deploy
│   │   └── demo/                ← Screenshots + Loom walkthrough
│   ├── lead-enrichment-agent/  ← Scrape → Enrich → CRM pipeline
│   │   ├── workflow.json
│   │   └── README.md
│   └── content-pipeline/        ← RSS → AI Write → Auto-Publish
│       ├── workflow.json
│       └── README.md
├── proposals/
│   ├── fintiba-compliance.md    ← Sent to Fintiba (warm lead)
│   ├── peopleperhour-general.md ← For PPH platform applications
│   └── arc-dev-solutions-architect.md ← For Arc.dev application
├── portfolio/
│   └── index.html               ← Portfolio website (open in browser)
├── verification/
│   ├── test-results.md          ← Proof workflows execute correctly
│   ├── screenshots/             ← Workflow execution screenshots
│   └── loom-links.md            ← Video walkthroughs
└── docs/
    ├── about.md                 ← Harvey's story + credentials
    ├── rates.md                 ← Pricing tiers + packages
    └── contact.md               ← How to hire Harvey
```

## Quick Start

```bash
# Clone
git clone https://github.com/marrowdivision/ai-automation-portfolio.git
cd ai-automation-portfolio

# View portfolio
open portfolio/index.html

# Import workflow into n8n
# 1. Open n8n → Workflows → Import from File
# 2. Select workflows/ai-email-agent/workflow.json
# 3. Configure credentials (Gmail, OpenAI, Slack)
# 4. Activate
```

## Who Is This For?

- **Small business owners** who need automation but can't afford enterprise consultants
- **Founders** who want AI agents handling email, leads, or content
- **Marketing agencies** who need white-label automation workflows
- **Anyone** who's tired of doing the same manual task every day

## Tech Stack

| Layer | Tool | Why |
|-------|------|-----|
| Automation | n8n (self-hosted) | Open source, no vendor lock-in |
| AI/LLM | OpenAI GPT-4o | Best reasoning for agent tasks |
| Email | Gmail API / IMAP | Universal — everyone has email |
| Data | Airtable / Google Sheets | Free tier, easy to demo |
| Hosting | Railway / Render | $5-7/month, always-on |
| Portfolio | Static HTML | Free, fast, no dependencies |

## Pricing

| Package | What | Price |
|---------|------|-------|
| Basic | Single workflow, up to 10 nodes, 3-day delivery | $125 |
| Standard | Multi-step workflow, integrations, 5-day delivery | $250 |
| Premium | Complex workflow, API integrations, error handling, docs + Loom | $400 |
| Monthly Retainer | Ongoing automation support + 2 new workflows/month | $500/mo |

## Contact

- Email: [your email]
- PeoplePerHour: [your PPH profile]
- GitHub: github.com/marrowdivision
- Portfolio: [your portfolio URL]

---

*Built by Harvey — MARRØW DIVISION. Music producer turned automation engineer.*
*20+ years of building systems that work. Now building them for you.*
