# Free / Free-Tier Engineering Tools Index (.md)

A curated table of tools that offer **free tiers** or are **fully free (open-source/self-hosted)**.

**Rating guide:** ⭐⭐⭐⭐⭐ (excellent) → ⭐⭐ (limited/rough). Based on community adoption, stability, DX, and ecosystem.

---

## 🔐 Auth / Identity

| Tool               | Type        | Free Tier | Rating | Best For                   | Avoid When                | Notes                  |
| ------------------ | ----------- | --------- | ------ | -------------------------- | ------------------------- | ---------------------- |
| Supabase Auth      | Hosted      | ✅         | ⭐⭐⭐⭐⭐  | MVPs, Postgres-native auth | complex enterprise SSO    | great DX               |
| Clerk              | Hosted      | ✅         | ⭐⭐⭐⭐☆  | fast UI + auth             | strict self-hosting needs | SaaS-heavy             |
| Firebase Auth      | Hosted      | ✅         | ⭐⭐⭐⭐☆  | quick social login         | avoiding lock-in          | easy                   |
| Auth0              | Hosted      | ⚠️        | ⭐⭐⭐⭐☆  | enterprise SSO             | cost-sensitive scale      | mature                 |
| WorkOS             | Hosted      | ⚠️        | ⭐⭐⭐⭐⭐  | enterprise SSO/SCIM        | small apps                | unmatched B2B features |
| NextAuth / Auth.js | Library     | ✅         | ⭐⭐⭐⭐☆  | Next.js apps               | non-Next stacks           | flexible               |
| Lucia              | Library     | ✅         | ⭐⭐⭐⭐☆  | custom auth flows          | no auth experience        | lightweight            |
| Keycloak           | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | enterprise IAM             | simple apps               | complex                |
| Ory                | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | modular identity infra     | small teams               | powerful               |
| Zitadel            | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | Auth0 alternative          | small/simple apps         | strong OSS option      |

---

## 🗄️ Databases

| Tool          | Type        | Free Tier | Rating | Best For            | Avoid When             | Notes              |
| ------------- | ----------- | --------- | ------ | ------------------- | ---------------------- | ------------------ |
| PostgreSQL    | Self-hosted | ✅         | ⭐⭐⭐⭐⭐  | most apps           | none                   | gold standard      |
| SQLite        | Embedded    | ✅         | ⭐⭐⭐⭐☆  | local-first apps    | multi-user systems     | simple             |
| Supabase      | Hosted      | ✅         | ⭐⭐⭐⭐⭐  | rapid backend       | heavy custom logic     | full platform      |
| Neon          | Hosted      | ✅         | ⭐⭐⭐⭐☆  | serverless Postgres | strict latency control | modern             |
| PlanetScale   | Hosted      | ⚠️        | ⭐⭐⭐⭐☆  | MySQL scale         | free-tier needs        | free tier removed  |
| Turso         | Hosted      | ✅         | ⭐⭐⭐⭐⭐  | edge SQLite         | heavy relational logic | edge-native        |
| DuckDB        | Embedded    | ✅         | ⭐⭐⭐⭐⭐  | local analytics     | OLTP workloads         | insanely fast OLAP |
| MongoDB Atlas | Hosted      | ✅         | ⭐⭐⭐⭐☆  | flexible schema     | relational needs       | popular            |
| Redis         | Self-hosted | ✅         | ⭐⭐⭐⭐⭐  | cache, queues       | persistence            | core tool          |
| Upstash Redis | Hosted      | ✅         | ⭐⭐⭐⭐☆  | serverless cache    | high throughput        | simple             |
| Meilisearch   | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | quick search        | analytics              | easy               |
| Typesense     | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | fast search         | scaling clusters       | lightweight        |
| pgvector      | Extension   | ✅         | ⭐⭐⭐⭐⭐  | embeddings in SQL   | massive scale          | simple AI          |
| Chroma        | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | vector DB (AI apps) | enterprise scale       | simple setup       |

---

## 🚀 Deployment / Hosting

| Tool             | Type   | Free Tier | Rating | Best For          | Avoid When          | Notes        |
| ---------------- | ------ | --------- | ------ | ----------------- | ------------------- | ------------ |
| Vercel           | Hosted | ✅         | ⭐⭐⭐⭐⭐  | frontend + SSR    | long jobs           | best DX      |
| Netlify          | Hosted | ✅         | ⭐⭐⭐⭐☆  | static + JAMstack | heavy backend       | stable       |
| Cloudflare Pages | Hosted | ✅         | ⭐⭐⭐⭐⭐  | edge apps         | traditional backend | powerful     |
| Railway          | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | quick fullstack   | strict uptime needs | dev-friendly |
| Render           | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | simple deploys    | free tier sleeping  | reliable     |
| Fly.io           | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | geo apps          | simple projects     | edge focus   |
| GitHub Pages     | Hosted | ✅         | ⭐⭐⭐⭐☆  | static sites      | dynamic apps        | simple       |

---

## ⚙️ CI/CD

| Tool           | Type        | Free Tier | Rating | Best For          | Avoid When                   | Notes       |
| -------------- | ----------- | --------- | ------ | ----------------- | ---------------------------- | ----------- |
| GitHub Actions | Hosted      | ✅         | ⭐⭐⭐⭐⭐  | most repos        | complex enterprise pipelines | default     |
| GitLab CI/CD   | Hosted      | ✅         | ⭐⭐⭐⭐☆  | all-in-one stack  | GitHub teams                 | integrated  |
| Jenkins        | Self-hosted | ✅         | ⭐⭐☆☆☆  | legacy systems    | modern setups                | outdated DX |
| CircleCI       | Hosted      | ⚠️        | ⭐⭐⭐⭐☆  | fast CI           | budget constraints           | good perf   |
| Buildkite      | Hybrid      | ⚠️        | ⭐⭐⭐⭐☆  | scaling CI        | small teams                  | powerful    |
| Dagger         | Open-source | ✅         | ⭐⭐⭐⭐☆  | pipelines as code | simple CI                    | underrated  |

---

## 🤖 AI Coding / Agents

| Tool         | Type        | Free Tier | Rating | Best For        | Avoid When          | Notes    |
| ------------ | ----------- | --------- | ------ | --------------- | ------------------- | -------- |
| Cursor       | IDE         | ⚠️        | ⭐⭐⭐⭐⭐  | daily dev       | offline-only        | top IDE  |
| Cline        | Open-source | ✅         | ⭐⭐⭐⭐☆  | local agents    | plug-and-play UX    | flexible |
| Aider        | CLI         | ✅         | ⭐⭐⭐⭐☆  | git workflows   | GUI workflows       | fast     |
| Continue.dev | Open-source | ✅         | ⭐⭐⭐⭐☆  | custom setups   | non-technical users | flexible |
| Claude Code  | Tool        | ⚠️        | ⭐⭐⭐⭐⭐  | reasoning-heavy | cost sensitivity    | strong   |

---

## 🧠 AI Infra / Local LLMs

| Tool        | Type   | Free Tier | Rating | Best For             | Avoid When          | Notes         |
| ----------- | ------ | --------- | ------ | -------------------- | ------------------- | ------------- |
| Ollama      | Local  | ✅         | ⭐⭐⭐⭐⭐  | local LLMs           | no GPU/large models | dead simple   |
| LM Studio   | Local  | ✅         | ⭐⭐⭐⭐☆  | GUI LLMs             | CLI workflows       | great UX      |
| Groq        | Hosted | ⚠️        | ⭐⭐⭐⭐⭐  | ultra-fast inference | long context        | insanely fast |
| Together AI | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | open models          | proprietary needs   | cheap         |

---

## 📊 Observability

| Tool          | Type        | Free Tier | Rating | Best For                | Avoid When   | Notes           |
| ------------- | ----------- | --------- | ------ | ----------------------- | ------------ | --------------- |
| Prometheus    | Self-hosted | ✅         | ⭐⭐⭐⭐⭐  | metrics                 | simple apps  | standard        |
| Grafana       | Self-hosted | ✅         | ⭐⭐⭐⭐⭐  | dashboards              | quick setups | great UI        |
| Sentry        | Hosted      | ✅         | ⭐⭐⭐⭐⭐  | error tracking          | full APM     | essential       |
| OpenTelemetry | Framework   | ✅         | ⭐⭐⭐⭐⭐  | tracing                 | MVPs         | future-proof    |
| Loki          | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | logs                    | enterprise   | simple          |
| Highlight.io  | Open-source | ✅         | ⭐⭐⭐⭐☆  | session replay + errors | full APM     | fills gap       |
| Better Stack  | Hosted      | ⚠️        | ⭐⭐⭐⭐☆  | uptime + logs           | deep APM     | great free tier |

---

## 🧪 Testing

| Tool       | Type      | Free Tier | Rating | Best For     | Avoid When       | Notes        |
| ---------- | --------- | --------- | ------ | ------------ | ---------------- | ------------ |
| Jest       | Framework | ✅         | ⭐⭐⭐⭐☆  | JS testing   | ultra-fast needs | standard     |
| Vitest     | Framework | ✅         | ⭐⭐⭐⭐⭐  | modern JS    | legacy setups    | fast         |
| PyTest     | Framework | ✅         | ⭐⭐⭐⭐⭐  | Python       | none             | best         |
| Playwright | Tool      | ✅         | ⭐⭐⭐⭐⭐  | E2E          | simple apps only | best         |
| Cypress    | Tool      | ⚠️        | ⭐⭐⭐⭐☆  | dev UX       | scaling CI cost  | expensive CI |
| k6         | Tool      | ✅         | ⭐⭐⭐⭐☆  | load testing | GUI preference   | simple       |

---

## 📦 Build / Package

| Tool      | Type    | Free Tier | Rating | Best For    | Avoid When     | Notes                    |
| --------- | ------- | --------- | ------ | ----------- | -------------- | ------------------------ |
| npm       | Manager | ✅         | ⭐⭐⭐⭐⭐  | default     | perf-critical  | standard                 |
| pnpm      | Manager | ✅         | ⭐⭐⭐⭐⭐  | performance | legacy tooling | best                     |
| Yarn      | Manager | ✅         | ⭐⭐⭐⭐☆  | stability   | modern alt     | mature                   |
| Vite      | Build   | ✅         | ⭐⭐⭐⭐⭐  | frontend    | legacy apps    | modern                   |
| Webpack   | Build   | ✅         | ⭐⭐⭐⭐☆  | legacy apps | greenfield     | avoid new                |
| Turborepo | Tool    | ✅         | ⭐⭐⭐⭐☆  | monorepos   | small repos    | fast                     |
| Biome     | Tool    | ✅         | ⭐⭐⭐⭐⭐  | lint+format | none           | replaces ESLint+Prettier |

---

## 🎨 Design / UI

| Tool                   | Type       | Free Tier | Rating | Best For                      | Avoid When          | Notes                |
| ---------------------- | ---------- | --------- | ------ | ----------------------------- | ------------------- | -------------------- |
| Figma                  | Design     | ✅         | ⭐⭐⭐⭐⭐  | UI design                     | offline             | standard             |
| draw.io / diagrams.net | Tool       | ✅         | ⭐⭐⭐⭐⭐  | architecture diagrams         | pixel-perfect UI    | free forever         |
| Mermaid                | Tool       | ✅         | ⭐⭐⭐⭐⭐  | code-based diagrams (docs/MD) | drag-and-drop needs | great for repos/docs |
| Eraser.io              | Tool       | ⚠️        | ⭐⭐⭐⭐☆  | AI diagrams                   | free-only needs     | dev-focused          |
| Framer                 | Builder    | ⚠️        | ⭐⭐⭐⭐☆  | quick sites                   | apps                | visual               |
| v0                     | AI UI      | ⚠️        | ⭐⭐⭐⭐☆  | components                    | full apps           | dev tool             |
| Lovable                | AI builder | ⚠️        | ⭐⭐⭐⭐☆  | MVPs                          | control apps        | early                |
| Excalidraw             | Tool       | ✅         | ⭐⭐⭐⭐⭐  | quick diagrams                | formal diagrams     | simple               |

---

## 🌐 API Hosting (Non-BaaS / Real Backends)

| Tool              | Type   | Free Tier | Rating | Best For                  | Avoid When            | Notes       |
| ----------------- | ------ | --------- | ------ | ------------------------- | --------------------- | ----------- |
| Railway           | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | simple APIs, quick deploy | strict uptime SLOs    | great DX    |
| Render            | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | REST APIs, workers        | free tier sleeping    | reliable    |
| Fly.io            | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | geo-distributed APIs      | simple apps           | edge-first  |
| Cloud Run         | Hosted | ⚠️        | ⭐⭐⭐⭐⭐  | containerized APIs        | vendor-agnostic needs | autoscaling |
| AWS Fargate       | Hosted | ⚠️        | ⭐⭐⭐⭐⭐  | scalable container APIs   | simple projects       | prod-grade  |
| DigitalOcean Apps | Hosted | ⚠️        | ⭐⭐⭐⭐☆  | small/medium APIs         | hyperscale            | easy setup  |

---

## 🌐 Local Dev & Tunneling

| Tool              | Type        | Free Tier | Rating | Best For           | Avoid When          | Notes      |
| ----------------- | ----------- | --------- | ------ | ------------------ | ------------------- | ---------- |
| ngrok             | Hosted      | ⚠️        | ⭐⭐⭐⭐⭐  | webhook dev        | custom domains free | essential  |
| Cloudflare Tunnel | Self-hosted | ✅         | ⭐⭐⭐⭐⭐  | persistent tunnels | quick throwaway     | best free  |
| LocalStack        | Self-hosted | ✅         | ⭐⭐⭐⭐☆  | AWS emulation      | full parity         | saves cost |

---

## Notes

* Ratings are directional
* Choose based on use-case, not stars

---

## Recommended Free Stack

* Frontend: Vercel
* Backend: Supabase
* DB: Postgres
* Auth: Supabase Auth
* Queue: BullMQ + Redis
* CI/CD: GitHub Actions
* Monitoring: Sentry
* AI: Cursor + Cline
* Edge: Cloudflare
* Secrets: Infisical
* Linting: Biome
* Tunneling: Cloudflare Tunnel
* Local AI: Ollama
* Diagrams: draw.io
