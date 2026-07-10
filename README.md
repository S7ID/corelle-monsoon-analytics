# Corelle India — Performance Analytics Dashboard

Live, interactive analytics for the **Corelle India** Meta Ads account, built for the **Monsoon Mania** relaunch.

**🔴 Live dashboard → https://s7id.github.io/corelle-s7-ad-analytics/**

- Single self-contained `index.html` — no build step, no dependencies, theme-aware (light/dark), interactive hover tooltips.
- **Data source:** Meta Ads API (live pull), window **11 Apr – 9 Jul 2026** (last 90 days). Generated **2026-07-10**.
- **Headline metric:** blended **MER** = all corelle.co.in revenue since a campaign's start ÷ ad spend over that period (site revenue live from Shopify). Meta's platform ROAS is a secondary optimisation signal only.

## What's inside
- Headline KPIs (ROAS, spend, revenue, impressions, clicks, CTR, CPC, CPM, reach, last-30d)
- **Daily spend & return** trend (interactive area chart)
- **Age × ROAS** and **gender** breakdowns
- **Placement** (Feed / Stories / Reels) and **device** (iPhone / Android) efficiency
- **Facebook vs Instagram** and **top states** geography
- Campaign table + a "what the data says" insights panel

## Headline (90 days)
| Metric | Value |
|---|---|
| **Blended MER (90d)** | **14.8×** |
| Site revenue (90d) | ₹15,41,174 · 292 orders · AOV ₹5,278 |
| Ad spend (90d) | ₹1,03,977 |
| Meta ROAS (platform signal) | 4.52× |
| Impressions | 314,332 · Reach 95,973 |
| CTR / CPC | 7.63% / ₹4.33 |

## Key reads
- **Relaunch moment** — last 30 days only ₹1,073 spent on a proven 4.52× base.
- **Feed is the money** — 74% of spend at 4.93× ROAS; FB Reels weakest (1.57×).
- **Fund the young** — 25–34 returns 8.06×; 35–44 over-funded and weakest (3.18×).
- **iPhone > Android** on ROAS (4.86× vs 3.74×); **women** are 80% of spend at higher ROAS.
- **Geo:** Maharashtra & Delhi lead; the South is a deep, consistent pocket.

## Refresh
Static snapshot. To refresh: re-pull the Meta Ads metrics, update the data arrays in `index.html`, and push — GitHub Pages redeploys automatically.

---
*Note: this is a **public** GitHub Pages URL — it contains ad spend & ROAS. Prepared for S7 HQ Marketing Analytics.*
