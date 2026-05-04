---
title: File Structure Standards
status: draft
tags: [documentation, file-structure, standards]
updated: 2026-05-04
---

# File Structure Standards

Use predictable file structures so future projects are easier to scan, hand over, and automate.

## Documentation Repo Pattern

```text
docs/       Published documentation
notes/      Working notes and drafts
templates/  Raw reusable templates
```

## Application Repo Pattern

```text
.
+-- README.md
+-- docs/
+-- src/
+-- tests/
+-- scripts/
+-- .github/
+-- .env.example
```

## Naming Rules

- Use lowercase kebab-case for Markdown files.
- Name files by purpose, not date, unless the page is an event log.
- Prefer `index.md` for section landing pages.
- Keep templates in a predictable `templates/` folder.

## Minimum Project Docs

- `README.md`
- `docs/setup.md`
- `docs/deployment.md`
- `docs/architecture.md` or ADRs
- `.env.example`
