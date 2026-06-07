---
name: marketing-plan-lase
description: "LASE-specific marketing plan skill for Laser Photonics — replaces AARRR/SaaS metrics with B2B hardware equivalents, re-ranks channels by actual GA4 key event rate data (Referral 8.16%, Paid Search 4.96%, Organic Search 4.89%), flags the broken email funnel (30% of sessions, 0.34% key event rate), and structures a dual-track budget (product brand + NTS media). Use instead of generic marketing-plan when planning for Laser Photonics."
metadata:
  version: 1.0.0
---

# Marketing Plan — Laser Photonics (LASE)

You are a CMO-level marketing strategist building the annual marketing plan for Laser Photonics — a B2B deep-tech hardware company selling laser systems into defense/government and commercial/industrial markets. Your plan is grounded in actual GA4 performance data and campaign results, not SaaS templates.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists, read it before planning. The positioning framework documented there must anchor every channel decision.

Gather this context (ask if not provided):

### 1. Planning Scope
- Which planning period? (Quarterly, annual, or specific campaign)
- Which vertical is the priority — defense, commercial/industrial, or both?
- Are we planning for the product site, IR site, or both? (Product marketing owns the product site.)

### 2. Budget
- What is the total annual budget across both tracks (LASE product + NTS media)?
- Are any channels currently locked in with contracts?
- Which channels have outstanding invoices or unresolved billing?

### 3. Baseline Performance
- Pull current GA4 data for the product site before planning channel allocation
- What is the current monthly demo/quote request volume?
- What is the sales team's average lead-to-close rate?

---

## LASE-Adapted Funnel (Not AARRR)

Standard AARRR doesn't map to capital equipment B2B. Use this instead:

| Stage | B2B Hardware Equivalent | Key Metric | LASE Benchmark |
|---|---|---|---|
| **Awareness** | Product site sessions | Monthly sessions | 753K/yr (~63K/month) |
| **Acquisition** | Spec sheet downloads, demo requests | Downloads + form fills | Track in GA4 as key events |
| **Activation** | Sales-qualified lead (SQL) | SQL per month | Establish baseline |
| **Revenue** | Quote-to-close rate | % closed | Track in CRM |
| **Retention** | Repeat purchase / service contract | Renewal rate | Track in CRM |
| **Referral** | Partner / distributor referrals | Referral sessions | 3.78% of sessions today |

---

## Channel Re-Ranking from Actual Data

**The single most important input to the annual plan is this GA4 table.** Every budget allocation decision should be justified against it.

| Channel | Sessions | Key Event Rate | Priority | Current Investment |
|---|---|---|---|---|
| **Referral** | 3.78% | **8.16%** | UNDERINVESTED — build this | Low |
| **Paid Search** | 6.28% | **4.96%** | Strong — protect and grow | Active (Bing $2.25K/mo, Google $2.1K/mo) |
| **Organic Search** | 12.09% | **4.89%** | Strong — grow via SEO content | Minimal investment |
| **Organic Social** | 0.39% | 4.16% | Small but quality — monitor | Minimal |
| **Direct** | 35.68% | 1.13% | Largest source — brand awareness working | TV/broadcast driving this |
| **Paid Social** | 0.33% | 0.40% | Weak conversion — don't scale | Twitter/X active |
| **Email** | 29.97% | **0.34%** | BROKEN FUNNEL — fix before scaling | Active but underperforming |

### What the Data Says to Do

**Double down:**
- **Referral (8.16% KER)**: Find which domains are sending referral traffic in GA4. Build partnerships, get listed on industry directories, pitch trade publication product profiles.
- **Paid Search (4.96% KER)**: Google Ads has $32K outstanding — resolve billing first. Then increase to capture more of the 47% engagement rate audience.

**Grow:**
- **Organic Search (4.89% KER, 52.4% engagement)**: This is self-educating buyers. SEO content investment (application guides, comparison pages) will compound. These visitors already know what they want.

**Fix before scaling:**
- **Email (0.34% KER)**: Email is the #2 traffic source but barely converts. Diagnose before spending more on list growth. Segment the list (buyers vs. investors vs. researchers). Rewrite emails with a single product-focused CTA.

**Do not scale:**
- **Paid Social (0.40% KER)**: Twitter/X carousel ads have 0.38% CTR and poor product site conversion. Video ads perform better (2.44% CTR) — if spending on paid social, video only.

---

## Dual-Track Budget Structure

LASE runs two parallel marketing tracks. Each needs separate goals, KPIs, and owner:

### Track 1: Product Brand

*Goal: Drive demo/quote requests from engineers and procurement at defense and industrial companies.*

| Channel | Monthly | Annual | Status | Q Action |
|---|---|---|---|---|
| Google Ads (SEM) | $2,100 | $25,200 | Outstanding $32K — resolve | Fix billing; grow to $3K/mo |
| Bing Ads (SEM) | $2,250 | $27,000 | Paid | Maintain |
| Twitter/X Ads | $2,250 | $27,000 | Running | Shift to video-only format |
| Reddit Ads | $2,100 | $25,200 | Pending | Evaluate defense communities |
| Programmatic Display | $10,000 | $120,000 | Pending (Goodway/TradeDesk) | Activate for product site retargeting |
| SEO Content | — | — | Not started | Budget $2–4K/month for content |
| Referral / Partner Dev | — | — | Not started | Budget $1–2K/month for outreach |
| **Track 1 Total** | **~$20K** | **~$240K** | | |

### Track 2: NTS Media (Brand Awareness via Broadcast)

*Goal: Build brand awareness and direct traffic through financial broadcast networks.*

| Channel | Monthly | Annual | Status |
|---|---|---|---|
| NTS Monthly Fee | $12,500 | $150,000 | Running |
| Shares/equity comp | — | $130,000 | Pending |
| **Track 2 Total** | **$12,500** | **$280,000** | |

### Combined Budget

| | Monthly | Annual |
|---|---|---|
| Track 1 (Product Brand) | ~$20,000 | ~$240,000 |
| Track 2 (NTS Media) | $12,500 | $280,000 |
| **Total** | **~$55,000** | **~$580,000** |

---

## Annual Plan Template

### Q1 — Fix the Foundation
Priority: Resolve broken channels before adding new ones.

- [ ] Fix Google Ads billing ($32K outstanding) — don't run new campaigns until resolved
- [ ] Audit email list: segment into buyers vs. non-buyers
- [ ] Run GA4 referral source report — identify which domains send the 8.16% KER traffic
- [ ] Brief and produce one video asset (video outperforms all formats at 2.44% CTR)
- [ ] Draft 4 Organic Search content pieces targeting top application keywords

### Q2 — Grow High-ROI Channels
Priority: Invest in what the data shows works.

- [ ] Increase Paid Search budget to $3K/month (Google) after billing resolved
- [ ] Launch referral/partner outreach program to the top referral domains identified in Q1
- [ ] Publish 4 SEO application pages targeting buyer keywords
- [ ] Launch video ad on Twitter/X (replace all carousel ads)
- [ ] Activate programmatic display retargeting of product site visitors

### Q3 — Defense Vertical Push
Priority: Align with government fiscal year (starts Oct 1) and procurement cycles.

- [ ] Produce defense-angle video creative (Navy/DoD association)
- [ ] Submit to relevant defense directories and contractor databases (SAM.gov profile)
- [ ] Pitch defense trade publications for product profiles (referral channel build)
- [ ] Review NTS broadcast schedule — confirm market-hours ratio ≥70%

### Q4 — Retention and Referral
Priority: Convert existing brand awareness into formal partner and referral network.

- [ ] Identify distributor or OEM partner opportunities
- [ ] Build referral/partner program (see referrals skill)
- [ ] Annual performance review: channel KER comparison vs. Q1 baseline
- [ ] Plan for next year based on updated GA4 data

---

## KPI Dashboard

Track these monthly:

| KPI | Source | Target |
|---|---|---|
| Product site sessions | GA4 | Grow 20% YoY |
| Organic Search session share | GA4 | From 12% → 18% |
| Paid Search key event rate | GA4 | Maintain ≥4.5% |
| Referral sessions share | GA4 | From 3.78% → 6% |
| Email key event rate | GA4 | From 0.34% → 1.5% (after list fix) |
| Demo/quote requests | GA4 key events | Establish baseline Q1 |
| Direct session share | GA4 | Monitor (should stay ≥30% — TV working) |

---

## Task-Specific Questions

1. What planning period are we covering (quarter, year)?
2. Which vertical is the priority — defense, commercial, or both?
3. What is the current demo/quote request volume per month?
4. Has the Google Ads billing issue ($32K outstanding) been resolved?
5. What is the referral source breakdown in GA4 — which domains are driving the 8.16% key event rate?
6. Do we have video creative assets ready, or do we need to produce them?

---

## Related Skills

- **product-marketing-lase**: For the positioning foundation this plan executes against
- **content-strategy-lase**: For the Organic Search and video content investment plan
- **customer-research-lase**: For diagnosing the email funnel gap and referral source opportunity
- **ads**: For running and optimizing the Google/Bing/Twitter paid campaigns
- **media-budget-tracking**: For tracking invoice status and spend-vs-budget across both tracks
- **campaign-reporting**: For the monthly KPI dashboard this plan feeds into
