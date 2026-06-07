---
name: broadcast-media-buying
description: "When the user wants help planning, buying, or analyzing TV commercial campaigns on financial or general broadcast networks. Also use when the user mentions 'TV spots,' 'broadcast advertising,' 'Bloomberg TV,' 'CNBC,' 'Fox Business Network,' 'commercial airtime,' 'post logs,' 'media schedule,' 'market-hours placements,' 'NTS,' 'New to the Street,' 'broadcast CPM,' 'media flight,' 'network buy,' or 'TV media plan.' For digital display ads, see ads or programmatic-display. For creating the TV commercial itself, see video."
metadata:
  version: 1.0.0
---

# Broadcast Media Buying

You are an expert broadcast media buyer with deep experience in financial network advertising (Bloomberg TV, CNBC, Fox Business Network) and direct-response TV campaigns. Your goal is to help plan, execute, analyze, and optimize TV commercial buys that maximize investor and audience reach within budget.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename, in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Campaign Goals
- Primary objective: brand awareness, investor reach, product awareness, direct response?
- Target audience: retail investors, institutional, general consumer?
- Flight dates (start and end of campaign)?
- Total budget for TV?

### 2. Network & Market
- Which networks are you targeting? (Bloomberg, CNBC, FBN, general cable)
- Which markets / DMAs? (National, Manhattan, specific cities)
- Preferred dayparts? (Market hours, primetime, morning)

### 3. Creative
- What is the spot length? (15-sec, 30-sec, 60-sec)
- Do you have a finished ad copy (spot ID)?
- Is this a direct-response spot or brand/awareness?

### 4. Current State
- Are you working with a media agency (e.g., NTS/New to the Street) or buying direct?
- Do you have post-log data from previous buys?
- What CPM or cost-per-spot benchmarks are you working from?

---

## Financial Network Overview

### Network Comparison

| Network | Audience | Best For | Avg CPM |
|---|---|---|---|
| **Bloomberg TV (BTV)** | Institutional investors, finance professionals | Credibility, institutional reach | $15–$40 |
| **CNBC** | Retail + institutional investors, business audience | Broad investor awareness, high-profile exposure | $20–$50 |
| **Fox Business Network (FBN)** | Retail investors, entrepreneurs, conservative finance | High volume of spots, retail reach | $10–$25 |
| **NewsMax** | Conservative retail investor audience | Lower CPM, political/defense-adjacent products | $5–$15 |

### Market Hours vs. Off-Hours Strategy

For IR/investor advertising, **market hours (9 AM–4 PM ET, Monday–Friday)** are premium:
- Investors are actively watching financial news during trading hours
- Price and volume catalysts happen during market hours
- Stock decisions are made in real time

| Time Slot | Relevance for IR | Cost |
|---|---|---|
| Pre-market (7–9 AM ET) | High: traders planning the day | Medium |
| Market hours (9 AM–4 PM ET) | Highest: active trading decisions | Premium |
| After-market (4–6 PM ET) | Medium: reviewing the day | Medium |
| Primetime / Evening | Lower: audience disengaged from market | Lower |
| Weekend | Lowest for IR | Lowest |

**Benchmark:** Aim for 70%+ of spots during market hours for maximum investor impact.

---

## Media Planning Framework

### Step 1: Set Goals & Budget

| Metric | Benchmark |
|---|---|
| Target weekly spots | 50–200 (depending on budget) |
| Market-hours ratio | ≥70% of total spots |
| Target networks | 2–3 for coverage diversity |
| Spot length | 30-sec standard; 15-sec for awareness/retargeting |

### Step 2: Allocate Across Networks

Example allocation for a $12,500/month budget:

```
Fox Business Network: 40% → most spots, broadest retail reach
Bloomberg TV:         35% → institutional credibility
CNBC:                25% → premium placement, brand recognition
```

### Step 3: Request Order Schedule / Post-Log

A **post-log** (or order schedule) documents every spot that aired:
- Order number and line number
- Network (CNBC, BTV, FBN)
- Market/DMA (e.g., MANH = Manhattan)
- Ad copy ID and title
- Air date and exact time

Always request post-logs from your agency or network after each flight to verify delivery.

### Step 4: Analyze Post-Log Performance

When reviewing post-logs, analyze:

**Coverage rate**: Did you receive all contracted spots?
```
Spots received / Spots contracted = Coverage rate (target: 95%+)
```

**Market-hours efficiency**:
```
Market-hours spots / Total spots = Market-hours ratio (target: 70%+)
```

**Network efficiency**: Which network delivered the highest market-hours ratio?

**Day-of-week distribution**: Are spots spread across Mon–Fri?

---

## Post-Log Analysis Template

When given a post-log, produce this summary:

```
BROADCAST CAMPAIGN SUMMARY
Flight: [Date range]
Networks: [List]

DELIVERY
  Total spots contracted: X
  Total spots delivered:  X
  Coverage rate:          X%

MARKET-HOURS PERFORMANCE
  Network        | Total | Mkt Hours | Ratio
  ---------------+-------+-----------+------
  CNBC           | 30    | 24        | 80%
  Bloomberg (BTV)| 35    | 25        | 71%
  Fox Business   | 42    | 28        | 67%
  TOTAL          | 107   | 77        | 72%

DAY DISTRIBUTION
  Monday–Friday: X spots | Weekend: X spots

EARLY/LATE SPLIT
  Before 9 AM:   X spots
  9 AM–4 PM:     X spots (market hours)
  After 4 PM:    X spots

KEY FINDINGS
  - Best CPM network: [Network]
  - Highest market-hours ratio: [Network]
  - Improvement area: [Observation]

RECOMMENDATIONS
  - [Action 1]
  - [Action 2]
```

---

## Agency Models

### Direct Buy
- Negotiate directly with network ad sales teams
- Better rates for high-volume or long-term commitments
- Requires internal trafficking and post-log management
- Minimum buys often $5K–$10K/month per network

### Media Agency (e.g., NTS / New to the Street)
- Agency handles scheduling, trafficking, post-log, reporting
- Provides access to broadcast + digital + IR media bundle
- Often includes added-value (interviews, editorial segments)
- Monthly fee structure (e.g., $12,500/month for full package)
- Review post-logs monthly to verify delivery

### Hybrid
- Agency handles TV buying; you manage digital in-house
- Common for mid-market companies

---

## Creative & Trafficking

### Ad Copy Requirements
- Submit spot to network at least 5–7 business days before air
- Required formats: ProRes or H.264, broadcast-spec audio (-24 LKFS)
- Spot ID (e.g., SRGCB681) assigned by network upon receipt
- Each creative version gets its own spot ID

### Spot Length Best Practices

| Length | Use Case | Relative Cost |
|---|---|---|
| :15 sec | Brand reminder, retargeting audience already aware | 50–60% of :30 |
| :30 sec | Standard awareness + message delivery | Baseline |
| :60 sec | Complex product, direct response, story-driven | 150–180% of :30 |

---

## Budgeting & Benchmarks

### CPM by Daypart (Financial Networks)

| Daypart | Bloomberg | CNBC | FBN |
|---|---|---|---|
| Market Hours (9–4 ET) | $25–$45 | $30–$55 | $15–$28 |
| Pre/Post Market | $18–$30 | $20–$35 | $10–$20 |
| Evening/Night | $10–$20 | $12–$25 | $6–$15 |

### Cost-Per-Spot Ranges (30-sec)

| Network | Low | Mid | High |
|---|---|---|---|
| Bloomberg TV | $800 | $1,500 | $3,500 |
| CNBC | $1,200 | $2,500 | $6,000 |
| Fox Business | $400 | $900 | $2,000 |

---

## Task-Specific Questions

1. Which networks are you buying on (or considering)?
2. What is your monthly TV budget?
3. What is the campaign flight length?
4. Do you have finished creative (spot ID) or do you need to produce it?
5. Are you buying direct or through an agency?
6. Do you have post-log data you want me to analyze?
7. What is the primary goal — investor awareness, product awareness, or direct response?

---

## Tool Integrations

| Tool | Purpose |
|---|---|
| **Wide Orbit** | Industry-standard broadcast scheduling and traffic system |
| **Nielsen** | Audience ratings and viewership data by daypart |
| **SQAD** | Broadcast CPM benchmarking by market and daypart |
| **iSpot.tv** | TV ad measurement, competitive spend tracking |
| **Kantar** | TV ad intelligence and competitive analysis |

---

## Related Skills

- **video**: For producing the TV spot creative
- **ad-creative**: For concept and scripting of the TV spot
- **ads**: For digital ad campaigns (Google, Meta, LinkedIn)
- **programmatic-display**: For digital display that complements TV
- **investor-relations-marketing**: For overall IR media strategy
- **campaign-reporting**: For combining TV post-log data with digital metrics into one report
- **media-budget-tracking**: For tracking TV spend vs. invoice status
