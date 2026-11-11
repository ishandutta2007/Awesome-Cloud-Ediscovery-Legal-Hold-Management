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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Druva eDiscovery and Legal Hold](https://www.druva.com/)** | Cloud-native eDiscovery and legal hold within Druva's data protection platform. Enables legal teams to identify, preserve, and export custodian data across endpoints, SaaS apps, and cloud workloads. Integrates with the broader Druva Cyber Resilience suite . | Quote-only (enterprise contract; typically bundled with Druva data protection licensing) | No free tier; trial available via sales |
| **[Logikcull](https://www.logikcull.com/)** | Self-service cloud eDiscovery platform for small and mid-sized legal teams. Supports upload, processing, search, tagging, and production with a focus on simplicity and speed. Positioned as an accessible alternative to enterprise platforms . | Quote-only (custom pricing; historically positioned as cost-effective for SMB legal teams) | Free trial available; no permanent free tier |
| **[Everlaw](https://www.everlaw.com/)** | Cloud-based eDiscovery and litigation platform with advanced analytics, predictive coding, and collaborative review. Used by law firms, corporations, and government agencies for complex matters. | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Relativity](https://www.relativity.com/)** | Industry-standard eDiscovery platform (RelativityOne cloud) with comprehensive processing, review, analytics, and production capabilities. Extensive REST APIs for legal hold management and case administration . | Quote-only (custom enterprise pricing; RelativityOne subscription model) | No free tier; trial via sales |
| **[DISCO](https://www.csdisco.com/)** | AI-powered legal technology platform with eDiscovery, legal hold, and case management. Features one-click preserve-in-place across M365, Google Vault, Slack, and other sources with automated custodian workflows . | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Exterro](https://www.exterro.com/)** | Enterprise legal governance, risk, and compliance platform with eDiscovery, legal hold, and forensic collection. Features automated reminder and escalation rules for custodian acknowledgments . | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Onna](https://www.onna.com/)** | Knowledge integration and eDiscovery platform with legal hold and preservation API. Supports JSON Logic query-based custodian targeting and lifecycle management for preservation workspaces . | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Microsoft Purview eDiscovery](https://learn.microsoft.com/en-us/purview/)** | Native eDiscovery and legal hold within Microsoft 365. Standard cases support up to 1,000 mailboxes on hold; Premium adds advanced features. Integrates with Exchange, SharePoint, OneDrive, and Teams for in-place preservation . | Included with Microsoft 365 E3/E5 licensing; Premium add-on available | Included with qualifying Microsoft 365 subscriptions; no separate free tier |
| **[OpenText Axcelerate](https://www.opentext.com/)** | Enterprise eDiscovery and investigations platform with AI-assisted review, analytics, and production. Part of OpenText's broader information management suite. | Quote-only (enterprise contract) | No free tier; trial via sales |
| **[Casepoint](https://www.casepoint.com/)** | Unified eDiscovery platform with legal hold module featuring automated communications, notifications, and custodian management. Includes collection, processing, and review capabilities . | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Nextpoint](https://www.nextpoint.com/)** | Cloud-based eDiscovery and trial preparation platform with legal hold, processing, review, and production. Positioned for litigation teams seeking an integrated workflow. | Quote-only (custom pricing; per-GB or per-user models available) | Free trial available; no permanent free tier |

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
