---
title: Choose An AI App Stack
status: draft
tags: [ai, decisions, stack-selection]
updated: 2026-05-04
---

# Choose An AI App Stack

## Default Recommendation

Start with a normal web app stack and add AI only where it creates clear user value.

Use hosted models first. Add vector search or agent frameworks only after the product flow proves it needs them.

## Common Stack

- Frontend: Next.js or React
- Backend: serverless functions or API routes
- Database: Postgres
- Embeddings: pgvector for simple retrieval
- Observability: Sentry plus model usage logging
- Evaluation: small test sets before complex eval tooling

## Avoid

- Building RAG before documents and retrieval needs are clear
- Adding agent frameworks for simple prompt-response flows
- Storing prompts, outputs, and costs nowhere

## Future Default

Static docs and structured Markdown first. AI retrieval comes later when the knowledge base has enough useful content.
