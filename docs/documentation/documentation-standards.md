---
title: Documentation Standards
status: active
tags: [documentation, standards, writing]
updated: 2026-05-04
---

# Documentation Standards

Documentation should make future work faster and safer.

## Published Page Requirements

Every page in `docs/` should have:

- A clear title
- Minimal frontmatter
- A specific purpose
- Public-safe content
- Useful links to related pages
- Standard Markdown links

Default frontmatter:

```yaml
---
title: Page Title
status: draft
tags: [documentation, tooling]
updated: 2026-05-04
---
```

## Status Values

- `draft`: useful but still evolving
- `active`: current working guidance
- `evergreen`: durable reference
- `archived`: kept for context, not current guidance

## Writing Rules

- Prefer reusable guidance over stream-of-consciousness notes.
- Keep raw capture in `notes/`.
- Promote only clear and public-safe material into `docs/`.
- Use examples when they reduce ambiguity.
- Keep decisions separate from tool indexes.
- Avoid private names, credentials, client secrets, and sensitive context.

## Link Rules

- Use standard Markdown links in `docs/`.
- Wiki-links are allowed in `notes/`.
- Normalize important links when promoting content.
