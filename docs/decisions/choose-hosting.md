---
title: Choose Hosting
status: draft
tags: [hosting, deployment, decisions]
updated: 2026-05-04
---

# Choose Hosting

## Default Recommendation

Use GitHub Pages for static documentation sites.

Use Vercel for frontend-heavy Next.js apps.

Use Cloudflare Pages for static or edge-first apps.

Use Render, Railway, Fly.io, or Cloud Run when the app needs a real backend service.

## Choose Based On

- Static site, server-rendered app, API, worker, or container
- Build and deploy complexity
- Preview deployment needs
- Environment variable model
- Background jobs
- Runtime limits
- Domain and DNS control

## Avoid

- Hosting long-running jobs on platforms optimized for short serverless requests
- Adding containers before the app needs them
- Choosing a platform without checking production logs and rollback workflow
