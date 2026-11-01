# Awesome-Continuous-Threat-Exposure-Management-CTEM

# Awesome-Continuous-Threat-Exposure-Management-CTEM

# Awesome-Continuous-Threat-Exposure-Management-CTEM

**Top Continuous Threat Exposure Management CTEM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Attack Path Analysis, Exposure Validation, Risk-Based Prioritization & Self-Hosted CTEM Workflows*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Continuous Threat Exposure Management (CTEM)**. These tools enable organizations to move beyond periodic vulnerability scans toward a continuous cycle of scoping, discovery, prioritization, validation, and mobilization—identifying which exposures are actually exploitable and worth fixing first.



**Examples** include CrowdStrike Falcon Exposure Management, Tenable ExposureAI, XM Cyber, Rapid7 Exposure Command, Qualys VMDR, Picus Security, Cymulate, Hadrian, Balbix, and Skybox Security (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted exposure management, attack surface discovery, and open validation infrastructure. **Critical note**: True open-source CTEM is nascent—**ExposureNexus** is the only purpose-built open-source CTEM platform, but it is in **early development** with automated scanner import incomplete . No open-source project matches XM Cyber's attack path analysis or Picus's automated validation, but for teams building a CTEM program from scratch, the foundational components are available.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[CrowdStrike Falcon Exposure Management](https://www.crowdstrike.com/)**

  **CTEM platform** driven by real-time Falcon telemetry rather than periodic scans. **ExPRT.AI** predicts exploitability using real-world vulnerability exploitation data; focuses resources on the **5% of exposures most likely to be exploited** . **Pricing**: CDW lists **$126.99/year** for Tier 2 (150–299) single license ; enterprise bundles quote-based. **Free tier**: None. **Best for**: CrowdStrike customers wanting CTEM grounded in live endpoint telemetry—**trade-off**: requires Falcon agent on endpoints; blind to assets without Falcon .



- **[Tenable ExposureAI](https://www.tenable.com/)**

  **Generative AI-powered exposure management** built on Tenable's **Exposure Graph**. **AI Exposure** extends visibility to AI workloads with dashboard, issues, explorer, and policies . **Pricing**: **Flexible pricing and packaging introduced April 2026** for new customers—predictable spend, simplified procurement, faster time-to-value . Quote-only for specific tiers. **Free tier**: Trial available. **Best for**: Tenable customers wanting AI-assisted prioritization with simplified buying—**trade-off**: AI Exposure is an add-on category; validate budget adoption .



- **[XM Cyber](https://xmcyber.com/)**

  **Hybrid cloud exposure management** using attack path analysis. **Continuous Exposure Management (CEM)** identifies attack paths, prioritizes based on risk to critical assets, and mobilizes remediation. AWS Marketplace lists **XM CEM Medium Enterprise Network at $350,000/year** ; Taiwan pricing table shows **CEM for Cloud (100–1000 assets) at ~$14,250–$14,408** . **Free tier**: None. **Best for**: enterprises wanting attack path visualization—**trade-off**: six-figure enterprise pricing; cloud analysis dependency.



- **[Rapid7 Exposure Command](https://www.rapid7.com/)**

  **Unified exposure management** named a **Leader in the 2025 Gartner Magic Quadrant for Exposure Assessment Platforms**. **Pricing**: **Asset-based, pay for what you use**—pricing reflects asset types and use cases in scope; **not publicly listed**, typically custom quotes; annual subscriptions with volume discounts . **Free tier**: None. **Best for**: organizations wanting a Gartner-validated CTEM platform with flexible asset-based pricing—**trade-off**: requires custom quote; asset modeling required.



- **[Qualys VMDR with TruRisk](https://www.qualys.com/)**

  **Cloud-native vulnerability management and exposure platform** with **TruRisk** scoring. CDW lists **Qualys VMDR TruRisk at $4,415.99** . **Free tier**: Trial available. **Best for**: organizations wanting mature vulnerability management with TruRisk prioritization as the foundation for CTEM—**trade-off**: CTEM is an evolution of VMDR, not a purpose-built CTEM workflow.



- **[Picus Security Validation Platform](https://www.picussecurity.com/)**

  **Security validation platform** unifying exposure management through **adversarial exposure validation**. **Pricing**: **Available upon request** per Software Advice ; free trial and free version listed. **Free tier**: Trial available. **Best for**: teams wanting to validate which exposures are actually exploitable before remediation—**trade-off**: validation-focused; requires integration with existing scanners.



- **[Cymulate](https://cymulate.com/)**

  **Exposure validation and security posture platform** with breach and attack simulation. **Pricing**: **Quote-only**; Genesee County signed a Cymulate agreement in August 2026 for platform licensing, onboarding, and support . **Free tier**: None. **Best for**: teams wanting to validate exploitability and communicate risk—**trade-off**: simulation-focused; not a full CTEM workflow platform.



- **[Hadrian](https://hadrian.io/)**

  **Agentic offensive security platform** operationalizing CTEM. **Atlas** continuously monitors external exposure; **Nova** runs AI agents through applications on demand. **Nova available from €1,250 per test** (excluding VAT) . Raised **$40M in October 2026** . **Free tier**: None. **Best for**: enterprises wanting continuous, autonomous external attack surface validation—**trade-off**: Nova is per-test pricing; Atlas enterprise quote required.



- **[Balbix](https://www.balbix.com/)** (**Acquired by SAFE**)

  **AI-native exposure discovery and assessment** platform. **Acquired by SAFE in November 2025**; now part of SAFE's unified platform combining AI-SPM, TPRM, CTEM, and CRQ . **Pricing**: **Custom quote**; **no free trial, no free plan** . **Free tier**: None. **Best for**: historical reference—evaluate SAFE's integrated offering instead.



- **[Skybox Security](https://www.skyboxsecurity.com/)**

  **Security posture management** with network mapping and firewall assurance. **Skybox CertiFire** available at **€595 per firewall per year** for a 10-license pack . **Free tier**: None. **Best for**: organizations prioritizing network-centric exposure visibility and firewall rule analysis—**trade-off**: CertiFire is firewall-focused; broader CTEM requires additional modules.



## Open-Source GitHub Projects



- **[ExposureNexus](https://github.com/s-schoen/exposurenexus)**

  **Open-source continuous threat exposure management (CTEM) platform** (license per repo) — **the only purpose-built open-source CTEM platform** found in this research, though **explicitly in early development** . **Features**: **Asset-centered findings**—organizes security observations into findings grouped around affected assets; **triage queue** reviewing active findings by asset; **status tracking** from discovery through confirmation, mitigation, accepted risk, false positive, duplicate, or out-of-scope; **assignment and due dates**; **asset inventory** with owners and custom fields; **vulnerability catalog**; **RBAC** (viewer, editor, admin). **Core model**: Assets → Findings → Observations (manual or scanner detection records) → Vulnerabilities. **Tech stack**: PostgreSQL, RabbitMQ, React, NestJS. **Deploy**: Local evaluation via Docker Compose . **Trade-off**: **Early development, not production-ready**—automated scanner import is **incomplete**: API registers metadata and queues ingestion, but worker **logs completion without parsing** data; UI import page **disabled**. Currently requires manual finding creation and triage . **Best for**: developers and security teams wanting to evaluate or contribute to the first open-source CTEM platform—**not for production deployment without significant development**.



### Additional Strong Open-Source Options



- **No mature open-source CTEM platform exists beyond ExposureNexus.** The category is dominated by proprietary vendors (CrowdStrike, Tenable, XM Cyber, Rapid7, Qualys) with no open-source equivalents for attack path analysis, exploitability validation, or automated prioritization. **ExposureNexus** provides a conceptual starting point but lacks automated ingestion and production hardening.



**Frameworks for building custom systems**: **ExposureNexus** is the only open-source building block for CTEM workflow management. For a complete stack, pair it with open-source scanners (Nuclei, Trivy, Amass) and validation tools. **No open-source project provides a turnkey CTEM platform comparable to XM Cyber or Picus.**



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CTEM platforms handling vulnerability data and attack paths must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for security findings.

- **The "CTEM platform" vs. "validation platform" vs. "ASM platform" vs. "early-stage open-source" distinction is critical.** **CrowdStrike, Tenable, XM Cyber, Rapid7, and Qualys** are **CTEM or exposure management platforms**—they cover multiple CTEM stages (discovery, prioritization, often validation) . **Picus and Cymulate** are **validation platforms**—they prove exploitability but are not full CTEM workflow engines . **Hadrian** is an **agentic offensive platform**—it automates external validation with Atlas (continuous) and Nova (on-demand) . **ExposureNexus** is an **early-stage CTEM workflow platform**—it models findings and triage but lacks automated ingestion . **No open-source project replicates XM Cyber's attack path analysis or Picus's automated validation.**

- **ExposureNexus is the only purpose-built open-source CTEM platform, but it is not production-ready.** Automated scanner import is incomplete—the worker logs completion without parsing data; the UI import page is disabled . **For teams wanting to evaluate or contribute to open-source CTEM, it is the starting point. For production CTEM today, commercial platforms are required.**

- **XM Cyber pricing is six-figure enterprise.** AWS Marketplace lists **$350,000/year** for Medium Enterprise Network . **Do not evaluate without enterprise budget approval.**

- **Hadrian's Nova is per-test pricing**—**€1,250 per test** excluding VAT . **Atlas (continuous external monitoring) requires enterprise quote.** **Model your validation cadence before committing.**

- **Skybox CertiFire is firewall-focused** at **€595/firewall/year** for a 10-license pack . **For broader CTEM, additional Skybox modules are required.**

- **Balbix is no longer independent.** It was acquired by SAFE in November 2025 and is now part of SAFE's integrated platform . **Do not evaluate Balbix as a standalone option**—evaluate SAFE's integrated offering.

- **Tenable introduced flexible pricing in April 2026** to reduce buying friction and simplify procurement . **AI Exposure extends CTEM to AI workloads**—validate whether buyers are budgeting for this category .

- **Pricing opacity is universal across commercial CTEM vendors.** CrowdStrike, Tenable, XM Cyber, Rapid7, Qualys, Picus, Cymulate, Hadrian, Balbix, and Skybox all require sales contact or marketplace quotes for full pricing. **Validate with direct vendor conversations against your existing scanner investments and CTEM maturity.**

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL, RabbitMQ for ExposureNexus), security hardening for scanner credentials, and ongoing maintenance. **CTEM platforms handle vulnerability data and attack paths**—ensure your deployment meets your organization's security standards before connecting production environments.



---



**Made for security engineers, vulnerability management teams, and organizations building transparent exposure management solutions.**

Let's make Continuous Threat Exposure Management more open, data-driven, and risk-validated.
