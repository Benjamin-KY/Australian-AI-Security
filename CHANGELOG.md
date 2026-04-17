# Changelog

All notable changes to the Australian AI Security Framework Index will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [Unreleased]

### Planned for v1.2.0

- [ ] JSON data files for knowledge graph construction
- [ ] Compliance checklist templates
- [ ] ISM AI control implementation guidance
- [ ] State framework update tracker
- [ ] RSS feed for document updates

### Planned for v2.0.0

- [ ] Interactive knowledge graph visualisation
- [ ] Searchable document database
- [ ] Compliance mapping tool
- [ ] API for programmatic access

---

## [1.1.0] - 2026-04-17

### Fixed

**Comprehensive audit and update (67 issues resolved):**

**Critical Corrections:**
- OWASP Top 10 for LLM: Updated from v1.0 (2023) to v2.0 (2025) list
- NSW AI Ethics Policy: Added missing 6th principle (Reliability and Safety)
- AISI status: Harmonised across all documents (operational early 2026, $29.9M)
- ISO/IEC 27090: Corrected from "In development" to "Published December 2024"
- Removed unverifiable ACSC advisory entries (2024-003, 2024-007, 2025-002)
- Fixed broken #changelog anchor in README
- Fixed malformed markdown table in KNOWLEDGE-GRAPH.md
- Corrected INVENTORY document count totals
- Document count reduced from 75+ to 68: removed 3 unverifiable advisory entries, deduplicated cross-listed documents, recounted against actual inventory entries

**Content Updates (reflecting April 2026 reality):**
- Privacy Act reform: Added Privacy and Other Legislation Amendment Act 2024
- Mandatory guardrails: Noted government decision not to proceed with mandatory guardrails following public consultation in Dec 2025 National AI Plan
- EU AI Act: Updated phased implementation timeline (prohibitions Feb 2025, GPAI Aug 2025)
- US policy: Added EO 14179, CAISI rename, deregulatory shift
- SOCI Act: Noted active Mar 2026 consultation on CIRMP rules
- International network: Updated name to "International Network for Advanced AI Measurement, Evaluation and Science"
- Added Privacy Act, AI Ethics Framework, and missing international frameworks

**Structural Improvements:**
- Replaced corruption artifact placeholders in STATES.md with diagram cross-references
- Removed placeholder text ("[Architecture diagram removed for corruption artifacts]")
- Added accessibility attributes to SVG diagrams
- Compressed Header.png from 6.4MB to optimised size

---

## [1.0.1] - 2025-12-07

### Fixed

**Comprehensive fact-check corrections based on verification of 85+ claims:**

**Federal Framework Corrections:**
- ACSC "Engaging with AI" date: March 2025 → January 2024
- Removed non-existent "Mitigating Strategies for AI Threats" document
- ISM-1924 wording: "detect and block" → "detect and mitigate" (per official control text)
- PSPF Release 2025 date: October 2025 → July 2025
- PSPF Policy Advisory 001-2025 date: February 2025 → October 2025
- Removed GOVSEC-14 reference (does not exist in federal PSPF; state/territory nomenclature)
- DTA Chief AI Officers deadline: July 2025 → by end of 2026
- eSafety Industry Standards date: June 2025 → June 2024 (effective December 2024)

**State/Territory Framework Corrections:**
- NSW: Changed "world's first" to "one of the first" mandatory government AI framework
- Victoria Police AI Ethics Framework date: 2023 → March 2024
- SA Office for AI establishment: November 2025 → July 2025
- NT AI Ethics Principles count: 5 → 6 principles (added Accountability)

**International Framework Corrections:**
- EU AI Act penalty rate: 1.5% → 1% for misleading information tier
- UK: Removed "6-monthly" training claim; corrected to "regular" risk-based training
- Canada AIA Tool question count: 48 → 106 questions (65 risk + 41 mitigation)
- Japan AISI establishment: April 2024 → 14 February 2024

**Structural Corrections:**
- Document count: 65+ → 75+ (verified total across all sources)

### Verified (No Changes Required)
- UK AI Safety Institute rename to AI Security Institute (14 February 2025) ✓
- National AI Plan release date (2 December 2025) ✓
- AISI funding ($29.9 million) ✓
- All EU AI Act article references (15, 53, 55) ✓
- SOCI Act incident reporting timeframes (12/72 hours) ✓
- All NSW AIAF details including AI Review Committee ✓

---

## [1.0.0] - 2025-12-06

### Added

**Initial Release**

- Complete inventory of 75+ Australian AI security documents
- Federal frameworks documentation (ACSC, ISM, PSPF, SOCI, DTA, DISR, sector regulators)
- State and territory frameworks (NSW, VIC, QLD, SA, WA, TAS, NT, ACT)
- International comparison (EU, UK, US, Singapore, Canada, Japan)
- Gap analysis identifying 10 critical gaps in Australia's approach
- Knowledge graph documentation with Mermaid diagrams
- Compliance pathway visualisations
- Entity relationship model for graph database construction

**Documents Indexed:**
- 13 ACSC/ASD documents
- 6 PSPF/DHA documents
- 5 DTA documents
- 5 DISR/NAIC documents
- 12 Sector regulator documents
- 6 NSW documents
- 6 Victoria documents
- 5 Queensland documents
- 3 South Australia documents
- 5 Western Australia documents
- 2 Tasmania documents
- 1 Northern Territory document
- 2 ACT documents
- Cross-jurisdictional frameworks

**Analysis:**
- Safety vs Security distinction documented
- Australia vs international comparison across 8 dimensions
- Gap priority matrix with recommendations
- Compliance pathways for Commonwealth entities, CI owners, private sector

---

## Document Update Log

Track when key documents are updated:

| Document | Current Version | Last Checked | Notes |
|----------|-----------------|--------------|-------|
| ISM | September 2025 | 2026-04-17 | AI controls current |
| PSPF | 2025 Release | 2026-04-17 | AI provisions added |
| DTA AI Policy | v2.0 | 2026-04-17 | Current |
| NSW AIAF | 2022 | 2026-04-17 | Check for updates |
| VIC GenAI Guideline | Nov 2024 | 2026-04-17 | Current |
| QLD AI Governance | Sep 2024 | 2026-04-17 | Current |
| WA AI Policy | v2 Jul 2025 | 2026-04-17 | Current |
| National AI Plan | Dec 2025 | 2026-04-17 | Just released |

---

## How to Report Changes

Found a document update we've missed?

1. Check the [Issues](../../issues) for existing reports
2. Create a new issue with `document-update` label
3. Include:
   - Document name
   - New version/date
   - Link to updated document
   - Summary of changes (if known)

---

## Version Numbering

- **Major (X.0.0)**: Significant structural changes, major new sections
- **Minor (0.X.0)**: New documents, expanded analysis, new features
- **Patch (0.0.X)**: Corrections, broken links, minor updates

---

[View all releases](../../releases)
