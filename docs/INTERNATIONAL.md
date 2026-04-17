# International Comparison: AI Security Frameworks

> **How Australia compares to global AI security approaches**

This document compares Australia's AI security landscape against major international frameworks: the European Union, United Kingdom, United States, Singapore, Canada, and Japan.

---

## Comparison Matrix

| Dimension | 🇦🇺 Australia | 🇪🇺 EU | 🇬🇧 UK | 🇺🇸 US | 🇸🇬 Singapore | 🇨🇦 Canada |
|-----------|--------------|--------|--------|--------|---------------|------------|
| **Binding AI Security Law** | ❌ No | ✅ AI Act | ⚠️ Emerging | ⚠️ State-level | ❌ No | ⚠️ Sector |
| **Risk Classification** | ❌ No | ✅ 4-tier | ⚠️ Principles | ⚠️ NIST RMF | ✅ AI Verify | ⚠️ ADM levels |
| **Adversarial Testing** | ⚠️ Detection only | ✅ Mandatory | ✅ AISI conducts | ⚠️ Recommended | ✅ Moonshot | ❌ No |
| **AI Security Body** | ❌ Fragmented | ⚠️ Distributed | ✅ AISI | ⚠️ NIST/NSA | ✅ IMDA | ❌ No |
| **Supply Chain** | ⚠️ Guidance | ✅ Mandatory | ⚠️ Code | ⚠️ NIST guidance | ⚠️ AI Verify | ❌ No |
| **Foundation Models** | ❌ No | ✅ GPAI rules | ✅ AISI focus | ⚠️ EO (rescinded) | ⚠️ Emerging | ❌ No |
| **Incident Reporting** | ❌ No (AI-specific) | ✅ High-risk AI | ⚠️ Emerging | ⚠️ Sector | ❌ No | ❌ No |
| **Private Sector** | ❌ Voluntary | ✅ All high-risk | ⚠️ Voluntary+ | ⚠️ Mixed | ⚠️ Voluntary+ | ⚠️ Federal only |

**Legend:** ✅ Comprehensive | ⚠️ Partial/Emerging | ❌ Gap

---

## European Union

### EU AI Act

The EU AI Act is the world's first comprehensive, legally binding AI regulation. It entered into force in August 2024 with phased implementation through 2027.

**Key AI Security Provisions:**

#### Article 15: Accuracy, Robustness and Cybersecurity

High-risk AI systems must:
- Achieve appropriate levels of accuracy, robustness, and cybersecurity
- Be resilient against attempts by unauthorised third parties to alter use, outputs or performance
- Address technical solutions for:
  - **Data poisoning**
  - **Model poisoning**
  - **Adversarial examples**
  - **Model flaws**

#### Article 53: GPAI Provider Obligations

General-purpose AI providers must:
- Provide technical documentation
- Make information available to downstream providers
- Document training data (summary)
- Comply with copyright requirements

#### Article 55: Systemic Risk GPAI

GPAI models with systemic risk must additionally:
- Perform model evaluation
- Assess and mitigate systemic risks
- **Conduct adversarial testing**
- Report serious incidents
- Ensure cybersecurity protections

### Enforcement

| Violation | Maximum Penalty |
|-----------|-----------------|
| Prohibited AI practices | €35M or 7% global turnover |
| High-risk non-compliance | €15M or 3% global turnover |
| Incorrect information | €7.5M or 1% global turnover |

### Australia vs EU

| Aspect | Australia | EU |
|--------|-----------|-----|
| Private sector binding requirements | ❌ No | ✅ Yes |
| Risk classification system | ❌ No | ✅ 4-tier |
| Adversarial testing mandate | ❌ No | ✅ Systemic risk GPAI |
| Conformity assessment | ❌ No | ✅ High-risk AI |
| Penalties for non-compliance | ❌ N/A | ✅ Up to 7% turnover |

---

## United Kingdom

### AI Security Institute (AISI)

The UK renamed its AI Safety Institute to the **AI Security Institute** in February 2025, explicitly expanding mandate to include:
- National security applications
- Cyberattacks and fraud
- Adversarial robustness
- Model security evaluation

**Key Activities:**
- Red-teaming of frontier models
- Security evaluation methodology
- Published research on adversarial attacks
- International cooperation

### UK AI Cyber Security Code of Practice

Published January 2025, provides 13 principles across 5 lifecycle phases:

**Lifecycle Phases:**
1. Secure Design
2. Secure Development
3. Secure Deployment
4. Secure Maintenance
5. Secure End-of-Life

**Security Requirements:**
- Security awareness training (regular, risk-based frequency)
- Secure coding training for AI developers
- Threat modelling including AI-specific attacks
- Supply chain security
- Incident response for AI systems

### Australia vs UK

| Aspect | Australia | UK |
|--------|-----------|-----|
| Dedicated AI Security body | ❌ AISI is Safety-focused | ✅ AISI renamed to Security |
| AI Cyber Security Code | ❌ No | ✅ 13 principles, 5 phases |
| Red-teaming capability | ❌ No | ✅ AISI conducts |
| Training requirements | ❌ No | ✅ regular security training |
| Frontier model evaluation | ⚠️ AISI operational | ✅ Active program |

---

## United States

### Federal Landscape

The US approach is fragmented across agencies with sector-specific requirements.

**Key Frameworks:**

#### NIST AI Risk Management Framework (AI RMF 1.0, NIST AI 100-1)

Voluntary framework with four core functions:
1. **Govern** - Cultivate AI risk management culture
2. **Map** - Identify and categorise AI risks
3. **Measure** - Analyse and assess AI risks
4. **Manage** - Prioritise and act on risks

**Security Coverage:**
- "Secure and Resilient" is core trustworthy AI characteristic
- Addresses adversarial robustness
- Supply chain risk management
- Incident management

#### NIST Adversarial Machine Learning Report (NIST AI 100-2e2023)

Comprehensive taxonomy covering:
- **Evasion attacks** - Manipulating inputs to cause misclassification
- **Poisoning attacks** - Corrupting training data
- **Privacy attacks** - Extracting training data or model information
- **Availability attacks** - Denial of service against AI systems

#### NSA AI Security Center

Established to:
- Develop AI security guidance
- Coordinate with Five Eyes partners (including ACSC)
- Focus on national security AI applications
- Co-authored "Deploying AI Systems Securely" (CSI, April 2024) with ACSC

#### DHS AI Guidelines for Critical Infrastructure (DHS, February 2024)

14 February 2024 guidelines categorise three risk areas:
1. Attacks **using** AI
2. Attacks **targeting** AI systems
3. AI **design failures**

### Executive Order 14110 (Rescinded)

The October 2023 Executive Order established AI safety requirements including:
- Red-teaming definitions
- Reporting requirements for dual-use foundation models
- Security standards development

**Note:** EO 14110 was rescinded in January 2025. Impact on AI security requirements ongoing.

**EO 14179 "Removing Barriers to American Leadership in AI" (January 2025)** replaced EO 14110 with a deregulatory approach. The US AI Safety Institute was subsequently renamed to the **Center for AI Standards and Innovation (CAISI)** in June 2025. The Trump administration released legislative recommendations in March 2026 seeking to preempt state AI laws with a "minimally burdensome" federal framework.

### Australia vs US

| Aspect | Australia | US |
|--------|-----------|-----|
| Risk management framework | ❌ No | ✅ NIST AI RMF |
| Adversarial ML taxonomy | ❌ No | ✅ NIST AI 100-2 |
| AI security research | Limited | ✅ >$700M annually (NSF) |
| CI AI guidelines | ⚠️ CISC factsheet | ✅ DHS comprehensive |
| Five Eyes coordination | ✅ Via ACSC | ✅ NSA AISC |

---

## Singapore

### National AI Strategy 2.0

Singapore's updated AI strategy emphasises trusted AI with practical implementation tools.

**Key Initiatives:**

#### AI Verify

World's first AI governance testing framework:
- Self-assessment tool
- Technical testing
- Maps to international standards (ISO/IEC 42001)
- Process-based and technical checks

**Testing Areas:**
- Transparency
- Fairness
- Robustness
- Accountability
- Data governance

#### Project Moonshot

World's first open-source LLM red-teaming toolkit:
- Automated testing
- Manual adversarial testing
- Jailbreak detection
- Prompt injection testing
- Benchmark against attack libraries

**Freely available:** [github.com/aiverify-foundation/moonshot](https://github.com/aiverify-foundation/moonshot)

#### Model AI Governance Framework

Practical guidance for:
- Internal governance
- Human oversight
- Operations management
- Stakeholder communication

### Australia vs Singapore

| Aspect | Australia | Singapore |
|--------|-----------|-----------|
| AI governance tool | ❌ No | ✅ AI Verify |
| Red-teaming toolkit | ❌ No | ✅ Project Moonshot (open source) |
| Model governance framework | ⚠️ NAIC guidance | ✅ Comprehensive framework |
| Testing/certification | ❌ No | ✅ AI Verify self-assessment |
| International standards alignment | ⚠️ References | ✅ Maps to ISO 42001 |

---

## Canada

### Federal Approach

#### Directive on Automated Decision-Making

Mandatory for all federal government AI:

**Impact Assessment Levels:**
| Level | Impact | Requirements |
|-------|--------|--------------|
| Level I | Little to no | Basic documentation |
| Level II | Moderate | Peer review, testing |
| Level III | High | Expert review, public notice |
| Level IV | Very High | Full review, legal compliance |

**Security Requirements:**
- Security assessments during development
- Measures to secure data and model integrity
- Prevention of tampering and unauthorised modifications
- Regular testing and monitoring

#### Algorithmic Impact Assessment Tool

Public tool for assessing AI systems:
- 106 questions
- Generates impact level
- Identifies mitigation requirements

### Australia vs Canada

| Aspect | Australia | Canada |
|--------|-----------|--------|
| Government AI mandate | ✅ DTA Policy | ✅ ADM Directive |
| Impact assessment tool | ❌ No | ✅ AIA Tool |
| Security in AI directive | ⚠️ General reference | ✅ Explicit requirements |
| Tamper prevention | ❌ Not specified | ✅ Required |
| Public transparency | ⚠️ DTA transparency statements | ✅ Mandatory for Level III+ |

---

## Japan

### AI Safety Institute (Japan AISI)

Established 14 February 2024, Japan's AISI focuses on:
- AI safety evaluation
- Evaluation methodology development
- International cooperation

**Published:**
- AI Safety Evaluation Perspectives v1.01
- Guidelines for AI development
- Testing methodology

### AI Security Coverage

Japan AISI evaluation perspectives include:
- Robustness against adversarial inputs
- Security of AI systems
- Privacy protection
- Misuse prevention

### Australia vs Japan

| Aspect | Australia | Japan |
|--------|-----------|-------|
| Safety Institute | ✅ AISI (operational early 2026) | ✅ AISI (operational) |
| Evaluation methodology | ❌ Not published | ✅ Published v1.01 |
| Adversarial robustness | ⚠️ ISM control | ✅ In evaluation framework |
| International cooperation | ✅ INASI member | ✅ INASI member |

---

## China

### Regulatory Landscape

China has binding AI regulations that predate the EU AI Act:

| Regulation | Date | Scope |
|------------|------|-------|
| **Algorithmic Recommendation Provisions** | Mar 2022 | Algorithmic transparency, user opt-out |
| **Deep Synthesis Provisions** | Jan 2023 | Deepfakes, synthetic media labelling |
| **Interim Measures for Generative AI** | Aug 2023 | Content review, training data compliance, watermarking |

**Key difference from Australia:** China has mandatory, enforceable AI regulations covering the private sector. Australia has no equivalent.

**Important context:** China's AI regulations serve fundamentally different governance objectives, including content control and political censorship. The regulatory framework is embedded in an authoritarian governance model not comparable to liberal democracies. However, the technical regulatory mechanisms (registration, impact assessment, transparency requirements) offer useful comparison points.

---

## International Network for Advanced AI Measurement, Evaluation and Science

Australia is a member of INASI, connecting with peer institutes:

**Members:**
- 🇬🇧 UK AISI (AI Security Institute)
- 🇺🇸 US CAISI (formerly AISI)
- 🇯🇵 Japan AISI
- 🇰🇷 Korea AISI
- 🇫🇷 France AISI
- 🇨🇦 Canada AISI
- 🇸🇬 Singapore (observer)
- 🇦🇺 Australia AISI (member)
- 🇪🇺 EU AI Office (observer)

**Focus Areas:**
- Frontier AI safety
- Evaluation methodology sharing
- Joint research
- Information sharing on risks

**Note:** Network focuses on AI Safety; AI Security coordination varies by member.

---

## Key Lessons for Australia

### From EU
- **Lesson:** Mandatory requirements drive compliance
- **Action:** Consider binding AI security requirements for high-risk AI

### From UK
- **Lesson:** Safety and Security need unified approach
- **Action:** Expand AISI mandate or rename to Security Institute

### From Singapore
- **Lesson:** Practical tools enable adoption
- **Action:** Develop Australian AI security assessment toolkit

### From US
- **Lesson:** Comprehensive taxonomy enables understanding
- **Action:** Adopt or develop Australian adversarial ML framework

### From Canada
- **Lesson:** Government can lead by example
- **Action:** Strengthen DTA policy with explicit security requirements

---

## Standards Alignment

### ISO/IEC Standards

| Standard | Description | Australia Status |
|----------|-------------|------------------|
| ISO/IEC 42001:2023 | AI Management Systems | Referenced, not mandated |
| ISO/IEC 23894:2023 | AI Risk Management | Referenced |
| ISO/IEC 27001:2022 | Information Security Management | ISM aligns |
| ISO/IEC 27701:2019 | Privacy Information Management | OAIC references |

### Emerging and Recently Published Standards

| Standard | Description | Status |
|----------|-------------|--------|
| ISO/IEC 27090:2024 | AI Cybersecurity Guidelines | **Published December 2024** |
| ISO/IEC 24029-1:2021 | AI Robustness — Part 1: Overview | **Published** |
| ISO/IEC 24029-2:2023 | AI Robustness — Part 2: Formal Methods | **Published** |
| IEEE 2841 | Framework and Process for Deep Learning Evaluation | In development |

### International Treaties

| Treaty | Date | Australia Status |
|--------|------|-----------------|
| **Council of Europe Framework Convention on AI** | Adopted May 2024, open for signature Sep 2024 | Not yet signed |
| **Bletchley Declaration on AI Safety** | Nov 2023 | Signatory |
| **Seoul Declaration on AI Safety** | May 2024 | Signatory |

---

## Conclusion

Australia's AI security approach has strengths in technical guidance (ACSC) and government policy (ISM, PSPF), but lags international peers in:

1. **Mandatory private sector requirements** (EU leads)
2. **Unified Safety/Security approach** (UK leads)
3. **Practical assessment tools** (Singapore leads)
4. **Adversarial ML framework** (US leads)
5. **Government AI security requirements** (Canada leads)

Closing these gaps requires learning from international approaches while adapting to Australian context.

---

[← Back to Index](../README.md) | [Gap Analysis →](GAPS.md) | [Knowledge Graph →](KNOWLEDGE-GRAPH.md)
