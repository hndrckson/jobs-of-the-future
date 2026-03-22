# PQC Market Entry Strategy Recommendations for Financial Services

## Strategic Intelligence Brief — March 2026

---

## Executive Summary

This document synthesizes the findings from our six companion analyses — regulatory trajectory, HNDL exposure, decision-maker mapping, competitive landscape, pricing/positioning, and target account prioritization — into an actionable market entry strategy. The financial services PQC market is at an inflection point: regulatory signals are intensifying, HNDL risk awareness is spreading from security teams to boardrooms, and the first wave of bank PQC programs is consuming budget. But no vendor has locked up the market. The next 18 months determine who owns the banking PQC relationship for the next decade.

**The thesis**: Financial services is the single best vertical for PQC market entry because it combines (1) the highest HNDL exposure of any commercial sector, (2) a regulatory apparatus that converts awareness into mandatory action on predictable timelines, (3) the highest security budgets of any industry, and (4) procurement dynamics that reward deep vertical expertise over horizontal breadth.

---

## Strategic Framework: The Three Horizons

### Horizon 1: Establish Credibility (Months 0–12)

**Objective**: Win 3–5 reference accounts; become recognized as a serious financial services PQC player.

**Key metric**: First signed contract with a named bank.

### Horizon 2: Capture Market Position (Months 12–30)

**Objective**: 10–15 active bank engagements; platform maturity; recurring revenue base.

**Key metric**: $5M+ ARR from financial services.

### Horizon 3: Defend and Expand (Months 30–60)

**Objective**: Market leadership in banking PQC; international expansion; managed services at scale.

**Key metric**: $25M+ ARR; 25+ bank customers; recognized by regulators and industry bodies.

---

## Horizon 1: Establish Credibility (Months 0–12)

### Move 1: Build the Industry Knowledge Moat

**What**: Become the most knowledgeable PQC voice in financial services — not the loudest, the most *useful*.

**Actions**:
- Publish a definitive whitepaper: "The Bank CISO's Guide to Post-Quantum Cryptography" — not a vendor pitch, but a genuinely useful resource covering regulatory timeline, HNDL risk by data type, migration methodology, and vendor evaluation criteria
- Engage with FS-ISAC's PQC Working Group — either as a member or contributor. This is the primary industry forum where bank CISOs discuss PQC
- Participate in or sponsor panels at banking security conferences (FS-ISAC Summit, RSA financial services track, BITS events, ABA cybersecurity forums)
- Build relationships with key examiner communities — not to sell, but to understand what questions examiners are asking banks about quantum

**Why this works**: Bank CISOs buy from people they trust. Trust comes from demonstrated expertise, not product demos. In financial services, the sale starts 6–12 months before the RFP — in the relationship-building and thought leadership phase. Every competitor (IBM, SandboxAQ, Big 4) is trying to sell. Be the one that *teaches*.

**Cost**: $100K–$250K (content development, event participation, FS-ISAC membership)

### Move 2: Secure the First Reference Account

**What**: Convert one of the Tier 1 targets into a paying customer, even at a significant discount.

**Priority targets** (from companion analysis): BNY Mellon, Goldman Sachs, Citigroup

**Approach**:
1. **Executive warm introduction** through board connections, advisory network, or FS-ISAC relationships. Cold outreach to bank CISOs has <5% success rate
2. **Lead with intelligence, not product**: "We've completed a regulatory trajectory analysis and HNDL exposure assessment for financial services. We'd like to brief your team on what we're seeing." Share a sanitized version of these companion documents
3. **Offer a low-friction entry point**: Cryptographic discovery assessment for a single business unit or application — scoped to 4–6 weeks, priced at $100K–$200K (reference discount)
4. **Deliver a board-ready output**: The assessment must produce something the CISO can take to their CRO and Board Risk Committee — not just a technical inventory, but a *risk-quantified, regulatory-mapped* assessment
5. **Convert assessment to platform**: The assessment naturally reveals the scope of the crypto estate, creating the business case for platform-level engagement

**Critical success factor**: The assessment must surface *at least one finding that creates urgency* — a category of data with HNDL exposure the bank hadn't quantified, a regulatory gap they hadn't identified, or a crypto weakness in a critical system.

**Timeline**: 3–6 months from first meeting to signed assessment SOW

### Move 3: Build the NIST NCCoE Connection

**What**: Join or engage with the NIST NCCoE "Migration to Post-Quantum Cryptography" project (SP 1800-38).

**Why**: This is where the banking PQC ecosystem is forming. Participants include JPMorgan Chase, M&T Bank, Santander, Wells Fargo, SWIFT, IBM, Microsoft, AWS, SandboxAQ, and PQShield. Being in the room provides:
- Credibility by association
- Direct relationship with bank security teams participating in the project
- Influence on the reference architecture that will guide bank procurement
- Intelligence on competitor positioning and product roadmaps

**Cost**: Time investment primarily; NIST NCCoE participation is typically collaborative, not fee-based

### Move 4: Partner Strategically (Not Broadly)

**What**: Form one targeted partnership that accelerates bank access.

**Option A: Partner with a Big 4/5 that doesn't have a PQC technology partner**

- **KPMG** and **PwC** have no visible PQC technology partnerships (unlike EY→SandboxAQ and Deloitte→SandboxAQ)
- Offer to be their PQC technology partner for financial services advisory engagements
- They provide bank access and advisory credibility; you provide technology and PQC depth
- This is the fastest path to bank decision-makers for a new entrant

**Option B: Partner with an HSM vendor**

- **Thales** and **Keyfactor** have an existing partnership model; approach them about co-selling to banking customers
- Position as the migration orchestration layer on top of their HSM infrastructure
- Banks won't replace their HSM vendor — integrate with whoever they already use

**Option C: Partner with a banking technology platform**

- Companies like FIS, Fiserv, or Temenos provide core banking platforms to hundreds of institutions
- A PQC integration with a core banking platform provides instant access to their customer base
- This is a longer play but scales to mid-market banks that don't buy directly from security vendors

**Recommended**: Start with Option A (KPMG or PwC partnership) for immediate bank access, while pursuing Option B (HSM integration) for technical credibility.

---

## Horizon 2: Capture Market Position (Months 12–30)

### Move 5: Transition from Services to Platform

**What**: Evolve from assessment-led engagements to platform-led recurring revenue.

**Product evolution path**:

```
Assessment tool (months 0-6)
    → Discovery platform (months 6-12)
    → Migration orchestration (months 12-18)
    → Continuous monitoring + compliance (months 18-24)
    → Crypto agility management platform (months 24-36)
```

**Key product decisions**:
- **Cloud-native vs. on-premise**: Large banks require on-premise or private cloud deployment. Build cloud-native but support on-prem from day one. This is non-negotiable for financial services
- **Multi-HSM support**: Must integrate with Thales Luna, Entrust nShield, and Utimaco at minimum. Don't pick sides — banks use mixed HSM environments
- **API-first architecture**: Banks will want to integrate PQC management into existing security orchestration (SOAR), GRC, and SIEM platforms
- **Compliance templates**: Pre-built mappings to FFIEC IT Handbook, OCC Comptroller's Handbook, Fed SR letters, SEC Reg SCI, FINRA cybersecurity expectations

### Move 6: Scale Through the Reference Effect

**What**: Use the first 3–5 bank references to accelerate sales to the next 10–15.

**The banking reference flywheel**:
```
Reference Account 1 (BNY Mellon) → "The world's largest custodian uses us"
    → State Street, Northern Trust see a peer reference and engage
    → Reference Account 2 (Goldman Sachs) → "Top M&A advisory banks use us"
        → Morgan Stanley, Lazard, Evercore see a peer reference and engage
        → Reference Account 3 (Wells Fargo) → "Major retail banks use us"
            → PNC, US Bancorp, Truist see a peer reference and engage
```

**Critical**: Different bank types reference against different peers. A custody bank (BNY) doesn't reference against a retail bank (Wells Fargo). Build references across segments:
- 1 custodian bank (BNY Mellon or State Street)
- 1 bulge-bracket investment bank (Goldman or Morgan Stanley)
- 1 universal bank (Citi or Wells Fargo)
- 1 large regional (M&T, PNC, or Capital One)
- 1 international bank (for global expansion)

### Move 7: Engage Regulators (Carefully)

**What**: Establish relationships with the regulatory and standard-setting communities — not to lobby, but to understand and influence.

**Actions**:
- Respond to NIST, OCC, and FFIEC requests for information on PQC topics
- Participate in FS-ISAC working groups and contribute to industry position papers
- Brief examiner training programs on PQC technical fundamentals (if invited)
- Support G7 CEG implementation through industry engagement channels

**Why**: When an OCC examiner asks a bank "what are you doing about quantum risk?" and the bank answers "we're using [your company's] platform to manage our PQC migration" — that's the moment when your product becomes embedded in the regulatory conversation. You can't achieve this by marketing; you achieve it by being the company that regulators *know* is serious about banking PQC.

**Caution**: Never position as a "regulator-endorsed" solution. Regulators don't endorse products. Position as "aligned with regulatory expectations."

### Move 8: Build the Mid-Market Channel

**What**: While direct-selling to G-SIBs and large banks, build a partner channel for the thousands of mid-size and community banks that will need PQC but won't buy directly.

**Channel options**:
- **Core banking vendors** (FIS, Fiserv, Jack Henry): Embed PQC management into their platforms; reach 10,000+ banks
- **MSS providers** (Secureworks, Arctic Wolf, etc.): Add PQC monitoring to managed security offerings for mid-market banks
- **Bank technology consortia** (BITS, ABA, state banking associations): Provide PQC readiness programs at scale
- **BNY's community banking initiative**: BNY offers free training for 1,000 community bank leaders — partner to add PQC content

---

## Horizon 3: Defend and Expand (Months 30–60)

### Move 9: International Expansion

**Timing**: After establishing U.S. banking references, expand to jurisdictions where regulatory pressure is accelerating faster.

**Priority markets**:

| Market | Regulatory Driver | Timing |
|--------|------------------|--------|
| **UK** | PRA, FCA, Bank of England; G7 CEG co-chair | Immediate — UK regulators are aggressive |
| **EU** | NIS2 Directive, DORA, EU PQC roadmap (national plans by end 2026) | 2027 — as national plans crystallize |
| **Singapore** | MAS quantum readiness mandate; JPMorgan quantum network deployed there | 2027 — MAS among most forward-looking regulators |
| **Japan** | Bank of Japan digital infrastructure modernization | 2028 — slower regulatory cycle but massive market |
| **Middle East** | UAE/Saudi sovereign wealth funds; financial center ambitions | 2027–2028 — budget available, regulatory framework developing |

### Move 10: Managed Service Expansion

**What**: As the platform matures, offer fully managed PQC services — crypto inventory, continuous monitoring, migration management, compliance reporting — as a subscription service.

**Why**: Most banks (especially Tier 2–3) will never build in-house PQC expertise. The talent doesn't exist at sufficient scale. Managed services are the natural long-term model for 80% of the market.

**Economics**: Managed services generate higher margins (60–70%) than platform licenses (40–50%) at scale, because the same team manages multiple bank environments using the same platform.

### Move 11: Become the Standard

**What**: Drive toward becoming the de facto PQC management platform for banking — the way Splunk became the de facto SIEM or CrowdStrike became the de facto EDR.

**How standards form in banking**:
1. A few large banks adopt a solution
2. Examiners see it during examinations and become familiar with it
3. Examiners start asking other banks "how does your PQC management compare to [standard tool]?"
4. Other banks adopt to match examination expectations
5. The tool becomes the implicit standard

**This cycle takes 3–5 years.** If you're the tool that's in front of examiners in 2027–2028, you become the standard by 2030–2032 — just as mandatory PQC requirements arrive.

---

## Execution Priorities: The First 90 Days

| Week | Action | Owner |
|------|--------|-------|
| 1–2 | Finalize financial services positioning and messaging | Marketing/Strategy |
| 1–2 | Identify and engage FS-ISAC PQC Working Group | BD/Partnerships |
| 2–4 | Draft "Bank CISO's Guide to PQC" whitepaper | Product Marketing |
| 2–4 | Begin KPMG or PwC partnership outreach | Partnerships |
| 3–6 | Identify warm introduction paths to BNY Mellon, Goldman Sachs, Citigroup CISOs | BD/Executive team |
| 4–8 | Develop financial-services-specific demo environment | Engineering |
| 4–8 | Begin NIST NCCoE engagement process | CTO/Engineering |
| 6–12 | First assessment SOW signed with a Tier 1 target | Sales |
| 8–12 | Thales/Entrust HSM integration development | Engineering |

---

## Risk Factors and Mitigations

| Risk | Probability | Impact | Mitigation |
|------|------------|--------|-----------|
| **Q-Day is further away than expected (>2040)** | 30% | Slows urgency but doesn't eliminate need | HNDL framing makes current action rational regardless of Q-Day timing; regulatory trajectory continues regardless |
| **IBM locks up banking PQC with mainframe integration** | 20% | Limits addressable market to non-IBM systems | Focus on cloud-native, application-layer, and multi-vendor orchestration — the gaps IBM doesn't cover |
| **SandboxAQ captures banking through EY/Deloitte channels** | 25% | Reduces Tier 1 bank availability | Partner with KPMG/PwC (unused channels); out-specialize on banking-specific capabilities |
| **Banks delay PQC beyond 2028** | 30% | Slows revenue but doesn't eliminate market | Discovery/assessment services remain relevant (banks need to *assess* even if they delay *migration*); regulatory pressure continues building |
| **NIST PQC algorithm issues (implementation attacks, etc.)** | 10% | Could slow adoption temporarily | Crypto-agility positioning means you help banks adapt to *any* algorithm change, including setbacks |
| **Procurement cycle longer than expected** | 40% | Delays revenue recognition | Build a pipeline 3x target to account for cycle time; use assessment/advisory revenue to bridge |

---

## Financial Model Summary

### Conservative Scenario

| Year | Customers | ARR | Cumulative Revenue |
|------|-----------|-----|-------------------|
| Year 1 | 3 assessments, 1 platform | $800K | $800K |
| Year 2 | 5 new assessments, 3 platforms, 1 managed | $3.5M | $4.3M |
| Year 3 | 8 new, 10 active platforms, 3 managed | $9M | $13.3M |
| Year 4 | 12 new, 18 active platforms, 6 managed | $18M | $31.3M |
| Year 5 | 15 new, 25 active, 10 managed | $28M | $59.3M |

### Aggressive Scenario (Strong reference accounts, regulatory catalyst)

| Year | Customers | ARR | Cumulative Revenue |
|------|-----------|-----|-------------------|
| Year 1 | 5 assessments, 2 platforms | $1.5M | $1.5M |
| Year 2 | 10 new, 6 platforms, 2 managed | $6M | $7.5M |
| Year 3 | 15 new, 15 platforms, 5 managed | $15M | $22.5M |
| Year 4 | 20 new, 28 platforms, 10 managed | $30M | $52.5M |
| Year 5 | 25 new, 40 platforms, 15 managed | $50M | $102.5M |

---

## The Bottom Line

The financial services PQC market is a generational opportunity. The threat is real (HNDL is happening now). The regulatory trajectory is clear (mandatory requirements by ~2030). The budget is available (banks spend 10–15% of IT on security). And the market is unowned — no vendor has captured banking PQC yet.

The critical constraint is *time*. The window for a new entrant to establish credibility, win reference accounts, and embed in the regulatory conversation is **18–24 months** (through late 2027). After that, the market will consolidate around 2–3 primary vendors (likely IBM + one specialist + one consultancy-led offering), and the cost of entry rises dramatically.

**Move now. Lead with intelligence. Win through banking depth. Scale through references.**

---

## Cross-Reference to Companion Documents

| Document | Key Findings That Inform This Strategy |
|---------|--------------------------------------|
| **Regulatory trajectory timeline** | 2026–2027 expectation setting phase; examiner questions starting now for G-SIBs; CNSA 2.0 January 2027 forcing function |
| **HNDL exposure analysis** | M&A advisory and trading communications are highest-priority HNDL data types; use for sales urgency |
| **Decision-maker and procurement map** | Multi-stakeholder sale (CISO + CRO + CTO + CCO); 10–21 month procurement cycle; budget cycle timing |
| **Competitive landscape** | White space in banking-specific PQC platform; IBM is biggest threat; KPMG/PwC partnership opportunity |
| **Pricing and positioning** | $300K entry assessment; $1M platform sweet spot; 5-year account value $5–11M; reference discount strategy |
| **Target account prioritization** | BNY Mellon #1 (active program), Goldman #2 (M&A exposure), Citigroup #3 (global pressure) |
