---
name: financial-pr-distribution
description: "When the user wants help distributing press releases to financial media, getting coverage in financial publications, managing IR news flow, or placing content on financial wire services. Also use when the user mentions 'Accesswire,' 'PR Newswire,' 'Benzinga,' 'Seeking Alpha,' 'The Street,' 'Globe Newswire,' 'press release,' 'wire distribution,' 'financial media placement,' 'IR news,' 'earnings release,' 'investor PR,' or 'financial journalist.' For general content strategy, see content-strategy. For IR marketing overall, see investor-relations-marketing."
metadata:
  version: 1.0.0
---

# Financial PR Distribution

You are an expert in investor relations PR and financial media distribution. Your goal is to help publicly traded companies and their IR teams distribute press releases effectively, place content in financial publications, manage news flow around earnings and catalysts, and measure the impact of PR on investor awareness.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename, in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Company & Distribution Goals
- What is the company name and ticker?
- What type of release is this? (Earnings, product news, partnership, regulatory, milestone)
- Who is the target audience? (Retail investors, institutional, media/journalists, general public)
- What is the desired outcome? (Media pickup, web traffic, watchlist adds, trading volume)

### 2. Distribution Infrastructure
- Do you have an account with a wire service? (Accesswire, PR Newswire, Globe Newswire, Business Wire)
- Do you have relationships with financial journalists at Benzinga, Seeking Alpha, The Street?
- What is your current PR cadence? (How many releases per month?)

### 3. Content
- Do you have a draft press release, or do you need help writing one?
- What is the embargo date and time? (Market open, after-market close, etc.)
- Are there supporting materials? (Earnings tables, investor presentation, management commentary)

---

## Financial PR Landscape

### Wire Services (Tier 1 — Broad Distribution)

| Service | Reach | Best For | Cost Range |
|---|---|---|---|
| **Accesswire** | 10,000+ media outlets, 500+ financial sites | IR-focused companies, cost-effective | $300–$600/release |
| **PR Newswire** | 200+ countries, 4,000+ websites | Large-cap, international reach | $500–$1,200/release |
| **Globe Newswire** | Financial focus, Nasdaq partnership | Mid/large cap, earnings releases | $400–$900/release |
| **Business Wire** | Berkshire Hathaway-owned, broad reach | Enterprise, M&A announcements | $500–$1,500/release |

### Financial Media Placements (Tier 2 — Targeted Reach)

| Publication | Audience | Content Type | Paid vs. Earned |
|---|---|---|---|
| **Benzinga** | Active retail traders, day traders | Native articles, interviews, sponsored posts, newsletters | Paid placement available |
| **Seeking Alpha** | Long-term retail investors | Long-form analysis, earnings previews | Earned (submit) or sponsored |
| **The Street** | Retail investors, financial advisors | News, analysis, product features | Earned or sponsored |
| **Investopedia** | Retail investor education audience | Sponsored content, product reviews | Paid |
| **Yahoo Finance** | Broad consumer finance audience | Wire pickup (automatic via Accesswire/PRN) | Via wire distribution |

### Financial Social Amplification (Tier 3 — Community Reach)

After distributing via wire, amplify via:
- StockTwits: Post company update on ticker page
- Twitter/X: Link to release with key stats
- Reddit (r/investing, r/stocks): Community-appropriate posts
- LinkedIn: CEO/IR officer post with company page tag

---

## Release Timing Strategy

### By Market Hours

| Timing | Recommended For | Notes |
|---|---|---|
| **Pre-market (7–8 AM ET)** | Earnings releases, major news | Traders see before market open; wire services and media have time to process |
| **Market hours (9 AM–4 PM ET)** | Product news, partnerships | Gets real-time attention; risk of news getting lost in market noise |
| **After market (4:15–6 PM ET)** | Earnings releases (alternative) | Time for analysis before next trading day |
| **Weekend** | Non-material updates only | Low readership; avoid for time-sensitive news |

**Best practice for earnings**: Release after market close (4:15 PM ET) or before pre-market (7:30 AM ET). Never during active trading unless required.

### By Earnings Cycle

| Timing | Action |
|---|---|
| 4–6 weeks before | Begin financial media outreach, pitch articles |
| 1–2 weeks before | Earnings preview pitch to Benzinga/Seeking Alpha |
| Day of earnings | Wire distribution + social amplification |
| 1–2 weeks after | Analyst recap pitch, Seeking Alpha commentary |
| Between earnings | 1–2 product/milestone releases per month |

---

## Press Release Structure

### Standard Financial PR Template

```
FOR IMMEDIATE RELEASE / EMBARGOED UNTIL [DATE TIME ET]

[COMPANY NAME] [VERB: Reports, Announces, Launches, Achieves] [KEY RESULT]

[City, Date] — [COMPANY NAME] (Ticker: [TICKER]), a [one-line company description], today announced [key news in one sentence].

[PARAGRAPH 1: Lead — the most important fact. Answer: who, what, when, where, why.]

[PARAGRAPH 2: Business impact — what does this mean for investors? Revenue, contracts, market opportunity.]

[PARAGRAPH 3: CEO Quote — forward-looking but cautious; include safe harbor if any projections.]

[PARAGRAPH 4: Supporting details — secondary facts, metrics, context.]

About [Company Name]
[3–4 sentence boilerplate describing the company, its products, exchange listing, and ticker.]

Forward-Looking Statements
This press release may contain forward-looking statements... [safe harbor language]

Investor Contact:
[Name]
[Email]
[Phone]

Media Contact:
[Name]
[Email]
[Phone]
```

### Headline Formula

Good financial PR headlines follow the pattern:
```
[Company] [Achieves/Reports/Announces] [Specific Metric or Milestone] for [Time Period]
```

Examples:
- "Laser Photonics Reports Record Q3 Revenue of $X Million"
- "Laser Photonics Secures $X Defense Contract with U.S. Navy"
- "LASE Watchlist Additions Surge 66x Following December Campaign"

---

## Content Cadence Planning

### Recommended Monthly IR PR Cadence

| Frequency | Content Type | Platform |
|---|---|---|
| 1–2x/month | Official press release | Wire service (Accesswire) |
| 2–4x/month | Financial media placement | Benzinga, Seeking Alpha, The Street |
| Weekly | Social amplification | Twitter/X, StockTwits, LinkedIn |
| Quarterly | Earnings release + presentation | Wire + IR website |

### Content Calendar Template

```
Month: [Month]

Week 1:
- [Date] — Wire release: [Topic]
- [Date] — Benzinga article: [Topic]

Week 2:
- [Date] — Seeking Alpha pitch: [Topic]
- [Date] — Twitter/StockTwits amplification

Week 3:
- [Date] — Wire release: [Topic] (if applicable)
- [Date] — Newsletter mention / financial podcast pitch

Week 4:
- [Date] — Earnings preview pitch (if near earnings)
- [Date] — The Street or financial blog placement

Monthly total: [X] releases, [Y] placements
```

---

## Measuring PR Impact

### Key Metrics

| Metric | How to Track |
|---|---|
| Wire pickups | Accesswire/PRN distribution report (# of outlets that picked up) |
| Web traffic from PR | GA4 Referral traffic from wire/Benzinga/Seeking Alpha after release |
| Search volume spike | Google Search Console — branded searches after release |
| Social amplification | Twitter/X impressions, StockTwits ticker activity |
| Trading volume | Compare stock volume on release day vs. 30-day average |
| Watchlist adds | StockTwits watchlist / brokerage data if available |

### PR Attribution Model

```
Baseline day: Average [sessions / volume / watchlist adds] in 5 days before release
Release day: Same metrics on day of release
Lift: (Release day metric - Baseline) / Baseline × 100%

Strong PR performance: 50%+ lift in web traffic, 2x+ spike in trading volume
```

---

## Journalist & Analyst Relationships

### Building the Press List

Target these tiers for financial companies:
1. **Wire service auto-distribution** (automated via Accesswire/PRN)
2. **Financial media beat reporters** (Benzinga editors, Seeking Alpha contributors)
3. **Sector-specific analysts** (if you have sell-side coverage)
4. **Financial podcasters** (investor-focused shows)
5. **Financial newsletter writers** (Substack, Beehiiv financial newsletters)

### Pitch Template (Financial Media)

```
Subject: [TICKER]: [Key news hook in 5 words]

Hi [Name],

[Company name] (Ticker: [TICKER]) just [key news in one sentence].

This might be interesting for your [publication/audience] because [why it matters to their readers — specific angle].

Key stats:
• [Metric 1]
• [Metric 2]
• [Metric 3]

Happy to arrange a [CEO/CFO/IR] interview or provide additional materials.

[Your name]
[Title]
[Contact info]
```

---

## Task-Specific Questions

1. What is the announcement and when does it need to go out?
2. Do you have an Accesswire (or other wire service) account?
3. Is this a material announcement requiring immediate 8-K filing with the SEC?
4. Do you have existing relationships with Benzinga, Seeking Alpha, or The Street?
5. What was the last release you distributed, and how did it perform?
6. What is your monthly PR budget?
7. Do you need help writing the release, distributing it, or both?

---

## Tool Integrations

| Tool | Purpose |
|---|---|
| **Accesswire** | Wire distribution, IR-focused distribution network |
| **PR Newswire / Globe Newswire** | Broad financial media wire distribution |
| **Benzinga Pro** | Financial news placement, interview scheduling |
| **Seeking Alpha** | Long-form investor content submission and sponsored posts |
| **Google Search Console** | Measure branded search volume lift post-release |
| **Google Analytics 4** | Referral traffic from media placements |
| **Meltwater / Mention** | Monitor media pickup and brand mentions |

---

## Related Skills

- **investor-relations-marketing**: For the overall IR marketing strategy
- **copywriting**: For writing compelling press release copy
- **content-strategy**: For planning the editorial calendar beyond press releases
- **financial-social-platforms**: For amplifying releases on StockTwits, Reddit, Twitter/X
- **analytics**: For measuring traffic lift from press releases in GA4
- **campaign-reporting**: For including PR impact in monthly campaign reports
