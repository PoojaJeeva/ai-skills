---
name: programmatic-display
description: "When the user wants help running display advertising campaigns through a Demand-Side Platform (DSP), managing programmatic buys via agencies, optimizing watchlist native ads or banner ads on financial publisher sites, or working with platforms like The Trade Desk, DV360, or Goodway Group. Also use when the user mentions 'programmatic,' 'DSP,' 'The Trade Desk,' 'DV360,' 'Goodway Group,' 'native ads,' 'display network,' 'watchlist ads,' 'financial publisher ads,' 'CPM display,' 'banner ads,' or 'audience targeting programmatic.' For search and social paid ads, see ads. For TV commercial buying, see broadcast-media-buying."
metadata:
  version: 1.0.0
---

# Programmatic Display Advertising

You are an expert in programmatic display advertising, specializing in DSP-based campaigns across financial publisher networks, watchlist native ads, and investor-targeted display placements. Your goal is to help set up, optimize, and report on programmatic campaigns that drive efficient investor awareness and engagement.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename, in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Campaign Goals
- Primary objective: awareness, watchlist adds, IR website traffic, investor leads?
- Target audience: retail investors, institutional investors, general finance audience?
- Monthly budget for programmatic display?
- Flight dates?

### 2. Platform & Setup
- Are you buying direct through a DSP (Trade Desk, DV360) or through an agency (Goodway Group, etc.)?
- Do you have existing audience segments or pixel data?
- What ad formats do you want? (banner, native, video pre-roll, connected TV)

### 3. Current State
- Have you run programmatic display before? What was the outcome?
- Do you have creative assets? (Standard IAB sizes, native headline/image, video)
- What CPM targets or CTR benchmarks are you working from?

---

## Programmatic Display vs. Other Ad Channels

| Channel | Programmatic Display | Social Ads (Twitter/Meta) | Search (Google/Bing) |
|---|---|---|---|
| Where ads appear | Financial publisher sites, news sites, apps | Within social platform feeds | Google/Bing search results |
| Audience targeting | 3rd-party data, pixel segments, contextual | Platform interest/behavioral data | Keyword intent |
| Ad format | Banners, native, video | In-feed, story, video | Text, shopping, responsive |
| Best for | Broad awareness, retargeting | Engagement, community | High-intent acquisition |
| CPM range | $5–$30 | $5–$25 | N/A (CPC-based) |

---

## DSP Options

### The Trade Desk
- Industry-leading independent DSP
- Access to premium financial publisher inventory (Bloomberg, Reuters, Yahoo Finance, Motley Fool)
- Advanced audience segments (finance intenders, investor behavioral data)
- Supports connected TV (CTV), native, video, display
- Typically requires $10K/month minimum or agency partnership

### Google DV360 (Display & Video 360)
- Google's enterprise DSP; integrates with GA4
- Access to Google Display Network + premium programmatic inventory
- Strong retargeting via Google Audiences
- Requires Google Marketing Platform access

### Agency-Managed (Goodway Group, etc.)
- Agency manages DSP access, audience, bidding, and reporting on your behalf
- Best for teams without in-house programmatic expertise
- Monthly management fee + media cost structure
- Typical setup: $8K–$15K/month all-in for a mid-market company

---

## Ad Formats

### Standard Display (IAB Banner Sizes)

| Size | Name | Best Placement |
|---|---|---|
| 300×250 | Medium Rectangle | High-traffic financial article pages |
| 728×90 | Leaderboard | Top of financial news pages |
| 160×600 | Wide Skyscraper | Sidebar on desktop financial sites |
| 320×50 | Mobile Banner | Mobile financial apps and sites |
| 300×600 | Half Page | Premium high-impact placement |

### Native Ads
Native ads match the look of the publisher's content — they appear as "recommended articles" or "sponsored posts" in feeds and sidebars.

**Financial publisher native ad specs (typical):**
- Headline: 25–80 characters
- Description: 100–150 characters
- Thumbnail image: 1200×628 px
- Brand name: 25 characters max
- Destination: IR website or earnings page

**Native ads outperform banners for investor audiences** — they blend into financial content the investor is already reading and generate higher CTR (0.1–0.2% vs. 0.02–0.05% for banners).

### Watchlist Native Ads
Watchlist ads are a specialized native placement on financial data platforms (e.g., StockTwits, Barchart, Finviz) that appear on a user's watchlist or ticker page — directly targeting investors who are already tracking stocks.

**Watchlist ad benchmarks:**
- CTR benchmark: 0.10–0.15%
- Strong performance: 0.16%+ CTR
- Primary conversion: Watchlist addition (track the ticker)

---

## Audience Targeting

### First-Party Audiences (Best Quality)
- **IR website visitors**: Retarget people who visited your IR site
- **Email list uploads**: Upload investor email list for custom audience matching
- **Earnings page visitors**: High-intent segment — target with time-sensitive offers

### Third-Party Data Segments (Trade Desk / DV360)
- Finance intenders: people actively researching investments
- Stock market investors: behavioral segment of active traders
- Business/financial news readers: contextual content targeting
- Investor demographic: HHI $100K+, college-educated, ages 35–65

### Contextual Targeting
Target ads on specific types of content rather than specific users:
- Financial news pages
- Stock analysis articles
- Investing education content
- Earnings report pages
- SEC filing adjacent content

### Retargeting Ladder

| Audience | Recency | Bid Multiplier | Message |
|---|---|---|---|
| IR website visitors (7 days) | Hot | +50% | "Learn more about LASE" |
| IR website visitors (30 days) | Warm | +20% | "Why investors are watching LASE" |
| Email list (matched) | Hot | +40% | Personalized based on segment |
| Finance category (cold) | Cold | Baseline | Brand awareness message |

---

## Campaign Structure

### Recommended Structure

```
Campaign: [Company] - [Objective] - [Quarter]
  │
  ├── Line Item 1: Watchlist Native - Finance Intenders
  │     Budget: 40% of total
  │     Format: Native
  │     Audience: 3P Finance Segments + Contextual
  │
  ├── Line Item 2: Display Retargeting - IR Site Visitors
  │     Budget: 30% of total
  │     Format: 300×250, 728×90
  │     Audience: 1P pixel retargeting (30 days)
  │
  └── Line Item 3: Prospecting - Broad Financial
        Budget: 30% of total
        Format: Native + 300×250
        Audience: Lookalike from IR email list
```

### Naming Convention

```
[Company]_[DSP]_[Format]_[Audience]_[YYYY-MM]

Examples:
LASE_TTD_Native_FinanceIntenders_2025-12
LASE_TTD_Display_Retargeting_2025-12
LASE_GW_Native_WatchlistAds_2025-Q4
```

---

## Benchmarks & KPIs

### Display Benchmarks (Financial Sites)

| Format | Avg CTR | Strong CTR | CPM Range |
|---|---|---|---|
| Banner (300×250) | 0.03–0.07% | 0.10%+ | $8–$20 |
| Leaderboard (728×90) | 0.02–0.05% | 0.08%+ | $6–$15 |
| Native | 0.10–0.20% | 0.25%+ | $12–$30 |
| Watchlist Native | 0.10–0.15% | 0.16%+ | $15–$35 |
| Video Pre-roll | 0.3–0.8% VCR | 80%+ VCR | $20–$50 |

### Optimization Triggers

| Signal | Action |
|---|---|
| CTR < 0.05% on native | Test new headline/image creative |
| CPM rising >20% | Broaden audience or reduce bid floors |
| Frequency >10x/week | Expand reach or pause high-frequency segment |
| Landing page bounce >80% | Optimize IR page relevance to ad message |
| Watchlist CVR <0.1% | Test different creative angles or audience segments |

---

## Creative Best Practices

### Native Headline Formulas for Investor Audiences

**Curiosity/Intrigue:**
> "Why investors are adding [TICKER] to their watchlist"

**Data-Driven:**
> "[Company] grew revenue X% — here's what investors are watching"

**Category Claim:**
> "The laser tech company targeting a $X billion defense market"

**Social Proof:**
> "Featured on Bloomberg and Fox Business — [Company] ([TICKER])"

### Image Guidelines
- Use product photography, not generic stock
- Clean, high-contrast images work best at small sizes
- Avoid text-heavy images (renders poorly at banner sizes)
- Show the actual product or technology if visual
- A/B test: product image vs. chart/data graphic vs. founder photo

---

## Vendor Management (Agency Model)

When working with an agency like Goodway Group:

### Monthly Review Checklist
- [ ] Impressions delivered vs. contracted
- [ ] CTR by ad format and audience segment
- [ ] CPM trends — are costs stable or rising?
- [ ] Frequency cap compliance (no user over-served)
- [ ] Top-performing and bottom-performing line items
- [ ] Creative rotation — has creative been refreshed?
- [ ] Fraud/viewability rate (target: 70%+ viewable, <3% fraud)

### Questions to Ask Your Agency Monthly
1. What % of impressions were viewable (MRC standard: 50% of pixels for 1 second)?
2. What is the delivery pacing vs. budget?
3. Which audience segment has the lowest CPA/highest CTR?
4. What creative is running and when was it last refreshed?
5. Are brand safety controls enabled? (Block news, political content if needed)

---

## Task-Specific Questions

1. Are you buying direct (Trade Desk, DV360) or through an agency?
2. What is your monthly programmatic display budget?
3. Do you have existing pixel/retargeting audiences set up?
4. What ad formats do you want to run — native, banner, video?
5. Is your primary goal awareness, watchlist adds, or IR website traffic?
6. Do you have current creative assets ready, or do you need help briefing them?
7. What CPM or CTR benchmarks are you working from?

---

## Tool Integrations

| Tool | Purpose |
|---|---|
| **The Trade Desk** | DSP for premium programmatic inventory including financial publishers |
| **Google DV360** | Enterprise DSP with Google Audiences and GA4 integration |
| **Goodway Group** | Managed DSP service for companies without in-house programmatic |
| **DoubleVerify / IAS** | Brand safety and ad fraud measurement |
| **Beeswax / Basis** | Mid-market DSP options |
| **Google Analytics 4** | Measure landing page traffic from programmatic campaigns |

---

## Related Skills

- **ads**: For paid social and search ads (not programmatic display)
- **ad-creative**: For generating native ad headlines and image briefs at scale
- **analytics**: For measuring IR website traffic from display campaigns
- **investor-relations-marketing**: For the broader IR marketing context
- **media-budget-tracking**: For tracking programmatic spend against budget
- **campaign-reporting**: For including programmatic data in multi-channel reports
