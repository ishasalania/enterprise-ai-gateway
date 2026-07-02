# RheinEnergie — Agentic-AI Platform Content Hub

GitHub Pages site consolidating all Microsoft capabilities, documentation, architecture references, and labs mapped to RheinEnergie's 9 technical requirements for an agentic-AI platform.

## Live Site

🔗 **https://ishasalania.github.io/rheinenergie-agentic-platform/**

## What's covered

| # | Requirement | Microsoft Capability |
|---|---|---|
| 1 | AI Lifecycle Plattform | Microsoft Foundry |
| 2 | AI Gateway & Integration | Azure API Management AI Gateway |
| 3 | Observability | OpenTelemetry + Datadog |
| 4 | FinOps | emit-token-metric + FinOps toolkit |
| 5 | Governance | Entra ID, Purview, Content Safety, Azure Policy |
| 6 | Agent Tracking | Foundry tracing + A2A/MCP management |
| 7 | Data Privacy / DSGVO | Metadata-only tracing + EU Data Boundary |
| 8 | Multi-Provider | Model catalog + Model router + Foundry Local + Unified API |
| 9 | Cost Efficiency | Model router + semantic caching + token limits |

## Structure

```
docs/
└── index.html    # Single-page GitHub Pages site (all content)
```

## Deploying

GitHub Pages is configured to serve from the `docs/` folder on the `main` branch.

Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → Folder: `/docs`
