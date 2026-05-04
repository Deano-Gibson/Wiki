---
title: Start Here
status: active
tags: [project-start, workflow, templates]
updated: 2026-05-04
---

# Start Here

Use this page when starting or shaping a project.

## New Project Flow

1. Define the project using the [Project Brief](templates/index.md#project-brief).
2. Pick a default stack from [Best Free MVP Stack](decisions/best-free-mvp-stack.md) or [Recommended Client Project Stack](decisions/recommended-client-project-stack.md).
3. Confirm major choices with the decision guides:
   - [Choose Auth](decisions/choose-auth-provider.md)
   - [Choose Database](decisions/choose-database.md)
   - [Choose Hosting](decisions/choose-hosting.md)
   - [Choose Observability](decisions/choose-observability.md)
4. Write the technical shape with the [Technical Specification](templates/index.md#technical-specification).
5. Apply [File Structure Standards](documentation/file-structure-standards.md).
6. Apply [Documentation Standards](documentation/documentation-standards.md).
7. Track architecture choices with the [ADR Template](templates/index.md#architecture-decision-record).
8. Prepare launch with the [Deployment Checklist](templates/index.md#deployment-checklist).
9. Close delivery with the [Client Handover Checklist](templates/index.md#client-handover-checklist).

## Promotion Flow

Capture first, publish later:

```text
notes/inbox -> notes/drafts or notes/working -> docs/ curated page -> MkDocs site
```

Only promote material into `docs/` when it is reusable, public-safe, and clear enough to help future work.

## Link Rule

Use standard Markdown links in `docs/`. Obsidian wiki-links can be used in `notes/`, but normalize them when promoting content.
