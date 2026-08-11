# The Business — Plan & Operations

**What this is:** a digital-products storefront selling polished spreadsheet templates, built and maintained in this repo with Claude. Phase 1 is three money-management templates sold on Gumroad. You handle the accounts and decisions; Claude builds, analyzes, and iterates.

_Last updated: 2026-08-11_

---

## Current status

| # | Product | File | Suggested price | Status |
|---|---------|------|-----------------|--------|
| 1 | Personal Budget Dashboard **v3** — 8 tabs: monthly, annual heatmap, savings goals, debt payoff, bills | `products/personal-budget-dashboard.xlsx` | $12 (launch $9) | ✅ Built & verified — ready to list |
| 2 | Freelance Invoice + Income Tracker **v2** — adds quarterly view, avg days-to-pay, collection rate | `products/freelance-invoice-income-tracker.xlsx` | $14 (launch $11) | ✅ Built & verified — ready to list |
| 3 | Small Business Bookkeeping Tracker **v2** — adds quarterly P&L, fee % per platform | `products/small-business-bookkeeping-tracker.xlsx` | $14 (launch $11) | ✅ Built & verified — ready to list |
| 4 | **Bundle:** The Money Toolkit (all 3) | create as a Gumroad bundle | $29 | ⏳ Create after the 3 singles are live |

Every workbook was formula-verified: all formulas recalculate with zero errors, and dashboard numbers were checked against hand-computed totals from the example data (37 checks on v2).

**All three are break-proof:** formula cells carry sheet protection (no password) so buyers can't wreck the math by accident — the top post-purchase complaint on template listings — while every input cell stays unlocked.

**v2 was built against competitive research:** bestselling budget templates bundle annual + monthly views, savings/debt tracking, and bill trackers in one file, and listings convert on multiple real screenshots with sample data plus keyword-front-loaded titles. All of that is now in: each listing has 3–4 real, unedited screenshots in `listings/screenshots/`, and titles lead with search keywords.

---

## Your signup checklist (one-time, ~30 minutes)

The only accounts a business needs someone real to own. Everything else is already done.

- [ ] **Create a Gumroad account** — gumroad.com → Start selling. Free; Gumroad takes a cut per sale (roughly 10% + card processing — check their current pricing page) and there's no monthly fee, which is why it's the right first platform.
- [ ] **Pick your store name** — set it in Gumroad → Settings → Profile. Ideas: *Ledgerly Studio*, *TidySheets*, *PlainNumbers*. Your call — tell Claude what you picked so listings/covers can match.
- [ ] **Connect your payout method** — Gumroad → Settings → Payments (bank account or PayPal; requires identity verification). Money from sales lands here.
- [ ] **Create the 3 products** — for each one: New product → Digital product → paste the title, price, and description from the matching file in `listings/` → upload the `.xlsx` from `products/` → upload the cover from `covers/` and the gallery screenshots from `listings/screenshots/` (order listed in each listing file) → Publish.
- [ ] **Buy-test one product yourself** at a $0 price or with Gumroad's test mode, so you've seen the buyer experience once.
- [ ] *(Optional, later)* **Etsy shop** — bigger template marketplace, but $0.20 per listing + more fees + more setup. Do it after the first Gumroad sale, not before.

**What you never need to give Claude:** bank details, passwords, or payment logins. If you later want automated sales reporting, Gumroad has an API key you can create with read-only scope — that's the only credential worth discussing, and only when there are sales to report.

---

## How we track the business

- **Sales log:** `tracking/sales-log.csv` — one row per sale. Either paste your Gumroad sales into it, or just tell Claude ("2 budget templates sold this week, $18 net") and Claude updates it and the dashboards.
- **Your own books:** dogfood product #3 — the bookkeeping tracker — with real numbers. First expense to log: $0 so far. First income to log: the goal.
- **Weekly review (recommended):** a scheduled routine can wake up weekly, read the sales log, and produce a short "how's business" report with suggested next actions. Ask Claude to set this up once you've listed the products.

## Marketing starters (all free, no spam)

1. **Pinterest** — templates are one of Pinterest's biggest niches. 2–3 pins per product linking to the Gumroad pages. Claude can generate pin images and copy.
2. **A free lite version** — e.g. a single-tab budget sheet at $0+ on Gumroad. Free products rank well, collect emails, and upsell the paid one.
3. **Gumroad Discover** — good titles/tags/covers (already written) are the whole game; Gumroad promotes products that convert.
4. **One honest Reddit/community post** where allowed — "I made a budget template, here's what it does" with real screenshots. Never astroturf.

## Roadmap

- **Phase 1 (now):** list 3 products, get first sale, learn what converts.
- **Phase 1.5:** bundle + free lite version + Pinterest pins.
- **Phase 2 (after signal):** either double down (more templates in the winning niche, Etsy expansion) or start the bigger swing — a micro-SaaS or an auto-updating niche site. Decision point: ~30 days of data.

## Boring-but-real notes

- Income from sales is taxable income in basically every country; keep the bookkeeping tracker current and talk to a tax person once money is real.
- Refund policy is stated in each listing (30 days) — honor it; refund rate is a quality signal.
- Templates are sold as-is, not financial/tax advice (already noted in the bookkeeping listing).
