---
title: Free And Free-Tier Engineering Tools
status: active
tags: [tools, free-tier, stack-selection]
updated: 2026-05-04
---

# Free And Free-Tier Engineering Tools

A curated table of tools that are free, open-source, self-hostable, or useful on a free tier.

Ratings are directional. Choose based on use case, constraints, and operating cost, not only popularity.

## Auth And Identity

| Tool | Type | Free Tier | Rating | Best For | Avoid When |
| --- | --- | --- | --- | --- | --- |
| Supabase Auth | Hosted | Yes | 5/5 | MVPs, Postgres-native auth | Complex enterprise SSO |
| Clerk | Hosted | Yes | 4/5 | Fast UI and auth | Strict self-hosting |
| Firebase Auth | Hosted | Yes | 4/5 | Quick social login | Avoiding lock-in |
| Auth0 | Hosted | Limited | 4/5 | Enterprise SSO | Cost-sensitive scale |
| WorkOS | Hosted | Limited | 5/5 | B2B enterprise auth | Small apps |
| Auth.js | Library | Yes | 4/5 | Next.js apps | Non-Next stacks |
| Keycloak | Self-hosted | Yes | 4/5 | Enterprise IAM | Simple apps |
| Ory | Self-hosted | Yes | 4/5 | Modular identity infra | Small teams |

## Databases

| Tool | Type | Free Tier | Rating | Best For | Avoid When |
| --- | --- | --- | --- | --- | --- |
| PostgreSQL | Self-hosted | Yes | 5/5 | Most apps | Rarely |
| SQLite | Embedded | Yes | 4/5 | Local-first apps | Multi-user server systems |
| Supabase | Hosted | Yes | 5/5 | Rapid backend | Heavy custom backend logic |
| Neon | Hosted | Yes | 4/5 | Serverless Postgres | Strict latency control |
| Turso | Hosted | Yes | 5/5 | Edge SQLite | Heavy relational workloads |
| DuckDB | Embedded | Yes | 5/5 | Local analytics | OLTP apps |
| MongoDB Atlas | Hosted | Yes | 4/5 | Flexible schema | Strong relational needs |
| Redis | Self-hosted | Yes | 5/5 | Cache and queues | Durable primary storage |
| Upstash Redis | Hosted | Yes | 4/5 | Serverless cache | High-throughput workloads |
| Meilisearch | Self-hosted | Yes | 4/5 | Quick search | Complex analytics |
| Typesense | Self-hosted | Yes | 4/5 | Fast search | Large search clusters |
| pgvector | Extension | Yes | 5/5 | Embeddings in SQL | Massive vector scale |
| Chroma | Self-hosted | Yes | 4/5 | Simple vector apps | Enterprise scale |

## Deployment And Hosting

| Tool | Type | Free Tier | Rating | Best For | Avoid When |
| --- | --- | --- | --- | --- | --- |
| Vercel | Hosted | Yes | 5/5 | Frontend and SSR | Long-running jobs |
| Netlify | Hosted | Yes | 4/5 | Static and JAMstack | Backend-heavy apps |
| Cloudflare Pages | Hosted | Yes | 5/5 | Edge and static apps | Traditional backend apps |
| GitHub Pages | Hosted | Yes | 4/5 | Static docs | Dynamic apps |
| Railway | Hosted | Limited | 4/5 | Quick fullstack deploys | Strict free uptime |
| Render | Hosted | Limited | 4/5 | Simple APIs | Free tier sleeping |
| Fly.io | Hosted | Limited | 4/5 | Geo apps | Simple static sites |

## CI/CD

| Tool | Type | Free Tier | Rating | Best For | Avoid When |
| --- | --- | --- | --- | --- | --- |
| GitHub Actions | Hosted | Yes | 5/5 | Most GitHub repos | Complex enterprise pipelines |
| GitLab CI/CD | Hosted | Yes | 4/5 | GitLab projects | GitHub-first teams |
| Jenkins | Self-hosted | Yes | 2/5 | Legacy systems | Modern greenfield setups |
| Dagger | Open-source | Yes | 4/5 | Pipelines as code | Simple docs sites |

## AI Coding And Agents

| Tool | Type | Free Tier | Rating | Best For | Avoid When |
| --- | --- | --- | --- | --- | --- |
| Cursor | IDE | Limited | 5/5 | Daily AI-assisted dev | Offline-only work |
| Cline | Open-source | Yes | 4/5 | Local agent workflows | Plug-and-play UX |
| Aider | CLI | Yes | 4/5 | Git-based coding | GUI-first workflows |
| Continue | Open-source | Yes | 4/5 | Custom AI coding setup | Non-technical users |
| Claude Code | Tool | Limited | 5/5 | Reasoning-heavy code tasks | Cost-sensitive usage |

## Observability

| Tool | Type | Free Tier | Rating | Best For | Avoid When |
| --- | --- | --- | --- | --- | --- |
| Sentry | Hosted | Yes | 5/5 | Error tracking | Full APM replacement |
| Prometheus | Self-hosted | Yes | 5/5 | Metrics | Tiny apps |
| Grafana | Self-hosted | Yes | 5/5 | Dashboards | Quick hosted-only setup |
| OpenTelemetry | Framework | Yes | 5/5 | Tracing standardization | MVP complexity |
| Loki | Self-hosted | Yes | 4/5 | Logs | Enterprise managed logging |
| Better Stack | Hosted | Limited | 4/5 | Uptime and logs | Deep APM |

## Recommended Free MVP Stack

- Frontend: Vercel or Cloudflare Pages
- Backend: Supabase
- Database: Postgres
- Auth: Supabase Auth
- Queue: BullMQ and Redis when needed
- CI/CD: GitHub Actions
- Monitoring: Sentry
- Linting: Biome
- Local AI: Ollama
- Diagrams: Mermaid and diagrams.net

Keep this page reviewed because free tiers change over time.
