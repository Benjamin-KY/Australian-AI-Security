# Gap Analysis: Australian AI Security

> **What's missing from Australia's approach to AI Security**

This analysis identifies critical gaps in Australia's AI security landscape compared to international best practice and emerging threats.

---

## Executive Summary

Australia's AI security framework has significant strengths in technical guidance (ACSC) but critical gaps in mandatory requirements, private sector coverage, and institutional coordination. The National AI Plan's focus on AI Safety over AI Security leaves fundamental adversarial and operational security issues unaddressed.

**Key Gaps:**
1. No mandatory AI security requirements for private sector
2. No systematic risk classification system
3. No AI incident reporting regime
4. No foundation model governance
5. No adversarial testing mandates
6. No consolidated AI Security body
7. Limited integration between safety and security efforts

---

## Gap 1: No Mandatory AI Security for Private Sector

### The Gap

All binding AI security obligations in Australia apply only to:
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

---

## Gap 2: No Systematic Risk Classification

### The Gap

Australia lacks a national AI risk classification system. The September 2024 "Mandatory Guardrails" proposals paper consulted on risk categories but no legislation emerged.

Individual frameworks implement their own tiers:
- NSW AIAF: Low/Medium/High/Very High
- QLD FAIRA: Component + Values assessment
- WA Framework: Self-assessment with mid-range threshold

**No consistent cross-jurisdictional definitions.**

### International Comparison

**EU AI Act Risk Tiers:**

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚                    EU AI ACT RISK PYRAMID                       â”‚
â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚                                                                 â”‚
â”‚                    â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                           â”‚
â”‚                    â”‚  PROHIBITED   â”‚  Banned outright          â”‚
â”‚                    â”‚  (Unacceptableâ”‚  Social scoring,          â”‚
â”‚                    â”‚   Risk)       â”‚  manipulation, etc.       â”‚
â”‚                    â””â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”˜                           â”‚
â”‚                            â”‚                                    â”‚
â”‚                   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”                          â”‚
â”‚                   â”‚   HIGH RISK     â”‚  Strict requirements     â”‚
â”‚                   â”‚                 â”‚  Conformity assessment   â”‚
â”‚                   â”‚  CI, employment,â”‚  Registration            â”‚
â”‚                   â”‚  credit, etc.   â”‚                          â”‚
â”‚                   â””â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”˜                          â”‚
â”‚                            â”‚                                    â”‚
â”‚              â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                     â”‚
â”‚              â”‚      LIMITED RISK         â”‚  Transparency       â”‚
â”‚              â”‚   Chatbots, deepfakes     â”‚  obligations        â”‚
â”‚              â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜                     â”‚
â”‚                            â”‚                                    â”‚
â”‚         â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”                â”‚
â”‚         â”‚           MINIMAL RISK              â”‚  No specific   â”‚
â”‚         â”‚        Most AI applications         â”‚  requirements  â”‚
â”‚         â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜                â”‚
â”‚                                                                 â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

**Australia has no equivalent.**

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

### International Comparison

**EU AI Act GPAI Provisions:**

| Requirement | Standard GPAI | Systemic Risk GPAI |
|-------------|---------------|-------------------|
| Technical documentation | âœ… | âœ… |
| Training data summary | âœ… | âœ… |
| Copyright compliance | âœ… | âœ… |
| Model evaluation | âŒ | âœ… |
| Adversarial testing | âŒ | âœ… |
| Incident reporting | âŒ | âœ… |
| Systemic risk assessment | âŒ | âœ… |

### Impact

- Australian AI developers have no local guidance
- Imported models have no assurance requirements
- Supply chain for AI models is opaque
- Cannot address concentration risks

### Recommendation

Develop GPAI governance framework, potentially through AISI, addressing model documentation, evaluation, and distribution requirements.

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
| **US NIST** | AI RMF recommends; EO 14110 (rescinded) defined red-teaming |
| **Australia** | ISM-1924 detection only; no testing mandate |

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

```
UK Approach (Feb 2025):
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚     AI SECURITY INSTITUTE (AISI)        â”‚
â”‚                                         â”‚
â”‚  â€¢ Frontier AI safety                   â”‚
â”‚  â€¢ Adversarial robustness               â”‚
â”‚  â€¢ National security applications       â”‚
â”‚  â€¢ Cyber threats involving AI           â”‚
â”‚  â€¢ Evaluation and testing               â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜

Australia Approach (Dec 2025):
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚     AI SAFETY INSTITUTE (AISI)          â”‚
â”‚                                         â”‚
â”‚  â€¢ Frontier AI safety                   â”‚
â”‚  â€¢ Alignment research                   â”‚
â”‚  â€¢ Monitoring capabilities              â”‚
â”‚  â€¢ International cooperation            â”‚
â”‚  â€¢ (Security not in mandate)            â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
           +
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚              ACSC                       â”‚
â”‚                                         â”‚
â”‚  â€¢ Cyber security guidance              â”‚
â”‚  â€¢ AI security publications             â”‚
â”‚  â€¢ (Separate from AISI)                 â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

### Impact

- Fragmented approach to AI security
- Gaps between safety and security
- No single point of expertise
- Inefficient resource allocation

### Recommendation

Either expand AISI mandate to explicitly include AI Security, or establish coordination mechanism between AISI and ACSC.

---

## Gap 7: Safety â‰  Security Conflation

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

- AI Security receives no dedicated attention
- AISI mandate excludes adversarial threats
- Technical security work continues in ACSC silo
- No national strategy for AI Security

### Recommendation

Explicitly acknowledge Safety/Security distinction. Ensure AISI mandate includes or coordinates with AI Security work.

---

## Gap 8: Limited Supply Chain Security

### The Gap

ACSC published "AI/ML Supply Chain Risks and Mitigations" (October 2025)â€”Australia's first standalone AI supply chain guidance.

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

Australia's AISI receives $29.9 million, focused on safety research.

**No identified funding stream for AI security research.**

### International Comparison

| Jurisdiction | AI Security Research Investment |
|--------------|--------------------------------|
| **US NSF** | >$700 million annually in AI research (includes security) |
| **UK AISI** | Â£100 million (expanded to security mandate) |
| **Australia AISI** | $29.9 million (safety focus only) |

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
| No private sector requirements | High | High | ðŸ”´ Critical |
| No risk classification | High | Medium | ðŸ”´ Critical |
| Safety/Security conflation | High | Low | ðŸ”´ Critical |
| No adversarial testing mandates | High | Medium | ðŸŸ¡ High |
| No AI incident reporting | Medium | Medium | ðŸŸ¡ High |
| No consolidated AI Security body | Medium | Low | ðŸŸ¡ High |
| No foundation model governance | Medium | High | ðŸŸ¡ High |
| Limited supply chain security | Medium | Medium | ðŸŸ¡ High |
| No workforce strategy | Medium | Medium | ðŸŸ¢ Medium |
| Limited research funding | Low | High | ðŸŸ¢ Medium |

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

Australia's AI security landscape has strong foundations in ACSC technical guidance but critical gaps in mandatory requirements, institutional coordination, and private sector coverage. The National AI Plan's focus on AI Safety leaves AI Security without dedicated national attention.

Closing these gaps requires:
- Recognising Safety â‰  Security
- Extending mandatory requirements beyond government
- Building AI Security institutional capability
- Investing in research and workforce

The conversation on AI Security in Australia needs to get louder.

---

[â† Back to Index](../README.md) | [International Comparison â†’](INTERNATIONAL.md) | [Knowledge Graph â†’](KNOWLEDGE-GRAPH.md)
