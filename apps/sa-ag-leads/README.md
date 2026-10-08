# Paddock Pipeline

A single-page tool for generating and tracking sales leads in South Australian agriculture.

## Features

- **Pipeline board**: drag leads through New → Contacted → Qualified → Proposal → Won / Lost. Every stage change is logged.
- **Lead scoring**: a 0–100 score from stage, estimated annual value, farm size (ha) and how complete the contact details are. Leads are marked hot, warm or cold.
- **Follow-ups**: overdue and due-today chips, a "Follow up next" list, and a filter for follow-ups that are due.
- **Regional view**: open pipeline value across 12 SA regions, from Eyre Peninsula to Limestone Coast.
- **Find prospects**:
  - an SA seasonal calendar for each sector (seeding, harvest, vintage and so on) showing when to call
  - pre-filled searches on Google Maps, Yellow Pages, LinkedIn and ABN Lookup for the region's towns
  - a list of field days in the region
  - Claude-suggested prospect groups that you can add to the pipeline. These are marked "Unverified".
- **Activity log** for each lead, with Claude-drafted follow-up emails.
- **ABNs**: each lead has an ABN and registered entity name. ABNs are checked with the ABR check-digit rule as you type, linked to their ABN Lookup record, and can be marked "confirmed" once checked there. Leads can be filtered by ABN status, and a confirmed ABN raises the lead score. The finder links to ABN Lookup searches for businesses named after each town. ABN Lookup is not called directly, because artifacts cannot fetch other sites, and Claude never supplies ABNs.
- **CSV import and export** (including `abn`, `legalName`, `abnConfirmed`).

## Running it

- **Published artifact** (shared, saved live): https://claude.ai/artifact/JDbqNGLvHrjYMNbVbikxRu
- **Standalone**: open `index.html` in a browser. Leads are saved to `localStorage` in that browser only. Claude features and CSV download are hidden outside the claude.ai viewer, but Copy CSV still works.
