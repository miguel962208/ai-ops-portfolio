# Case Study #0 — C&O Designs: Running a Print-on-Demand Shop with an AI Agent Team

*Repo-ready version, prepared Nov 9, 2026. Merged from the General Manager bot's case study (PDF, Nov 9, 2026) and the owner's figures. Sanitized: no customer data, no credentials, no API keys.*

## Summary

C&O Designs is a one-person print-on-demand shop selling on **Etsy** and **TikTok Shop**, fulfilled through **Printify**, and operated day to day by an AI agent team (Grok Bot, xAI) with human approval gates. The owner spends **2–3 hours per week** on the shop — reviewing and approving batches and handling exceptions.

**Status as of November 9, 2026 (honest version):** the shop is new and **pre-revenue — 0 orders, $0 in sales so far**. This case study documents the operating system and the volume it already handles, not a revenue result.

| Metric | Value |
|---|---|
| Active Etsy listings | 64 |
| TikTok Shop products | ~44 (40 confirmed Nov 6 + 4 published Nov 9) |
| Orders to date | 0 |
| New listings | Weekly batches (7 in the Oct 26 batch; 16 channel listings in the Nov 9 week) |
| Owner time | 2–3 hours/week |
| Estimated hours avoided | 85–90 hours, mid-October → Nov 9, 2026 (assumptions below) |

Catalog mix: seasonal bilingual holiday apparel, home goods, personalized gifts, and printable holiday planners (digital products are Etsy-only).

## The problem

A one-person print-on-demand shop never stops generating work: research what is selling, design original artwork, write listings, set prices that survive platform fees, answer customers, keep the books, and watch two storefronts for flags, expired logins, and listings that never went live. Doing it by hand competes with everything else in the owner's day — so the catalog stalls, quality slips, or prices quietly go underwater. The agent team's job is to take the research, production, monitoring, and bookkeeping off the owner's desk, and leave the owner with decisions.

## How the agent team works

Seven specialist bots run the shop, coordinated by the Shop Manager, with a General Manager above all the businesses' managers. **Nothing is published until the owner approves the batch.**

| Role | Job |
|---|---|
| General Manager (Jarvis) | Morning check-in with the shop manager; verifies important claims; escalates to the owner only when a decision or a sign-in is needed |
| Shop Manager (orchestrator) | Runs the production line, assembles review packages, publishes after approval, checks for orders through the day, files the daily report |
| Researcher | Finds product ideas, reads competitor listings, proposes prices at or below market median |
| Designer | Creates original artwork and realistic mockups; files stay unpublished until owner sign-off |
| Listing Creator | Writes titles, tags, and descriptions; packages photos and digital files per storefront |
| Pricing | Compares proposed prices with similar live listings; flags anything that would miss the profit rule |
| Accountant | Checks fee, cost, and shipping math, including sale scenarios, against a $3 minimum profit per item |
| Customer Service | Watches the shop inbox; set up to personalize an order before print; woken only when there is a real order or message |

**Weekly batch flow:** (1) Research proposes a short list — ideas that can't hold the $3 profit floor are dropped before design; (2) Designer + Listing Creator build the short list, with trademark and language checks; (3) Pricing + Accountant confirm every size/color at least breaks even; (4) **Owner approves the batch** — the team does not treat another agent's go-ahead as the owner's approval; (5) Shop Manager publishes and reports what went live, what failed, and whether storefront counts moved.

Roles that were not earning their keep (specialist SEO, inventory, and shop-social roles) were retired so the team stayed small.

## Volume handled

Operating since early October 2026. By Oct 16 the catalog stood at 36 Etsy listings / 35 TikTok products. Later waves added 32 unique products and 41 channel listings, taking Etsy from 36 → 64:

- Mid-October: 10 personalized gift items launched; 7 Etsy-only printable/spreadsheet planners
- Oct 26: 7 seasonal bilingual holiday apparel listings
- Nov 2: 2 seasonal bilingual tees on both shops (a larger drop, including a family pajama line, was cut because costs broke the profit floor)
- Nov 9: 6 printable holiday downloads + 4 seasonal tees, plus a 6-item holiday-list drop on Etsy (~1:20 PM ET)

Traffic is still modest and is the known bottleneck: e.g., 74 Etsy visits / 138 listing views in the 30 days ending Oct 29; 293 TikTok impressions / 5 clicks Oct 23–29; 0% conversion so far. The bottleneck is discoverability, not production.

## Hours saved — estimate with stated assumptions

The team does not time-track each task, and no dollar figure is claimed. Estimated manual time per task: research/pricing 25 min per product; design + mockups 60 min per product; listing copy/tags/upload 35 min per listing; profit/fee check 10 min per product; second-channel publishing 15 min; daily shop operations 30 min/day; bookkeeping 45 min/week.

Applied to the documented waves (32 unique products, 41 channel listings): ~70 hours of production work + ~15–20 hours of daily operations and bookkeeping = **roughly 85–90 hours of owner time avoided in about four weeks**. This excludes the earlier catalog built before Oct 16, so it is conservative relative to the full stand-up.

## Monitoring and failure handling — real examples

1. **Verify claims instead of trusting dashboard counts.** On Nov 9, after six new Etsy downloads published, the active-listing count rose by only four (53 → 57). The team checked each listing individually and confirmed all six were live rather than assuming failures or republishing.
2. **Usage spike (Nov 1).** The owner's Grok Bot account usage jumped from 38% to 94% overnight (normal overnight usage ~2%). When assistant usage hit its weekly cap, scheduled shop checks paused until the reset. Response: retire unused roles and wake Customer Service only on a real order, so empty checks don't burn budget.
3. **Expired seller sign-in.** The TikTok seller login expired after Nov 6 — blocking fresh stats, a planned sale setup, and flagged-product review — while publishing through Printify still worked (four Nov 9 tees went live anyway). The fix is an owner sign-in, not a workaround. Lesson: treat sign-in health as its own checklist item.
4. **Flagged products.** TikTok flagged a small set of products (e.g., a color-name mismatch with the platform's naming — corrected and resubmitted; an update rejected for inconsistent product information — live version left alone pending owner decision).
5. **$3 minimum-profit guardrail.** Every new product and sale price is checked against a $3 minimum profit per item. The rule has already cancelled a product line and blocked deep discounts that would lose money; older listings are audited against the same floor.
6. **Quality gates before publish.** Trademark screening and a language pass for bilingual listings happen before a batch reaches the owner; personalized orders wait for a manual check so the name is correct before print (path in place; no such orders yet).

## Lessons and next steps

- Production is no longer the bottleneck — a 10–16-listing week is routine. Growth now depends on search visibility and promotion, not more files. (A short Etsy Ads test produced essentially no clicks; creator promotion at 10% commission is set up but has produced no affiliate sales yet.)
- Approval gates are worth the pause: unprofitable or risky ideas are cancelled or rewritten before they reach a storefront.
- Dashboard numbers can lag — a count that doesn't move as expected is a prompt to verify item by item.
- Keep the owner for exceptions: morning reports and empty order checks stay inside the team; the owner is asked to act only on a sale, a failure, or a sign-in.

**Open items (Nov 9, 2026):** restore the TikTok seller sign-in (blocks fresh stats, the planned sale, and flagged-product review); clear the remaining flagged TikTok products; keep the weekly cadence under the same gates; work on discoverability; keep the first-order playbook ready.

*Sources: shop dashboards and the shop team's operating reports, current as of Nov 9, 2026 ET, except where a figure is labeled older or inferred. Hours-saved figures are estimates from the stated assumptions, not time-tracked hours, and no dollar cost is claimed.*
