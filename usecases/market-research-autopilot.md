# Market Research Autopilot

Let OpenClaw mine Reddit, X, and niche forums to discover real customer pain points — then have it build MVPs that solve them.

## Pain Point

You spend hours reading Reddit threads and X posts trying to find what people actually complain about. By the time you've validated an idea, someone else has shipped it. This workflow automates pain-point discovery and turns the best finds into actionable product specs.

## What It Does

- Scans subreddits and X hashtags in your niche for complaints, feature requests, and frustrations
- Scores pain points by frequency, intensity, and monetization potential
- Generates a weekly 'Opportunity Report' with the top 10 validated pain points
- For the best ones, drafts a product spec, landing page copy, and MVP feature list
- Saves results in your Notion or Google Sheets pipeline

## Skills You Need

- [reddit-readonly](https://clawhub.ai/buksan1950/reddit-readonly) — Browse and search Reddit posts and comments
- [x-engagement](https://clawhub.ai) — Analyze X/Twitter posts and trends
- Web search skill — For broader market research
- Notion or Google Sheets — For storing findings

## How to Set It Up

1. Install the required skills:
```bash
clawhub install reddit-readonly
clawhub install x-engagement
```

2. Add to your OpenClaw agent instructions:
```text
Every Monday at 6 AM, run a market research scan:

1. Search these subreddits for posts with high engagement about problems, frustrations, and wishes:
   [paste your subreddit list]

2. Search X for complaints and feature requests using these keywords:
   [paste your keyword list]

3. For each pain point found, score it on:
   - Frequency (how often people mention it)
   - Intensity (how frustrated they are)
   - Willingness to pay (do they mention paying for a solution?)

4. Compile the top 10 into a report and send to me on Telegram.
5. For any scoring above 8/10, draft a one-page product spec.
6. Save everything to my "Market Research" Notion database.
```

## Real World Example

**You:** "Run a market research scan for AI productivity tools"

**OpenClaw:**

Scanned 47 subreddits and 2,300+ X posts. Here's your weekly opportunity report:

**#1 — AI Meeting Note Fatigue (Score: 9.2/10)**
- 340+ mentions across r/productivity, r/startups, r/SaaS
- People want meeting notes that auto-create tasks in their PM tool — not just summaries
- Willingness to pay: High ($15-30/mo range mentioned)
- Product spec drafted → saved to Notion

**#2 — Email Reply Suggestions That Actually Sound Like You (Score: 8.7/10)**
- 180+ mentions, especially from founders and sales reps
- Current tools sound too generic — people want voice-matching
- Product spec drafted → saved to Notion

[8 more entries...]

Full report saved to your "Market Research" database.

## Variations

- **Niche-specific scanning**: Focus on a single industry (e.g., only scan legal tech or healthcare subreddits)
- **Competitor gap analysis**: Cross-reference pain points against existing solutions to find underserved niches
- **Auto-MVP builder**: For pain points scoring above 9, have OpenClaw build a landing page overnight

## Key Insights

- The best startup ideas come from patterns across multiple sources — not a single Reddit post
- Scoring by willingness-to-pay eliminates 'nice to have' ideas that nobody would actually pay for
- Running this weekly builds a pipeline of validated ideas you can pick from whenever you're ready to build

## Related Links

- [reddit-readonly skill](https://clawhub.ai/buksan1950/reddit-readonly)
- [Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills)

