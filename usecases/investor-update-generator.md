# Investor Update Generator

Pull metrics from Stripe, Google Analytics, and your CRM to draft a polished monthly investor email with charts and narrative.

## Pain Point

Writing investor updates is important but always gets deprioritized. You know you should send monthly updates, but pulling numbers from 5 different tools and crafting a narrative takes 3-4 hours. Most founders either skip months or send low-effort updates.

## What It Does

- Pulls revenue data from Stripe (MRR, growth rate, churn)
- Fetches traffic and conversion data from Google Analytics
- Grabs pipeline data from your CRM or Notion
- Compiles everything into a structured investor update email
- Follows a proven investor update template (Wins, Metrics, Challenges, Asks)

## Skills You Need

- [stripe](https://clawhub.ai) — Revenue and billing data
- [google-analytics](https://clawhub.ai) — Traffic and conversion metrics
- Gmail — For sending the update
- Google Sheets — For data compilation (optional)

## How to Set It Up

1. Install required skills:
```bash
clawhub install stripe
clawhub install google-analytics
```

2. Prompt OpenClaw:
```text
On the 1st of every month at 10 AM, generate an investor update:

1. Pull from Stripe: MRR, MRR growth %, new customers, churned customers, net revenue retention
2. Pull from Google Analytics: unique visitors, signup conversion rate, top acquisition channels
3. Pull from my pipeline (Notion "Sales Pipeline" database): deals in pipeline, closed this month

4. Draft an email using this format:
   - Subject: "[Company Name] — [Month] Investor Update"
   - TL;DR (3 sentences)
   - Key Wins (top 3 highlights)
   - Metrics Dashboard (table format)
   - Challenges & Learnings
   - Key Asks (what I need help with)

5. Send me the draft on Telegram for review before sending.
6. Once I approve, send to my investor list (stored in memory).
```

## Real World Example

**You:** "Draft this month's investor update"

**OpenClaw:**

**Draft ready for review:**

Subject: Acme AI — February 2026 Investor Update

**TL;DR:** MRR grew 18% to $47K. Closed our largest enterprise deal ($2,400/mo). Working on reducing churn in the SMB segment.

**Key Wins:**
1. 🚀 MRR hit $47,200 (+18% MoM)
2. 🏢 Closed first enterprise deal — GlobalCorp at $2,400/mo
3. 📈 Organic traffic up 34% after SEO push

**Metrics:**
| Metric | This Month | Last Month | Change |
|--------|-----------|------------|--------|
| MRR | $47,200 | $40,000 | +18% |
| Customers | 312 | 287 | +8.7% |
| Churn | 3.2% | 2.8% | ⚠️ +0.4% |

**Challenges:**
- SMB churn ticking up — investigating onboarding experience

**Asks:**
- Intro to VP Product at [target company]

Shall I send this to your investor list?

## Variations

- **Board deck generator**: Expand into a full board presentation with slides
- **Weekly internal report**: Shorter version for your team, sent on Mondays
- **LP update for funds**: Modify template for fund managers reporting to LPs

## Key Insights

- Investors consistently say the best founders send regular, honest updates — even when numbers are down
- The 'Asks' section is the most valuable part — it turns a report into an actionable network request
- Automating data collection means your time goes to narrative and strategy, not spreadsheet wrangling

## Related Links

- [Stripe MCP Skill](https://clawhub.ai)
- [Y Combinator Investor Update Template](https://www.ycombinator.com/library)

