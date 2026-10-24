# Contributing

Guidelines for writing and maintaining 77 Metrics documentation.

## Workflow

1. Work from the `docs/` directory for all public help content.
2. Check `DOCUMENTATION_STATUS.md` to see what needs writing.
3. Run `mkdocs serve` locally to preview changes before committing.
4. Do not commit the `site/` build output — it is in `.gitignore`.

## Style guide

**Voice and tone**
- Address the reader as "you." Use second person throughout.
- Use active voice. "Tap Start Drive" not "The Start Drive button should be tapped."
- Be direct and brief. One idea per sentence where possible.

**Terminology**
- The app is **77 Metrics** (never "the app" on first reference in a section).
- A recording session is a **drive**, not a "trip" or "session."
- Saved recordings are **drives** in trip history. A **trip** is a named group of drives.
- Dashboard pages contain **tiles**. Tiles display **metrics**.
- Use the exact metric names as they appear in the app (e.g., "Moving Avg", "Net Elevation").

**Formatting**
- Use sentence case for headings: "Your first drive" not "Your First Drive."
- Bold UI element names on first reference in a procedure: **Start Drive**, **Settings**.
- Use ordered lists for step-by-step procedures, unordered for non-sequential items.
- Admonition blocks (`!!! tip`, `!!! note`, `!!! warning`) for callouts.

**Metric pages**
- Each metric page should cover: what the metric measures, how it is calculated, when it shows a dash (—), and any relevant limitations or tips.
- List the display label (as shown on the tile) and the short label (shown in compact tiles).

## What goes where

| Content type | Location |
|---|---|
| Help documentation | `docs/` |
| App Store copy | `marketing/app-store/listing.md` |
| Website landing page | `marketing/website/landing.md` |
| App audit notes | `internal/research/` |
| Documentation progress | `DOCUMENTATION_STATUS.md` |
| Screenshot assets | `screenshots/` |

## Screenshots

Place screenshots in `screenshots/` with descriptive filenames:
`dashboard-portrait-default.png`, `drive-complete-elevation.png`, etc.

Reference them in docs with relative paths:
```markdown
![Default dashboard](../../screenshots/dashboard-portrait-default.png)
```
