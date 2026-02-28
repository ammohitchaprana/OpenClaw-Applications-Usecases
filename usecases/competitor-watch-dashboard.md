# Competitor Watch Dashboard

Monitor competitor websites, pricing pages, changelogs, and social accounts for changes — get a weekly diff report.

## Pain Point

You find out about competitor launches from your customers instead of catching them early. Manually checking 5-10 competitor websites, changelogs, and social accounts weekly is tedious and unreliable. By the time you notice a change, it's old news.

## What It Does

- Crawls competitor websites and pricing pages weekly, detecting any changes
- Monitors competitor changelogs and release notes for new features
- Tracks competitor social media for product announcements and positioning changes
- Generates a diff report highlighting what changed, what's new, and what it means for you
- Archives historical snapshots for trend analysis

## Skills You Need

- Browser automation — For crawling competitor pages
- Web search — For finding competitor announcements
- [x-engagement](https://clawhub.ai) — Track competitor social accounts
- Google Sheets or Notion — For storing historical data

## How to Set It Up

1. Prompt OpenClaw:
```text
I want you to monitor these competitors weekly:
- [Competitor 1]: website.com, twitter.com/handle, changelog URL
- [Competitor 2]: website.com, twitter.com/handle, changelog URL
- [Competitor 3]: website.com, twitter.com/handle, changelog URL

Every Sunday at 8 PM:
1. Visit each competitor's pricing page and compare to last week's snapshot
2. Check their changelog/blog for new releases
3. Scan their X accounts for product announcements
4. Generate a "Competitive Intelligence Report" with:
   - Pricing changes (old vs new)
   - New features launched
   - Positioning or messaging changes
   - Notable social media activity
5. Send the report to me on Telegram
6. Save snapshots to memory for historical tracking
```

## Real World Example

**You:** "Check my competitors this week"

**OpenClaw:**

**Weekly Competitive Intelligence Report — Feb 24, 2026**

**Competitor A (Acme SaaS):**
- 🔴 Pricing change: Pro plan increased from $29 → $39/mo
- 🟡 New feature: Added AI-powered reporting dashboard
- Social: Announced Series B funding on X (12K likes)

**Competitor B (RivalCo):**
- 🟢 No pricing changes
- 🟡 New feature: Slack integration launched
- Social: Hiring aggressively — 8 new engineering job posts

**Competitor C (BigPlayer):**
- 🔴 Launched a free tier (previously paid-only)
- 🟡 Blog post: "Why we're going open source" — potential strategic shift
- Social: CEO did a podcast about moving downmarket

**Key Takeaways:**
- Competitor A raising prices = opportunity to position on value
- Competitor C launching free tier = they may be targeting your customer segment

## Variations

- **Real-time alerts**: For critical competitors, monitor daily instead of weekly
- **Job posting tracker**: Monitor competitor job boards to infer strategic direction
- **Patent/trademark monitor**: Track new IP filings from competitors

## Key Insights

- Pricing page changes are the highest-signal competitive intelligence — they reveal strategy
- Job postings tell you what competitors are building 6 months before launch
- Historical tracking reveals patterns — e.g., competitor always launches features before their funding announcements

## Related Links

- [OpenClaw Browser Docs](https://docs.openclaw.ai)
- [Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills)

