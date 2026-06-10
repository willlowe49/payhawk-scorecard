# Payhawk Partner Qualification Scorecard

A lightweight browser-based tool for Partner Managers to score and qualify potential partners using the Payhawk qualification framework.

## What it does

- Score partners across 6 criteria (1–5 each)
- Live total with colour-coded Prioritise / Develop / Deprioritise verdict
- Partner details form with date, contact, next step
- Notes section for key observations
- Copy-to-clipboard summary for pasting into Salesforce, Slack, or email
- Print / Save as PDF

## Scoring criteria

| Criterion | Weight |
|---|---|
| Client Volume & ICP Fit | /5 |
| Partner Motivation | /5 |
| Champion Identified | /5 |
| Technology Ecosystem Fit | /5 |
| Competitive Position | /5 |
| Decision Process Clarity | /5 |
| **Total** | **/30** |

## Tiers

| Score | Tier | Action |
|---|---|---|
| 22–30 | **Prioritise** | Fast-track to partnership agreement within 30 days |
| 14–21 | **Develop** | 90-day nurture plan with defined milestones |
| 6–13 | **Deprioritise** | Light-touch nurture, revisit in 6 months |

## Deployment

This site is deployed automatically via GitHub Pages on every push to `main`.

Live URL: `https://<your-github-username>.github.io/payhawk-scorecard`

## Local development

No build step needed — just open `index.html` in a browser.

## Roadmap

- [ ] Salesforce integration (write scores back to Partner Account record)
- [ ] Pre-populate partner details from Salesforce via URL param
- [ ] Save/load scores from local storage
- [ ] Team leaderboard / pipeline view

---

*Payhawk Partnerships · Internal Use Only · v1.0*
