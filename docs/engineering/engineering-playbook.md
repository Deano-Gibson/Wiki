---
title: Engineering Playbook
status: active
tags: [engineering, tools, architecture]
updated: 2026-05-04
---

# Engineering Playbook

A living reference of software engineering tools, categorized by system layer. Use this as lookup, comparison, and decision-support material.

## How To Use This

For any project, answer:

1. Auth: which provider?
2. Data: which database?
3. Compute: serverless, container, edge, or static?
4. Async: queues, workflows, or scheduled jobs?
5. Delivery: CI/CD and hosting?
6. Observability: logs, metrics, traces, and errors?
7. AI: where does it actually fit?

## Version Control And Collaboration

- Git: foundational distributed version control
- GitHub: Actions, pull requests, ecosystem
- GitLab: full DevOps platform
- Bitbucket: Atlassian integration
- Perforce: large binary repos
- Gitea: lightweight self-hosted Git
- Graphite: stacked diffs workflow

## CI/CD And DevOps

- GitHub Actions
- GitLab CI/CD
- Jenkins
- CircleCI
- ArgoCD
- Flux
- Dagger
- Earthly
- Buildkite

## Containers And Infrastructure

- Docker
- Kubernetes
- Helm
- Terraform
- Pulumi
- Fly.io
- Railway
- Render
- Podman
- k3s

## Cloud And Deployment

- AWS
- Azure
- Google Cloud
- Vercel
- Netlify
- Cloudflare
- DigitalOcean
- Hetzner

## Databases

Relational:

- PostgreSQL
- MySQL
- SQLite
- MariaDB

Serverless and managed:

- Neon
- Supabase
- Turso
- CockroachDB

NoSQL:

- MongoDB
- DynamoDB
- Firestore

Cache:

- Redis
- Memcached
- Valkey
- Dragonfly

Search:

- Elasticsearch
- Meilisearch
- Algolia
- Typesense
- OpenSearch

Vector:

- pgvector
- Pinecone
- Weaviate
- Chroma
- Qdrant
- Milvus

## Backend Frameworks

JavaScript and TypeScript:

- Node.js
- Express
- NestJS
- Fastify
- Hono
- Elysia

Python:

- FastAPI
- Django
- Flask
- Litestar

Other:

- ASP.NET Core
- Laravel
- Rails
- Phoenix
- Spring Boot
- Gin

## Frontend And Fullstack

- React
- Next.js
- Vue
- Angular
- Svelte
- Remix
- Astro
- Tailwind CSS
- CSS Modules
- Styled Components

## Testing

- Vitest
- Jest
- PyTest
- Testing Library
- Playwright
- Cypress
- Pact
- k6
- Locust

## Observability

- Sentry
- OpenTelemetry
- Prometheus
- Grafana
- Datadog
- Loki
- Jaeger

## Auth

- Supabase Auth
- Clerk
- Auth0
- Firebase Auth
- Auth.js
- Keycloak
- WorkOS
- Ory
- Zitadel

## Messaging And Background Work

- RabbitMQ
- Kafka
- NATS
- SQS
- BullMQ
- Celery
- Sidekiq
- Temporal
- Inngest
- Trigger.dev

## Security

- Vault
- Doppler
- Snyk
- Dependabot
- Trivy
- Semgrep
- SonarQube

## AI Tools

Coding:

- Cursor
- GitHub Copilot
- Claude Code
- Aider
- Cline

Frameworks:

- LangChain
- LlamaIndex
- AutoGen
- CrewAI

Infra:

- Replicate
- Modal
- Hugging Face
- Ollama

Evaluation:

- LangSmith
- Weights & Biases
- PromptLayer
- Helicone

## Notes

Prefer decision guides over raw lists when starting real projects. Use this playbook to discover options, then use the decision documents to choose.
