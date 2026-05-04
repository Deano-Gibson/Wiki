---
title: Choose A Database
status: draft
tags: [database, decisions, stack-selection]
updated: 2026-05-04
---

# Choose A Database

## Default Recommendation

Use Postgres unless there is a specific reason not to.

For MVPs, Supabase is the fastest full-platform Postgres default. For serverless Postgres without the full backend platform, use Neon.

## Choose Based On

- Relational data needs
- Query complexity
- Hosting model
- Local development ergonomics
- Migrations and backups
- Team familiarity
- Expected scale

## Common Defaults

- Most apps: Postgres
- Local-first or embedded: SQLite
- Analytics on files: DuckDB
- Edge SQLite: Turso
- Document-heavy flexible schema: MongoDB
- Embeddings in app data: Postgres with pgvector

## Avoid

- Choosing NoSQL to avoid schema design
- Adding a separate vector database before Postgres with pgvector is insufficient
- Picking a database only because the free tier is attractive
