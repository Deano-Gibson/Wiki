---
title: Choose An Auth Provider
status: draft
tags: [auth, decisions, stack-selection]
updated: 2026-05-04
---

# Choose An Auth Provider

## Default Recommendation

Use Supabase Auth when the project already uses Supabase or Postgres and needs fast MVP auth.

Use Clerk when the app needs polished auth UI quickly and vendor lock-in is acceptable.

Use WorkOS or Auth0 when enterprise SSO, SCIM, or B2B identity is a real requirement.

## Choose Based On

- Required login methods
- B2B or B2C audience
- SSO and organization support
- User management UI requirements
- Self-hosting requirements
- Cost at expected scale
- Framework fit

## Avoid

- Building custom auth for a normal MVP
- Choosing enterprise auth for a simple app
- Ignoring account recovery, email verification, and session management

## Future Default

For most small apps: Supabase Auth or Clerk.
