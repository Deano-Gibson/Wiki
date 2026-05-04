---
title: Recommended Client Project Stack
status: draft
tags: [client-delivery, stack-selection, delivery]
updated: 2026-05-04
---

# Recommended Client Project Stack

## Default Recommendation

Use maintainable, well-known tools with low handover risk.

For typical client web projects:

- Frontend: Next.js or static React depending on requirements
- Hosting: Vercel, Cloudflare Pages, or GitHub Pages for docs/static
- Database: Supabase Postgres when a backend is needed
- Auth: Supabase Auth or Clerk
- Payments: Stripe
- Email: Resend
- Monitoring: Sentry
- CI/CD: GitHub Actions
- Docs: Markdown in repo plus MkDocs when needed

## Prioritize

- Clear ownership
- Simple deploys
- Easy rollback
- Good documentation
- Low support burden
- Handover-friendly tooling

## Avoid

- Novel tools without client benefit
- Over-custom infrastructure
- Tool choices that only the original developer can operate
