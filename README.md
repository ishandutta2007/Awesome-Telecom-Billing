# Awesome-Telecom-Billing

# Top Telecom Billing Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Convergent Billing, Real-Time Charging (OCS), Rating, Mediation, Invoicing & Revenue Management for CSPs, MVNOs & ISPs*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telecom Billing**. These systems handle usage rating, online/offline charging, account balances, invoicing, mediation of CDRs, and convergent billing across voice, data, IoT, and digital services for communications service providers.

**Examples** include CSG, Amdocs, Optiva, Matrixx Software, Oracle Communications Billing, Openet, Enghouse Networks, Cerillion, NTS Utility Billing, and Sigma Systems (the category leaders).

**Open-source emphasis**: Real-time charging and billing have strong open-source options. **CGRateS**, **BillRun**, and related OCS/BSS projects enable operators and service providers to run high-performance, customizable billing stacks without proprietary lock-in. This section is heavily expanded with these and supporting tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[CSG](https://www.csgi.com/)**  
  Leading provider of customer engagement, revenue management, and convergent billing solutions widely used by telecom and digital service providers, especially in North America.

- **[Amdocs](https://www.amdocs.com/)**  
  Comprehensive convergent billing and revenue management suite for Tier-1 and large CSPs, covering rating, charging, invoicing, and complex multi-play offerings.

- **[Optiva](https://www.optiva.com/)**  
  Cloud-native charging and billing platform popular with digital telcos and operators needing flexible, real-time monetization capabilities.

- **[Matrixx Software](https://www.matrixx.com/)**  
  Real-time convergent charging platform (often associated with advanced 5G and digital service monetization; note ongoing market consolidation).

- **[Oracle Communications Billing](https://www.oracle.com/industries/communications/)**  
  Enterprise billing and revenue management (BRM) solutions supporting complex rating, policy, and charging for large communications providers.

- **[Openet](https://www.openet.com/)**  
  Specialist in policy, charging, and real-time monetization components frequently deployed in 4G/5G and digital service environments.

- **[Enghouse Networks](https://www.enghouse.com/)**  
  Network and service management solutions that include billing and operational support capabilities for service providers.

- **[Cerillion](https://www.cerillion.com/)**  
  BSS platform offering billing, customer management, and related capabilities aimed at mid-market and specialist communications providers.

- **[NTS Utility Billing](https://www.nts-billing.com/)**  
  Billing solutions oriented toward utilities and related service providers with telecom-adjacent or multi-utility needs.

- **[Sigma Systems](https://www.sigma-systems.com/)**  
  Catalog, order, and related BSS components that often integrate with or support billing and fulfillment processes.

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
