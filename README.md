### Hi, I'm Morena

Johannesburg · Software Developer · APIs, integrations & systems that stay correct in production

I own delivery end to end: stakeholder conversations → specs → code → tests → CI/CD → release.
I care about dry-run safety, audit trails, and software other people can run without me.

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Start here

- **What I've shipped** — production systems (private; walkthrough on request)
- **Public builds** — small, open artefacts you can clone and run
- **How I work** — specs, tests, governed AI-assisted delivery

## What I've shipped

Production work lives in private repositories (mining / operational systems). Happy to walk through design and code. Titles match the Entelect CV (no internal product names).

| System | What it does | Stack signals |
|---|---|---|
| **Multi-tenant platform + SSO** | Company web spine: schema-per-tenant Postgres, OIDC / ADFS, audited per-app grants, versioned API contract, desktop update feeds, Docker cutovers | TypeScript, NestJS, React, PostgreSQL, Docker |
| **Offline production-floor desktop** | Offline-first tracker on local SQLite; outbox + two-way station sync; hardware bridge for safe tag writes; pilot/general release channels; Vitest / Playwright / pytest in CI | Electron, TypeScript, SQLite, Python |
| **Field-service compliance app** | Took over mid-delivery; certificates, service reports, risk assessments offline with durable sync; ~180 users; Microsoft Store packaging | Electron, JavaScript, Firestore, IndexedDB |
| **Also delivered** | Quality-records desktop (shared client/server reducer); field device config over laptop hotspot + TCP; payroll leave sync with dry-run / backup-before-write | TypeScript / Python / PyQt6 |

## Public builds

| Repo | Status | One-liner |
|---|---|---|
| [Codecast](https://github.com/MorenaDlamini/Codecast) | Live | Podcast player SPA — React, TypeScript, Zustand ([demo](https://codecastpod.netlify.app/)) |
| [rentscape](https://github.com/MorenaDlamini/rentscape) | Demo | Property listings with a hand-rolled MVC in TypeScript |
| [event-risk-gateway](https://github.com/MorenaDlamini/event-risk-gateway) | *Next* | Event-driven risk decisions with dry-run mode, idempotency, tests, CI |
| [randmatch-recon](https://github.com/MorenaDlamini/randmatch-recon) | Specs | Payout reconciliation for SA merchants — matching, exceptions, eval-scored explainer |
| [randmatch-ledger](https://github.com/MorenaDlamini/randmatch-ledger) | Specs | Double-entry clearing ledger (idempotent postings, journal, audit) |
| [randmatch-sim](https://github.com/MorenaDlamini/randmatch-sim) | Specs | Provider/bank test data with planted breaks |

## How I work

Governed delivery, not vibe-only shipping:

1. **Spec first** — written requirements and acceptance criteria before implementation volume  
2. **Human owns judgment** — AI may draft; I keep/reject and I never commit a line I cannot explain  
3. **Tests name the risk** — acceptance tests map to the spec; CI on every push  
4. **Production habits** — dry-run paths, health checks, release notes, handover docs  

Practice lab (habits, not the portfolio face): [dotnet-ai-engineering](https://github.com/MorenaDlamini/dotnet-ai-engineering)

## Stack

```
Languages     TypeScript, JavaScript, Python, SQL · C# / .NET (building depth)
Front end     React, Electron, Vite
Back end      NestJS, Node.js, FastAPI, REST, OIDC / Active Directory
Data          PostgreSQL, SQL Server, SQLite, Firestore
Delivery      Docker, GitHub Actions, Linux, Azure (hosted migrations 2016–2020)
Quality       Vitest, Playwright, pytest · ADRs · dry-run / rollback patterns
```

Polyglot on purpose — pick the runtime that fits the problem; the constant is delivery discipline.

## Connect

[LinkedIn](https://www.linkedin.com/in/morena-dlamini-b33081169/) · [GitHub](https://github.com/MorenaDlamini) · [Email](mailto:dlaminimorena@gmail.com)