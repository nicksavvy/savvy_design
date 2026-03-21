# CLAUDE.md

## Project Overview

This is the **Savvy.com design mockup repository** — a collection of static HTML/CSS prototypes for marketing pages and UI component variations. These are visual design references, not a production application.

## Repository Structure

```
savvy_design/
├── savvy-pricing-page-v3.html   # Full landing page for "boosted listings" product
├── why-book-with-savvy-card.html # Card component variations (A–G) with Trustpilot integration
└── CLAUDE.md                     # This file
```

## Tech Stack

- **HTML5 + CSS3** (all styles embedded in `<style>` tags, no external stylesheets)
- **Google Fonts** — Inter font family via CDN
- **Trustpilot widget** — third-party review widget integration
- No JavaScript frameworks, build tools, package managers, or dependencies

## Design System

CSS custom properties define the brand palette:

| Variable        | Value     | Usage               |
|-----------------|-----------|----------------------|
| `--savvy-blue`  | `#1D414C` | Primary brand color  |
| `--pool`        | `#C3E2DB` | Accent / highlights  |
| `--sunrise`     | `#FCB22D` | CTA / badges         |
| `--soft-white`  | `#F4F1E9` | Backgrounds          |
| `--fog`         | `#eff0ed` | Neutral backgrounds  |

## Development Workflow

- **No build step** — open HTML files directly in a browser
- **No tests, linting, or CI/CD** configured
- Files are self-contained; each HTML file includes all its own styles

## Conventions

- Each HTML file is a standalone prototype — keep styles embedded, not in separate CSS files
- Use the CSS custom properties above for brand consistency
- Card variations are labeled alphabetically (A, B, C, D, etc.)
- When adding new page designs, create a new HTML file at the repo root

## Git

- **Primary branch**: `main`
- Commits should describe the design change (e.g., "Add condensed card variations D–G")
- SSH signing is enabled for commits
