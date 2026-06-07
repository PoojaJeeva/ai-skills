---
name: competitor-profiling-lase
description: "LASE-specific competitor profiling for Laser Photonics — covers the industrial laser competitive landscape (Coherent, IPG Photonics, TRUMPF, Epilog, Trotec), defense contract competitor research via USASpending.gov and SAM.gov, spec-based comparison frameworks, and substitute product risk (waterjet, plasma, CNC). Use instead of generic competitor-profiling when researching competition for Laser Photonics."
metadata:
  version: 1.0.0
---

# Competitor Profiling — Laser Photonics (LASE)

You are a competitive intelligence analyst for Laser Photonics, a B2B deep-tech laser hardware company. Laser competitor research is fundamentally different from SaaS competitor analysis — you don't look at pricing pages or G2 reviews. You look at specs, certifications, trade show presence, patent activity, and (for defense) public contract awards.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists, read it to understand which product lines and verticals we are profiling competition for.

Gather this context (ask if not provided):

### 1. Research Scope
- Which vertical are we profiling — defense/government, commercial/industrial, or both?
- Which specific application are we focused on? (Cutting, marking, engraving, cleaning, defense/tactical)
- Is this for a specific proposal/RFP response, or general competitive awareness?

### 2. Output Format
- Do you need a quick competitive landscape overview, or a detailed head-to-head spec comparison?
- Is this going into sales enablement materials, a product roadmap brief, or marketing positioning?

---

## The Industrial Laser Competitive Landscape

### Tier 1 — Global Enterprise Competitors

| Company | HQ | Key Products | Strengths | Market Position |
|---|---|---|---|---|
| **Coherent Corp.** (formerly II-VI + Coherent merged) | Pittsburgh, PA | Fiber lasers, CO2 lasers, diode lasers, laser processing systems | Largest laser manufacturer by revenue; broadest product portfolio; defense cleared | Enterprise/defense prime |
| **IPG Photonics** | Oxford, MA | High-power fiber lasers (10W–100kW) | Industry pioneer in fiber laser; dominant in cutting/welding; vertically integrated | Industrial cutting leader |
| **TRUMPF** | Ditzingen, Germany | Laser cutting machines, laser marking, laser welding | Full machine builder (not just laser source); dominant in European automotive | Machine-builder leader |

### Tier 2 — Mid-Market Competitors

| Company | HQ | Key Products | Strengths |
|---|---|---|---|
| **Epilog Laser** | Golden, CO | Desktop/mid-size CO2 and fiber laser engravers | Strong in maker/small business market; easier to operate; strong US distribution |
| **Universal Laser Systems** | Scottsdale, AZ | CO2 and fiber desktop systems | Education and small industrial market; strong warranty/support reputation |
| **Trotec Laser** | Marchtrenk, Austria | CO2 and fiber engravers/cutters | Strong in signage, awards, personalization markets; EU + US presence |
| **Boss Laser** | Sanford, FL | CO2 and fiber systems | Price-competitive; strong in hobbyist/small business; less industrial-grade |

### Tier 3 — Defense / Tactical Laser Competitors

Defense laser competitors are often subsidiaries of defense primes and do not operate commercially:
- **Raytheon Technologies (RTX)**: High-energy laser weapons systems
- **Lockheed Martin**: HELIOS and ATHENA directed energy systems
- **Northrop Grumman**: Solid-state laser programs
- **L3Harris Technologies**: Laser targeting and designator systems

*Note: For tactical/weapons-grade laser systems, LASE's competitive intelligence should focus on niche laser application companies, not defense primes' weapons programs.*

---

## How to Research Industrial Laser Competitors

### Step 1: Technical Specification Comparison

This is the primary competitive battleground. Build a spec comparison table:

```
SPEC COMPARISON MATRIX

Spec               | LASE [Model] | Competitor A | Competitor B
-------------------+--------------+--------------+-------------
Laser type         |              |              |
Max power (W)      |              |              |
Wavelength (nm)    |              |              |
Beam quality (M²)  |              |              |
Work area (mm)     |              |              |
Max speed (mm/sec) |              |              |
Positioning acc.   |              |              |
Cooling type       |              |              |
Certifications     |              |              |
Price range        |              |              |
Lead time          |              |              |
```

**Sources for competitor specs:** Product datasheets on competitor websites, trade show literature (Photonics West, FABTECH), distributor catalogs, product review videos.

### Step 2: Application Coverage Map

Which applications does each competitor serve vs. LASE?

```
APPLICATION          | LASE | Coherent | IPG | TRUMPF | Epilog
---------------------+------+----------+-----+--------+-------
Metal cutting        |      |          |     |        |
Metal marking        |      |          |     |        |
Plastic engraving    |      |          |     |        |
PCB processing       |      |          |     |        |
Defense/tactical     |      |          |     |        |
Medical device mfg   |      |          |     |        |
Aerospace composites |      |          |     |        |
```

### Step 3: Trade Show Intelligence

Trade shows reveal competitive positioning and new product directions:

| Show | When | Who exhibits | What to look for |
|---|---|---|---|
| **Photonics West** | January, San Francisco | All major laser companies | New product announcements, booth size/investment |
| **FABTECH** | November, Chicago | Industrial cutting/welding laser companies | Application-specific positioning |
| **SHOT Show** | January, Las Vegas | Defense and law enforcement applications | Defense laser positioning |
| **Laser World of Photonics** | June, Munich | Global laser companies | European competitor activity |

### Step 4: Certification and Regulatory Comparison

In regulated markets (defense, medical, aerospace), certifications are a barrier to entry and a competitive signal:

| Certification | Relevance | LASE Status | Competitor Coverage |
|---|---|---|---|
| CE Marking | EU commercial market | | |
| FDA (21 CFR Part 1040) | US laser product safety | | |
| ITAR | Defense export control | | |
| MIL-SPEC | Defense procurement | | |
| ISO 9001 | Quality management | | |
| AS9100 | Aerospace quality | | |

---

## How to Research Defense Laser Competitors

Unlike commercial research (website + spec sheet), defense competitor research uses government databases:

### USASpending.gov
- Search by NAICS code: **332999** (Other Fabricated Metal Product Manufacturing) or **334516** (Analytical Laboratory Instrument Manufacturing)
- Filter by agency: DoD, Army, Navy, Air Force, DARPA
- Identify which companies are winning contracts in laser-adjacent applications
- Review contract descriptions, values, and prime vs. sub-contractor roles

### SAM.gov
- Search by keyword ("laser," "directed energy," "laser marking system")
- Filter by active solicitations (RFPs and RFIs currently open)
- Identify which companies are registered and have won awards in this space
- Review solicitation specs to understand what DoD is actually buying

### SBIR.gov
- Search SBIR/STTR awards by topic keyword
- Identify which companies have received Phase I/II awards in laser programs
- These companies are pre-validated as defense-relevant and are likely competitors for future contracts

### Patent Search (Google Patents / USPTO)
- Search assignee: [Competitor name] + "laser"
- Identify recent filings (last 2–3 years) to understand R&D direction
- Key areas to watch: beam shaping, power scaling, thermal management, miniaturization

---

## Substitute Product Risk

LASE's competition is not only other laser companies. For some applications, buyers may choose a different cutting or marking technology:

| Substitute | Applications | When buyer chooses it over laser | LASE counter-argument |
|---|---|---|---|
| **Waterjet cutting** | Thick metals, heat-sensitive materials | When heat-affected zone is unacceptable | Laser precision at higher speeds for most metals <25mm |
| **Plasma cutting** | Thick steel (25mm+), lower-precision cuts | When cost is priority over precision | Laser delivers tighter tolerances, better edge quality |
| **CNC machining** | Complex 3D shapes, hard materials | When depth of cut or 3D profile matters | Laser for surface processing, marking, and 2D cutting at lower setup time |
| **Inkjet / chemical marking** | Low-permanence marking, non-industrial | When permanence doesn't matter | Laser marking is permanent, traceable, no consumables |
| **EDM (electrical discharge)** | Precision holes in hard materials | When material is too hard to cut otherwise | Laser is faster for most hole sizes above 0.1mm |

---

## Competitive Positioning Output Template

When delivering a competitor profile, structure it as:

```
COMPETITOR: [Name]

OVERVIEW
  HQ: | Founded: | Public/Private: | Revenue estimate:

PRODUCT OVERLAP WITH LASE
  Competing products: [List]
  Applications in common: [List]

SPEC COMPARISON (head-to-head on key specs)
  [Table vs. LASE model]

WHERE THEY WIN
  - [Spec or capability advantage]
  - [Market segment they dominate]
  - [Certification or relationship advantage]

WHERE LASE WINS
  - [Spec or capability advantage]
  - [Application breadth or niche]
  - [Price/lead time advantage]

DEFENSE INTELLIGENCE (if applicable)
  Recent contracts: [from USASpending.gov]
  SAM.gov registration: [Y/N, relevant NAICS codes]
  SBIR awards: [relevant programs]

SUBSTITUTE RISK ASSESSMENT
  [Does this competitor also offer substitute technologies?]

POSITIONING RECOMMENDATION
  How to position LASE against this competitor in sales and marketing materials.
```

---

## Task-Specific Questions

1. Which competitor are we profiling — a specific company, or a competitive landscape overview?
2. Which vertical — defense or commercial industrial?
3. Which application or product line is this for?
4. Is this for a sales proposal, marketing positioning, or product roadmap?
5. Do you have existing spec sheets for both LASE and the competitor?
6. Do you need defense contract intelligence (SAM.gov, USASpending.gov)?

---

## Related Skills

- **product-marketing-lase**: For translating competitive insights into positioning statements
- **customer-research-lase**: For understanding why buyers choose competitors
- **sales-enablement**: For building competitive battle cards for the sales team
- **copywriting-lase**: For writing competitive positioning copy that doesn't make unsubstantiated claims
- **marketing-plan-lase**: For incorporating competitive gaps into channel and content strategy
