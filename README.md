# Budget & Procurement Management Dashboard

An interactive dashboard for managing an operations budget line-by-line and tracking the
procurement requisition lifecycle — requisition → approval → purchase order → completion —
with a live utilisation view.

> **Demonstration build.** All figures, vendors, and sites are fictional and anonymized.
> It represents a generic data-centre operations budget and does not contain any real
> organisation's data.

## Features

- **Line-by-line budget** — 2,400+ budget lines with per-line utilisation and budget-health flags
- **Requisition pipeline** — Budgeted → PRF Submitted → Pending Approval → PO Issued → Completed
- **Interactive workflow** — raise and advance requisitions; the dashboard updates live and
  remembers your changes in the browser
- **Dashboard** — KPIs, pipeline funnel, budget-vs-committed by site and by account group,
  and a cumulative planned-vs-committed pacing chart
- **Filters & search** across sites, account groups, status, and budget health

## Technical notes

A single self-contained HTML file — no backend, no build step, no external dependencies
(inline SVG charts, system fonts). Runs entirely in the browser and works offline.
Light and dark themes.

---

© 2026 Erica Chong.XY — submitted as a work sample.
