---
title: Choose Observability
status: draft
tags: [observability, decisions, production]
updated: 2026-05-04
---

# Choose Observability

## Default Recommendation

Use Sentry as the default first production observability tool for app errors.

Add uptime checks, structured logs, and metrics when the app has real users or operational risk.

## Minimum Production Baseline

- Error tracking
- Uptime monitoring
- Deployment visibility
- Basic logs
- Alert destination
- Known owner for alerts

## Tool Defaults

- Error tracking: Sentry
- Metrics: Prometheus and Grafana
- Tracing: OpenTelemetry
- Logs: platform logs first, Loki or Better Stack when needed

## Avoid

- Shipping production without error visibility
- Adding a complex observability stack before there is operational need
- Alerts that nobody owns
