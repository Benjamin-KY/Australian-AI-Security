# Gap Analysis: Australian AI Security

> **What's missing from Australia's approach to AI Security**

This analysis identifies critical gaps in Australia's AI security landscape compared to international best practice and emerging threats.

---

## Executive Summary

Australia's AI security framework has significant strengths in technical guidance (ACSC) but critical gaps in mandatory requirements, private sector coverage, and institutional coordination. The National AI Plan (December 2025) decided not to proceed with mandatory guardrails following public consultation, opting instead for voluntary guidance, and its focus on AI Safety over AI Security leaves fundamental adversarial and operational security issues unaddressed.

**Key Gaps:**
1. No cross-sector mandatory AI security requirements for private sector
2. No systematic risk classification system
3. No AI incident reporting regime
4. No foundation model governance
5. No adversarial testing mandates
6. No consolidated AI Security body
7. Limited integration between safety and security efforts

---

## Gap 1: No Cross-Sector Mandatory AI Security for Private Sector

### The Gap

All binding AI security obligations in Australia are sector-specific, applying only to:
- Government entities (ISM, PSPF, DTA Policy)
- Specific regulated sectors (APRA for finance, eSafety for online services)

The private sector operates under **purely voluntary guidance**.

### International Comparison

| Jurisdiction | Private Sector AI Security Requirements |
|--------------|----------------------------------------|
| **EU** | AI Act mandates security for all high-risk AI, any sector |
| **UK** | AI Cyber Security Code of Practice (voluntary but referenced by regulators) |
| **US** | Sector-specific (NIST AI RMF voluntary, but state laws emerging) |
| **Australia** | ACSC guidance voluntary; no general requirements |

### Impact

- Inconsistent security posture across the economy
- Critical infrastructure supply chain includes unsecured AI
- Consumer AI products have no security baseline
- Competitive disadvantage for security-conscious organisations

### Recommendation

Develop mandatory AI security requirements for high-risk AI applications regardless of sector, aligned with international frameworks.

**Government rationale:** The December 2025 National AI Plan explicitly chose a voluntary, principles-based approach following consultation (500+ submissions). The Productivity Commission assessed AI could contribute $115-170 billion to the Australian economy by 2030, and the government concluded premature mandatory regulation could impede this opportunity. Existing sector regulators (APRA, eSafety, TGA, SOCI) already cover the highest-risk AI applications.

---

## Gap 2: No Systematic Risk Classification

### The Gap

Australia lacks a national AI risk classification system. The September 2024 "Mandatory Guardrails" proposals paper consulted on risk categories, but the Government decided not to proceed with mandatory guardrails following public consultation in the December 2025 National AI Plan, opting instead for voluntary AI6 guidance.

Individual frameworks implement their own tiers:
- NSW AIAF: Low/Medium/High/Very High
- QLD FAIRA: Component + Values assessment
- WA Framework: Self-assessment with mid-range threshold

**No consistent cross-jurisdictional definitions.**

### International Comparison

**EU AI Act Risk Tiers:**

| Tier | Description | Examples |
|------|-------------|---------|
| **Prohibited** | Unacceptable risk (banned from Feb 2025) | Social scoring, manipulative AI, predictive policing |
| **High-Risk** | Significant risk (obligations from Aug 2026) | Biometric ID, critical infrastructure, employment |
| **Limited Risk** | Transparency obligations | Chatbots, deepfakes, emotion recognition |
| **Minimal Risk** | No specific obligations | Spam filters, AI-enabled games |

Australia has no equivalent tiered system.

### Impact

- Organisations cannot determine their obligations
- Inconsistent treatment of similar AI applications
- Regulatory uncertainty inhibits investment
- Cross-jurisdictional compliance complexity

### Recommendation

Implement national AI risk classification aligned with EU categories, with clear mapping to security requirements per tier.

---

## Gap 3: No AI Incident Reporting Regime

### The Gap

Australia has:
- SOCI Act: 12/72 hour cyber incident reporting for critical infrastructure
- APRA: 72 hour security incident notification
- No AI-specific incident reporting

AI incidents are only captured if they qualify as a "cyber security incident" under existing frameworks.

**Not captured:**
- AI model failures without cyber cause
- Adversarial attacks that don't breach systems
- AI reliability failures
- Bias incidents discovered post-deployment

### International Comparison

| Jurisdiction | AI Incident Reporting |
|--------------|----------------------|
| **EU AI Act** | Serious incidents to market surveillance authorities (high-risk AI) |
| **US** | Agency-specific; NIST AI RMF recommends incident management |
| **UK** | Sector-specific; AISI monitors frontier model incidents |
| **Australia** | No AI-specific regime |

### Impact

- No visibility of AI incident landscape
- Cannot identify systemic issues
- No early warning system
- Reactive rather than proactive response

### Recommendation

Establish AI incident reporting obligations for high-risk AI, separate from but complementary to cyber incident reporting.

---

## Gap 4: No Foundation Model Governance

### The Gap

Australia has no specific framework for:
- Foundation models
- General-purpose AI (GPAI)
- Large language models
- Frontier AI systems

ISM controls apply to LLM implementation but not to model development, training, or distribution.

**Note:** ACSC published "Frontier Models and Their Impact on Cyber Security" (April 2026), providing defensive guidance but not governance requirements for frontier model providers.

### International Comparison

**EU AI Act GPAI Provisions:**

| Requirement | Standard GPAI | Systemic Risk GPAI |
|-------------|---------------|-------------------|
| Technical documentation |  |  |
| Training data summary |  |  |
| Copyright compliance |  |  |
| Model evaluation |  |  |
| Adversarial testing |  |  |
| Incident reporting |  |  |
| Systemic risk assessment |  |  |

### Impact

- Australian AI developers have no local guidance
- Imported models have no assurance requirements
- Supply chain for AI models is opaque
- Cannot address concentration risks

### Recommendation

Develop GPAI governance framework, potentially through AISI (operational since early 2026), addressing model documentation, evaluation, and distribution requirements.

---

## Gap 5: No Adversarial Testing Mandates

### The Gap

ISM-1924 requires detecting adversarial inputs but:
- No pre-deployment adversarial testing required
- No red-teaming mandates
- No methodology specified
- No third-party testing requirements

### International Comparison

| Jurisdiction | Adversarial Testing Requirements |
|--------------|----------------------------------|
| **EU AI Act Article 55** | Mandatory adversarial testing for GPAI with systemic risk |
| **UK AISI** | Conducts red-teaming; published research on attacks |
| **Singapore** | Project Moonshot open-source red-teaming toolkit |
| **US NIST** | AI RMF recommends; EO 14110 (rescinded Jan 2025; replaced by EO 14179 deregulatory approach) defined red-teaming |
| **Australia** | ISM-1924 detection only; ACSC frontier model guidance (Apr 2026) recommends using AI for vulnerability discovery but no testing mandate |

### Impact

- Unknown vulnerability posture before deployment
- Reactive discovery of weaknesses
- No baseline for AI security maturity
- Cannot benchmark against threats

### Recommendation

Mandate pre-deployment adversarial testing for high-risk AI, with published methodology and reporting requirements.

---

## Gap 6: No Consolidated AI Security Body

### The Gap

Australia's AI security functions are distributed:
- **ACSC/ASD:** Technical guidance, ISM
- **DHA/PSPF:** Protective security policy
- **CISC:** Critical infrastructure
- **DISR/AISI:** AI Safety (not Security)
- **DTA:** Government AI policy

**No single body coordinates AI Security.**

The UK explicitly recognised this gap and **renamed their AI Safety Institute to AI Security Institute** in February 2025.

### International Comparison

| Aspect | UK AI Security Institute (Feb 2025) | Australia AI Safety Institute (Dec 2025) |
|--------|-------------------------------------|------------------------------------------|
| Frontier AI safety | ✅ | ✅ |
| Adversarial robustness | ✅ | ❌ |
| National security applications | ✅ | ❌ |
| Cyber threats involving AI | ✅ | ❌ |
| Evaluation and testing | ✅ | ✅ |
| Alignment research | ✅ | ✅ |
| Monitoring capabilities | ❌ | ✅ |
| International cooperation | ✅ | ✅ |
| Security explicitly in mandate | ✅ | ❌ (security not explicitly in mandate; AISI operational since early 2026) |

**Note:** Australia's ACSC separately handles cyber security guidance and AI security publications.

### Impact

- Fragmented approach to AI security
- Gaps between safety and security
- No single point of expertise
- Inefficient resource allocation

### Recommendation

Either expand AISI mandate to explicitly include AI Security, or establish coordination mechanism between AISI and ACSC.

---

## Gap 7: Safety and Security Conflation

### The Gap

Australia's National AI Plan conflates "security" with general data protection while ignoring technical AI Security.

**AI Safety** concerns:
- Protecting humans from AI
- Alignment with human values
- Unintended consequences
- Bias and fairness

**AI Security** concerns:
- Protecting AI from malicious actors
- Adversarial attacks
- Data poisoning
- Model theft
- Supply chain integrity

**The Plan addresses Safety. It does not address Security.**

### Evidence from National AI Plan

| Term | Appearances | Context |
|------|-------------|---------|
| "Safety" | 47 | AI Safety Institute, safe practices |
| "Security" | 23 | National security (general), data security (general) |
| "Adversarial" | 0 | Not mentioned |
| "Poisoning" | 0 | Not mentioned |
| "Red team" | 0 | Not mentioned |
| "Supply chain" (AI context) | 0 | Not mentioned |

### Impact

- AI-specific security guidance remains distributed across ACSC publications rather than consolidated into a dedicated national AI Security strategy
- AISI mandate excludes adversarial threats
- Technical security work continues in ACSC silo
- No national strategy for AI Security

### Recommendation

Explicitly acknowledge Safety/Security distinction. Ensure AISI mandate includes or coordinates with AI Security work.

---

## Gap 8: Limited Supply Chain Security

### The Gap

ACSC published "AI/ML Supply Chain Risks and Mitigations" (October 2025)—Australia's first standalone AI supply chain guidance.

**However:**
- Voluntary only
- No mandatory supply chain due diligence
- No AI-BOM requirements
- No model provenance obligations

### International Comparison

| Jurisdiction | AI Supply Chain Requirements |
|--------------|------------------------------|
| **EU AI Act** | Article 53 mandates training documentation; downstream provider requirements |
| **US NIST** | AI RMF includes supply chain risk management |
| **UK** | Code of Practice addresses supply chain |
| **Australia** | ACSC guidance (voluntary); no mandatory requirements |

### Impact

- Unknown provenance of deployed models
- Backdoor and poisoning risks unmanaged
- Third-party AI risks not systematically assessed
- Supply chain incidents cannot be traced

### Recommendation

Mandate AI supply chain documentation (AI-BOM) for high-risk applications; require supply chain risk assessment in procurement.

---

## Gap 9: Workforce and Skills

### The Gap

Australia's National AI Plan invests in general AI skills but includes **no AI security workforce strategy**.

**Missing:**
- AI security specialist training
- Security track in AI education
- Professional certification pathway
- Security requirements for AI developers

### International Comparison

| Jurisdiction | AI Security Workforce |
|--------------|----------------------|
| **UK** | Code of Practice mandates security training for AI developers |
| **US** | NSF AI talent initiatives; NIST training resources |
| **Australia** | General AI skills only; no security focus |

### Impact

- Shortage of AI security specialists
- Security not embedded in AI development
- Organisations cannot find qualified staff
- Security becomes afterthought

### Recommendation

Include AI security track in national AI skills strategy; develop professional certification for AI security.

---

## Gap 10: Research Funding

### The Gap

Australia's AISI receives $29.9 million (safety focus; from National AI Plan's total $39.9M AI investment), focused on safety research.

**No publicly identified funding stream dedicated to AI security research.**

### International Comparison

| Jurisdiction | AI Security Research Investment |
|--------------|--------------------------------|
| **US NSF** | >$700 million annually in AI research (includes security) |
| **UK AISI** | £100 million (expanded to security mandate) |
| **Australia AISI** | $29.9 million (safety focus; from National AI Plan's total $39.9M AI investment) |

*Note: Raw funding figures are not directly comparable due to differences in economy size. On a per-capita basis, Australia's AISI funding is approximately $1.15 per person, compared to the UK's approximately £1.50 ($2.90 AUD) per person for AISI, and US NSF AI investment of approximately $2.10 per person.*

### Impact

- Limited domestic AI security research
- Dependent on international findings
- Cannot develop Australian-specific solutions
- Brain drain of AI security researchers

### Recommendation

Establish dedicated AI security research funding stream; include security in AISI research agenda.

---

## Summary: Gap Priority Matrix

| Gap | Impact | Effort to Close | Priority |
|-----|--------|-----------------|----------|
| No private sector requirements | High | High | Critical |
| No risk classification | High | Medium | Critical |
| Safety/Security conflation | High | Low | Critical |
| No adversarial testing mandates | High | Medium | High |
| No AI incident reporting | Medium | Medium | High |
| No consolidated AI Security body | Medium | Low | High |
| No foundation model governance | Medium | High | High |
| Limited supply chain security | High | Medium | High |
| No workforce strategy | Medium | Medium | Medium |
| Limited research funding | Low | High | Medium |

---

## Recommended Actions

### Immediate (0-6 months)

1. **Clarify AISI mandate** to explicitly include or coordinate with AI Security
2. **Publish ISM implementation guidance** for AI controls
3. **Establish ACSC-AISI coordination mechanism**

### Short-term (6-18 months)

4. **Develop national AI risk classification** aligned with EU tiers
5. **Mandate adversarial testing** for government high-risk AI
6. **Establish AI incident reporting** pilot program

### Medium-term (18-36 months)

7. **Legislate AI security requirements** for high-risk private sector AI
8. **Develop foundation model governance** framework
9. **Create AI security professional certification**
10. **Establish AI security research funding** stream

---

## Conclusion

Australia's AI security landscape has strong foundations in ACSC technical guidance but critical gaps in mandatory requirements, institutional coordination, and private sector coverage. The National AI Plan's focus on safety over security leaves many vulnerabilities unaddressed.

Closing these gaps requires:
- Recognising Safety and Security as distinct
- Extending mandatory requirements beyond government
- Building AI Security institutional capability
- Investing in research and workforce

The conversation on AI Security in Australia needs to get louder.

**Note:** This gap analysis focuses on what is missing. Australia's ACSC Five Eyes publications remain among the world's best technical AI security guidance, and the ISM AI controls provide a strong mandatory baseline for government.

---

[Back to Index](../README.md) | [International Comparison →](INTERNATIONAL.md) | [Knowledge Graph →](KNOWLEDGE-GRAPH.md)