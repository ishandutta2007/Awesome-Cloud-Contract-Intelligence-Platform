# Awesome-Cloud-Contract-Intelligence-Platform

# Top Cloud Contract Intelligence Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI-Powered Contract Analytics, Obligation Extraction & Risk Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Contract Intelligence Platforms**. These tools go beyond basic contract storage—using NLP, machine learning, and LLMs to automatically extract key terms, identify obligations, flag risks, and surface portfolio-wide insights from executed agreements, helping legal, procurement, and finance teams turn static documents into actionable business intelligence.

**Examples** include Icertis, Evisort (Workday), Ironclad, SirionLabs, Agiloft, ContractPodAi, Conga CLM, CobbleStone Software, Lexion (Docusign), and Summation (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted contract intelligence, AI-assisted extraction, and open-source CLM platforms with analytics capabilities—ideal for legal ops teams, developers, and organizations seeking transparent, vendor-neutral contract data ownership without six-figure enterprise contracts.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis](https://www.icertis.com/)** | AI-native contract intelligence platform powered by Vera, a conversational control plane that understands business context. Covers Engage (drafting/redlining), Operate (obligation fulfillment), and Analyze (portfolio risk exposure). Used by more than one-third of the Fortune 100 . | Quote-only (enterprise contract; implementation costs substantial) | No free tier or self-serve trial; demo via sales |
| **[Evisort (Workday)](https://www.evisort.com/)** | AI-powered CLM and contract intelligence platform acquired by Workday in 2024, now offered as Workday Contract Lifecycle Management. REST API supports document upload, field/metadata extraction, search, workflow automation, and webhooks. Self-serve signup with trial available . | $30,000–$60,000/year (small teams, 500–2,000 contracts); $60,000–$120,000/year (mid-market)  | Free trial available; self-serve signup with try-now option  |
| **[Ironclad](https://ironcladapp.com/)** | AI contract lifecycle platform with Ironclad Agent, Contract Review Agent for playbook redlines, and MCP server for Claude/ChatGPT. Covers creation, review, negotiation, signature, storage, and renewal. Gartner MQ Leader 2025 and Forrester Wave Leader Q1 2025 . | Quote-only (custom pricing; no public rates)  | No free trial, self-serve plan, or published pricing; demo via sales  |
| **[SirionLabs](https://www.sirion.ai/)** | AI-native CLM for large enterprises managing thousands of contracts. "Agentic AI" actively manages workflows—extraction, compliance flagging, redlines. Manages 7M+ contracts worth ~$800B. Named-user licensing based on role type (full-featured vs. light) . | Quote-only (custom; minimum user commitments start high; implementation 3–6 months)  | No free tier; no self-serve trial; demo via sales  |
| **[Agiloft](https://www.agiloft.com/)** | Data-first CLM with Astra, a contracts AI platform launched April 2026. Astra offers agentic AI for risk identification, obligation extraction, and compliance. Notable for offering a **free tier with usage-based credits**—unusual in enterprise CLM . | Quote-only for full CLM; Astra free tier available  | **Astra Free Tier**: usage-based credits, same data protection as paying customers, no procurement process required; early access waitlist  |
| **[ContractPodAi](https://contractpodai.com/)** | Enterprise AI-powered platform for legal teams (Leah). Covers contract management, review/analysis, generation, legal project management, and risk assessment. Integrates with Salesforce, SAP, Workday, Microsoft 365, and more . | Paid (quote-only; no public pricing)  | No free tier or trial listed; demo via sales  |
| **[Conga CLM](https://www.conga.com/)** | AI-powered CLM built on Conga Revenue Lifecycle Platform. Automates creation, negotiation, and execution with centralized repository, intelligent workflows, and actionable dashboards for buy-side and sell-side contracts . | $35/user/month (starting price; tailored to business needs)  | Free trial available via Salesforce AppExchange; no permanent free tier  |
| **[CobbleStone Software](https://www.cobblestonesoftware.com/)** | Contract lifecycle management with centralized repository, automated workflows, AI insights (VISDOM), obligation tracking, and compliance management. Offers text indexing/search, version control, and IntelliSign e-signatures . | $59/month (starting price per Software Advice)  | Free trial available; free version not listed  |
| **[Lexion (Docusign)](https://www.lexion.ai/)** | AI-powered CLM acquired by Docusign in May 2024 for ~$165M, folded into Docusign Intelligent Agreement Management and Navigator. AI extraction of clauses, key terms, renewal dates; no-code intake and approval workflows. Enterprise integration API is sales-led, no public REST reference . | Paid (enterprise; no public pricing)  | No free trial; sales-led onboarding  |
| **[Summation](https://www.lexisnexis.com/)** | Legacy eDiscovery and litigation review platform (LexisNexis). Limited contract intelligence positioning in current market; primarily known for document review in legal proceedings rather than proactive contract analytics. | Quote-only (enterprise legal software) | No free tier; trial via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Aakd](https://github.com/aaked-app/aakd)** | [![Stars](https://img.shields.io/github/stars/aaked-app/aakd?style=social&color=white)](https://github.com/aaked-app/aakd/stargazers) | Open-source, self-hostable CLM focused on post-signature contract intelligence. Upload executed PDFs/DOCX, review source-linked extracted obligations with page-level citations, assign owners and deadlines, track renewals, and capture completion evidence. AI is optional and human-reviewable; includes REST API and MCP endpoint for agent-assisted workflows. |
| **[draftLegal](https://github.com/AniketTati/draft-legal)** | [![Stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers) | Self-hosted AI-native CLM positioned as an Ironclad + Harvey alternative. Agent chat with ~30 tools over contracts (search, cite, compare, draft, redline, route approvals). Portfolio intelligence via hybrid search (pgvector + Elasticsearch + RRF). Bring-your-own LLM key. Deploys via `docker compose up`. |
| **[OpenContracts](https://github.com/JSv4/OpenContracts)** | [![Stars](https://img.shields.io/github/stars/JSv4/OpenContracts?style=social&color=white)](https://github.com/JSv4/OpenContracts/stargazers) | Document analytics platform for contract review and portfolio analysis. Focused on reading and extracting insights from large contract archives—useful as a foundation for custom contract intelligence pipelines. |
| **[OpenCLM](https://github.com/qik-ai/openclm)** | [![Stars](https://img.shields.io/github/stars/qik-ai/openclm?style=social&color=white)](https://github.com/qik-ai/openclm/stargazers) | Free, AGPL v3 CLM platform with 12 pre-built roles, clause library, approvals, e-signature, deadline reminders, obligation monitoring, and analytics. Self-hosted with Keycloak SSO and full audit trail. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[DocuSeal](https://github.com/docusealco/docuseal)** | [![Stars](https://img.shields.io/github/stars/docusealco/docuseal?style=social&color=white)](https://github.com/docusealco/docuseal/stargazers) | Open-source e-signature platform that can complement contract intelligence workflows for execution and storage. |
| **[Documenso](https://github.com/documenso/documenso)** | [![Stars](https://img.shields.io/github/stars/documenso/documenso?style=social&color=white)](https://github.com/documenso/documenso/stargazers) | Open-source document signing platform; pairs with contract repositories for end-to-end agreement lifecycle. |

**Frameworks for building custom systems**: Combine **Aakd** for source-linked obligation extraction and post-signature tracking, **draftLegal** for LLM-assisted contract reasoning and portfolio search, and **OpenContracts** for large-archive analytics—all deployable via Docker Compose with PostgreSQL and optional local LLM inference.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract intelligence platforms process sensitive commercial and legal data; enforce strong access controls, audit logging, and compliance with applicable data protection regulations.
- Self-hosted open-source solutions require validation of AI-assisted extraction accuracy before relying on automated fields; human review remains essential for legal and financial decisions.

---

**Made for legal operations teams, contract managers, procurement professionals, and developers building contract data intelligence.**  
Let's make contract intelligence more open, accurate, and auditable.
