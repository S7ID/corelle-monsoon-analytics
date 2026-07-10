# Corelle India — Performance Analytics Dashboard

A self-contained, single-file analytics dashboard for the **Corelle India** Meta Ads account, built for the **Monsoon Mania** campaign relaunch.

- **`index.html`** — open in any browser, no build step, no dependencies.
- **Data source:** Meta Ads API (live pull), window **11 Apr – 9 Jul 2026** (last 90 days). Generated **2026-07-10**.
- **Scope note:** Meta Ads only. GA4, Microsoft Clarity and Shopify order analytics are **not yet connected for Corelle** (the linked GA4/Clarity properties belong to a different brand), so revenue figures are Meta-attributed (spend × Purchase ROAS), not blended store revenue.

## Headline (90 days)
| Metric | Value |
|---|---|
| Purchase ROAS | 4.52× |
| Ad spend | ₹1,03,977 |
| Attributed revenue (est.) | ₹4,69,976 |
| Impressions | 314,332 |
| Clicks | 23,987 |
| CTR | 7.63% |
| CPC | ₹4.33 |
| Reach | 95,973 |

## Key reads
- **Relaunch moment** — last 30 days only ₹1,073 spent; account warm but idle.
- **Facebook > Instagram** on ROAS (4.71× vs 4.35×) and CPC (₹3.65 vs ₹5.72).
- **Younger converts cheaper** — 25–34 returns 8.06× on minimal spend; 35–44 over-funded and weakest (3.18×).
- **Proven seasonal template** — "Mother's Day 2026" hit 4.95× ROAS at 8.46% CTR; cloned for Monsoon Mania.

## Refresh
This is a **static snapshot**. To refresh, re-pull the Meta Ads metrics and regenerate `index.html`. A future version can be wired to auto-refresh once Corelle's GA4/Shopify are connected for blended, true-ROAS reporting.

---
*Private — contains ad spend & ROAS. Prepared for S7 HQ Marketing Analytics.*
