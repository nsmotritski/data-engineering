# Data Engineering — A Field Guide

A beginner-friendly introduction to databases, analytical warehouses and data engineering. English by default, with a complete Russian translation.

## Preview

Run `python3 -m http.server 8080 --directory dist`, then open http://localhost:8080.

No dependencies or build step. The static site lives in `dist/`:

- `index.html`: accessible application shell
- `style.css`: responsive sidebar and reading layout
- `app.js`: bilingual chapters, diagrams and hash-based navigation

Direct chapter links use `#en/databases` and `#ru/databases`. Language switching preserves the current chapter. All diagrams are original teaching illustrations; primary references are linked from the chapters and glossary.

Draft v0.1: content and design are ready for editorial review. External image selection remains a future editorial step.

## GitHub Pages

Site: https://nsmotritski.github.io/data-engineering/

The `.github/workflows/pages.yml` workflow publishes `dist/` on every push to `develop`. GitHub Pages uses GitHub Actions as its build source.
