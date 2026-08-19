# Petra Ride — Driver Care Center Dashboard (Prototype)

Interactive prototype dashboard for the Driver Care Center, consolidated from a 93-tab
source workbook into 8 master categories (Registrations, Performance, Fraud, Ratings,
Cases, Incentives, Vehicles, Fines).

## What's in here

`index.html` is a single self-contained file — no build step, no server required.
Open it directly in a browser, or enable GitHub Pages (Settings → Pages → deploy from
`main` / root) to get a shareable link.

It includes:
- Real KPI analytics (computed from the full 38,003-row consolidated dataset)
- Search across all categories, per-category filtering and sorting
- An "Add Record" form (session-only — nothing persists after the tab closes)
- Report export (copy-to-clipboard TSV)

## Data note

This file embeds a **sampled subset** (~400 rows per category, ~2,500 rows total) of
real driver data — names, phone numbers, and case notes — for demoing functionality.
The full 38,003-row consolidated workbook is **not** included in this repo; it was
shared directly with the team lead. Keep this repo private.

## Status

Prototype for team feedback — not a production tool. Data doesn't persist between
sessions; a real deployment would need a backend.
