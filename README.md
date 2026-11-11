# Awesome-Cloud-Ediscovery-Legal-Hold-Management

## Top Cloud eDiscovery & Legal Hold Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Electronic Discovery, Legal Hold Automation & Defensible Preservation Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud eDiscovery & Legal Hold Management**. These tools help legal and IT teams identify, preserve, collect, and review electronically stored information (ESI) for litigation, investigations, and regulatory compliance—covering custodian holds, data preservation, early case assessment, and document review workflows.

**Examples** include Druva eDiscovery and Legal Hold, Logikcull, Everlaw, Relativity, DISCO, Exterro, Onna, Microsoft Purview eDiscovery, OpenText Axcelerate, Casepoint, and Nextpoint (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted email archiving, legal hold management, and open-source eDiscovery review—ideal for legal ops teams, IT administrators, and developers seeking transparent, vendor-neutral preservation workflows without per-GB or per-custodian cloud billing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global eDiscovery and legal hold management market is valued at approximately **$15B to $21B** (projected to exceed **$31B to $46B by the early 2030s** at an 8%–11% CAGR), driven by exponential growth in enterprise data volumes, cloud collaboration tools, and GenAI-powered review. The sector is **moderately fragmented and actively consolidating**—anchored by dominant enterprise platforms (Microsoft, Relativity, OpenText) alongside specialized cloud-native legal tech vendors (Reveal, Everlaw, DISCO, Exterro), where private equity rollups and AI capabilities are accelerating consolidation toward unified legal GRC suites.

## SaaS/Hosted Platforms

| Product | Scale (Valuation / Market Cap / Revenue) | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
|---------|------------------------------------------|-------------|-------------------------|--------------------------|
| **[Microsoft Purview eDiscovery](https://learn.microsoft.com/en-us/purview/)** | ~$4.0T Market Cap (Public: MSFT) | Native eDiscovery and legal hold within Microsoft 365. Standard cases support up to 1,000 mailboxes on hold; Premium adds advanced analytics and custodian workflows. | Starts at **$36.00/user/month** (Microsoft 365 E3 for Standard eDiscovery); eDiscovery Premium add-on starts at **$12.00/user/month** over E3, or included in Microsoft 365 E5 at **$60.00/user/month** | **30-day free trial** of Microsoft 365 E3/E5 with up to 25 user licenses; no permanent free tier |
| **[OpenText Axcelerate](https://www.opentext.com/)** | ~$6.1B Market Cap (Public: OTEX) | Enterprise eDiscovery and investigations platform with AI-assisted review, analytics, and production. Part of OpenText's broader information management suite. | Custom enterprise subscription; starting tiers generally structure around **$10 to $20/GB/month** for active hosting, or G-Cloud public framework modules starting from **£230/user/year** | No permanent free tier; **custom proof-of-concept (PoC) / sandbox trial** available on request via sales team (typically 14–30 days under NDA) |
| **[Relativity](https://www.relativity.com/)** | ~$3.6B Valuation (Private equity backed) | Industry-standard eDiscovery platform (RelativityOne cloud) with comprehensive processing, review, analytics, and production capabilities. Extensive REST APIs for legal hold management. | Pay-As-You-Go starting tier begins at **$11.00 to $15.00/GB/month** for active data hosting; long-term Flex Commit volume tiers scale down to **$4.00 to $8.00/GB/month** | No permanent free tier; **custom test sandbox / demo trial** available upon request via sales and authorized hosting partners |
| **[Druva eDiscovery and Legal Hold](https://www.druva.com/)** | ~$2.0B Valuation (Private equity backed) | Cloud-native eDiscovery and legal hold within Druva's cyber resilience platform. Enables legal teams to identify, preserve, and export custodian data across endpoints, SaaS apps, and cloud workloads. | Starts at **$8.00/user/month** for entry SaaS/endpoint backup & discovery tiers; enterprise legal hold & compliance editions scale up to **$10–$16/user/month** | **30-day free trial** with up to 1 TB of storage and endpoint protection for evaluation; no permanent free tier |
| **[Everlaw](https://www.everlaw.com/)** | ~$2.0B Valuation (Private venture backed) | Cloud-based eDiscovery and litigation platform with advanced analytics, predictive coding, and collaborative review. Used by law firms, corporations, and government agencies for complex matters. | Active data hosting starting at **$18.00 to $35.00/GB/month** with **unlimited user reviewer seats** included; processing and native ingestion bundled | No permanent free tier; **guided evaluation trial / matter pilot** available on request via sales team (typically 14 to 30 days) |
| **[Exterro](https://www.exterro.com/)** | ~$1.0B+ Valuation (Unicorn / Private PE backed) | Enterprise legal governance, risk, and compliance platform with eDiscovery, legal hold, and forensic collection (FTK). Features automated reminder and escalation rules for custodian acknowledgments. | Modular enterprise licensing; starter legal hold & eDiscovery data packages start from baseline commitments (typically starting at **$10,000/year** or standalone FTK forensic seats starting from **$2,500/seat/year**) | No permanent free tier; **guided pilot / product trial** offered upon qualification via sales (typically 14–30 days) |
| **[Logikcull](https://www.logikcull.com/)** | ~$1.0B+ (Part of Reveal via $1B+ acquisition) | Self-service cloud eDiscovery platform for small and mid-sized legal teams. Supports upload, processing, search, tagging, and production with a focus on simplicity and speed. | Pay-As-You-Go starting at **$40.00/GB/month** with a 10 GB monthly minimum ($400/month) including unlimited users; annual subscription tiers offer lower per-GB commitments | **Free test tier up to 10 GB** of user data with sample matter exploration (no strict day cutoff, requires payment setup to export/scale); no permanent full free tier |
| **[Onna](https://www.onna.com/)** | ~$100M+ Scale (Acquired by Reveal in 2024; $50M+ total raised) | Knowledge integration and eDiscovery platform with legal hold and preservation API. Supports JSON Logic query-based custodian targeting and lifecycle management across collaboration tools. | Data volume-based starting at a **1 TB baseline tier** (typically priced from **$15,000 to $25,000/year**) with **unlimited users and connectors** included | No permanent free tier; **14-day to 30-day evaluation sandbox trial** available on request via enterprise sales |
| **[DISCO](https://www.csdisco.com/)** | ~$350M Market Cap (Public: LAW) | AI-powered legal technology platform with eDiscovery, legal hold, and case management. Features one-click preserve-in-place across M365, Google Vault, Slack, and other sources with automated custodian workflows. | All-inclusive per-GB pricing starting at approximately **$20.00 to $40.00/GB/month** for processed data, including Cecilia AI and unlimited user seats | No standard public free tier (custom 14-day sales demo/pilot available); provides a **permanent Free Pro Bono Tier up to 50 GB** for qualifying pro bono litigation |
| **[Casepoint](https://www.casepoint.com/)** | ~$100M+ Annual Revenue (Privately held) | Unified eDiscovery platform with legal hold module featuring automated communications, notifications, and custodian management. Includes collection, processing, and review capabilities. | All-inclusive hosting model starting at approximately **$12.00 to $25.00/GB/month** with **unlimited user seats and reviewers**, or modular legal hold packages from **$5,000/year** | No permanent free tier; **custom 14-day to 30-day pilot / sandbox trial** provided upon request for qualified corporate or law firm matters |
| **[Nextpoint](https://www.nextpoint.com/)** | ~$20M–$40M Scale (Privately held mid-market) | Cloud-based eDiscovery and trial preparation platform with legal hold, processing, review, and production. Positioned for litigation teams seeking an integrated workflow. | User-seat flat pricing starting at **$299.00/user/month** with **unlimited data storage and processing** (no per-GB hosting charges) | No self-serve free trial or permanent free tier; **live guided demo and pilot environment** available on request via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenArchiver](https://github.com/nimdassdev/OpenArchiver)** | [![Stars](https://img.shields.io/github/stars/nimdassdev/OpenArchiver?style=social&color=white)](https://github.com/nimdassdev/OpenArchiver/stargazers) | Self-hosted email archiving and eDiscovery platform with universal ingestion (Google Workspace, Microsoft 365, IMAP, PST, mbox), full-text search, deduplication, and S3-compatible storage. Legal hold capability listed as TBD; immutable audit trail also TBD. Docker Compose deployment with SvelteKit/Node.js/PostgreSQL/Meilisearch stack . |
| **[FreeEed](https://github.com/shmsoft/freeeed)** | [![Stars](https://img.shields.io/github/stars/shmsoft/freeeed?style=social&color=white)](https://github.com/shmsoft/freeeed/stargazers) | Open-source eDiscovery platform with OCR, metadata extraction, AI-assisted document analysis, and support for 1,400+ file types including PST. Runs on Windows, macOS, Linux, and AWS. Free activation key on registration . |
| **[IPED](https://github.com/sepinf-inc/IPED)** | [![Stars](https://img.shields.io/github/stars/sepinf-inc/IPED?style=social&color=white)](https://github.com/sepinf-inc/IPED/stargazers) | Digital forensics and eDiscovery tool developed by the Brazilian Federal Police. Maintained and updated since 2014; free of charge. Recommended as an open-source alternative for investigations . |
| **[Mayan EDMS](https://github.com/mayan-edms/Mayan-EDMS)** | [![Stars](https://img.shields.io/github/stars/mayan-edms/Mayan-EDMS?style=social&color=white)](https://github.com/mayan-edms/Mayan-EDMS/stargazers) | Open-source document management system with OCR, full-text search, tagging, and workflow. Suitable for basic litigation document organization though not purpose-built for formal eDiscovery review . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** | [![Stars](https://img.shields.io/github/stars/paperless-ngx/paperless-ngx?style=social&color=white)](https://github.com/paperless-ngx/paperless-ngx/stargazers) | Document management with OCR and full-text search. Useful for document organization and retrieval; lacks formal eDiscovery review workflows and chain-of-custody features . |
| **[Lenso Legal Hold Plugin](https://github.com/LioRael/lenso-legal-hold-plugin)** | [![Stars](https://img.shields.io/github/stars/LioRael/lenso-legal-hold-plugin?style=social&color=white)](https://github.com/LioRael/lenso-legal-hold-plugin/stargazers) | PostgreSQL-backed legal hold backend and retention guard. Provides create/get/list/release holds, scoped preservation rules, idempotency receipts, and guard-decision evidence. Does not notify custodians or provide a web UI—backend only . |
| **[Legal Hold Management Tool (Python)](https://github.com/topics/legal-hold)** | — | Community project on GitHub's legal-hold topic: creates, issues, tracks, and manages legal holds with custodian tracking, automated notices, acknowledgment workflows, and audit log for defensibility . |

**Frameworks for building custom systems**: Combine **OpenArchiver** for email ingestion and archival, **FreeEed** for document processing and OCR, **IPED** for forensic-grade ESI handling, and **Mayan EDMS** or **paperless-ngx** for document organization—deployable via Docker Compose with PostgreSQL and Meilisearch for search.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- eDiscovery and legal hold tools handle sensitive litigation data; enforce strong access controls, immutable audit trails, and compliance with applicable data protection regulations.
- Open-source alternatives to enterprise eDiscovery platforms (Relativity, Everlaw, DISCO) are limited in scope; most lack purpose-built review workflows, privilege tagging, and chain-of-custody features required for formal litigation. Consult legal counsel before relying on open-source tools for defensibility.

---

**Made for legal operations teams, IT compliance administrators, eDiscovery professionals, and developers building preservation infrastructure.**  
Let's make eDiscovery and legal hold management more open, transparent, and defensible.
