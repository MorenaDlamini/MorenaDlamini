### Hi, I'm Morena

Software engineer in Johannesburg (Python, TypeScript, SQL). I build systems that keep business
data correct as it moves: payroll-to-app sync pipelines, reconciliation, and multi-tenant
Postgres. Next: analytics models and AI agents on the same data.

### What I've shipped

These live in private repositories. I'm happy to walk through the code and design.

- **Payroll-to-HR leave sync pipeline** (Python, I built it). Keeps about 8,600 leave records for
  two companies in step between the payroll system and a workforce app. In production, running
  unattended on cron 34 times a week.
  - Extracts and normalises payroll records, diffs them against the app, and applies a
    create, update and delete plan. Safe to re-run: when nothing has changed, it writes nothing.
  - Before any write it runs a dry run and takes a backup, and it refuses to sync if payroll
    returns too few records, so an empty API response can't wipe the app.
  - Alerts on failure, sends a weekly digest, and has 109 tests.
  - I worked with the payroll vendor, IT and HR to take it live.
- **Multi-tenant platform for an industrial company** (TypeScript, NestJS, React, PostgreSQL).
  Live, with 93 users. I built the foundation (185 of its 195 commits): one Postgres schema
  per tenant, scripted tenant onboarding, OpenID Connect sign-in, 30 migrations and 20
  architecture decision records.
- **Workforce clock system** (contributor). Moved its web app onto the multi-tenant platform:
  hosting, deployment scripts, the cutover, nightly backups, and the network and firewall spec
  agreed with IT. Built the platform's reader for the old Firebase data during the move. Fixed
  payroll and timesheet exports that timed out on large workbooks, scoped access so each
  manager downloads only their own team's worksheets, and ran releases.

### How I work

**[Engineering practice](https://github.com/MorenaDlamini/dotnet-ai-engineering)**: specs
before code, decision records, tests that name the risk they cover, and written rules for how I
use AI assistants, starting with "I never commit a line I cannot explain". CI runs the tests on
every push.

### Projects

- **randmatch**: payout reconciliation for South African merchants, with an eval-scored AI
  explainer for mismatches. *Design stage: specs and evals written, implementation not
  started.*
  [Matching and exceptions](https://github.com/MorenaDlamini/randmatch-recon) ·
  [Double-entry ledger](https://github.com/MorenaDlamini/randmatch-ledger) ·
  [Test-data simulator with planted errors](https://github.com/MorenaDlamini/randmatch-sim)

### Where to find me

[LinkedIn](https://www.linkedin.com/in/morena-dlamini-b33081169/) ·
[Email](mailto:dlaminimorena@gmail.com)
