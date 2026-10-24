# 77 Metrics Documentation

Source repository for the 77 Metrics help website, App Store marketing copy, and internal documentation research.

## Repository layout

| Path | Purpose |
|------|---------|
| `docs/` | Public help site — built by MkDocs |
| `marketing/` | App Store listing copy and website content — not published by MkDocs |
| `internal/` | Research notes and documentation status — not published |
| `screenshots/` | Screenshot assets shared across docs and marketing |
| `mkdocs.yml` | MkDocs configuration |
| `DOCUMENTATION_STATUS.md` | Per-page documentation progress tracker |

## Local preview

MkDocs Material is required. Install once:

```bash
pip3 install mkdocs-material
```

MkDocs installs to `~/Library/Python/3.9/bin/` on the development machine. Add it to your PATH or use the full path:

```bash
# Serve with live reload
~/Library/Python/3.9/bin/mkdocs serve

# Build static site to site/
~/Library/Python/3.9/bin/mkdocs build
```

The live preview is available at `http://127.0.0.1:8000`.

## Scope

- **Public help site** (`docs/`): user-facing help content, metric reference, FAQ, and release notes. This is what MkDocs builds and what will be hosted publicly.
- **Marketing** (`marketing/`): App Store description, subtitle, keywords, and website landing page copy. Managed separately from the help site.
- **Internal** (`internal/`): App audit notes, documentation research, and per-page status. Never included in the public build.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for style guide and workflow.
