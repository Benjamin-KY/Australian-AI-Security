# Complete Inventory of Australian AI Security Documents

> **75+ documents across federal and state/territory governments**

This inventory catalogues all known Australian AI Security standards, policies, frameworks, and guidance documents. Each entry includes status (mandatory/voluntary), scope, and direct links where available.

**Legend:**
- **Mandatory** - Legal or policy requirement
- **Sector-Specific** - Binding for specific industries
- **Voluntary** - Guidance/best practice
- **Date** - Latest version or release date
- **Link** - Direct URL to document

---

## Table of Contents

1. [Federal - ACSC/ASD Technical Guidance](#federal---acscasd-technical-guidance)
2. [Federal - Information Security Manual (ISM)](#federal---information-security-manual-ism)
3. [Federal - Protective Security Policy Framework (PSPF)](#federal---protective-security-policy-framework-pspf)
4. [Federal - Critical Infrastructure (SOCI/CISC)](#federal---critical-infrastructure-socisc)
5. [Federal - Digital Transformation Agency (DTA)](#federal---digital-transformation-agency-dta)
6. [Federal - Department of Industry, Science and Resources (DISR)](#federal---department-of-industry-science-and-resources-disr)
7. [Federal - Sector Regulators](#federal---sector-regulators)
8. [Federal - Other Agencies](#federal---other-agencies)
9. [New South Wales](#new-south-wales)
10. [Victoria](#victoria)
11. [Queensland](#queensland)
12. [South Australia](#south-australia)
13. [Western Australia](#western-australia)
14. [Tasmania](#tasmania)
15. [Northern Territory](#northern-territory)
16. [Australian Capital Territory](#australian-capital-territory)
17. [Cross-Jurisdictional](#cross-jurisdictional)

---

## Federal - ACSC/ASD Technical Guidance

Primary technical guidance for AI security from Australia's cyber security authority.

| Document | Date | Status | Partners | Key Focus |
|----------|------|--------|----------|-----------|
| **[Engaging with Artificial Intelligence](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/engaging-with-artificial-intelligence)** | Jan 2024 | ðŸŸ¢ Voluntary | CISA, FBI, NSA, NCSC-UK, CCCS, NCSC-NZ, Japan NISC | Data poisoning, prompt injection, supply chain risks, model stealing |
| **[Deploying AI Systems Securely](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/deploying-ai-systems-securely)** | Apr 2024 | ðŸŸ¢ Voluntary | NSA AISC (lead), Five Eyes | Secure deployment, access controls, network segmentation, AI red-teaming, GPU security |
| **[Guidelines for Secure AI System Development](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/guidelines-secure-ai-system-development)** | Nov 2023 | ðŸŸ¢ Voluntary | NCSC-UK/CISA (lead), 23 agencies | Secure design lifecycle, SBOM, supply chain, threat modelling |
| **[AI Data Security](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/ai-data-security)** | May 2025 | ðŸŸ¢ Voluntary | NSA AISC, Five Eyes | Data supply chain, poisoning, encryption, provenance tracking, content credentials |
| **[AI/ML Supply Chain Risks and Mitigations](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/ai-ml-supply-chain)** | Oct 2025 | ðŸŸ¢ Voluntary | ASD's ACSC only | Pre-trained model risks, AI BOMs, vendor risk, defence-in-depth |
| **[Content Credentials](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/content-credentials)** | Jan 2025 | ðŸŸ¢ Voluntary | NSA, CCCS, NCSC-UK | Deepfakes, media provenance, C2PA standard, cryptographic signing |

### ACSC Alerts and Advisories (AI-related)

| Advisory | Date | Type | Summary |
|----------|------|------|---------|
| **Advisory 2024-003: AI-Enabled Phishing** | Feb 2024 | Alert | Increased sophistication in AI-generated phishing |
| **Advisory 2024-007: LLM Prompt Injection** | May 2024 | Alert | Prompt injection attack patterns and mitigations |
| **Advisory 2025-002: Deepfake Detection** | Jan 2024 | Guidance | Identifying AI-generated media in targeted attacks |

---

## Federal - Information Security Manual (ISM)

Mandatory security controls for Australian Government entities. AI-specific controls added 2024-2025.

| Control ID | Title | Date Added | Applicability | Requirement |
|------------|-------|------------|---------------|-------------|
| **ISM-1923** | OWASP Top 10 for LLM | Jun 2024 | ðŸ”´ Mandatory | Mitigate risks identified in OWASP Top 10 for Large Language Model Applications |
| **ISM-1924** | Adversarial Input Detection | Jun 2024 | ðŸ”´ Mandatory | Detect and mitigate adversarial inputs including prompt injection attempts |
| **ISM-2072** | AI Model Storage Formats | Sep 2025 | ðŸ”´ Mandatory | Store AI models in formats that do not allow arbitrary code execution (e.g., safetensors over pickle) |

**Source:** [Information Security Manual](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism)

### Related ISM Guidelines

| Guideline | Relevance to AI |
|-----------|-----------------|
| **Guidelines for Software Development** | Applies to AI/ML code development |
| **Guidelines for System Hardening** | Applies to AI infrastructure |
| **Guidelines for Database Systems** | Applies to training data storage |
| **Guidelines for Cryptography** | Applies to model encryption, secure inference |

---

## Federal - Protective Security Policy Framework (PSPF)

Mandatory protective security requirements for Commonwealth entities.

| Document | Date | Status | Scope | Key AI Provisions |
|----------|------|--------|-------|-------------------|
| **[PSPF Release 2025](https://www.protectivesecurity.gov.au/)** | Jul 2025 | Mandatory | Non-corporate Commonwealth entities | New AI, quantum, and connected peripherals content |
| **[PSPF Policy Advisory 001-2025](https://www.protectivesecurity.gov.au/policies/pspf-policy-advisory-001-2025)** | Oct 2025 | Mandatory | All Commonwealth entities | Rules for OFFICIAL information with generative AI; approved providers (OpenAI, Anthropic) |
| **[PSPF Direction 001-2025 (DeepSeek Ban)](https://www.protectivesecurity.gov.au/news/pspf-direction-update-deepseek-products-applications-and-web-services)** | Feb 2025 | Mandatory | All Commonwealth entities | Prohibition on DeepSeek products, applications, web services |

### PSPF Supporting Materials

| Document | Purpose |
|----------|---------|
| **Hosting Certification Framework** | Certifies AI service providers for government use |
| **FOCI Assessment Guidelines** | Foreign Ownership, Control, Influence assessment for AI providers |

---

## Federal - Critical Infrastructure (SOCI/CISC)

Requirements for critical infrastructure sectors under the Security of Critical Infrastructure Act 2018.

| Document | Date | Status | Scope | AI Relevance |
|----------|------|--------|-------|--------------|
| **[Security of Critical Infrastructure Act 2018](https://www.legislation.gov.au/Details/C2024C00267)** | Nov 2024 (amended) | Mandatory | 22 critical infrastructure asset classes | AI systems in CI must be covered under CIRMP |
| **[CIRMP Rules](https://www.cisc.gov.au/legislative-information-and-reforms/critical-infrastructure/critical-infrastructure-risk-management-program)** | Aug 2024 | Mandatory | Responsible entities | Cyber hazard vector covers AI systems |
| **[CISC AI Factsheet](https://www.cisc.gov.au/resources-subsite/Documents/artificial-intelligence-factsheet.pdf)** | Jun 2025 | Guidance | Critical infrastructure owners | Three AI risk categories: attacks using AI, attacks on AI, AI reliability failures |
| **[Cyber Incident Reporting Requirements](https://www.cisc.gov.au/legislative-information-and-reforms/critical-infrastructure/reporting-obligations)** | Jul 2024 | Mandatory | CI asset owners | 12-hour reporting for significant AI-related incidents |

---

## Federal - Digital Transformation Agency (DTA)

AI governance for the Australian Public Service.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[Policy for the Responsible Use of AI in Government v2.0](https://www.digital.gov.au/policy/ai/policy)** | Dec 2025 | Mandatory | Non-corporate Commonwealth entities | Chief AI Officers, transparency statements, high-risk oversight |
| **[AI Plan for the Australian Public Service](https://www.digital.gov.au/policy/ai/plan)** | Nov 2025 | Policy | APS | Every agency to have AI training, Chief AI Officers, usage tracking |
| **[AI Technical Standard](https://www.digital.gov.au/policy/ai/technical-standard)** | Jul 2025 | Mandatory | Commonwealth agencies | Technical implementation requirements |
| **[Public Generative AI Tools Guidance](https://www.dta.gov.au/guidance-use-public-generative-ai-tools)** | Jun 2024 | Guidance | APS staff | Do's and don'ts for public GenAI |
| **[GovAI Platform Requirements](https://www.digital.gov.au/policy/ai/govai)** | 2025 | Mandatory | Agencies using GovAI | Sovereign hosting, security controls |

---

## Federal - Department of Industry, Science and Resources (DISR)

National AI policy and adoption guidance.

| Document | Date | Status | Scope | Key Content |
|----------|------|--------|-------|-------------|
| **[National AI Plan](https://www.industry.gov.au/publications/national-ai-plan)** | Dec 2025 | Policy | National | 9 actions; AISI establishment; no dedicated AI Security provisions |
| **[Guidance for AI Adoption (AI6)](https://www.industry.gov.au/publications/guidance-ai-adoption)** | Oct 2025 | Voluntary | All sectors | 6 essential practices for responsible adoption |
| **[Being Clear About AI-Generated Content](https://www.industry.gov.au/publications/being-clear-about-ai-generated-content)** | Oct 2025 | Voluntary | All sectors | Labelling, watermarking, metadata recording |
| **[Voluntary AI Safety Standard (VAISS)](https://www.industry.gov.au/publications/voluntary-ai-safety-standard)** | Sep 2024 | Voluntary (superseded) | All sectors | 10 guardrails; replaced by AI6 |
| **[Australia's AI Ethics Principles](https://www.industry.gov.au/publications/australias-ai-ethics-principles)** | Oct 2024 (updated) | Voluntary | All sectors | 8 principles including privacy, security |

---

## Federal - Sector Regulators

Binding requirements for specific regulated industries.

### Financial Services (APRA/ASIC)

| Document | Date | Status | Scope | AI Provisions |
|----------|------|--------|-------|---------------|
| **[CPS 234 Information Security](https://www.apra.gov.au/information-security)** | Jul 2019 | Mandatory | APRA-regulated entities | All infosec requirements apply to AI systems |
| **[CPS 230 Operational Risk Management](https://www.apra.gov.au/operational-risk-management)** | Jul 2025 | Mandatory | APRA-regulated entities | New technology (including AI) risk assessment |
| **[ASIC Report 798: Beware of the Gap](https://asic.gov.au/regulatory-resources/find-a-document/reports/rep-798/)** | Oct 2024 | Guidance | Financial services | AI governance, third-party risk, human oversight |
| **[SPS 220 Risk Management](https://www.apra.gov.au/risk-management)** | Various | Mandatory | Superannuation | Applies to AI in investment decisions |

### Online Safety (eSafety)

| Document | Date | Status | Scope | AI Provisions |
|----------|------|--------|-------|---------------|
| **[eSafety Industry Standards](https://www.esafety.gov.au/industry/codes-and-standards)** | Jun 2024 | Mandatory | Online service providers | GenAI services, AI companion chatbots, model distribution platforms |
| **[eSafety Generative AI Position Statement](https://www.esafety.gov.au/industry/generative-ai)** | 2024 | Guidance | GenAI providers | Safety by design expectations |

### Privacy (OAIC)

| Document | Date | Status | Scope | AI Provisions |
|----------|------|--------|-------|---------------|
| **[OAIC Guide to Data Analytics and AI](https://www.oaic.gov.au/privacy/guidance-and-advice/guide-to-data-analytics-and-ai)** | 2023 | Guidance | APP entities | Privacy obligations for AI |
| **[APP Guidelines - AI Automated Decisions](https://www.oaic.gov.au/privacy/australian-privacy-principles-guidelines)**  | Mandatory | APP entities | Disclosure requirements for automated decisions (APP 1.7-1.9) |

### Healthcare (TGA)

| Document | Date | Status | Scope | AI Provisions |
|----------|------|--------|-------|---------------|
| **[TGA Regulation of Software as Medical Device](https://www.tga.gov.au/resources/resource/guidance/regulation-software-based-medical-devices)** | 2021 | Mandatory | Medical AI | AI in medical devices, SaMD classification |
| **[AI in Healthcare Legislation Review](https://www.health.gov.au/our-work/safe-and-responsible-ai-in-healthcare)** | Ongoing | Review | Healthcare sector | Review of AI regulation in healthcare |

---

## Federal - Other Agencies

| Agency | Document | Date | Status | Scope |
|--------|----------|------|--------|-------|
| **Defence** | [Method for Ethical AI in Defence](https://www.dst.defence.gov.au/) | 2021 | Mandatory (Defence) | Defence AI | Verification, human control, IHL compliance |
| **Attorney-General's** | [Copyright and AI Reference Group](https://www.ag.gov.au/rights-and-protections/copyright/copyright-and-ai-reference-group) | Ongoing | Consultation | AI developers | Copyright implications of AI training |
| **Finance** | [National Framework for AI Assurance](https://www.finance.gov.au/government/public-data/national-framework-assurance-artificial-intelligence-government) | Jun 2024 | Framework | All governments | 5 cornerstones for AI assurance |
| **Education** | [Australian Framework for GenAI in Schools](https://www.education.gov.au/schooling/generative-ai-schools) | Dec 2023 | Guidance | Schools | Safe classroom use of GenAI |

---

## New South Wales

**Maturity Level: Comprehensive**

NSW operates Australia's most mature mandatory government AI governance framework.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[NSW AI Assessment Framework (AIAF)](https://www.digital.nsw.gov.au/policy/artificial-intelligence/nsw-artificial-intelligence-assessment-framework)** | Mar 2022 | Mandatory | All NSW Government | Risk self-assessment, lifecycle governance, >$5M to DAF |
| **[NSW AI Ethics Policy](https://www.digital.nsw.gov.au/policy/artificial-intelligence/nsw-ai-ethics-policy)** | 2022 | Mandatory | All NSW Government | 5 mandatory principles |
| **[Circular DCS-2024-04](https://arp.nsw.gov.au/dcs-2024-04-use-of-artificial-intelligence-by-nsw-government-agencies/)** | 2024 | Mandatory | All NSW Government bodies | Compliance directive |
| **[NSW AI Strategy](https://www.digital.nsw.gov.au/policy/artificial-intelligence/nsw-ai-strategy)** | 2024 | Policy | NSW Government | Strategic direction |
| **[Cyber Security NSW GenAI Guidance](https://www.cyber.nsw.gov.au/guidance/generative-ai)** | 2024 | Guidance | NSW agencies | Do's and don'ts for public GenAI |
| **[NSW AI Review Committee Terms](https://www.digital.nsw.gov.au/policy/artificial-intelligence/ai-review-committee)** | 2022 | Governance | High/very-high risk projects | Expert review of significant AI |

---

## Victoria

**Maturity Level: Developing**

Victoria formalised AI governance in November 2024 with mandatory guidelines.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[Administrative Guideline for Safe and Responsible Use of GenAI in VPS](https://www.vic.gov.au/administrative-guideline-safe-responsible-use-gen-ai-vps)** | Nov 2024 | Mandatory | Victorian Public Sector | Adopts 8 AI Ethics Principles |
| **[Victorian AI Assurance Framework](https://www.vic.gov.au/ai-assurance-framework)** | Piloting | In development | VPS | Under development, piloting with Copilot |
| **[VPDSF v2.1](https://www.vic.gov.au/victorian-protective-data-security-framework)** | 2023 | Mandatory | Victorian agencies | 12 mandatory standards, 5 domains - applies to AI |
| **[OVIC AI Privacy Guidance](https://ovic.vic.gov.au/privacy/resources-for-organisations/artificial-intelligence-understanding-privacy-obligations/)** | 2024 | Guidance | Victorian organisations | Privacy obligations for AI |
| **[Victoria Police AI Ethics Framework](https://www.police.vic.gov.au/victoria-police-artificial-intelligence-ethics-framework)** | Mar 2024 | Mandatory (VicPol) | Victoria Police | 8 enabling principles including Human Rights |

---

## Queensland

**Maturity Level: Developing**

Queensland has comprehensive mandatory policy with sophisticated risk assessment.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[AI Governance Policy](https://www.forgov.qld.gov.au/information-and-communication-technology/queensland-government-enterprise-architecture/ai-governance)** | Sep 2024 | Mandatory | QLD Government | ISO 38507-based governance, ISMS integration |
| **[FAIRA Framework](https://www.forgov.qld.gov.au/information-and-communication-technology/queensland-government-enterprise-architecture/faira-framework)** | 2024 | Mandatory | QLD Government | Two-part risk assessment (Components + Values) |
| **[IS18 Information and Cyber Security Policy](https://www.qgcio.qld.gov.au/documents/information-security-policy-is18)** | 2024 | Mandatory | QLD Government | Mandatory ISMS, Essential Eight implementation |
| **[QChat GenAI Environment](https://www.forgov.qld.gov.au/qchat)** | 2024 | Platform | QLD Government | Secure government-approved GenAI |
| **[OIC AI Privacy Guidance](https://www.oic.qld.gov.au/guidelines/for-government/artificial-intelligence)** | 2024 | Guidance | QLD agencies | Privacy and RTI obligations for AI |

---

## South Australia

**Maturity Level: Basic (developing)**

SA established Australia's first state Office for AI in November 2025.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[Office for Artificial Intelligence](https://www.dpc.sa.gov.au/responsibilities/office-for-artificial-intelligence)** | Nov 2025 | Governance | SA Government | $28M budget, strategic coordination |
| **[AI Ethics Policy (DTF/P9.1)](https://www.dpc.sa.gov.au/documents/ai-ethics-policy)** | 2024 | Mandatory | SA Government | Design, development, deployment, operation |
| **[LLM Guideline (DPC/G13.1) v1.3](https://www.dpc.sa.gov.au/documents/llm-guideline)** | 2024 | Optional | SA Government | Practical LLM controls |
| **[SACSF v2.0](https://www.security.sa.gov.au/cyber-security/sacsf)** | 2024 | Mandatory | SA Government | 18 policy statements, 4-tier implementation |

---

## Western Australia

**Maturity Level: Comprehensive**

WA has the most comprehensive framework among smaller jurisdictions.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[WA Government AI Policy v2](https://www.wa.gov.au/government/publications/wa-government-artificial-intelligence-policy)** | Jul 2025 | Mandatory | WA Government | AI Accountable Officers by Sep 2025 |
| **[WA AI Assurance Framework](https://www.wa.gov.au/government/publications/wa-ai-assurance-framework)** | 2024 | Mandatory | WA Government | Self-assessment, mid-range+ to Advisory Board |
| **[WA AI Advisory Board](https://www.wa.gov.au/government/ai-advisory-board)** | Jan 2025 | Governance | High-risk projects | Independent expert review |
| **[WA Cyber Security Advisory 20230509001](https://www.wa.gov.au/government/publications/cyber-security-advisory-ai-chatbots)** | May 2023 | Advisory | WA agencies | AI chatbot security risks |
| **[WA Health AI Policy (MP 0193/25)](https://www.health.wa.gov.au/policies/mp-0193-25)** | 2025 | Mandatory (Health) | WA Health | Sector-specific AI requirements |

---

## Tasmania

**Maturity Level: Minimal**

Tasmania has the least developed AI governance, relying on guidance.

| Document | Date | Status | Scope | Key Content |
|----------|------|--------|-------|-------------|
| **[Guidance for AI Use in Tasmanian Government v1.4](https://www.digital.tas.gov.au/guidance/artificial-intelligence)** | 2024 | Voluntary | TAS Government | 7 recommendations; references NSW AIAF |
| **[Digital Strategy - AI Focus](https://www.digital.tas.gov.au/strategy)** | 2024 | Strategy | TAS Government | Strategic intent only |

**Note:** Tasmania recommends using NSW AIAF for detailed guidance. Economic Diversification and Investment Strategy with AI focus expected H1 2026.

---

## Northern Territory

**Maturity Level: Basic**

NT has a mandatory framework with territory-specific principles.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[NT Government AI Assurance Framework](https://nt.gov.au/data-and-digital/ai-assurance-framework)** | May 2024 | Mandatory | NT Government | 5 NT-specific AI Ethics Principles |
| **[AI Advisory Board](https://nt.gov.au/data-and-digital/ai-advisory-board)** | 2024 | Governance | High-risk assessments | Reports to ICT Governance Board |

**NT AI Ethics Principles:**
1. Community Benefit
2. Safety
3. Fairness
4. Privacy and Security
5. Transparency

---

## Australian Capital Territory

**Maturity Level: Developing**

ACT released comprehensive mandatory framework in May 2025.

| Document | Date | Status | Scope | Key Requirements |
|----------|------|--------|-------|------------------|
| **[ACT Government AI Policy v1.0](https://www.act.gov.au/data-and-digital/ai-policy)** | May 2025 | Mandatory | ACT Government | 4 responsible officers per AI initiative |
| **[ACT AI Assurance Framework](https://www.act.gov.au/data-and-digital/ai-assurance-framework)** | May 2025 | Mandatory | ACT Government | Aligned with National and NSW frameworks |
| **[AI Advisory Group (AIAG)](https://www.act.gov.au/data-and-digital/aiag)** | 2025 | Governance | Medium/high risk | Reviews significant assessments |

**ACT Required Officers:**
- AI System Owner
- AI Administrator
- Data Custodian
- Project Manager

---

## Cross-Jurisdictional

Documents agreed or relevant across multiple jurisdictions.

| Document | Authority | Date | Scope | Status |
|----------|-----------|------|-------|--------|
| **[National Framework for AI Assurance in Government](https://www.finance.gov.au/government/public-data/national-framework-assurance-artificial-intelligence-government)** | Data and Digital Ministers | Jun 2024 | All governments | Framework |
| **[Australia's AI Ethics Principles](https://www.industry.gov.au/publications/australias-ai-ethics-principles)** | DISR | 2024 | National | Referenced by all jurisdictions |
| **[Essential Eight Maturity Model](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/essential-eight)** | ACSC | Ongoing | Referenced nationally | Security baseline |

---

## Document Totals by Jurisdiction

| Jurisdiction | Mandatory | Sector-Specific | Voluntary | Total |
|--------------|-----------|-----------------|-----------|-------|
| Federal - ACSC | 3 | 0 | 10 | 13 |
| Federal - PSPF/DHA | 4 | 0 | 2 | 6 |
| Federal - DTA | 4 | 0 | 1 | 5 |
| Federal - DISR | 0 | 0 | 5 | 5 |
| Federal - Regulators | 0 | 8 | 4 | 12 |
| Federal - Other | 2 | 0 | 2 | 4 |
| NSW | 4 | 0 | 2 | 6 |
| VIC | 3 | 1 | 2 | 6 |
| QLD | 3 | 0 | 2 | 5 |
| SA | 2 | 0 | 1 | 3 |
| WA | 3 | 1 | 1 | 5 |
| TAS | 0 | 0 | 2 | 2 |
| NT | 1 | 0 | 0 | 1 |
| ACT | 2 | 0 | 0 | 2 |
| **TOTAL** | **31** | **10** | **34** | **75** |

---

## Last Updated

**6 December 2025**

See [CHANGELOG.md](../CHANGELOG.md) for update history.

---

## Contributing

Found a missing document? See [CONTRIBUTING.md](../CONTRIBUTING.md) to submit additions or corrections.
