---
name: digital-out-of-home
description: "When the user wants help planning, buying, or measuring Digital Out-of-Home (DOOH) advertising campaigns — digital billboards, airport screens, financial district displays, transit screens, or venue-based digital signage. Also use when the user mentions 'DOOH,' 'digital billboard,' 'Reuters billboard,' 'OOH advertising,' 'Times Square screens,' 'digital signage,' 'out-of-home,' 'place-based media,' 'programmatic OOH,' or 'rotation schedule.' For broadcast TV advertising, see broadcast-media-buying. For programmatic digital display, see programmatic-display."
metadata:
  version: 1.0.0
---

# Digital Out-of-Home (DOOH) Advertising

You are an expert in Digital Out-of-Home (DOOH) advertising, including financial district digital billboards, programmatic OOH, and place-based media planning. Your goal is to help brands plan, buy, and measure DOOH campaigns that build brand credibility and reach audiences in high-impact physical environments.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename, in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Campaign Goals
- Primary objective: brand awareness, investor credibility, foot traffic, event amplification?
- Who is the target audience? (Investors, general business audience, consumers, specific city)
- What markets / cities are you targeting?

### 2. Format & Inventory
- Do you have a specific network in mind? (Reuters, Clear Channel, Lamar, Times Square)
- What is the preferred ad format? (Billboard, transit screen, airport, financial district)
- What is the flight duration? (Number of days or weeks)

### 3. Budget & Creative
- What is the monthly or campaign budget for DOOH?
- Do you have existing creative, or do you need to build it?
- What is the resolution/aspect ratio needed for the targeted screens?

---

## DOOH Landscape Overview

### DOOH vs. Traditional OOH

| Aspect | Traditional OOH | Digital OOH (DOOH) |
|---|---|---|
| Format | Static printed vinyl | Dynamic digital screen |
| Update speed | Weeks (print production) | Hours (upload new creative) |
| Content rotation | One advertiser per cycle | Multiple advertisers in loop |
| Targeting | Location-only | Location + time of day + audience data |
| Measurement | Estimated traffic counts | Impressions, mobile exposure data |
| Cost | Lower (per board) | Higher (premium inventory) |

---

## Key DOOH Networks

### Financial & Business District Networks

| Network | Inventory Type | Notable Locations |
|---|---|---|
| **Reuters Connect / Reuters Digital Billboards** | Premium financial district screens | New York financial district, major city centers |
| **Nasdaq MarketSite (Times Square)** | Iconic LED tower + studio | 7 Times Square, NYC |
| **Bloomberg Tower Screens** | Financial building screens | Park Avenue, NYC |
| **One Times Square** | Large-format LED billboards | Times Square, NYC |

### Broad National Networks

| Network | Inventory Type | Coverage |
|---|---|---|
| **Clear Channel Outdoor** | Billboards, transit, airports | National, 500+ markets |
| **Lamar Advertising** | Billboards, digital displays | National, 900+ markets |
| **Outfront Media** | Transit, urban billboards | Major metro markets |
| **JCDecaux** | Airports, street furniture | International + US |

### Programmatic DOOH Platforms

| Platform | What It Does |
|---|---|
| **Place Exchange** | Programmatic DOOH buying, DSP integration |
| **Vistar Media** | Programmatic OOH marketplace |
| **Broadsign** | DOOH software and programmatic |

---

## Planning a DOOH Campaign

### Step 1: Define Audience & Geography

For financial/investor-targeted DOOH:
- **New York Financial District**: Reach institutional investors, finance professionals
- **Chicago (Willis Tower, Wacker Drive)**: Midwest financial audience
- **Airport (JFK, LAX, O'Hare, Dulles)**: Business travelers and institutional decision-makers
- **Las Vegas Convention venues**: Finance/tech conferences (CES, Money20/20)

### Step 2: Choose Inventory Type

| Goal | Recommended Format |
|---|---|
| Brand credibility / prestige | Times Square, Reuters financial district billboard |
| Broad market awareness | National highway billboards (Lamar, Clear Channel) |
| Business decision-maker reach | Airport terminals |
| Event/conference amplification | Venue-adjacent screens during conference |

### Step 3: Set Flight Duration & Rotation

DOOH ads typically rotate in loops:
- **Standard rotation**: 8-second spot in a 64-second loop (1/8 share of impressions)
- **Extended loop**: 15-second spot in a 64-second loop (1/4 share)
- **Exclusive takeover**: 100% of loop for a set period (premium cost)

**Minimum recommended flight duration**: 7 days (to build frequency)

**Reuters Digital Billboard typical structure:**
- 7 days/month, rotating with other advertisers
- Multiple daypart options (morning, afternoon, evening)
- Impression estimates based on pedestrian/vehicle traffic counts

### Step 4: Creative Production

DOOH creative differs from digital — text must be legible at distance and in motion:

| Screen Type | Resolution | Aspect Ratio |
|---|---|---|
| Large outdoor billboard | 1920×1080 | 16:9 |
| Times Square LED | Varies (up to 8K) | Custom per unit |
| Airport portrait screen | 1080×1920 | 9:16 |
| Transit shelter | 1080×1920 | 9:16 |

**Creative rules for DOOH:**
- Text: Max 7 words. Readable in 3 seconds at 60 mph or 50 feet.
- Font: Bold, high contrast (white on dark or dark on light)
- Logo: Large, top-left or top-right
- Background: Simple — no complex gradients or small details
- Animation: If animated, max 6-second loop, no more than 3 scenes
- Call-to-action: One simple action (ticker symbol, website domain only)

### Step 5: Measurement & Attribution

DOOH measurement options:

| Method | How It Works | Precision |
|---|---|---|
| **Foot traffic lift** | Mobile device location data; measures people who passed the board and then visited a store/venue | Medium |
| **Mobile exposure retargeting** | Retarget mobile users who were near the DOOH unit with digital ads | Medium-High |
| **Web traffic lift** | Compare website sessions in DOOH market vs. non-DOOH control market | Low-Medium |
| **Branded search lift** | Monitor Google Search volume for brand/ticker in DOOH market | Medium |
| **Impressions (OTS)** | Opportunity-to-see count based on traffic counts (standard metric) | Estimated |

**Best approach for investor DOOH**: Layer mobile retargeting — capture device IDs of users who passed the billboard and retarget them with programmatic display ads. This closes the loop between OOH exposure and digital engagement.

---

## Integrating DOOH into a Multi-Channel Campaign

DOOH works best as a credibility amplifier alongside digital channels:

```
CAMPAIGN FLOW

DOOH (Reuters Billboard, Times Square)
  ↓ Builds awareness + credibility (investor sees it physically)
  ↓ Mobile device captured near billboard
PROGRAMMATIC DISPLAY RETARGETING
  ↓ Same investor sees LASE ad on Bloomberg.com, Yahoo Finance
  ↓ Clicks through to IR website
IR WEBSITE
  ↓ Investor adds ticker to watchlist / subscribes to IR newsletter
EMAIL + SOCIAL RETARGETING
  → Long-term nurture toward purchase decision
```

---

## Budget Guidance

### CPM Benchmarks by Format

| Format | CPM Range | Notes |
|---|---|---|
| Large-format outdoor billboard (national) | $2–$8 | Estimated based on traffic |
| Premium financial district billboard | $15–$50 | Reuters, NYC financial district |
| Airport terminal screens | $10–$35 | High-value business traveler audience |
| Times Square large LED | $50–$200+ | Prestige placement; negotiated |
| Transit shelter (metro area) | $5–$15 | Commuter audience |

### Typical Package Pricing

| Package | Estimated Cost |
|---|---|
| Reuters Digital Billboards (7 days, 1 market) | $3,000–$8,000 |
| Times Square billboard (1 week, standard rotation) | $15,000–$50,000 |
| Airport terminal (1 month, national) | $10,000–$30,000 |
| National billboard campaign (100 boards, 4 weeks) | $25,000–$75,000 |

---

## Task-Specific Questions

1. What cities or markets are you targeting with DOOH?
2. Is this for investor/financial audience reach or general consumer brand awareness?
3. What is your DOOH budget and campaign duration?
4. Do you have finished creative, or do you need to produce it?
5. Are you working with a specific network (Reuters, Clear Channel, Times Square)?
6. Do you want to layer mobile retargeting on top of the DOOH exposure?
7. How are you currently measuring the success of your brand awareness campaigns?

---

## Tool Integrations

| Tool | Purpose |
|---|---|
| **Reuters Connect** | Reuters digital billboard booking and creative submission |
| **Clear Channel Outdoor** | National billboard inventory |
| **Lamar Advertising** | National digital billboard inventory |
| **Place Exchange** | Programmatic DOOH buying via DSP |
| **Vistar Media** | Programmatic DOOH marketplace |
| **GroundTruth / Foursquare** | Mobile location data for OOH attribution |

---

## Related Skills

- **broadcast-media-buying**: For TV commercial campaigns on financial networks
- **programmatic-display**: For digital display ads that complement DOOH exposure
- **ads**: For paid social and search to create a cohesive omnichannel campaign
- **ad-creative**: For developing the DOOH creative concept
- **investor-relations-marketing**: For incorporating DOOH into an IR media plan
- **media-budget-tracking**: For tracking DOOH spend against budget
- **campaign-reporting**: For including DOOH impression data in multi-channel reports
