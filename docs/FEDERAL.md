# Federal AI Security Frameworks

> **Detailed documentation of Commonwealth AI security requirements**

This document provides in-depth coverage of federal AI security frameworks, including implementation guidance and practical considerations.

---

## Table of Contents

1. [ACSC Technical Guidance](#acsc-technical-guidance)
2. [Information Security Manual (ISM)](#information-security-manual-ism)
3. [Protective Security Policy Framework (PSPF)](#protective-security-policy-framework-pspf)
4. [Critical Infrastructure (SOCI Act)](#critical-infrastructure-soci-act)
5. [DTA Policy and Standards](#dta-policy-and-standards)
6. [Sector Regulators](#sector-regulators)
7. [Implementation Considerations](#implementation-considerations)

---

## ACSC Technical Guidance

The Australian Cyber Security Centre (ACSC), part of the Australian Signals Directorate (ASD), provides the primary technical guidance for AI security in Australia. Much of this guidance is developed collaboratively with Five Eyes partners.

### Core Documents

#### Engaging with Artificial Intelligence (2024, updated 2025)

**Purpose:** Introductory guidance for organisations beginning to use AI systems.

**Key Security Topics:**
- **Data Poisoning:** Manipulation of training data to cause model misbehaviour
- **Prompt Injection:** Adversarial inputs designed to override system instructions
- **Supply Chain Risks:** Third-party models, libraries, and data sources
- **Model Stealing:** Extraction of proprietary model weights or behaviour
- **Information Disclosure:** Unintended exposure of training data or sensitive information

**Partners:** CISA, FBI, NSA, NCSC-UK, CCCS, NCSC-NZ, Japan NISC

**Implementation Notes:**
- Start here for organisations new to AI security
- Cross-reference with OWASP Top 10 for LLM Applications
- Consider as baseline awareness for all staff using AI tools

---

#### Deploying AI Systems Securely (April 2024)

**Purpose:** Technical guidance for secure deployment of AI systems in enterprise environments.

**Key Security Controls:**

| Category | Controls |
|----------|----------|
| **Access Control** | Role-based access, least privilege, MFA for AI systems |
| **Network Segmentation** | Isolate AI infrastructure, control data flows |
| **Logging and Monitoring** | Comprehensive logging of AI inputs/outputs, anomaly detection |
| **AI Red-Teaming** | Adversarial testing before and after deployment |
| **GPU Security** | Secure configuration of AI accelerators, memory protection |
| **Model Protection** | Encryption at rest and in transit, access controls on model files |

**Partners:** NSA AISC (lead), ASD's ACSC, CISA, FBI, NCSC-UK, CCCS, NCSC-NZ

**Implementation Notes:**
- Essential reading for security teams deploying AI
- Addresses infrastructure-level security often missed in AI ethics frameworks
- GPU security section particularly relevant for on-premise deployments

---

#### Guidelines for Secure AI System Development (November 2023)

**Purpose:** Security guidance for organisations developing AI systems.

**Lifecycle Phases Covered:**
- DESIGN
- DEVELOP
- DEPLOY
- OPERATE

**Key Requirements:**
- Software Bill of Materials (SBOM) for AI components
- Threat modelling including AI-specific attack vectors
- Secure handling of training data
- Model versioning and integrity verification

**Partners:** NCSC-UK/CISA (lead), 23 international agencies including ASD

---

#### AI Data Security (May 2025)

**Purpose:** Protecting data throughout the AI lifecycle.

**Key Topics:**
- **Data Supply Chain:** Provenance tracking for training data
- **Data Poisoning Mitigations:** Validation, anomaly detection, trusted sources
- **Encryption:** Data at rest, in transit, and during processing
- **Content Credentials:** C2PA standard for media provenance
- **Data Lineage:** Tracking data transformations and usage

**Partners:** NSA AISC, ASD's ACSC, Five Eyes partners

---

#### AI/ML Supply Chain Risks and Mitigations (October 2025)

**Purpose:** Managing risks from third-party AI components.

**This is Australia's first standalone AI supply chain guidance.**

**Risk Categories:**

| Risk | Description | Mitigations |
|------|-------------|-------------|
| **Pre-trained Models** | Backdoors, biases, malicious behaviour | Provenance verification, testing, trusted sources |
| **Third-party Libraries** | Vulnerabilities, supply chain attacks | Dependency scanning, version pinning, SBOM |
| **Training Data** | Poisoning, bias, IP issues | Data validation, trusted sources, documentation |
| **Cloud AI Services** | Provider security, data handling | Due diligence, contracts, monitoring |

**AI Bill of Materials (AI-BOM) Components:**
- Model architecture and version
- Training data sources and lineage
- Dependencies and versions
- Known limitations and failure modes
- Security testing results

---

#### Frontier Models and Their Impact on Cyber Security (April 2026)

**Purpose:** Guidance on preparing for the cyber security implications of frontier AI models with enhanced vulnerability discovery capabilities.

**Context:** Published in response to rapid advances in frontier AI model capabilities for vulnerability discovery. The ACSC guidance notes that frontier models have discovered long-standing vulnerabilities that survived decades of human review, and references industry blog posts including from Anthropic (7 April 2026) and warnings from OpenAI (December 2025) about frontier model cyber security risks.

> *Author's note: Anthropic's Claude Mythos model and Project Glasswing are illustrative examples of the capabilities the ACSC guidance addresses. The ACSC publication references these developments without naming specific models or products.*

**Key Mitigation Strategies:**

| Strategy | Description | ASD References |
|----------|-------------|----------------|
| **Reduce attack surfaces** | Assess external connectivity, apply network segmentation, limit to reputable suppliers | ISM System Hardening, Network Segmentation guidance |
| **Patch every day** | Adopt increased patching tempo; apply all patches regardless of severity rating | ISM System Management, Essential Eight |
| **Use AI to find vulnerabilities** | Leverage frontier models for Secure by Design; strengthen code before deployment | Safe Software Deployment guidance |
| **Implement layered security** | Defence-in-depth aligned with modern defensible architectures; zero trust principles | Secure by Design guidance |

**Key Insight:** AI is not creating new vulnerabilities — it is identifying those that already exist. Organisations should harness AI's vulnerability discovery capabilities defensively while preparing for adversaries using the same capabilities offensively.

**Partners:** References NCSC-UK analysis on defensive use of frontier models.

---

### ACSC Guidance Summary Table

| Document | Primary Audience | Threat Coverage | Implementation Effort |
|----------|------------------|-----------------|----------------------|
| Engaging with AI | All staff | Awareness | Low |
| Deploying Securely | Security/Ops | Infrastructure | High |
| Secure Development | Developers | SDLC | High |
| AI Data Security | Data teams | Data lifecycle | Medium |
| Supply Chain | Procurement/Security | Third-party | Medium |
| Frontier Models | All organisations | Frontier AI risks | Medium |

---

## Information Security Manual (ISM)

The ISM is the Australian Government's cybersecurity framework. It became mandatory for non-corporate Commonwealth entities and is referenced by most state frameworks.

### AI-Specific Controls

Three AI-specific controls have been added since June 2024:

#### ISM-1923: OWASP Top 10 for LLM

**Control Text:**
> Risks identified in the OWASP Top 10 for Large Language Model Applications are mitigated.

**OWASP Top 10 for LLM Applications (2025 v2.0):**
1. Prompt Injection
2. Sensitive Information Disclosure
3. Supply Chain Vulnerabilities
4. Data and Model Poisoning
5. Improper Output Handling
6. Excessive Agency
7. System Prompt Leakage
8. Vector and Embedding Weaknesses
9. Misinformation
10. Unbounded Consumption

**Implementation:**
- Map each OWASP risk to your LLM deployment
- Implement mitigations documented in OWASP guidance
- Document residual risks and acceptance decisions
- Regular review as OWASP updates the list

---

#### ISM-1924: Adversarial Input Detection

**Control Text:**
> Adversarial inputs, including prompt injection attempts, are detected and mitigated.

**Implementation Approaches:**

| Approach | Description | Effectiveness |
|----------|-------------|---------------|
| **Input Validation** | Pattern matching, blocklists | Basic |
| **Semantic Analysis** | Detect instruction-like patterns | Medium |
| **Anomaly Detection** | ML-based input classification | High |
| **Layered Prompts** | System prompts resistant to injection | Medium |
| **Output Filtering** | Detect when injection succeeded | Complementary |

*Note: Effectiveness ratings are the author's assessment based on practitioner experience, not ASD's official position. No single approach is comprehensive; defence in depth is required.*

**Critical: Indirect Prompt Injection**

ISM-1924's scope includes adversarial inputs that may not come directly from the user. In retrieval-augmented generation (RAG) systems and agentic AI deployments, adversarial content can be injected via:
- Poisoned documents ingested by the retrieval pipeline
- Malicious content in emails, databases, or external data sources
- Compromised tool outputs in multi-step agent workflows

Organisations should implement defences against indirect injection including retrieval sandboxing, output monitoring for tool-calling systems, and canary document detection.

**Practical Considerations:**
- No single approach is comprehensive
- Defence in depth required
- Monitor for emerging injection techniques
- Balance security with usability

---

#### ISM-2072: AI Model Storage Formats

**Control Text:**
> AI models are stored in formats that do not allow arbitrary code execution.

**Background:**
Pickle files (common in Python ML) can execute arbitrary code on load, enabling supply chain attacks.

**Safe Formats:**
- **safetensors** - Recommended; no code execution possible
- **ONNX** - Open format; safe when custom operators are disabled or restricted to a known allowlist
- **TensorFlow SavedModel** - When restricted to frozen graphs; disable py_function and custom layer code execution
- **GGUF/GGML** - Quantized format; inherently safe

**Unsafe Formats:**
- **pickle (.pkl, .pt, .pth)** - Arbitrary code execution
- **joblib** - Python serialisation; code execution possible
- **Custom formats** - Assess case by case
- **PyTorch .bin** - Uses pickle serialisation internally despite different extension
- **Keras HDF5 (.h5)** - Lambda layers can contain arbitrary Python code

**Implementation:**
- Convert existing models to safetensors where possible
- Scan incoming models for pickle content
- Establish approved formats list for procurement
- Training for ML engineers on secure formats

---

### Related ISM Guidelines

While not AI-specific, these ISM sections apply to AI systems:

| Guideline | AI Relevance |
|-----------|--------------|
| Guidelines for Software Development | AI/ML code, MLOps pipelines |
| Guidelines for System Hardening | AI infrastructure, GPU servers |
| Guidelines for Database Systems | Training data, vector databases |
| Guidelines for Cryptography | Model encryption, secure inference |
| Guidelines for System Management | AI system administration |
| Guidelines for Network Security | AI network segmentation |
| Guidelines for Email Security | AI-assisted email handling |

---

## Protective Security Policy Framework (PSPF)

The PSPF establishes protective security requirements for Commonwealth entities.

### PSPF 2025 AI Additions

The July 2025 PSPF release added new content specifically addressing:
- Artificial intelligence
- Quantum computing
- Connected peripheral technologies

### Key AI-Related Policies

#### PSPF Policy Advisory 001-2025: GenAI Use

**Scope:** Rules for using OFFICIAL information with generative AI services.

**Key Requirements:**

| Requirement | Detail |
|-------------|--------|
| **Approved Providers Only** | Must use Hosting Certification Framework certified providers |
| **Pre-approved Providers** | OpenAI and Anthropic approved without additional FOCI assessment |
| **Other Providers** | Require explicit FOCI (Foreign Ownership, Control, Influence) risk evaluation |
| **Classification Limits** | OFFICIAL only; no PROTECTED or above |
| **Logging** | Maintain records of GenAI use with official information |

---

#### PSPF Direction 001-2025: DeepSeek Ban

**Scope:** Prohibition on DeepSeek products across all Commonwealth entities.

**Requirements:**
- Remove all existing DeepSeek applications and services
- Block access to DeepSeek web services
- Applies to all devices accessing government systems
- Includes personal devices used for work

**Rationale:** National security concerns regarding data handling and foreign influence.

---

**AI-Relevant Requirements:**
- Authorisation process for AI technology systems
- Risk assessment before deployment
- Ongoing monitoring requirements
- Incident reporting obligations

---

### PSPF and AI Decision Flow

See the [Knowledge Graph](KNOWLEDGE-GRAPH.md) for the PSPF AI decision flow Mermaid diagram, or the [diagrams/](../diagrams/) folder for SVG visualisations.

---

## Critical Infrastructure (SOCI Act)

The Security of Critical Infrastructure Act 2018 (as amended) applies to 22 critical infrastructure asset classes.

### AI Under SOCI

AI systems are captured under SOCI when:
- Embedded in critical infrastructure assets
- Used to operate or manage critical infrastructure
- Could impact critical infrastructure if compromised

### Critical Infrastructure Risk Management Program (CIRMP)

CIRMPs must address AI under the **cyber and information security hazard vector**.

**CISC AI Risk Categories:**

| Category | Description | Examples |
|----------|-------------|----------|
| **Attacks Using AI** | AI-enhanced threats against CI | AI-powered intrusion, automated exploitation |
| **Attacks On AI** | Targeting AI systems in CI | Model poisoning, adversarial attacks |
| **AI Reliability Failures** | AI malfunction affecting CI | Hallucinations in critical decisions, automation failures |

### Incident Reporting

AI incidents affecting critical infrastructure require reporting:
- **Critical impact:** 12 hours
- **Significant impact:** 72 hours

**Reportable AI Incidents:**
- Successful adversarial attacks on CI AI systems
- AI system failures causing CI disruption
- Data breaches involving AI training data for CI
- Discovery of backdoors in CI AI models

---

## DTA Policy and Standards

The Digital Transformation Agency oversees AI governance for the Australian Public Service.

### Policy for Responsible Use of AI in Government v2.0

**Effective:** December 2025

**Key Requirements:**

| Requirement | Deadline | Detail |
|-------------|----------|--------|
| **Chief AI Officers** | By end of 2026 | Every agency to designate |
| **Transparency Statements** | 6 months from release | Public disclosure of AI use |
| **High-Risk Oversight** | Immediate | Submit to oversight committee |
| **Training** | Ongoing | All staff using AI |
| **Usage Tracking** | Immediate | Monitor and report AI use |

**Exclusions:**
- Defence portfolio
- National intelligence community

### AI Technical Standard

**Effective:** July 2025

**Covers:**
- Technical implementation requirements
- Integration standards
- Security baseline
- Interoperability requirements

### GovAI Platform

**Purpose:** Sovereign AI hosting service for government agencies.

**Security Features:**
- Australian-based hosting
- Certified under Hosting Certification Framework
- Centralised logging and monitoring
- Standardised security controls

---

### Australia's AI Ethics Principles

**Published by DISR** | 8 voluntary principles referenced by all jurisdictions:

1. Human, societal and environmental wellbeing
2. Human-centred values
3. Fairness
4. Privacy protection and security
5. Reliability and safety
6. Transparency and explainability
7. Contestability
8. Accountability

These principles are referenced by NSW, Victoria, Queensland, and the National Framework for AI Assurance.

---

## Sector Regulators

### Financial Services

**APRA CPS 234 (Information Security)**
- All information security requirements apply to AI systems
- Board oversight of AI security
- Third-party AI provider requirements
- 72-hour incident notification

**APRA CPS 230 (Operational Risk Management)**
- Effective July 2025
- New technology (including AI) risk assessment required
- Impact on operational risk profile
- Business continuity for AI dependencies

**ASIC Report 798**
- AI governance expectations
- Third-party risk management
- Human oversight requirements
- Existing licensee obligations apply to AI

### Online Safety

**eSafety Industry Standards (June 2024, effective December 2024)**
- First mandatory AI-specific safety requirements
- Applies to: Generative AI services, AI companion chatbots, model distribution platforms
- Safety by design obligations
- Enforceable under Online Safety Act 2021

### Privacy

**OAIC Guidance**
- APP 11 (Security) applies to AI systems processing personal information
- Automated decision disclosure (APP 1.7-1.9) - mandatory from December 2026 (per Privacy and Other Legislation Amendment Act 2024)
- Privacy Impact Assessments recommended for AI projects

### Privacy Act 1988 (as amended December 2024)

The **Privacy and Other Legislation Amendment Act 2024** received Royal Assent on 10 December 2024, progressing 23 proposals from the Privacy Act Review Report.

**Key AI-relevant provisions:**

| Provision | Effective Date | AI Relevance |
|-----------|---------------|--------------|
| Statutory tort for serious invasions of privacy | June 2025 | AI systems processing personal information |
| Automated decision-making transparency (APP 1.7-1.9) | December 2026 | Disclosure requirements for AI decisions |
| Children's Online Privacy Code | December 2026 | AI services targeting children |
| Enhanced OAIC enforcement powers | December 2024 | Civil penalties for AI-related privacy breaches |

**Note:** Second tranche of reforms (additional Privacy Act Review proposals) expected during 2026.

---

## Implementation Considerations

### Compliance Mapping

For organisations subject to multiple frameworks:

| If You Are... | Primary Frameworks | Additional Requirements |
|---------------|-------------------|------------------------|
| Commonwealth Entity | ISM, PSPF, DTA Policy | Sector-specific if applicable |
| CI Asset Owner | SOCI Act, CIRMP, ISM | ACSC guidance |
| Financial Services | APRA CPS 234/230, ASIC | ISM (recommended) |
| State Government | State framework, ISM (referenced) | Sector-specific |
| Private Sector | ACSC guidance (voluntary), sector-specific | Privacy Act if handling PI |

### Implementation Priority

**Recommended order for federal compliance:**

1. **ISM AI Controls** (ISM-1923, 1924, 2072) - Mandatory baseline
2. **PSPF AI Provisions** - If handling government information
3. **SOCI CIRMP** - If critical infrastructure
4. **Sector-specific** - APRA, eSafety, etc.
5. **ACSC Guidance** - Technical implementation

### Common Gaps

Based on audit and assessment findings, common compliance gaps include:

| Gap | Affected Control | Remediation |
|-----|------------------|-------------|
| No adversarial testing | ISM-1924 | Implement input validation + monitoring |
| Pickle format models | ISM-2072 | Convert to safetensors |
| Missing AI-BOM | Supply chain guidance | Document all AI components |
| No FOCI assessment | PSPF 001-2025 | Assess non-approved providers |
| Insufficient logging | Multiple | Comprehensive AI audit trail |

---

## Resources

- [ACSC AI Security Resources](https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/governance/engaging-with-artificial-intelligence)
- [Information Security Manual](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism)
- [Protective Security Policy Framework](https://www.protectivesecurity.gov.au/)
- [CISC Critical Infrastructure](https://www.cisc.gov.au/)
- [DTA AI Policy](https://www.digital.gov.au/policy/ai)
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

---

[Back to Index](../README.md) | [Complete Inventory →](INVENTORY.md) | [State Frameworks →](STATES.md)