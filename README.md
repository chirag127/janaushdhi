# Oriz Janaushdhi — PMBJP Generic Medicine Catalog

Read-only catalog of the Pradhan Mantri Bhartiya Janaushadhi Pariyojana (PMBJP) generic medicine list. Search, filter, and compare prices. Affiliate links to the nearest PMBJP Kendra.

## Stack

- Astro 6 (static)
- React 19 islands
- Tailwind v4
- @chirag127/astro-shell-npm-pkg + astro-chrome-npm-pkg

## Brand

Product brand: **Janaushdhi** — the program name itself (no extra product brand needed; Janaushdhi is the SEO target).

## Data source

CSV at `/data/janaushdhi.csv` — committed to this repo. Weekly GitHub Actions cron scrapes `pmbjp.gov.in/janaushadhi-product-list.aspx` and commits the latest snapshot.

## Live at

https://janaushdhi.oriz.in

## License

Source-available, all rights reserved. See `LICENSE`.
