# Random-project → Template Storefront

A digital-products business run out of a git repo: sellable spreadsheet templates, their listing copy, covers, and the operations docs — built and maintained with Claude.

## Map

```
products/    The sellable .xlsx files (the actual goods)
listings/    Ready-to-paste Gumroad copy for each product (title, price, description, tags)
covers/      Listing cover images (1280×720)
tracking/    sales-log.csv — one row per sale
BUSINESS.md  The plan: status, your signup checklist, tracking, marketing, roadmap
```

## Working on this repo

- Start with `BUSINESS.md` — it's the single source of truth for status and next actions.
- Templates are built by scripts (openpyxl) and formula-verified with LibreOffice before shipping; if you edit a product, re-verify that every formula still calculates.
- Ask Claude to update the sales log, analyze how the business is doing, build new products, or generate marketing assets.
