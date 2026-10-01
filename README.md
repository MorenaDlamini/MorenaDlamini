# Morena Dlamini

I build C#/.NET software that keeps working when the network doesn't: offline-first desktop and
tablet apps that reconcile when signal returns, ERP-to-cloud integration pipelines, and real-time
operational dashboards. It runs in production, used every day by people who aren't developers.

The code is private. Ask me about any of the design decisions behind it.

## Now building: randmatch

Payout reconciliation for South African merchants who take payments through several providers.
Every provider pays one net, batched deposit. randmatch breaks each one back down into sales,
fees, refunds and holds, and shows what doesn't match.

- **[randmatch-recon](https://github.com/MorenaDlamini/randmatch-recon)**: the product. Matching,
  the exceptions queue, and an AI break-explainer that cites the rows it read and never posts on
  its own. C#, SQL Server, React, Azure.
- **[randmatch-ledger](https://github.com/MorenaDlamini/randmatch-ledger)**: the double-entry
  clearing ledger behind it, with an idempotent posting API and Xero and Sage export. C#,
  Postgres, Angular, AWS.
- **[randmatch-sim](https://github.com/MorenaDlamini/randmatch-sim)**: generates provider
  exports, bank statements and webhooks with planted breaks, so every match rate is measured
  against a known answer.

## How I work

**[dotnet-ai-engineering](https://github.com/MorenaDlamini/dotnet-ai-engineering)**: specs
before code, decision records, tests that name their risk, postmortems, and the AI-review trail
behind every PR. [Dashboard](https://morenadlamini.github.io/dotnet-ai-engineering/)

---

Johannesburg, UTC+2 · [dlaminimorena@gmail.com](mailto:dlaminimorena@gmail.com) · [LinkedIn](https://www.linkedin.com/in/morena-dlamini-b33081169/)
