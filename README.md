

# Australian AI Security Framework Index

![Australian AI Security Framework Index](Header.png)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Last Updated](https://img.shields.io/badge/Last_Updated-December_2025-blue.svg)](#changelog)
[![Frameworks Indexed](https://img.shields.io/badge/Frameworks_Indexed-75+-green.svg)](docs/INVENTORY.md)

> **The comprehensive, community-maintained index of Australian AI Security standards, policies, frameworks, and guidance.**

Australia's National AI Plan was released on 2 December 2025. AI Security didn't make the cut.

This repository exists to fill that gap, consolidating every federal and state/territory AI security document into a single, navigable resource. Because if the government won't map AI Security, the community will.

---

## Why This Exists

Australia has **75+ AI-related security documents** spread across 11 jurisdictions, multiple departments, and various regulatory bodies. There is no single source of truth. Practitioners must navigate:

- **Federal**: ACSC, DHA, PSPF, CISC, DTA, DISR, APRA, ASIC, OAIC, eSafety
- **States/Territories**: NSW, VIC, QLD, SA, WA, TAS, NT, ACT
- **Mandatory vs Voluntary**: ISM controls, PSPF directions, sector regulations, voluntary guidance
- **Overlapping frameworks**: Multiple risk assessment approaches, inconsistent terminology, no clear hierarchy

This index provides:

**Complete inventory** of all Australian AI Security documents  
**Relationship mapping** showing how frameworks connect  
**Gap analysis** comparing Australia to international standards  
**Practical navigation** for compliance and implementation  
**Regular updates** as new documents are released  

---

## Quick Navigation

| Section | Description |
|---------|-------------|
| [Complete Inventory](docs/INVENTORY.md) | All 75+ documents in one place |
| [Federal Frameworks](docs/FEDERAL.md) | ACSC, PSPF, ISM, SOCI, DTA, regulators |
| [State & Territory](docs/STATES.md) | NSW, VIC, QLD, SA, WA, TAS, NT, ACT |
| [International Comparison](docs/INTERNATIONAL.md) | Australia vs EU, UK, US, Singapore |
| [Gap Analysis](docs/GAPS.md) | What's missing from Australia's approach |
| [Knowledge Graph](docs/KNOWLEDGE-GRAPH.md) | Visual map of framework relationships |
| [Changelog](CHANGELOG.md) | Update history |

---


## Key Findings

### What Australia Has

- **ISM AI Controls** (ISM-1923, ISM-1924, ISM-2072): Mandatory for government, references OWASP Top 10 for LLM
- **ACSC Five Eyes Guidance**: World-class technical guidance on secure AI deployment, supply chain, data security
- **PSPF AI Provisions**: First AI-specific protective security requirements (2025)
- **State Leaders**: NSW and WA have comprehensive mandatory frameworks

### What Australia Lacks

- **No mandatory AI security for private sector** (unlike EU AI Act)
- **No systematic risk classification** (EU has prohibited/high/limited/minimal)
- **No AI incident reporting regime** (despite SOCI cyber incident rules)
- **No foundation model governance** (EU has GPAI obligations)
- **No adversarial testing mandates** (EU requires for systemic risk models)
- **No consolidated AI Security body** (UK renamed theirs to AI *Security* Institute)

### The Safety vs Security Problem

Australia's National AI Plan establishes an AI Safety Institute focused on alignment and frontier risks. It does not address:

- Adversarial machine learning
- Model poisoning and data integrity
- AI supply chain security
- Red-teaming requirements
- Secure development lifecycle

The UK recognised this distinction and **renamed their AI Safety Institute to the AI Security Institute** in February 2025.

---

## How to Use This Resource

### For Compliance Teams
Start with the [Complete Inventory](docs/INVENTORY.md) to identify which frameworks apply to your organisation based on:
- Jurisdiction (federal/state)
- Sector (financial services, health, critical infrastructure, general)
- Obligation type (mandatory/voluntary)

### For Security Practitioners
The [Federal Frameworks](docs/FEDERAL.md) section details ACSC guidance with practical implementation notes.

### For Policy Analysts
The [Gap Analysis](docs/GAPS.md) and [International Comparison](docs/INTERNATIONAL.md) provide the evidence base for advocacy and submissions.

### For Researchers
The [Knowledge Graph](docs/KNOWLEDGE-GRAPH.md) visualises relationships.

---

## ISM AI Controls

The Information Security Manual contains three AI-specific controls (as of September 2025):

| Control | Requirement | Applicability |
|---------|-------------|---------------|
| **ISM-1923** | Mitigate risks identified in OWASP Top 10 for Large Language Model Applications | All LLM implementations |
| **ISM-1924** | Detect and mitigate adversarial inputs including prompt injection attempts | All AI systems accepting user input |
| **ISM-2072** | Store AI models in formats that do not allow arbitrary code execution (e.g., safetensors over pickle) | All AI model storage |

---

## Contributing

This is a community resource. Contributions welcome:

- **Document updates**: New policies, version changes, corrections
- **Relationship mapping**: Identify connections between frameworks
- **International comparisons**: Additional jurisdictions
- **Tooling**: Compliance checklists, automation, visualisations

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## Maintainers

**Ben Kereopa-Yorke**  
Senior AI Security Specialist | OWASP ML Security Top 10 Co-Lead  
---

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this material with appropriate attribution.

---

## Acknowledgements

This index builds on work by:
- Australian Cyber Security Centre (ACSC)
- Digital Transformation Agency (DTA)
- Department of Industry, Science and Resources (DISR)
- State and territory digital/cyber security agencies
- The Australian cybersecurity community

---

## Disclaimer

This resource is provided for informational purposes. It does not constitute legal advice. Always verify current versions of documents directly with issuing authorities. Framework applicability depends on your specific circumstances.

---

<p align="center">
  <i>AI Security in Australia needs to get louder.</i>
</p>
