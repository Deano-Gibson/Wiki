---
title: Knowledge Workflow
status: active
tags: [systems, obsidian, workflow]
updated: 2026-05-04
---

# Knowledge Workflow

This repo separates capture, curation, and publishing.

## Capture

Put raw thoughts, links, working ideas, and incomplete research in `notes/`.

Recommended folders:

- `notes/inbox/`: quick capture
- `notes/drafts/`: rough notes becoming real pages
- `notes/research/`: research material and source notes
- `notes/working/`: active thinking and project-specific drafts

## Curate

When a note becomes reusable:

1. Remove private or temporary details.
2. Add a stable title.
3. Add minimal frontmatter.
4. Convert important wiki-links to Markdown links.
5. Move or rewrite it into `docs/`.

## Publish

MkDocs builds only from `docs/`. This keeps the public site curated and protects rough working notes from accidental publication.

## Maintain

Review pages when:

- A tool changes pricing or free-tier limits.
- A project exposes a new lesson.
- A checklist misses something important.
- A template gets reused and needs tightening.
