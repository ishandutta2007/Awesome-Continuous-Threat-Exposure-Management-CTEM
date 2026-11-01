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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The Continuous Threat Exposure Management (CTEM) and exposure management market is estimated at **$1.3B to $2.7B in 2025** and projected to reach **$1.5B to $3.5B in 2026** (growing at ~11–13% CAGR) as enterprises shift away from static vulnerability scans toward continuous validation. The market exhibits a **moderately fragmented and transitional structure**—anchored by a concentrated core of large public incumbents (CrowdStrike, Tenable, Qualys, Rapid7) capturing high-volume enterprise spend, alongside a vibrant, fragmented periphery of specialized point-solution innovators and validation startups.

## SaaS/Hosted Platforms

| Platform | Company Scale (Revenue / Valuation) | Focus & Key Capabilities | Specific Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[CrowdStrike Falcon Exposure Management](https://www.crowdstrike.com/)** | **~$250B+ Market Cap**<br>($4.8B FY26 Revenue) | Telemetry-driven CTEM via Falcon agent; ExPRT.AI predicts exploitability across live endpoints. | Starting at **$126.99/year** per license (Tier 2: 150–299 assets, CDW listing); enterprise packages custom. | **15-day free trial**; includes Falcon Prevent NGAV, Device Control, and mobile protection (no credit card required). |
| **[Qualys VMDR with TruRisk](https://www.qualys.com/)** | **~$7.6B Market Cap**<br>(~$669M Revenue) | Cloud-native vulnerability management & exposure prioritization with TruRisk risk-scoring engine. | Starting at **$4,415.99/year** (CDW baseline package); volume tiers scale per managed IP/asset. | **30-day free trial**; grants full-featured evaluation across the Enterprise TruRisk Platform for test environments. |
| **[Tenable ExposureAI](https://www.tenable.com/)** | **~$4.5B Market Cap**<br>(~$995M Revenue) | Generative AI-powered exposure management built on Exposure Graph; extends visibility into AI workloads. | Starting at **$3,700/year** for 100 assets (~$37/asset/yr base VM); Tenable One suites range **$55–$90/asset/yr**. | **30-day free trial** for enterprise cloud platforms (or 7-day trial for standalone Nessus; non-commercial Nessus Essentials free for up to 5 IPs). |
| **[Rapid7 Exposure Command](https://www.rapid7.com/)** | **~$1.0B Market Cap**<br>(~$860M Revenue) | Unified exposure management combining CAASM, EASM, and posture management (Gartner Leader). | Baseline asset tiers start around **$1.60–$2.00/asset/month** (~$19–$24/asset/yr via InsightVM foundation); Exposure Command bundles scale per asset. | **No permanent free tier**; 30-day guided POC / proof-of-value available upon sales qualification (self-serve trial limited to point modules like InsightAppSec). |
| **[XM Cyber](https://xmcyber.com/)** | **$700M Valuation**<br>(Acquired by Schwarz Group; $140B+ parent revenue) | Hybrid cloud exposure management focusing on attack path analysis and critical asset choke points. | Cloud tiers start at **~$14,250–$14,408/year** (100–1,000 assets); AWS Marketplace lists Medium Enterprise at **$350,000/year**. | **14-day free trial / Proof of Value (PoV)**; full-feature access to simulate and analyze attack paths across scoping boundary. |
| **[Cymulate](https://cymulate.com/)** | **~$500M Valuation**<br>(~$30M–$50M ARR) | Continuous security validation, breach and attack simulation (BAS), and exposure risk posture assessment. | Starting at **$1,500/month** (~$18,000/yr) for single vectors; full multi-vector 1,000-endpoint packages start at **~$91,000/year**. | **14-day free trial**; provides simulated attack evaluation and risk report across selected test vectors. |
| **[Picus Security Validation Platform](https://www.picussecurity.com/)** | **~$250M–$500M Valuation**<br>(~$40M–$50M ARR) | Adversarial exposure validation proving exploitability before remediation; integrates with existing scanners. | Entry annual deployments start around **$20,000–$30,000/year** based on network choke points and simulated vectors. | **14-day free trial**; self-serve attack simulation across limited test vectors and integrations. |
| **[Balbix](https://www.balbix.com/)** *(Acquired by SAFE)* | **~$250M–$500M Valuation**<br>(SAFE Security parent valuation) | AI-native exposure discovery and cyber risk quantification (now part of SAFE's unified CRQ/CTEM platform). | AWS Marketplace baseline for Balbix lists at **$145,000/year** (AI Assistant tier) to **$220,000/year** (10,000 assets full platform). | **No free tier or public trial**; evaluation conducted via guided personalized platform demos and scheduled enterprise POCs. |
| **[Hadrian](https://hadrian.io/)** | **$65M Total Raised**<br>($40M Series B, Oct 2026) | Autonomous offensive security; Atlas continuous external ASM and Nova on-demand AI penetration testing. | Nova pentests start at **€1,250 per test** (~$1,350/test excl. VAT); continuous Atlas ASM priced via annual enterprise contracts. | **No self-serve free trial**; offers a free preliminary external attack surface discovery report and personalized live demo. |
| **[Skybox Security](https://www.skyboxsecurity.com/)** *(Liquidated / Assets Acquired)* | **Assets acquired by Tufin**<br>(Historically PE-backed / ~$30M–$85M rev) | Security posture management with network mapping and firewall rule compliance analysis. | Historical Skybox CertiFire baseline started at **€595/firewall/year** (10-license pack); broad enterprise deployments custom-quoted. | **No free tier or trial** (Operations liquidated; former customer base serviced via Tufin migration programs). |

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
