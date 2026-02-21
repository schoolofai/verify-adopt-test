# Pre-Flight Checklist: verify-adopt-test

## BLOCKING — Team cannot start without these

- [ ] **Product spec from CEO** — What is this product? What problem does it solve? Who is the user?
  - *Status: NEEDED — team can scaffold but cannot build features without direction*

## NEEDED BEFORE LAUNCH — Can start but must have before go-live

- [ ] **Hosting/deployment platform** — Vercel, Railway, Fly.io, or other
- [ ] **Domain name** — if web-facing
- [ ] **CI/CD pipeline** — GitHub Actions (repo already on GitHub)
- [ ] **Environment variables / secrets** — API keys for any external services
- [ ] **Database credentials** — if product requires persistence

## NICE-TO-HAVE — Can work around if not available

- [ ] **Analytics platform** — Google Analytics, Plausible, or PostHog
- [ ] **Error tracking** — Sentry or similar
- [ ] **Custom branding assets** — logo, color palette, fonts
- [ ] **npm organization** — for publishing under a branded scope

## Current State Summary

The repo is a minimal Node.js project with no dependencies, no framework, and no tests. The team can immediately begin:
1. Project scaffolding (package.json setup, linting, testing framework)
2. CI/CD pipeline configuration
3. README and documentation structure

**Blocked on:** Product spec to begin feature development.
