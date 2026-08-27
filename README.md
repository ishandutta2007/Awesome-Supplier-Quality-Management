# Awesome-Supplier-Quality-Management

## Top Supplier Quality Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Supplier Qualification, Audits, CAPA, Nonconformances, Incoming Quality, Risk & Compliance Across the Supply Base*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Supplier Quality Management (SQM)**. These systems help organizations qualify suppliers, manage audits, track nonconformances and CAPAs, control incoming quality, and maintain compliance across the extended supply chain.

**Examples** include Assent, Intelex, ETQ Reliance, MasterControl, SAP Supplier Quality, QT9, Qualio, Ideagen, MetricStream, and Greenlight Guru (the category leaders).

**Open-source emphasis**: Full enterprise supplier-quality suites are rare in pure open source. Relevant building blocks exist in open QMS projects (**Open QMS**, **QAtrial**, **Carbon**), workflow engines, and related quality/compliance tools. This section is expanded with the most useful open options.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Assent](https://www.assent.com/)**  
  Supply-chain compliance and sustainability platform widely used for supplier data collection, material compliance, and extended producer responsibility — often overlapping with supplier quality and risk programs.

- **[Intelex](https://www.intelex.com/)**  
  Configurable EHSQ platform with strong quality and supplier-related modules for audits, CAPA, performance tracking, and operational governance.

- **[ETQ Reliance](https://www.etq.com/)**  
  Enterprise QMS platform with configurable workflows for supplier quality, audits, nonconformances, CAPA, and risk management.

- **[MasterControl](https://www.mastercontrol.com/)**  
  Established QMS platform especially strong in regulated industries (life sciences, medical devices), covering document control, training, CAPA, audits, and supplier management.

- **[SAP Supplier Quality](https://www.sap.com/)**  
  Supplier quality capabilities within the SAP ecosystem, integrated with procurement, quality management, and broader ERP processes.

- **[QT9](https://qt9software.com/)**  
  Quality management software including supplier quality, CAPA, audits, and document control suited to mid-market manufacturers.

- **[Qualio](https://www.qualio.com/)**  
  Cloud QMS focused on life sciences and medical device companies, with modules that support supplier and quality system processes.

- **[Ideagen](https://www.ideagen.com/)**  
  Quality, safety, and compliance solutions (including Q-Pulse and related products) used for audits, document control, and supplier oversight.

- **[MetricStream](https://www.metricstream.com/)**  
  Enterprise GRC and quality platform supporting supplier risk, audits, and compliance workflows at scale.

- **[Greenlight Guru](https://www.greenlight.guru/)**  
  QMS platform purpose-built for medical device companies, covering design controls, risk, CAPA, and related quality processes that often include supplier elements.

## Open-Source GitHub Projects
- **[Open QMS](https://github.com/IridiumSoftware/open-qms)**  
  Open-source, GitHub-native QMS generator that produces traceable quality-system scaffolds (including CAPA, change control, training records) for regulated industries. Infrastructure for building auditable processes rather than a turnkey validated QMS.

- **[QAtrial](https://github.com/MeyerThorsten/QAtrial)**  
  Open-source (AGPL) quality management platform with CAPA, risk, audit trails, electronic signatures, supplier qualification modules, and integrations (Jira, GitHub), aimed at regulated and manufacturing environments.

- **[Carbon](https://github.com/crbnos/carbon)**  
  Open-source ERP, MES, and QMS for manufacturing. Includes quality management capabilities suitable for complex assembly and high-volume production contexts.

- **[ProcessMaker and open BPM/workflow engines](https://www.processmaker.com/)**  
  Open workflow platforms frequently used to automate CAPA, audit, and supplier-qualification processes when a full commercial QMS is not required.

- **[Senaite / Bika LIMS](https://github.com/senaite)**  
  Open-source laboratory information management systems that can support incoming inspection and quality testing data feeding supplier quality programs.

- **[Document control and approval open stacks](https://github.com/)**  
  Combinations of open DMS, Git-based controlled documents, and e-signature tools used to approximate QMS document control.

- **[Nonconformance and CAPA issue trackers](https://github.com/)**  
  Structured issue templates and state machines (often on top of GitLab/GitHub or open project tools) for tracking supplier-related quality events.

- **[Supplier scorecard and performance open dashboards](https://github.com/)**  
  Analytics notebooks and simple apps that aggregate delivery, quality, and audit data into supplier performance views.

- **[Risk and FMEA open toolkits](https://github.com/)**  
  Lightweight open templates and scripts for FMEA, risk registers, and design controls that complement supplier quality processes.

- **[GOSQAS and transparency-oriented tracking](https://github.com/gosqasorg)**  
  Open efforts focused on transparent, append-only quality and asset tracking, useful in distributed or low-resource manufacturing contexts.

### Additional Strong Open-Source Options
- Extending Odoo, ERPNext, or similar open ERPs with custom quality and supplier modules.
- Using open form builders and workflow engines for supplier questionnaires and audit checklists.
- Combining open eQMS document control with commercial or open LIMS for test results.
- Community ISO 9001 / IATF / ISO 13485 process templates under open licenses.
- Local-first quality record systems for small manufacturers with strict data-residency needs.

**Frameworks for building custom systems**: For smaller or less regulated environments, combine an open workflow engine (or QAtrial/Carbon) with structured CAPA/NCR templates, a document store, and simple supplier scorecards. Use Open QMS concepts to keep processes version-controlled and auditable in Git. This can support internal quality programs and early-stage supplier oversight. Highly regulated industries (medical devices, pharma, aerospace) and large multi-tier supply chains still rely primarily on validated commercial platforms (MasterControl, ETQ, Intelex, Qualio, Greenlight Guru, SAP, etc.) for audit readiness, electronic signatures, and proven compliance support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Supplier quality systems often support regulated processes (FDA, ISO, IATF, etc.). Open-source tools provide transparency and flexibility but are generally **not** pre-validated for regulated use. Any system used for real product quality or regulatory decisions must undergo appropriate validation, change control, and quality-system oversight. Always involve quality and regulatory professionals.
- This list is not legal, regulatory, or quality-system advice.

---
**Made for quality, procurement, and supply-chain teams working to improve supplier performance and compliance.**
Let's make quality processes more transparent and accessible where regulation and risk allow.