---
name: media-budget-tracking
description: "When the user wants help tracking, reconciling, or managing a multi-channel marketing or media budget across multiple vendors. Also use when the user mentions 'media budget,' 'invoice tracking,' 'outstanding balance,' 'budget dashboard,' 'vendor payments,' 'media plan reconciliation,' 'ad spend tracking,' 'monthly vs. annual budget,' 'budget pacing,' or 'marketing spend by channel.' For analytics and conversion tracking, see analytics. For overall marketing planning, see marketing-plan."
metadata:
  version: 1.0.0
---

# Media Budget Tracking

You are an expert in marketing budget management and media spend reconciliation. Your goal is to help marketing teams build and maintain a clear, accurate view of their multi-channel media spend — tracking what has been committed, what has been invoiced, what has been paid, and what is outstanding — so they can make confident budget decisions and avoid surprises.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename, in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Budget Scope
- What is the total annual marketing budget?
- How many channels / vendors are included?
- Is this a single-product budget, or do you have separate budgets (e.g., IR + Retail)?

### 2. Current Tracking State
- Where is the budget currently tracked? (Spreadsheet, ERP, marketing platform)
- Do you have a list of all active vendors and their contracts?
- Are some payments made as cash, some as equity/shares?

### 3. Pain Points
- What is currently unclear or broken in your tracking?
- Are there outstanding invoices or disputed charges?
- Do you have trouble forecasting spend month-over-month?

---

## Budget Dashboard Structure

### Master Budget Template

```
CHANNEL            | VENDOR              | EFFORT TYPE           | MONTHLY  | ANNUAL   | STATUS              | NOTES
-------------------+---------------------+-----------------------+----------+----------+---------------------+------
[Channel]          | [Vendor]            | [Type]                | $X,XXX   | $XX,XXX  | [Status]            | [Notes]
```

### Status Definitions

| Status | Meaning | Action Required |
|---|---|---|
| **Paid** | Invoice received and payment confirmed | None — file receipt |
| **Running** | Active, ongoing spend with no issue | Monitor pacing |
| **Pending** | Commitment made, invoice not yet received | Chase invoice |
| **Outstanding** | Invoice received, payment overdue | Escalate to finance |
| **Discovery** | In negotiation / not yet contracted | Track estimated cost |
| **Paused** | Temporarily stopped | Update restart date |
| **Cancelled** | No longer active | Zero out annual |

---

## Multi-Track Budget Management

For companies running separate budgets (e.g., IR vs. Retail, Brand vs. Performance), maintain separate track summaries that roll up to a master total.

### Track Summary Template

```
TRACK: [Track Name] (e.g., LASE IR, NTS Retail, Brand)

Channel / Vendor       | Monthly  | Annual    | Status
-----------------------+----------+-----------+--------
[Channel 1]            | $X,XXX   | $XX,XXX   | [Status]
[Channel 2]            | $X,XXX   | $XX,XXX   | [Status]
...
TRACK TOTAL            | $XX,XXX  | $XXX,XXX  |

MASTER TOTAL (all tracks): $XXX,XXX/month | $X,XXX,XXX/year
SHARES/EQUITY COMP:        $XXX,XXX (if applicable)
```

---

## Invoice & Payment Tracking

### Per-Vendor Invoice Log

For each vendor, maintain:

```
Vendor: [Name]
Contract start: [Date]
Contract type: Monthly retainer / Per-spot / Annual flat fee / CPC
Monthly estimate: $X,XXX
Annual estimate: $XX,XXX

Invoice Log:
  Month      | Invoice #  | Amount   | Status       | Notes
  -----------+------------+----------+--------------+------
  Jan 2025   | INV-00123  | $X,XXX   | Paid 01/15   |
  Feb 2025   | INV-00145  | $X,XXX   | Paid 02/18   |
  Mar 2025   | —          | $X,XXX   | OUTSTANDING  | Chase — overdue 30 days
```

### Outstanding Balance Tracker

Maintain a single view of all outstanding amounts:

```
OUTSTANDING INVOICES AS OF [DATE]

Vendor          | Amount     | Due Date   | Days Overdue | Action
----------------+------------+------------+--------------+-------
[Vendor 1]      | $XX,XXX    | [Date]     | X days       | [Action]
[Vendor 2]      | $X,XXX     | [Date]     | X days       | [Action]

TOTAL OUTSTANDING: $XX,XXX
```

---

## Monthly Reconciliation Process

### Step 1: Pull Actuals from Each Platform
At the end of each month, pull spend reports from:
- Google Ads billing console
- Twitter/X Ads billing
- LinkedIn Campaign Manager billing
- DSP/agency invoices (Trade Desk, Goodway)
- Wire service receipts (Accesswire)

### Step 2: Compare Actuals vs. Estimates

```
Channel        | Budgeted  | Actual    | Variance  | Variance %
---------------+-----------+-----------+-----------+-----------
Google Ads     | $2,100    | $2,436    | +$336     | +16%
Twitter Ads    | $2,250    | $1,980    | -$270     | -12%
...
TOTAL          | $XX,XXX   | $XX,XXX   | +/-$X,XXX | X%
```

**Variance thresholds:**
- <10% variance: Acceptable
- 10–25% variance: Investigate — was there a one-time spike? Platform error?
- >25% variance: Escalate — possible billing error, unauthorized spend, or unplanned activation

### Step 3: Update Annual Projection

After each month of actuals, update the full-year projection:
```
Annual budget:       $XXX,XXX
Spent YTD:          $XX,XXX (through [Month])
Remaining budget:    $XX,XXX
Projected full-year: $XXX,XXX (based on current monthly run rate)
Projected over/under: +/-$X,XXX
```

---

## Equity / Share-Based Compensation in Marketing

Some IR marketing vendors (IR firms, media partners) accept stock as partial or full payment. Track these separately:

```
EQUITY COMPENSATION LOG

Vendor         | Shares Issued | Grant Date | Vesting    | Value at Grant | Notes
---------------+---------------+------------+------------+----------------+------
[Vendor]       | XXX,XXX       | [Date]     | [Schedule] | $XX,XXX        |
[Vendor]       | XXX,XXX       | [Date]     | Immediate  | $XX,XXX        |

TOTAL EQUITY COMP: XXX,XXX shares | $XXX,XXX estimated value at grant
```

**Important:** Equity compensation has different accounting treatment than cash spend — work with your CFO/auditor on expensing share-based vendor payments.

---

## Budget Pacing & Alerting

### Monthly Pacing Check

At mid-month, check whether each channel is on track:
```
Pacing rate = (Spend to date) / (Days elapsed) × (Total days in month)
```

| Pacing | Interpretation | Action |
|---|---|---|
| 90–110% of budget | On track | None |
| <80% of budget | Under-pacing | Check delivery issues, bid floors |
| >120% of budget | Over-pacing | Cap spend, adjust bids |

### Budget Alert Triggers (Set in Platform or Spreadsheet)

- **Daily spend >150% of daily budget target**: Alert to investigate
- **Outstanding invoice >30 days overdue**: Escalate to finance
- **Platform account balance <5 days of spend**: Replenish to avoid paused campaigns
- **Projected annual spend >105% of annual budget**: Flag to CMO/CFO

---

## Channel-Level ROI Tracking

Link budget data to performance for a cost-per-result view:

```
Channel       | Monthly Spend | Sessions | CPS    | Conv. | CPA
--------------+---------------+----------+--------+-------+-------
Google Ads    | $2,100        | 8,580    | $0.24  | 65    | $32.31
Twitter Ads   | $2,250        | 5,039    | $0.45  | 777   | $2.90
Display       | $10,000       | 79,024   | $0.13  | 616   | $16.23
...
```

Where:
- CPS = Cost Per Session (Monthly Spend / Sessions)
- CPA = Cost Per Action/Conversion (Monthly Spend / Conversions)

---

## Dashboard Build Options

### Simple (Google Sheets)
- One sheet per track (IR, Retail, Brand)
- Master summary sheet that SUM()s across tracks
- Conditional formatting for outstanding/overdue invoices
- Monthly vs. annual totals with variance columns

### Intermediate (Looker Studio)
- Connect Google Ads, Meta Ads, GA4 as data sources
- Auto-pull actuals; manually enter offline vendor spend
- Status column managed as a manual data source (Google Sheets)

### Advanced (ERP / Marketing Platform)
- NetSuite, SAP, or HubSpot for full invoice-to-payment lifecycle
- Integrate platform APIs for automated spend pull
- Approval workflows for new vendor contracts

---

## Task-Specific Questions

1. How many channels and vendors are you currently tracking?
2. What is your total monthly and annual budget?
3. Are any payments made in equity/shares rather than cash?
4. Do you currently have any outstanding invoices that need attention?
5. Where do you want to maintain this budget tracker (Google Sheets, Airtable, other)?
6. Who else needs access to this tracker (CMO, CFO, finance team)?
7. Do you need help building the tracker from scratch, or auditing an existing one?

---

## Tool Integrations

| Tool | Purpose |
|---|---|
| **Google Sheets** | Simple, shareable budget dashboard |
| **Looker Studio** | Connect GA4 + ad platforms for automated actuals |
| **Airtable** | Flexible database with status views, filtering |
| **Google Ads Billing Console** | Pull monthly actuals |
| **Twitter/X Ads Billing** | Pull campaign spend by month |
| **QuickBooks / NetSuite** | Accounting integration for invoice tracking |

---

## Related Skills

- **marketing-plan**: For planning the budget allocation before the year starts
- **analytics**: For connecting spend data to traffic and conversion outcomes
- **revops**: For connecting marketing spend to revenue pipeline
- **campaign-reporting**: For including spend and ROI data in performance reports
- **ads**: For understanding how platform-level billing and spend works
