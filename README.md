# GANTI

GANTI — governed timeline and task-planning visual for dates, progress, and milestones.

## Current platform status

This project inherits the sanitized Data Lake Tables platform for packaging, settings persistence, accessibility, diagnostics, export governance, localization, and regression testing.

**Implementation focus:** Timeline foundation; visual-specific task-bar and dependency renderer is the next implementation layer.

This is an independent implementation. It does not include proprietary source code, logos, assets, identifiers, or branding from reference visuals.

## Data contract

- `task` — Task (Grouping)
- `startDate` — Start date (Grouping)
- `endDate` — End date (Grouping)
- `percentComplete` — Progress (Measure)
- `owner` — Owner (Grouping)
- `milestones` — Milestones (Grouping)
- `tooltips` — Tooltips (Grouping)
