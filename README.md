# Personal Knowledge Docs

This repository is a long-term personal knowledge base for reusable engineering, delivery, documentation, systems, templates, tools, and sanitized lessons learned.

It is designed to work as both:

- an Obsidian vault for capture, drafting, and refinement
- a MkDocs Material site that publishes only curated content from `docs/`

## Architecture

```text
Obsidian capture -> notes/ working area -> docs/ curated content -> MkDocs Material -> hosted static site
```

## Repository Layout

```text
docs/       Curated MkDocs-published content only
notes/      Rough notes, drafts, research, and in-progress thinking
templates/  Raw reusable copy-paste templates
.obsidian/  Shared Obsidian vault settings
mkdocs.yml  MkDocs Material configuration
```

`mkdocs.yml` is configured with `docs_dir: docs`, so the published site does not include `notes/`, root files, or private ignored folders.

## Working Rules

- Tracked content should be public-safe by default.
- Capture rough thinking in `notes/`.
- Promote reusable, cleaned-up material into `docs/`.
- Keep private material outside the repo or in ignored folders.
- Use standard Markdown links in `docs/`.
- Obsidian wiki-links are acceptable in `notes/`, but should be normalized before promotion.

## Local Preview

Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

Serve locally:

```powershell
$env:NO_MKDOCS_2_WARNING='true'; python -m mkdocs serve
```

Build:

```powershell
$env:NO_MKDOCS_2_WARNING='true'; python -m mkdocs build --strict
```

## Deployment

GitHub Actions builds and deploys the MkDocs site to GitHub Pages on pushes to `main`.

Use GitHub Pages first. Add a custom `docs.<domain>` once the content structure is stable.
