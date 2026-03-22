# HNDL Exposure Analysis by Financial Data Type

## Strategic Intelligence Brief — March 2026

---

## Executive Summary

"Harvest Now, Decrypt Later" (HNDL) is not a theoretical future threat — it is an active intelligence collection strategy being executed today by nation-state adversaries with documented interest in financial sector data. The question is not *whether* encrypted financial data is being harvested, but *which data categories* justify immediate PQC protection based on their retroactive value window.

This analysis maps financial data types against three dimensions: **regulatory retention period** (how long it must exist), **retroactive intelligence value** (how long it remains useful to an adversary after decryption), and **adversary interest level** (documented targeting by nation-state actors). The intersection of these three dimensions determines HNDL priority.

**Critical finding**: The financial sector has a uniquely dangerous HNDL profile because regulatory requirements *force* long data retention, creating a guaranteed harvest window that adversaries can plan around with high confidence.

---

## The HNDL Threat Model for Financial Services

### Why Financial Data Is a Priority HNDL Target

1. **Predictable retention**: Regulators mandate 3–7+ year retention for most financial records. Adversaries know the data *will exist* and *will be accessible* for defined periods
2. **Concentrated value**: A single bank's communications contain M&A intelligence, trading strategies, customer PII, regulatory strategy, and competitive intelligence
3. **Network effects**: Decrypting one bank's communications reveals information about counterparties, clients, and market movements affecting the entire ecosystem
4. **Documented targeting**: Nation-state actors (China's APT groups, Russia's APT28/APT29, North Korea's Lazarus Group) have confirmed, ongoing operations targeting financial institutions
5. **Infrastructure vulnerability**: Salt Typhoon's compromise of U.S. telecom providers (AT&T, Verizon, 20+ countries) demonstrates that encrypted-in-transit data is being intercepted at the infrastructure level

### The Adversary Timeline

```
TODAY (2026): Adversary harvests encrypted financial communications
    ↓
STORAGE: Adversary stores petabytes of encrypted traffic (cheap, ~$20/TB/year)
    ↓
Q-DAY (est. 2030-2035): Cryptographically relevant quantum computer operational
    ↓
DECRYPTION: RSA-2048 and ECDH traffic decrypted in hours/days
    ↓
EXPLOITATION: Retroactive intelligence value realized
```

The critical question: **What financial data harvested today will still have exploitable value in 2030–2035?**

---

## Data Type HNDL Priority Matrix

### Tier 1: CRITICAL — Immediate PQC Migration Required

These data categories have retroactive value measured in **decades** and are confirmed targets of nation-state collection.

#### 1. M&A Advisory Communications

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 3–6 years (SEC 17a-4, FINRA records); but *practical* retention often 10+ years in legal holds |
| **Retroactive value window** | **10–20+ years** |
| **Adversary interest** | EXTREME — direct economic espionage value |
| **HNDL Priority** | **CRITICAL** |

**Why the value persists**: M&A communications reveal:
- **Deal strategy and pricing**: Even completed deals reveal valuation methodologies, walk-away prices, and negotiating positions that inform future deal intelligence
- **Undisclosed discussions**: Failed/abandoned deals that were never public remain permanently sensitive — disclosure could affect stock prices, relationships, and future deal attempts
- **Client relationship mapping**: Which companies are acquisition targets, which advisors they use, which banks compete for mandates
- **Industry consolidation intelligence**: Pattern analysis across years of M&A communications reveals strategic industry trajectories
- **Legal exposure**: Communications that could be weaponized in future litigation (antitrust, shareholder suits, regulatory investigations)

**Extrapolation**: A nation-state actor with access to 5 years of a bulge-bracket bank's M&A communications would have a comprehensive map of corporate America's strategic intentions — worth tens of billions in economic espionage value. Chinese APT groups have specifically targeted law firms and financial advisors involved in M&A (documented by FBI/CISA).

#### 2. Trading Communications and Strategies

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 3–6 years (trading blotters 6 years, order tickets 3 years, communications 3 years) |
| **Retroactive value window** | **5–15 years** (varies by strategy type) |
| **Adversary interest** | HIGH — market manipulation, competitive intelligence |
| **HNDL Priority** | **CRITICAL** |

**Differentiated analysis by trading type**:

- **Proprietary trading strategies**: Algorithmic trading models, quantitative strategies, and proprietary signals retain value for 5–10+ years. Even "stale" strategies reveal the *methodology* and *thinking patterns* of top trading desks, which can be reverse-engineered
- **Market-making communications**: Reveal pricing models, risk appetite, and counterparty relationships — valuable for 3–7 years
- **Options/derivatives structuring**: Complex structured products often have multi-year lifespans; communications about their construction reveal risk assumptions and pricing models for years
- **Fixed income/credit trading**: Credit assessments, bond pricing discussions, and syndication communications reveal issuer financial health and institutional positioning — valuable for 5–10 years

**Key insight**: The SEC's $200M enforcement action against JPMorgan for off-channel communications (WhatsApp, iMessage) demonstrates that traders *are* communicating sensitive information through channels that may have weaker encryption or be more easily intercepted. This is exactly the kind of traffic adversaries prioritize for HNDL collection.

#### 3. Customer PII and Account Data

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 6 years (FINRA Rule 4512); 5 years (BSA/AML); effectively lifetime for active accounts |
| **Retroactive value window** | **Lifetime of the individual** (SSN, DOB don't change) |
| **Adversary interest** | HIGH — intelligence targeting, identity fraud, economic espionage |
| **HNDL Priority** | **CRITICAL** |

**Why PII is a permanent HNDL target**:
- Social Security numbers, dates of birth, mother's maiden names, and account numbers **don't expire**
- High-net-worth individual data enables targeted intelligence operations (recruitment, blackmail, sanctions evasion monitoring)
- Wealth data combined with identity data enables sophisticated social engineering for decades
- Customer relationship data reveals who does business with whom — a permanent intelligence map

**Critical distinction**: Credit card numbers (easily canceled) are LOW HNDL priority. SSNs, account numbers, and identity verification data are CRITICAL because they cannot be rotated.

---

### Tier 2: HIGH — PQC Migration Within 12–24 Months

These data categories have retroactive value measured in **years** and represent significant intelligence or financial value.

#### 4. Internal Strategy Communications

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 3 years (business communications); often longer in practice |
| **Retroactive value window** | **3–10 years** |
| **Adversary interest** | MODERATE-HIGH — competitive intelligence, regulatory strategy |
| **HNDL Priority** | **HIGH** |

**What's at stake**:
- Board-level strategic planning (market entry/exit, product strategy, geographic expansion)
- Regulatory strategy (how the bank plans to respond to new regulations, compliance approach)
- Technology strategy (IT modernization plans, vendor selection, security architecture)
- Competitive assessments (internal analysis of competitors)
- Personnel decisions affecting key positions

**Extrapolation**: A competitor or nation-state actor with access to a bank's internal strategy communications could systematically anticipate and counter the bank's moves for years. For sovereign wealth funds and state-owned enterprises competing with Western banks, this intelligence is directly actionable.

#### 5. Regulatory and Compliance Communications

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 6 years (examination records); indefinite for consent orders |
| **Retroactive value window** | **5–15 years** |
| **Adversary interest** | MODERATE — leverage for future negotiations, legal exposure |
| **HNDL Priority** | **HIGH** |

**Why compliance data has long-tail value**:
- Internal audit findings reveal known weaknesses that persist for years
- Examination preparation documents reveal what the bank is worried about
- Remediation plans and timelines expose the gap between stated and actual compliance
- Attorney-client privileged communications about regulatory risk become leverage if disclosed
- BSA/AML investigation notes reveal the bank's knowledge of suspicious activity — potential liability exposure for decades

#### 6. Correspondent Banking and SWIFT Communications

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 5 years (BSA requirements); SWIFT messages retained per network rules |
| **Retroactive value window** | **5–10 years** |
| **Adversary interest** | EXTREME — sanctions evasion monitoring, financial intelligence |
| **HNDL Priority** | **HIGH** |

**Unique risk factors**:
- SWIFT messages reveal the full topology of global money flows
- Correspondent banking relationships map the entire global financial network
- Wire transfer data enables sanctions enforcement intelligence and evasion detection
- Payment patterns reveal supply chain relationships, government procurement, and defense spending
- North Korean and Iranian actors specifically target SWIFT and payment systems (Bangladesh Bank heist, $81M)

---

### Tier 3: MODERATE — PQC Migration Within 24–48 Months

#### 7. Credit and Risk Assessment Data

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 7 years (credit reports); varies for internal risk models |
| **Retroactive value window** | **3–7 years** |
| **Adversary interest** | MODERATE — economic intelligence |
| **HNDL Priority** | **MODERATE** |

**Value analysis**: Credit assessments of sovereign borrowers, major corporations, and infrastructure projects reveal economic intelligence about countries and industries. Internal risk models reveal the bank's view of systemic risks. However, this data degrades in value faster than M&A or PII data.

#### 8. Research and Investment Analysis

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 3 years (research records) |
| **Retroactive value window** | **1–5 years** |
| **Adversary interest** | MODERATE — front-running, competitive intelligence |
| **HNDL Priority** | **MODERATE** |

**Differentiation**: Unpublished research reports and analyst communications have value for front-running purposes only until publication. However, *unpublished negative analysis* that was suppressed or modified before distribution has potential exposure value for years (regulatory, legal, reputational).

#### 9. Employee HR and Compensation Data

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 3–7 years (varies by jurisdiction) |
| **Retroactive value window** | **3–10 years** (PII component is lifetime) |
| **Adversary interest** | MODERATE — recruitment targeting, social engineering |
| **HNDL Priority** | **MODERATE** |

**Intelligence value**: Compensation data reveals organizational hierarchy, key personnel, and talent concentration. For nation-state actors, this enables targeted recruitment of insiders. The PII component (SSN, benefits, health information) has the same lifetime exposure as customer PII.

---

### Tier 4: LOW — Standard PQC Migration Timeline

#### 10. Routine Operational Communications

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | 3 years |
| **Retroactive value window** | **< 1 year** |
| **Adversary interest** | LOW |
| **HNDL Priority** | **LOW** |

Routine operational messages, meeting logistics, vendor coordination for non-sensitive matters. Low retroactive value but still part of the overall cryptographic estate that needs migration.

#### 11. Public-Facing Marketing and Investor Relations

| Dimension | Assessment |
|-----------|-----------|
| **Regulatory retention** | Varies |
| **Retroactive value window** | **Near zero** (publicly available) |
| **Adversary interest** | NEGLIGIBLE |
| **HNDL Priority** | **LOW** |

Data that is or will be made publicly available. HNDL exposure is minimal, though *draft* versions of public communications before they are finalized may contain strategically sensitive revisions.

---

## Aggregate HNDL Exposure by Institution Type

### G-SIB / Bulge-Bracket Investment Bank

| Data Category | Volume (est.) | HNDL Exposure | Annual Risk Value |
|--------------|--------------|---------------|-------------------|
| M&A advisory | High | CRITICAL | $500M–$5B+ (deal intelligence) |
| Trading comms | Very High | CRITICAL | $100M–$1B (strategy value) |
| Customer PII | Very High | CRITICAL | $50M–$500M (identity value) |
| Strategy comms | High | HIGH | $50M–$200M |
| SWIFT/payments | Very High | HIGH | $100M–$1B (financial intelligence) |
| **Total estimated HNDL exposure** | | | **$800M–$8B+** |

### Large Regional Bank ($50–250B)

| Data Category | Volume (est.) | HNDL Exposure | Annual Risk Value |
|--------------|--------------|---------------|-------------------|
| Customer PII | High | CRITICAL | $20M–$100M |
| Commercial lending | Moderate | HIGH | $10M–$50M |
| Strategy comms | Moderate | MODERATE | $5M–$20M |
| SWIFT/payments | Moderate | HIGH | $10M–$50M |
| **Total estimated HNDL exposure** | | | **$45M–$220M** |

### Wealth Management / Private Bank

| Data Category | Volume (est.) | HNDL Exposure | Annual Risk Value |
|--------------|--------------|---------------|-------------------|
| UHNW client PII | Moderate | CRITICAL | $50M–$500M (target intelligence) |
| Investment strategy | Moderate | HIGH | $20M–$100M |
| Trust/estate data | Moderate | HIGH | $10M–$50M |
| **Total estimated HNDL exposure** | | | **$80M–$650M** |

---

## Cross-Cutting HNDL Amplifiers

### 1. Off-Channel Communications

The SEC/FINRA enforcement wave against off-channel communications (WhatsApp, iMessage, Signal, personal email) has revealed that a significant volume of the *most sensitive* financial communications — exactly the data with highest HNDL value — flows through channels with:
- Weaker or unknown encryption implementations
- No institutional key management
- Unclear data retention and potential third-party access
- Personal device storage vulnerable to physical compromise

**Implication**: The highest-value HNDL targets may be the communications that institutions have the *least* visibility into and control over.

### 2. Third-Party and Cloud Data

Financial institutions increasingly store data with cloud providers, SaaS platforms, and outsourced service providers. Each third-party relationship creates an additional HNDL exposure surface:
- Data in transit between institution and provider
- Data at rest in provider infrastructure
- Provider-to-provider data flows (sub-processors)
- API communications containing authentication credentials

### 3. Telecom Infrastructure Compromise

Salt Typhoon's confirmed compromise of U.S. telecom providers means that **all data traversing compromised networks is potentially harvested** — regardless of the financial institution's own security controls. This includes:
- VPN tunnel metadata (even if not content)
- TLS-encrypted API calls
- SWIFT message traffic
- Inter-branch communications
- Remote employee access

---

## Strategic Recommendations for PQC Vendors

### Positioning by HNDL Tier

1. **Lead with M&A and trading communications** — These are the data types where HNDL risk is most visceral and quantifiable. Every investment banker understands the value of deal communications; every trader understands strategy theft. This creates immediate urgency

2. **Customer PII is the compliance play** — PII protection maps directly to existing regulatory requirements (GLBA, CCPA, GDPR). Position PQC as the natural evolution of PII protection programs banks already have

3. **SWIFT/payments is the systemic risk play** — For regulators, central banks, and industry bodies (FS-ISAC, BIS), the interconnected payment infrastructure represents systemic risk. Position PQC solutions for payment systems as systemic risk mitigation

4. **Use the retention requirement as a sales tool** — "You're required to keep this data for 6 years. Are you confident it will remain encrypted for 6 years?" This reframes PQC from a future problem to a *current regulatory compliance gap*

### The "Data Shelf Life" Framework

Adapt Europol's Quantum Safe Financial Forum framework for sales conversations:

```
HNDL Risk = Data Shelf Life × Exposure to Adversaries × Business Impact

Where:
- Data Shelf Life = MAX(regulatory retention, practical sensitivity window)
- Exposure = likelihood of interception (near-certain for G-SIBs given Salt Typhoon)
- Business Impact = financial, legal, regulatory, reputational consequences
```

If any dimension is high and the product of all three exceeds a threshold, immediate PQC migration is warranted.

---

## Sources and References

- [Harvest Now, Decrypt Later — Palo Alto Networks](https://www.paloaltonetworks.com/cyberpedia/harvest-now-decrypt-later-hndl)
- [HNDL: A Temporal Cybersecurity Risk in the Quantum Transition — MDPI](https://www.mdpi.com/2673-4001/6/4/100)
- [Harvest Now, Decrypt Later — HashiCorp](https://www.hashicorp.com/en/blog/harvest-now-decrypt-later-why-today-s-encrypted-data-isn-t-safe-forever)
- [HNDL: A CISO's Guide — SafeLogic](https://www.safelogic.com/blog/harvest-now-decrypt-later-quantum-threat)
- [Quantum Disentangled: HNDL — Freshfields](https://technologyquotient.freshfields.com/post/102lx4l/quantum-disentangled-1-harvest-now-decrypt-later-the-quantum-threat-is-alr)
- [HNDL Explained — Qryptonic](https://qryptonic.com/learn/hndl-explained)
- [SEC Rule 17a-4 and Related Interpretations — FINRA](https://www.finra.org/rules-guidance/guidance/interpretations-financial-operational-rules/sea-rule-17a-4-and-related-interpretations)
- [Books and Records — FINRA](https://www.finra.org/rules-guidance/key-topics/books-records)
- [SEC Rule 17a-3 & FINRA Records Retention — PageFreezer](https://blog.pagefreezer.com/sec-finra-books-records-retention-requirements)
- [CISA Advisory — Chinese State-Sponsored Actors](https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-239a)
- [Foreign Economic Espionage in Cyberspace — DNI/NCSC](https://www.dni.gov/files/NCSC/documents/news/20180724-economic-espionage-pub.pdf)
- [FS-ISAC PQC Resources](https://www.fsisac.com/knowledge/pqc)
- [Protecting Financial Data With Encryption Controls — FS-ISAC](https://www.fsisac.com/hubfs/Knowledge/ProtectingFinancialDataWithEncryptionControls.pdf)
- [BIS Project Leap — Quantum-proofing Payment Systems](https://www.bis.org/publ/othp107.pdf)
- [Europol Quantum Safe Financial Forum](https://postquantum.com/quantum-policy/fs-isac-pqc-migration/)
