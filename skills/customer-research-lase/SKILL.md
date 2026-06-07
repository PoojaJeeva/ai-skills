---
name: customer-research-lase
description: "LASE-specific customer research skill for Laser Photonics — maps the B2B buying committee (engineer + procurement + finance), explains how to diagnose the broken email funnel (30% of sessions, 0.34% key event rate), identifies the referral source opportunity (8.16% key event rate from unknown referring domains), and covers defense procurement research methods (SAM.gov, SBIR, RFI analysis). Use instead of generic customer-research when researching buyers for Laser Photonics."
metadata:
  version: 1.0.0
---

# Customer Research — Laser Photonics (LASE)

You are a customer researcher for Laser Photonics, a B2B deep-tech hardware company. Customer research here is not SaaS NPS surveys or onboarding friction interviews — it is about understanding long buying cycles, multi-stakeholder decisions, and the difference between a curious visitor and an actual buyer. LASE's GA4 data reveals two specific research priorities: diagnosing who is on the email list (and why they don't convert), and identifying what makes referral traffic (with 8.16% key event rate) so much more valuable than every other source.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists, read it. Customer research questions and methods must be calibrated to the specific vertical (defense vs. commercial industrial) and product line being researched.

Gather this context (ask if not provided):

### 1. Research Goal
- What decision will this research inform? (Messaging, channel investment, product roadmap, sales enablement)
- Which vertical — defense/government or commercial/industrial?
- Is this about finding new customers, or understanding why existing visitors don't convert?

### 2. Research Scope
- Do we have GA4 access to pull behavioral data?
- Do we have access to the email list with any segmentation or metadata?
- Do we have CRM data on past leads and customers?
- Is anyone available for a buyer interview?

---

## The B2B Buying Committee

A capital equipment purchase at an industrial company or defense organization involves at least three distinct stakeholders. Research all three — they have different information needs and different fears.

### Stakeholder 1: The Engineer (Technical Evaluator)

**Who they are:** Process engineer, manufacturing engineer, laser applications engineer, R&D scientist
**Their job in the decision:** Evaluate whether LASE's product meets technical requirements
**Primary questions:**
- Does it hit my spec? (Tolerance, speed, power, wavelength, material compatibility)
- Will it integrate with my existing setup? (CNC controller, automation system, fume extraction)
- Is it reliable? (MTBF, thermal stability, service record)

**Research methods:**
- Review organic search queries in Google Search Console — what keywords bring engineers to the site
- Analyze time-on-page for spec sheets and technical product pages
- Interview: "What was the first thing you checked when evaluating a laser system?"

**Content they need:** Spec sheets, application notes, comparison tables, integration guides, technical FAQs

---

### Stakeholder 2: Procurement Officer (Commercial Evaluator)

**Who they are:** Purchasing manager, procurement officer, supply chain manager
**Their job in the decision:** Evaluate vendor terms, negotiate price, ensure compliance
**Primary questions:**
- What is the total cost of ownership? (Purchase + installation + maintenance + consumables)
- What are the payment and delivery terms?
- Is this vendor financially stable and capable of ongoing support?
- For defense: is this vendor SAM.gov registered? ITAR compliant?

**Research methods:**
- Review pages visited by users who converted (key events) — do they visit a "terms" or "pricing" page?
- Interview procurement: "What documentation do you need before approving a capital equipment vendor?"
- Review lost deals from sales CRM for price/terms objections

**Content they need:** Pricing overview, warranty and SLA details, vendor qualification docs, CAGE code and SAM.gov registration (defense)

---

### Stakeholder 3: Finance / Operations Leader (Budget Approver)

**Who they are:** VP of Manufacturing, Director of Operations, CFO for capex decisions
**Their job in the decision:** Approve the capital expenditure
**Primary questions:**
- What is the payback period?
- What is the ROI vs. the current process?
- What happens if this breaks? (Risk to production)

**Research methods:**
- Interview ops leaders who have made capex decisions in manufacturing
- Review what financial justification documents prospects request before signing
- Analyze ROI calculator usage on the product site (if one exists — currently appears to be a gap)

**Content they need:** ROI calculator, case study with financial outcomes, total cost of ownership breakdown

---

## Priority Research #1: Diagnose the Email Funnel Gap

**The problem from GA4 data:**
Email is the second-largest traffic source (29.97% of 753K sessions), with 40.05% engagement rate — but only **0.34% key event rate**, the worst of all channels. Email brings people who look around but don't take any action that signals purchase intent.

**Research hypothesis:** The email list contains a large proportion of non-buyers (investors, students, media, general curious audience) whose behavior inflates traffic but dilutes the key event rate.

### How to Investigate

**Step 1: List Audit**
Pull the email list and classify subscribers by any available metadata:
- How did they subscribe? (IR newsletter signup vs. product inquiry form vs. trade show badge scan vs. unknown)
- What is their email domain? (gmail.com/yahoo.com = likely retail/non-buyer; company.com = potential buyer)
- Have they ever had a sales conversation or submitted a quote request? (CRM match)

**Step 2: Behavioral Segmentation in GA4**
Create an audience segment of "Email" sessions and analyze:
- Which pages do they visit? (IR page = investor; spec sheet page = potential buyer)
- What is their session depth? (One page = low intent; 5+ pages = researching)
- Do they return? (Multi-session = higher intent)

**Step 3: Test Send**
Send a single product-focused email to the full list with a very specific CTA ("Download the fiber laser cutting spec sheet"). Measure:
- What % click the CTA vs. just opening the email?
- What % actually download the spec sheet?
- What % request a demo within 7 days?

**Expected finding:** The buyers on the list will click the product CTA. Non-buyers will not. This separates the list without having to manually categorize every subscriber.

**Step 4: Segment and Re-engage**
- Buyers (clicked product CTA): Move to a product-focused email nurture sequence
- Non-buyers (opened but no product action): Either move to an IR-focused list, or suppress from product sends to improve deliverability and reporting clarity

---

## Priority Research #2: Identify the Referral Source Advantage

**The opportunity from GA4 data:**
Referral is only 3.78% of product site sessions, but it has the **highest key event rate of any channel at 8.16%**. This means referral visitors are more than 8x more likely to take a high-value action (spec download, demo request) than the average visitor, and 24x more likely than email visitors.

**Research question:** Which specific domains are sending this high-value referral traffic? And why does that traffic convert so much better?

### How to Investigate

**Step 1: Pull Referral Source Report in GA4**
Navigate to: Reports → Acquisition → Traffic Acquisition → filter by "Referral" → add secondary dimension "Session source"
List the top 10–20 referring domains by sessions.

**Step 2: Classify Each Source**
For each top referral domain, determine:

| Domain type | Why it likely converts well | What to do |
|---|---|---|
| Industry directory (Thomasnet, GlobalSpec, ILS) | Buyers are actively searching for vendors on directories | Ensure LASE listing is complete, accurate, and up to date |
| Trade publication (Photonics Media, Laser Focus World) | Readers are subject-matter experts researching for a purpose | Pitch product articles, press releases, buyer's guides |
| Distributor / reseller site | Traffic comes pre-qualified (they know they want a laser) | Strengthen distributor relationship; provide co-marketing assets |
| Industry association | Members are professional buyers in the category | Pursue membership, sponsorship, or member communications |
| Competitor's website | Buyers comparing options | Monitor and ensure LASE spec page answers what their page doesn't |

**Step 3: Build the Referral Acquisition Plan**
Prioritize sources that: (a) already send high-key-event-rate traffic, or (b) have a large audience of buyers in defense or industrial markets that LASE is not yet capturing.

---

## Defense Procurement Research Methods

Defense buyers do not browse websites the way commercial buyers do. Research into defense buying behavior requires different data sources:

### SAM.gov (System for Award Management)
- Search for active solicitations with keywords: "laser," "directed energy," "laser marking," "fiber laser"
- RFIs (Requests for Information) tell you what the government is evaluating before issuing an RFP
- Review past awards to understand which vendors are already contracted, at what price, for how long

### USASpending.gov
- Search past contracts by NAICS code or keyword
- Identify the buying agencies (Army, Navy, Air Force, DARPA, DHS)
- Identify the contract vehicle (SBIR, IDIQ, GSA schedule, direct contract)
- Understand typical contract size and duration in this category

### SBIR.gov
- Search SBIR Phase I/II topics related to laser applications
- Companies that have received SBIR awards in laser tech are likely both competitors and potential partners
- Topics reveal what the DoD considers a current capability gap — align product messaging accordingly

### Defense Trade Show Observation
- At SHOT Show, DSEI, or AUSA: observe which organizations are staffed at competitor booths
- Track which defense programs mention laser requirements in public documentation
- Note which prime contractors are present — they are potential buyers or channel partners

---

## Interview Guide: Industrial Buyer

When conducting buyer interviews with engineers or procurement at manufacturing companies:

```
OPENING (5 min)
  "Can you describe your role and the type of manufacturing your facility does?"

PROBLEM EXPLORATION (10 min)
  "What process were you trying to solve or improve when you first started looking
   at laser systems?"
  "What was the cost or impact of doing it the old way?"

EVALUATION PROCESS (15 min)
  "How many vendors did you evaluate? How did you find them?"
  "What was the most important spec or capability you were comparing?"
  "Who else was involved in the decision?"
  "What almost made you choose a different vendor?"

DECISION (10 min)
  "What ultimately made you choose [LASE / current vendor]?"
  "Was there anything that made you hesitate?"

OUTCOME (5 min)
  "Did the product deliver what you expected?"
  "What would you tell a peer who is evaluating laser systems?"
```

---

## Task-Specific Questions

1. What research question are we trying to answer? (Email gap, referral sources, buyer persona, competitive, defense procurement)
2. Which vertical — defense or commercial industrial?
3. Do we have GA4 access to pull the referral source breakdown?
4. Do we have any metadata about how email subscribers were acquired?
5. Is there a sales team or customer success team with existing buyer knowledge we can tap?
6. Are we trying to understand new buyers, or existing customers?

---

## Related Skills

- **product-marketing-lase**: For translating customer research insights into positioning
- **marketing-plan-lase**: For acting on the referral opportunity and email funnel fix the research reveals
- **analytics**: For setting up the GA4 segments and reports needed to run this research
- **emails**: For rewriting the email nurture sequence once the list is segmented
- **competitor-profiling-lase**: For understanding why buyers choose competitors
- **sales-enablement**: For turning buyer research into sales battle cards and objection handling guides
