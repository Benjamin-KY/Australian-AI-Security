# State and Territory AI Security Frameworks

> **Detailed documentation of jurisdictional AI security requirements**

Australian states and territories have developed their own AI governance frameworks at varying levels of maturity. This document provides detailed coverage of each jurisdiction's approach.

---

## Maturity Overview

| Jurisdiction | Maturity | Mandatory Framework | AI Advisory Body | Key Strength |
|--------------|----------|---------------------|------------------|--------------|
| **NSW** | â–ˆâ–ˆâ–ˆ Comprehensive | Yes (AIAF) | AI Review Committee | First mandatory government AI framework globally |
| **WA** | â–ˆâ–ˆâ–ˆ Comprehensive | Yes (AI Policy v2) | AI Advisory Board | Comprehensive accountability structure |
| **VIC** | â–ˆâ–ˆâ–‘ Developing | Yes (GenAI Guideline) | In development | Strong data security foundation (VPDSF) |
| **QLD** | â–ˆâ–ˆâ–‘ Developing | Yes (AI Governance) | Via QGCIO | Sophisticated risk assessment (FAIRA) |
| **ACT** | â–ˆâ–ˆâ–‘ Developing | Yes (AI Policy) | AI Advisory Group | Clear role definitions |
| **SA** | â–ˆâ–‘â–‘ Basic | Partial | Office for AI | First state AI Office |
| **NT** | â–ˆâ–‘â–‘ Basic | Yes (Assurance Framework) | AI Advisory Board | Territory-specific principles |
| **TAS** | â–‘â–‘â–‘ Minimal | No | None | Relies on NSW guidance |

---

## New South Wales

### Overview

NSW operates Australia's most mature mandatory government AI governance system, established in March 2022. It was recognised as the one of the first mandatory government AI assurance frameworks.

### Framework Architecture

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚                    NSW AI GOVERNANCE                            â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚                                                                 â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚              NSW AI Ethics Policy                        â”‚   â”‚
â”‚  â”‚         (5 Mandatory Principles)                         â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                           â”‚                                     â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚        NSW AI Assessment Framework (AIAF)                â”‚   â”‚
â”‚  â”‚         (Risk-based lifecycle assessment)                â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                           â”‚                                     â”‚
â”‚         â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                  â”‚
â”‚         â”‚                 â”‚                 â”‚                  â”‚
â”‚         â–¼                 â–¼                 â–¼                  â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”       â”‚
â”‚  â”‚ Low Risk   â”‚   â”‚ Medium Risk â”‚   â”‚ High/Very High  â”‚       â”‚
â”‚  â”‚ Self-assessâ”‚   â”‚ Self-assess â”‚   â”‚ AI Review       â”‚       â”‚
â”‚  â”‚            â”‚   â”‚ + Document  â”‚   â”‚ Committee       â”‚       â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜       â”‚
â”‚                                                                 â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚           Digital Assurance Framework (DAF)              â”‚   â”‚
â”‚  â”‚         (Projects >$5M through DAF process)              â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                                                                 â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

### Key Documents

#### NSW AI Assessment Framework (AIAF)

**Status:** ðŸ”´ Mandatory for all NSW Government agencies

**Purpose:** Risk-based assessment throughout AI lifecycle

**Assessment Process:**
1. Complete self-assessment questionnaire
2. Determine risk rating (Low/Medium/High/Very High)
3. Document outcomes and mitigations
4. Submit high/very high risk to AI Review Committee
5. Ongoing monitoring and reassessment

**Risk Categories:**

| Risk Level | Trigger Criteria | Requirements |
|------------|------------------|--------------|
| **Low** | Limited impact, no personal data | Self-assessment, document |
| **Medium** | Moderate impact, some personal data | Self-assessment, senior sign-off |
| **High** | Significant impact, sensitive decisions | AI Review Committee review |
| **Very High** | Critical impact, automated decisions affecting rights | AI Review Committee + Minister brief |

#### NSW AI Ethics Policy

**Status:** ðŸ”´ Mandatory

**Six Mandatory Principles:**
1. **Community Benefit** - AI must benefit NSW communities
2. **Fairness** - AI must not create or reinforce unfair bias
3. **Privacy and Security** - Protect personal information and systems
4. **Transparency** - Be open about AI use
5. **Accountability** - Clear responsibility for AI outcomes

#### Circular DCS-2024-04

**Status:** ðŸ”´ Mandatory compliance directive

**Requirements:**
- All NSW Government bodies must comply with AIAF
- Regular reporting on AI use
- Risk assessments for all AI projects
- Documentation requirements

#### Cyber Security NSW GenAI Guidance

**Status:** ðŸŸ¢ Guidance

**Practical guidance for public generative AI tools:**

**Do:**
- Use approved tools only
- Be cautious with any data input
- Verify AI outputs
- Report security concerns

**Don't:**
- Input classified or sensitive information
- Use for official decisions without verification
- Share access credentials
- Assume AI outputs are accurate

### Governance Bodies

**AI Review Committee:**
- Reviews high and very high risk AI projects
- Provides expert guidance
- Reports to Digital NSW leadership

**Contact:** Digital.NSW - ai@digital.nsw.gov.au

---

## Victoria

### Overview

Victoria formalised AI governance in November 2024 with mandatory guidelines for the Victorian Public Sector. The framework builds on the strong Victorian Protective Data Security Framework.

### Key Documents

#### Administrative Guideline for Safe and Responsible Use of GenAI in VPS

**Status:** ðŸ”´ Mandatory for all Victorian Public Sector bodies

**Effective:** November 2024

**Key Requirements:**
- Adopts Australia's 8 AI Ethics Principles
- Risk assessment before use
- Human oversight required
- Training for staff
- Incident reporting

**Prohibited Uses:**
- Processing PROTECTED or higher classified information
- Automated decisions affecting individuals without human review
- Use of non-approved AI services for official purposes

#### Victorian Protective Data Security Framework (VPDSF) v2.1

**Status:** ðŸ”´ Mandatory

**AI Relevance:** All 12 mandatory standards apply to AI systems:

| Domain | Standards | AI Application |
|--------|-----------|----------------|
| **Information Security** | 4 standards | Training data, model protection |
| **Physical Security** | 2 standards | AI infrastructure |
| **Personnel Security** | 3 standards | AI system access |
| **ICT Security** | 3 standards | AI deployment, networks |

#### Victorian AI Assurance Framework

**Status:** In development (piloting)

**Approach:** Piloting with Microsoft Copilot deployment before broader rollout.

#### OVIC AI Privacy Guidance

**Status:** ðŸŸ¢ Guidance

**Covers:**
- Privacy obligations under Victorian privacy legislation
- Privacy Impact Assessments for AI
- Collection and use of personal information
- Automated decision-making disclosure

#### Victoria Police AI Ethics Framework

**Status:** ðŸ”´ Mandatory for Victoria Police

**8 Enabling Principles:**
1. Human Rights
2. Human Oversight
3. Transparency
4. Accountability
5. Fairness
6. Privacy
7. Safety and Security
8. Contestability

### Governance Bodies

**In Development:** Victorian AI advisory arrangements being established.

**Contact:** Digital Victoria - digital.victoria@dpc.vic.gov.au

---

## Queensland

### Overview

Queensland has comprehensive mandatory policy with a sophisticated two-part risk assessment framework (FAIRA).

### Framework Architecture

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚                 QUEENSLAND AI GOVERNANCE                        â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚                                                                 â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚              AI Governance Policy                        â”‚   â”‚
â”‚  â”‚           (ISO 38507 aligned)                            â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                           â”‚                                     â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚             FAIRA Framework                              â”‚   â”‚
â”‚  â”‚    â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                â”‚   â”‚
â”‚  â”‚    â”‚   Components    â”‚     Values      â”‚                â”‚   â”‚
â”‚  â”‚    â”‚   Analysis      â”‚   Assessment    â”‚                â”‚   â”‚
â”‚  â”‚    â”‚   (Technical)   â”‚   (Ethical)     â”‚                â”‚   â”‚
â”‚  â”‚    â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”´â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜                â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                           â”‚                                     â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚              IS18 Information Security                   â”‚   â”‚
â”‚  â”‚         (Mandatory ISMS, Essential Eight)                â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                                                                 â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

### Key Documents

#### AI Governance Policy

**Status:** ðŸ”´ Mandatory

**Key Features:**
- ISO 38507 (Governance of IT) aligned
- Integration with Information Security Management System (ISMS)
- Executive accountability requirements
- Regular review and update cycles

#### FAIRA Framework

**Status:** ðŸ”´ Mandatory

**Two-Part Assessment:**

**Part 1: Components Analysis (Technical)**
- Data sources and quality
- Model architecture and training
- Technical security controls
- Integration points
- Monitoring capabilities

**Part 2: Values Assessment (Ethical)**
- Alignment with AI Ethics Principles
- Bias and fairness evaluation
- Transparency requirements
- Human oversight mechanisms
- Community impact

#### IS18 Information and Cyber Security Policy

**Status:** ðŸ”´ Mandatory

**AI-Relevant Requirements:**
- Mandatory ISMS (ISO 27001 based)
- Essential Eight implementation required
- Applies to all AI systems
- Regular security assessments

#### QChat

**Status:** Approved platform

**Queensland's secure GenAI environment:**
- Government-approved
- Built-in governance controls
- Logging and monitoring
- Compliant with IS18

### Governance Bodies

**Queensland Government Chief Information Office (QGCIO):**
- Oversees AI governance
- Maintains FAIRA framework
- Provides guidance and support

**Contact:** QGCIO - qgcio@qld.gov.au

---

## South Australia

### Overview

SA established Australia's first state-level Office for Artificial Intelligence in July 2025, signalling strategic investment in AI governance.

### Key Documents

#### Office for Artificial Intelligence

**Established:** July 2025

**Budget:** $28 million

**Functions:**
- Strategic AI coordination across government
- Policy development
- Capability building
- Industry engagement
- Research partnerships

#### AI Ethics Policy (DTF/P9.1)

**Status:** ðŸ”´ Mandatory

**Covers:**
- Design phase requirements
- Development standards
- Deployment controls
- Operational governance

#### LLM Guideline (DPC/G13.1) v1.3

**Status:** ðŸŸ¢ Optional (recommended)

**Practical controls for generative AI:**
- Input restrictions
- Output verification
- Use case boundaries
- Security considerations

#### South Australian Cyber Security Framework (SACSF) v2.0

**Status:** ðŸ”´ Mandatory

**Structure:**
- 18 policy statements
- 4-tier implementation model
- Applies to AI systems

### Governance Bodies

**Office for Artificial Intelligence:**
- Reports to Department of Premier and Cabinet
- Strategic coordination role

**Contact:** Office for AI - ai@sa.gov.au

---

## Western Australia

### Overview

WA has the most comprehensive framework among smaller jurisdictions, with clear accountability structures and an independent advisory board.

### Framework Architecture

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚                    WA AI GOVERNANCE                             â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚                                                                 â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚           WA Government AI Policy v2                     â”‚   â”‚
â”‚  â”‚     (Mandatory - AI Accountable Officers by Sep 2025)    â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                           â”‚                                     â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚            WA AI Assurance Framework                     â”‚   â”‚
â”‚  â”‚         (Mandatory self-assessment)                      â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                           â”‚                                     â”‚
â”‚         â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”´â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                  â”‚
â”‚         â”‚                                   â”‚                  â”‚
â”‚         â–¼                                   â–¼                  â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”        â”‚
â”‚  â”‚ Low Risk    â”‚                   â”‚ Mid-range+      â”‚        â”‚
â”‚  â”‚ Self-assess â”‚                   â”‚ AI Advisory     â”‚        â”‚
â”‚  â”‚ + Document  â”‚                   â”‚ Board Review    â”‚        â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜                   â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜        â”‚
â”‚                                                                 â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

### Key Documents

#### WA Government AI Policy v2

**Status:** ðŸ”´ Mandatory

**Effective:** July 2025

**Key Requirements:**
- AI Accountable Officers designated by September 2025
- Risk assessment for all AI projects
- Compliance with WA AI Assurance Framework
- Regular reporting

#### WA AI Assurance Framework

**Status:** ðŸ”´ Mandatory

**Process:**
1. Complete self-assessment
2. Determine risk level
3. Document mitigations
4. Mid-range and above to AI Advisory Board
5. Ongoing monitoring

#### WA AI Advisory Board

**Established:** January 2025

**Role:**
- Independent expert review of AI projects
- Guidance on high-risk implementations
- Reports to government

#### WA Health AI Policy (MP 0193/25)

**Status:** ðŸŸ¡ Mandatory for WA Health

**Sector-specific requirements for health AI:**
- Clinical AI governance
- Patient safety requirements
- Data handling for health AI
- Integration with clinical workflows

### Governance Bodies

**WA AI Advisory Board:**
- Independent experts
- Reviews mid-range+ risk projects
- Provides recommendations

**Contact:** Office of Digital Government - digital@dpc.wa.gov.au

---

## Tasmania

### Overview

Tasmania has the least developed AI governance framework, relying primarily on guidance rather than mandatory policy. The jurisdiction recommends using NSW AIAF for detailed assessment.

### Key Documents

#### Guidance for AI Use in Tasmanian Government v1.4

**Status:** ðŸŸ¢ Voluntary

**Content:**
- 7 recommendations for AI use
- References NSW AIAF for detailed guidance
- High-level principles
- Not mandatory

#### Digital Strategy - AI Focus

**Status:** Strategy only

**AI coverage:** Strategic intent; operational framework expected H1 2026.

### Governance Bodies

**None established.**

**Note:** Tasmania acknowledges the gap and recommends NSW AIAF for agencies requiring detailed guidance.

**Contact:** Digital Tasmania - digital@dpac.tas.gov.au

---

## Northern Territory

### Overview

NT has a mandatory framework with six territory-specific AI Ethics Principles developed to reflect NT context.

### Key Documents

#### NT Government AI Assurance Framework

**Status:** ðŸ”´ Mandatory

**Effective:** May 2024

**NT AI Ethics Principles:**
1. **Community Benefit** - AI must benefit NT communities
2. **Safety** - AI must be safe and reliable
3. **Fairness** - AI must not discriminate
4. **Privacy and Security** - Protect data and systems
5. **Transparency** - Be open about AI use
6. **Accountability** - Clear responsibility for AI outcomes

### Governance Bodies

**AI Advisory Board:**
- Reports to ICT Governance Board
- Reviews high-risk assessments

**Contact:** Department of Corporate and Digital Development - digital@nt.gov.au

---

## Australian Capital Territory

### Overview

ACT released a comprehensive mandatory framework in May 2025 with clear role definitions for AI governance.

### Key Documents

#### ACT Government AI Policy v1.0

**Status:** ðŸ”´ Mandatory

**Effective:** May 2025

**Required Officers (per AI initiative):**
1. **AI System Owner** - Accountable executive
2. **AI Administrator** - Operational management
3. **Data Custodian** - Data governance
4. **Project Manager** - Implementation oversight

#### ACT AI Assurance Framework

**Status:** ðŸ”´ Mandatory

**Features:**
- Aligned with National Framework
- Aligned with NSW AIAF
- Risk-based assessment
- Medium/high risk to AIAG

### Governance Bodies

**AI Advisory Group (AIAG):**
- Reviews medium and high risk assessments
- Provides guidance
- Reports to digital leadership

**Contact:** Digital, Data and Technology Solutions - ai@act.gov.au

---

## Cross-Jurisdictional Alignment

### National Framework for AI Assurance in Government

Agreed by Data and Digital Ministers in June 2024, this framework establishes five cornerstones for AI assurance:

| Cornerstone | Description |
|-------------|-------------|
| **Governance** | Clear accountability and oversight |
| **Risk Assessment** | Identify and manage AI risks |
| **Standards** | Adopt relevant standards and principles |
| **Procurement** | Address AI in procurement processes |
| **Assurance Practices** | Ongoing monitoring and review |

### State Framework Comparison

| Feature | NSW | VIC | QLD | SA | WA | TAS | NT | ACT |
|---------|-----|-----|-----|----|----|-----|----|----|
| Mandatory AI policy | âœ… | âœ… | âœ… | âš ï¸ | âœ… | âŒ | âœ… | âœ… |
| Risk assessment framework | âœ… | ðŸ”„ | âœ… | âŒ | âœ… | âŒ | âœ… | âœ… |
| AI Advisory body | âœ… | ðŸ”„ | âœ… | âœ… | âœ… | âŒ | âœ… | âœ… |
| Sector-specific policies | âŒ | âœ… | âŒ | âŒ | âœ… | âŒ | âŒ | âŒ |
| Aligned with National Framework | âœ… | âœ… | âœ… | âœ… | âœ… | âœ… | âœ… | âœ… |

**Legend:** âœ… Yes | âš ï¸ Partial | ðŸ”„ In development | âŒ No

---

## Recommendations by Jurisdiction

### For NSW-based organisations
- Follow AIAF for all AI projects
- Submit high/very high risk to AI Review Committee
- Use Cyber Security NSW guidance for GenAI

### For Victorian organisations
- Comply with GenAI Administrative Guideline
- Apply VPDSF requirements to AI systems
- Watch for AI Assurance Framework release

### For Queensland organisations
- Complete FAIRA assessment (both parts)
- Ensure IS18 compliance for AI systems
- Consider QChat for secure GenAI

### For smaller jurisdictions
- Reference NSW AIAF for detailed guidance
- Apply local mandatory requirements
- Engage with local advisory bodies where available

---

[â† Back to Index](../README.md) | [Federal Frameworks â†’](FEDERAL.md) | [Gap Analysis â†’](GAPS.md)
