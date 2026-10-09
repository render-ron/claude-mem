# Ledger Pipeline

A copy of [Paddock Pipeline](../sa-ag-leads/) for generating and tracking leads among South Australian accounting firms. It has its own separate lead database.

## What differs from Paddock Pipeline

- **Regions**: 13 SA areas, from Adelaide CBD and the suburbs to regional centres such as Mount Gambier, Port Lincoln and the Riverland.
- **Specialties** replace farm sectors: small practice, mid-tier, national or Big Four office, bookkeeping and BAS agent, tax agent, SMSF, audit, agribusiness accounting, advisory and virtual CFO, insolvency, and accountant-led financial planning.
- **When to call** follows the tax calendar: peak season July to October, BAS due dates, and SMSF season.
- **Staff (headcount)** replaces farm size in the lead score.
- **TPB number**: tax or BAS agent registration, with a link to the Tax Practitioners Board register.
- **Find prospects** links to the TPB register, CPA Australia's "Find a CPA" and CA ANZ's "Find a CA" directories, and lists industry events.

Everything else is the same: the pipeline board, scoring, follow-ups, ABN and ACN checks, activity log, Claude suggestions, Claude-drafted emails, and CSV import and export.

## Running it

- **Published artifact** (shared, saved live): https://claude.ai/artifact/RFnTqZ7iN14dAL1HkvEQit
- **Standalone**: open `index.html` in a browser. Leads are saved in that browser only.
