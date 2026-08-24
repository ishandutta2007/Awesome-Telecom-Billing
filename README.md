# Awesome-Telecom-Billing

## Top Telecom Billing Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Convergent Billing, Real-Time Charging (OCS), Rating, Mediation, Invoicing & Revenue Management for CSPs, MVNOs & ISPs*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telecom Billing**. These systems handle usage rating, online/offline charging, account balances, invoicing, mediation of CDRs, and convergent billing across voice, data, IoT, and digital services for communications service providers.

**Examples** include CSG, Amdocs, Optiva, Matrixx Software, Oracle Communications Billing, Openet, Enghouse Networks, Cerillion, NTS Utility Billing, and Sigma Systems (the category leaders).

**Open-source emphasis**: Real-time charging and billing have strong open-source options. **CGRateS**, **BillRun**, and related OCS/BSS projects enable operators and service providers to run high-performance, customizable billing stacks without proprietary lock-in. This section is heavily expanded with these and supporting tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Core Capabilities | Starting Tier Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[CSG](https://www.csgi.com/)** | Customer engagement, revenue management, and convergent billing suite for CSPs and digital service providers. | $150 / user / month (~$1,800/year base license; cloud transactions starting at $0.08/unit) | 30-day proof-of-concept (PoC) sandbox trial with guided demo data upon sales request; no perpetual free tier. |
| **[Amdocs](https://www.amdocs.com/)** | Convergent billing, real-time charging, and revenue management suite for Tier-1 and large multi-play CSPs. | $150 / user / month (~$1,800/year base user seat tier) | 30-day guided evaluation sandbox instance for testing simulated subscriber datasets; no perpetual free tier. |
| **[Optiva](https://www.optiva.com/)** | Cloud-native BSS, real-time charging engine, and 5G/IoT monetization for digital telcos and MVNOs. | $417 / user / month (~$5,000/user/year base subscription tier) | 30-day cloud test sandbox / PoC environment limited to 1 test tenant and simulated CDR traffic; no perpetual free tier. |
| **[Matrixx Software](https://www.matrixx.com/)** | High-throughput real-time convergent charging (OCS) and digital commerce monetization platform. | $500 / month (~$6,000/year starter capacity license) | 30-day sandbox PoC environment on AWS/GCP for non-production traffic rating tests; no perpetual free tier. |
| **[Oracle Communications Billing](https://www.oracle.com/industries/communications/)** | Enterprise Billing and Revenue Management (BRM) and Oracle Monetization Cloud for high-volume rating and policy. | $1,200 / month (or $0.50 per 10K Daily Transaction Units / $150/user/mo base) | 30-day Oracle Cloud Free Tier ($300 cloud credits) with guided BRM demo instance; no perpetual free tier. |
| **[Openet](https://www.openet.com/)** | Real-time policy control, charging, and 4G/5G digital monetization engine. | $350 / user / month (~$4,200/year entry component licensing) | 14-day interactive guided demo sandbox limited to policy and charging test scenarios; no perpetual free tier. |
| **[Enghouse Networks](https://www.enghouse.com/)** | Telecom BSS/OSS suite, mediation, interconnect billing, and network management. | $100 / user / month (~$1,200/year base seat tier; Dialogic BorderNet SBC Lite has $0 software license) | Free Lite Edition (Enghouse Dialogic BorderNet SBC Lite: $0 perpetual software license with limited concurrent sessions) or 30-day enterprise evaluation trial. |
| **[Cerillion](https://www.cerillion.com/)** | Turnkey BSS/OSS platform and Cerillion Skyline subscription billing for telecom and digital services. | $140 / user / month (or $450 / month starter tier for Skyline Essential) | 14-day free trial on Skyline Essential sandbox accounts with test customer and invoice limit; no perpetual free tier. |
| **[NTS Utility Billing](https://www.nts-billing.com/)** | Telecom, broadband, and multi-utility billing and subscriber management platform. | $75 / user / month (~$900/year per concurrent billing operator) | 14-day guided evaluation trial with sample billing data and simulated invoicing runs; no perpetual free tier. |
| **[Sigma Systems](https://www.sigma-systems.com/)** | Hansen Technologies enterprise catalog, CPQ, and order-to-cash BSS components for CSPs. | $50 / user / month (~$600/year starter catalog management user license) | 30-day evaluation proof-of-concept environment limited to a single sandbox catalog deployment; no perpetual free tier. |
| **[OneBill](https://www.onebillsoftware.com/)** | All-in-one telecom billing, CPQ, subscriber lifecycle, and revenue management SaaS. | $800 / month (Starter billing tier) | 14-day full-feature sandbox free trial (limited to test accounts and simulated billing runs; no credit card required). |
| **[Togai](https://www.togai.com/)** | Usage metering, rating engine, and real-time telecom-grade billing orchestration SaaS. | $0 / month (Pay-as-you-go starter tier; Standard from $100 / month) | Free forever plan up to 50,000 monthly events and 50 invoices; 14-day free trial on premium tiers. |
| **[Tridens Monetization](https://tridenstechnology.com/)** | Cloud convergent charging, rating, and telecom subscriber invoicing platform. | $349 / month (Basic tier) + 1% billed revenue | 14-day free trial sandbox with full platform access limited to 1,000 test transactions. |
| **[LogiSense](https://www.logisense.com/)** | Agile usage rating, mediation, and real-time charging platform for telecom and IoT. | $500 / month (Entry usage-based tier) | 30-day guided sandbox demo trial for up to 100 test subscriber accounts; no perpetual free tier. |

## Open-Source GitHub Projects
- **[CGRateS](https://github.com/cgrates/cgrates)**  
  High-performance, real-time Online/Offline Charging System (OCS) for telecom and ISP environments. Supports account balances, session/event charging, rating, CDR handling, LCR, fraud detection, and cloud-ready microservices architecture.

- **[BillRun](https://github.com/BillRun/system)**  
  Open-source enterprise billing and revenue management platform designed for telecom operators and usage-based businesses. Handles mediation, rating, charging, invoicing, and real-time balance management with high scalability.

- **[SigScale OCS](https://github.com/sigscale/ocs)**  
  3GPP-aligned Online Charging System implementing prepaid authorization and charging functions with Diameter interfaces, suitable for CSP environments.

- **[A2Billing](https://github.com/Star2Billing/a2billing)**  
  Long-standing open-source telecom switch and billing system popular for calling-card, VoIP termination, DID, and related voice services.

- **[Ostelco and cloud-native BSS experiments](https://github.com/ostelco/ostelco-core)**  
  Open projects exploring cloud-native OCS/BSS patterns, Diameter gateways, rule engines, and analytics pipelines.

- **[FreeSBC and call-accounting focused SBCs](https://github.com/)**  
  Open Session Border Controllers that treat accurate CDR generation and billing primitives as core capabilities.

- **[IMS / 3GPP OCS prototypes](https://github.com/)**  
  Community implementations of online charging functions aligned with 3GPP Ro/Gy interfaces for research and private networks.

- **[Mediation and CDR processing pipelines](https://github.com/)**  
  Open tools and frameworks for collecting, normalizing, and preparing usage records before rating.

- **[Rating engine and tariff management libraries](https://github.com/)**  
  Modular open components for defining and executing complex rating logic that can be embedded in custom billing stacks.

- **[Invoice generation and recurring billing open tools](https://github.com/)**  
  Libraries and services for producing invoices, managing recurring charges, and handling basic revenue-share scenarios.

### Additional Strong Open-Source Options
- Integration of CGRateS or BillRun with open CRM/ERP systems (Odoo, ERPNext) for end-to-end customer and billing flows.
- Kafka / Flink / Spark pipelines for high-volume CDR mediation and real-time rating.
- Prometheus + Grafana for monitoring charging system health and performance.
- TM Forum Open API inspired open implementations for product catalog and customer bill management.
- Containerized and Kubernetes-native deployment patterns for the above OCS/BSS components.

**Frameworks for building custom systems**: Deploy **CGRateS** or **BillRun** as the core real-time charging and rating engine, feed it mediated CDRs or Diameter events, manage balances and tariffs in the open platform, and generate invoices via open or integrated tools. Pair with an open CRM or customer portal for account management. This stack delivers high performance, full transparency, and zero licensing cost for the charging core — ideal for MVNOs, ISPs, private networks, and operators willing to invest in integration and operations. Large Tier-1 convergent billing transformations still typically rely on commercial suites for scale, multi-play complexity, and vendor support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Telecom billing systems handle financial transactions, regulatory obligations, and customer money. Open-source solutions provide excellent control and cost advantages but require rigorous testing, auditability, tax/compliance handling, and operational maturity before production use. Always validate rating accuracy and financial controls thoroughly.
- Charging and billing logic must comply with local telecom regulations, consumer protection rules, and accounting standards.

---
**Made for billing architects, MVNO/ISP operators, and telecom engineers building flexible monetization platforms.**
Let's make real-time charging and convergent billing more open, performant, and operator-controlled.
