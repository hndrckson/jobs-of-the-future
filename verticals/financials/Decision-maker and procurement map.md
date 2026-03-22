# Decision-Maker and Procurement Map for PQC in Financial Services

## Strategic Intelligence Brief — March 2026

---

## Executive Summary

Selling PQC solutions to banks requires navigating one of the most complex procurement environments in any industry. Unlike tech companies where a CISO can sign a six-figure deal with a credit card, banks have multi-layered governance, vendor management requirements, regulatory oversight of technology purchases, and procurement cycles that routinely stretch 6–18 months. Understanding the decision-making topology is a prerequisite for market entry — the best technology loses to the best-connected competitor every time in financial services.

**Key insight**: PQC is unusual in that it sits at the intersection of *cybersecurity* (CISO domain), *risk management* (CRO domain), *technology architecture* (CTO domain), and *regulatory compliance* (CCO domain). This means the buying process involves more stakeholders than a typical security tool purchase, but it also means there are more entry points.

---

## The Decision-Making Hierarchy

### Tier 1: Strategic Decision (Board + C-Suite)

For PQC — a multi-year, enterprise-wide cryptographic transformation — the initial decision to pursue migration is a **strategic decision** that requires board-level awareness and C-suite sponsorship. This is not a tool purchase; it's a security architecture transformation.

| Role | Influence on PQC Decision | What They Care About |
|------|--------------------------|---------------------|
| **Board Risk Committee** | Final authority on risk appetite and major investment | Regulatory expectations, systemic risk, peer actions, fiduciary duty |
| **CEO** | Sets strategic priority; allocates executive attention | Business risk, regulatory relationship, competitive positioning |
| **CRO (Chief Risk Officer)** | Frames quantum as enterprise risk; influences timeline | Risk quantification, regulatory posture, scenario analysis |
| **CIO/CTO** | Owns technology architecture; controls implementation budget | Feasibility, integration complexity, vendor ecosystem, architecture impact |
| **CISO** | Champions security need; drives technical requirements | Threat landscape, HNDL risk, crypto inventory, compliance gaps |
| **CCO (Chief Compliance Officer)** | Validates regulatory drivers; ensures examination readiness | Examiner expectations, regulatory trajectory, documentation requirements |
| **CFO** | Controls budget approval; demands ROI justification | Total cost, phasing, ROI/risk-reduction quantification |

### The Decision Flow for PQC

```
AWARENESS PHASE
Board Risk Committee ← Fed/OCC examiner questions about quantum risk
CEO ← Board direction to assess quantum readiness
    ↓
ASSESSMENT PHASE
CRO ← Enterprise risk assessment incorporating quantum threat
CISO ← Cryptographic inventory and vulnerability assessment
CIO/CTO ← Architecture impact assessment
CCO ← Regulatory gap analysis
    ↓
STRATEGY PHASE
CISO + CTO jointly ← PQC migration roadmap and vendor requirements
CFO ← Budget request and phasing
Board ← Approval of multi-year migration program
    ↓
PROCUREMENT PHASE
CISO ← Technical requirements and vendor shortlist
CTO ← Architecture compatibility validation
Vendor Management/Procurement ← RFP, due diligence, contracting
    ↓
IMPLEMENTATION
CISO + CTO ← POC, pilot, production rollout
```

### Where PQC Differs from Normal Security Purchases

| Dimension | Normal Security Tool | PQC Migration |
|-----------|---------------------|--------------|
| **Decision level** | CISO with CIO approval | Board-level strategic initiative |
| **Budget** | Single line item ($500K–$5M) | Multi-year program ($5M–$50M+) |
| **Stakeholders** | CISO, CTO, procurement | CISO, CTO, CRO, CCO, CFO, Board |
| **Regulatory driver** | Specific compliance requirement | Evolving examiner expectations |
| **Timeline** | 3–6 month procurement cycle | 12–24 month initial procurement, multi-year program |
| **Success metric** | Threat prevention, compliance checkbox | Enterprise cryptographic transformation |

---

## Detailed Buyer Personas

### The CISO — Primary Champion

**Title variations**: Chief Information Security Officer, SVP Information Security, Head of Cybersecurity, Global CISO

**Reporting structure at banks**:
- ~33% report to CIO/CTO (limits budget independence)
- ~20% report to CRO (growing in financial services — aligns with risk framing)
- ~7% report to CEO (strongest position, but uncommon)
- Increasingly has dotted line to Board Risk/Technology Committee

**Budget authority**:
- Average cybersecurity budget in financial services: 10–15% of IT spend
- For a large bank with $3–5B IT budget: $300M–$750M cybersecurity allocation
- CISO typically has direct authority over purchases up to $500K–$2M
- Above that threshold: requires CIO/CTO or C-suite approval
- Above $5–10M: board-level approval usually required

**What the CISO wants from a PQC vendor**:
- Clear technical roadmap aligned with NIST standards
- Crypto inventory and discovery capabilities (immediate need)
- Minimal operational disruption during migration
- Compliance documentation mapping to FFIEC, OCC, SEC expectations
- Peer references (other bank CISOs who've deployed)
- Vendor viability — will you exist in 5 years?

**Pain points**:
- Budget competition with AI/ML security, cloud security, zero trust — PQC competes for the same dollars
- "Crypto-procrastination" — difficulty justifying urgency for a threat without a clear date
- Talent shortage — few crypto engineers on staff
- Vendor sprawl — already managing 40–60+ security tools; resistance to adding another

**How to engage**: Through CISO peer networks (FS-ISAC, Evanta CISO summits), threat briefings, regulatory risk framing. **Do not lead with product; lead with intelligence.**

### The CRO — Strategic Sponsor

**Why CRO matters for PQC**: The CRO owns enterprise risk management and increasingly oversees cyber risk as a category. For PQC specifically, the CRO is critical because:
- They frame risks in language the board understands (probability × impact)
- They control the risk appetite statement, which determines how aggressively the bank must respond to quantum threats
- CISO-CRO collaboration is increasingly required for major cyber initiatives

**What the CRO wants**:
- Quantified risk exposure (dollar value of HNDL exposure)
- Scenario analysis (what happens if Q-Day arrives in 2030 vs. 2035)
- Peer benchmarking (what are other G-SIBs doing?)
- Regulatory defensibility (can we demonstrate diligence to examiners?)

**How to engage**: Through risk quantification frameworks, board-ready risk assessments, regulatory trajectory analysis (i.e., documents like this one).

### The CTO/CIO — Architecture Gatekeeper

**Why CTO/CIO matters**: They control the technology architecture and the implementation budget. A PQC solution that doesn't fit the existing architecture won't get deployed regardless of CISO enthusiasm.

**What the CTO/CIO wants**:
- Architecture compatibility (works with existing PKI, HSMs, key management)
- Crypto agility (can swap algorithms without re-architecting)
- Performance impact data (latency, throughput, key sizes)
- Integration with existing vendor ecosystem (IBM, Microsoft, AWS, etc.)
- Migration path that doesn't require forklift upgrades

**Blockers they control**:
- Technology standards approval
- Architecture review board sign-off
- Integration testing requirements
- Performance benchmarking gates

### The CCO — Regulatory Validator

**Why CCO matters**: They determine whether PQC rises to a "regulatory requirement" vs. "nice to have." Their assessment of examiner expectations directly influences board urgency.

**What the CCO wants**:
- Clear mapping of PQC to existing regulatory requirements
- Gap analysis against current examination expectations
- Timeline alignment with examination cycle
- Documentation that can be presented to examiners

---

## The Procurement Process — Step by Step

### Phase 1: Need Identification (1–3 months)

**Activities**:
- CISO identifies quantum/PQC as priority based on threat intelligence, regulatory signals, or examiner questions
- Internal risk assessment conducted (often with consulting support)
- Cryptographic inventory initiated
- Business case developed for CTO/CIO and CFO review

**Vendor opportunity**: Advisory services, cryptographic discovery/inventory tools. This is where the sale *starts*.

### Phase 2: Requirements Definition (2–4 months)

**Activities**:
- Cross-functional team formed (CISO, CTO, CRO, CCO representatives)
- Technical requirements document created
- Procurement/vendor management team engaged
- Market scan conducted (vendor landscape assessment)

**Vendor opportunity**: Shape requirements through thought leadership, technical workshops, and reference architecture discussions. **Banks that talk to vendors during requirements definition are 3x more likely to include those vendors on the shortlist.**

### Phase 3: RFP and Evaluation (3–6 months)

**Activities**:
- Formal RFP issued (or sole-source justification for smaller purchases)
- Vendor responses evaluated (technical, commercial, risk)
- Vendor due diligence (financial stability, SOC 2, ISO 27001, references)
- Shortlist created (typically 2–4 vendors)

**Vendor management requirements at large banks**:
- SOC 2 Type II report
- ISO 27001 certification (or equivalent)
- Financial stability assessment (Dun & Bradstreet, revenue verification)
- Business continuity/disaster recovery plan
- Data handling and privacy assessment
- Subcontractor/fourth-party risk assessment
- Annual penetration testing results
- Cyber insurance verification

**Critical gate**: Many large banks maintain **approved vendor lists**. Getting on the list can take 6–12 months *before* any product evaluation begins. Some banks require existing vendor relationship as a prerequisite.

### Phase 4: Proof of Concept (2–4 months)

**Activities**:
- POC scope defined with specific success criteria
- Test environment provisioned
- Solution deployed in controlled setting
- Performance, integration, and security testing
- Results documented and presented to evaluation committee

**What banks expect from a POC**:
- **Realistic environment**: Not a vendor-controlled demo, but deployment in the bank's actual (or realistic replica) infrastructure
- **Defined success metrics**: Latency impact <X ms, key generation time <Y, integration with existing HSMs confirmed, etc.
- **Attack simulation**: Demonstrate protection against defined threat scenarios
- **Compliance validation**: Show how the solution meets specific regulatory requirements
- **Rollback capability**: Demonstrate that the solution can be removed cleanly if needed
- **Scale testing**: Prove performance at production volume, not just lab scale

**Common POC killers**:
- Performance degradation beyond acceptable thresholds
- Integration failures with bank-specific infrastructure
- Lack of FIPS 140-3 validation (or clear path to it)
- Vendor inability to support the bank's specific HSM and PKI environment
- Insufficient documentation for the bank's compliance team

### Phase 5: Contracting and Compliance (2–4 months)

**Activities**:
- Commercial negotiation (pricing, licensing, SLAs)
- Legal review (data handling, liability, IP rights)
- Compliance and regulatory review
- Vendor risk assessment finalized
- Contract execution

**Typical contract terms at banks**:
- Multi-year agreements preferred (3–5 years) for stability
- Annual true-up or consumption-based pricing
- SLAs with financial penalties for downtime
- Right to audit vendor security controls
- Data residency and sovereignty requirements
- Escrow requirements for source code (for critical infrastructure)
- Regulatory cooperation clauses (vendor must support examination)

### Phase 6: Implementation (6–24 months)

**Activities**:
- Phased deployment starting with lowest-risk systems
- Integration with existing security infrastructure
- Staff training and knowledge transfer
- Continuous monitoring and optimization
- Expansion to additional use cases

---

## Total Procurement Timeline

| Phase | Duration | Cumulative |
|-------|----------|-----------|
| Need identification | 1–3 months | 1–3 months |
| Requirements definition | 2–4 months | 3–7 months |
| RFP and evaluation | 3–6 months | 6–13 months |
| Proof of concept | 2–4 months | 8–17 months |
| Contracting | 2–4 months | 10–21 months |
| **Total to contract** | | **10–21 months** |
| Implementation (Phase 1) | 6–12 months | 16–33 months |

**Reality check**: For a brand-new PQC vendor selling into a Tier 1 bank with no prior relationship, expect **18–24 months from first conversation to signed contract**, and **24–36 months to production deployment**. This timeline can be compressed to 12–18 months with an existing vendor relationship or a compelling regulatory trigger.

---

## Budget Decision Cycles

### Annual Budget Cycle (Most Banks)

| Month | Activity | PQC Implication |
|-------|----------|----------------|
| **Jun–Aug** | Strategic planning; IT and security priorities identified | PQC must be on the priority list by June |
| **Sep–Oct** | Budget proposals submitted by CISO to CIO/CFO | PQC budget request must be in this cycle |
| **Nov–Dec** | Board approval of annual budget | PQC funding confirmed or deferred |
| **Jan–Mar** | New fiscal year; procurement begins | RFPs can be issued |
| **Apr–Jun** | Mid-year reviews; reallocation possible | Opportunity for unplanned PQC spend if triggered by exam findings |

**Key insight**: If a bank doesn't include PQC in its 2027 budget cycle (planning starts mid-2026), the earliest it can begin meaningful PQC procurement is 2028 — which puts it behind the regulatory trajectory curve.

### How to Enter the Budget Cycle

1. **Regulatory trigger**: Examiner questions about quantum risk create urgency that can force mid-cycle budget allocation
2. **Peer pressure**: "JPMorgan and HSBC have already deployed PQC pilots" is a powerful argument for inclusion in next year's budget
3. **Risk quantification**: Presenting a quantified HNDL exposure assessment (see companion document) creates a measurable risk gap that demands budget response
4. **Attached to existing initiative**: Position PQC as an extension of an existing crypto modernization, PKI upgrade, or HSM refresh project that already has budget

---

## Navigating Bank Vendor Management

### Getting on the Approved Vendor List

Large banks maintain approved vendor lists that are prerequisites for any procurement. To get listed:

1. **SOC 2 Type II**: Non-negotiable. Must be current (within 12 months)
2. **Financial stability**: Banks assess vendor viability — small startups face scrutiny. Revenue >$10M helps; >$50M significantly reduces friction
3. **Insurance**: Cyber liability insurance, errors & omissions, general liability
4. **References**: Ideally from other financial institutions. A reference from a peer bank is worth more than 10 non-bank references
5. **Data handling**: Clear data classification, processing, and residency documentation
6. **Business continuity**: Documented BCP/DR with tested failover

### The Reference Requirement Problem

Banks strongly prefer references from other banks. This creates a classic chicken-and-egg problem for new PQC vendors:
- Bank A won't buy without a bank reference
- You can't get a bank reference without Bank A buying

**Breaking the cycle**:
- Start with a bank that is culturally open to innovation (e.g., innovation lab, fintech partnerships)
- Offer a deeply discounted or free pilot program to establish the reference
- Leverage non-bank but highly regulated references (defense, healthcare)
- Use industry partnerships (FS-ISAC working groups, NIST NCCoE collaboration) to build credibility
- Partner with an established bank vendor (IBM, Thales, Entrust) who can provide the relationship and reference umbrella

---

## Multi-Entry Strategy

Given the multi-stakeholder buying process, successful PQC vendors should pursue multiple entry points simultaneously:

### Entry Point 1: CISO — Bottom-Up (Technical Champion)

- **Approach**: Threat intelligence briefings, HNDL risk quantification, technical workshops
- **Tool**: Cryptographic discovery/inventory (immediate need, low-risk purchase, under CISO budget authority)
- **Expansion**: From discovery → assessment → migration planning → implementation
- **Timeline**: 6–12 months to initial tool purchase; 12–24 months to program-level engagement

### Entry Point 2: CRO — Top-Down (Risk Framing)

- **Approach**: Board-ready quantum risk assessment, regulatory trajectory briefing, peer benchmarking
- **Tool**: Risk quantification framework / consulting engagement
- **Expansion**: Risk assessment creates urgency → budget allocation → technology procurement
- **Timeline**: 3–6 months for advisory engagement; influences next budget cycle (6–18 months)

### Entry Point 3: CTO/CIO — Architecture Play

- **Approach**: Crypto agility architecture workshop, HSM/PKI modernization alignment
- **Tool**: Crypto agility platform that fits existing architecture
- **Expansion**: Architecture approval opens door for enterprise-wide deployment
- **Timeline**: 6–12 months for architecture review; 12–18 months for deployment

### Entry Point 4: CCO — Regulatory Compliance

- **Approach**: Examination preparation support, regulatory gap analysis, compliance documentation
- **Tool**: Compliance mapping and documentation tools
- **Expansion**: Compliance need creates procurement justification for technical solutions
- **Timeline**: Aligned with examination cycle (varies, but 3–12 months to next exam)

---

## Sources and References

- [Cybersecurity Budget Benchmarks 2025 — Elisity](https://www.elisity.com/blog/cybersecurity-budget-benchmarks-for-2025-essential-planning-guide-for-enterprise-cisos)
- [Cybersecurity Budget Benchmarks 2026 — Elisity](https://www.elisity.com/blog/cybersecurity-budget-benchmarks-for-2026-essential-planning-guide-for-enterprise-security-leaders)
- [Cyber Budget Wars: CFOs Steering Security Strategy — Intelligent CISO](https://www.intelligentciso.com/2025/10/28/cyber-budget-wars-why-cfos-are-now-steering-security-strategy/)
- [CISO Budget Priorities 2025 — Forrester via VentureBeat](https://venturebeat.com/security/forresters-ciso-budget-priorities-for-2025-focus-on-api-supply-chain-security/)
- [2025 CISO Leadership Perspectives — Evanta](https://www.evanta.com/resources/ciso/infographic/2025-ciso-leadership-perspectives)
- [CISO Reporting Structure — TechTarget](https://www.techtarget.com/searchsecurity/tip/Why-the-ideal-CISO-reporting-structure-is-highest-level)
- [CIO vs CISO vs CEO: Reporting Structures — BitSight](https://www.bitsight.com/blog/cio-vs-ciso)
- [CISO-CRO Join Forces — Aon](https://www.aon.com/en/insights/articles/for-cyber-readiness-the-ciso-and-cro-join-forces)
- [Board Technology Committees in Financial Services — BPI](https://bpi.com/cyber-board-governance-the-role-of-board-technology-committees-for-financial-services-companies/)
- [Making Smart Cybersecurity Spending Decisions 2025 — IBM](https://www.ibm.com/think/insights/making-smart-cybersecurity-spending-decisions-in-2025)
- [Bank Cybersecurity Budgets 2025 — IntegrisIT](https://integrisit.com/2025-predictions-where-the-smart-money-will-be-spent-in-bank-cybersecurity/)
- [Cybersecurity Vendor Consolidation — TechTarget](https://www.techtarget.com/searchsecurity/tip/CISOs-guide-to-security-vendor-consolidation)
- [How to Conduct a Cybersecurity POC — HackRead](https://hackread.com/how-to-conduct-cybersecurity-proof-of-concept-poc-vendor/)
- [How to Build a Cybersecurity RFP — TechTarget](https://www.techtarget.com/searchsecurity/tip/How-to-build-a-cybersecurity-RFP)
