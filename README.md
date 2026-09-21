# Morena Dlamini

Software engineer at Booyco Electronics, Johannesburg — a mining-safety manufacturer. I build
the software the business runs on, from the test bench to the field to the dashboards
management reads, for people who are not developers and cannot wait for a fix.

| Shipped | For whom | What it does |
|---|---|---|
| Offline-first desktop and tablet applications | Test engineers on the bench, field technicians on site | Automated hardware testing, field-service compliance — certificates of compliance and service reports — and production traceability. Built to keep working where there is no signal and reconcile when there is. Electron, Firebase |
| End-to-end production tracking | Assembly, QC and dispatch | RFID, NFC and barcode scanning at every step, so a component's history from assembly to dispatch is recorded by the scan rather than by memory |
| Sage ERP → Firebase integration pipeline | Operations | Centralises operational reporting — ERP data and operational records in one place instead of re-keyed between systems |
| Real-time web dashboards | Field services and operations | Production analytics as it happens: what is being built, tested and serviced, live |
| Internal platform with single sign-on *(in progress)* | Every department | One login across the company's internal applications, with each department's tools built for that department rather than one generic portal |

None of it is at scale, and I say so. What it is: real users and real consequences.

### What that work taught me

- **Offline-first** means deciding who wins when two devices disagree.
- **A scan** is only a source of truth if the process cannot skip it.
- **A system boundary** — ERP to database, device to server — is where things break.
- **Single sign-on** is where authentication stops being a library and becomes a design.

### The other half — [worked-examples](https://github.com/MorenaDlamini/worked-examples)

Each topic I study becomes a module: a written lesson, failing tests, my solutions, a spoken
answer. CI runs every module on every push.

- [`CONTRIBUTING.md`](https://github.com/MorenaDlamini/worked-examples/blob/master/CONTRIBUTING.md) — the bar a module clears before it counts
- [`NON-CLAIMS.md`](https://github.com/MorenaDlamini/worked-examples/blob/master/NON-CLAIMS.md) — what the repository refuses to claim
- [`CURRICULUM.md`](https://github.com/MorenaDlamini/worked-examples/blob/master/CURRICULUM.md) — the phases, each with the exit test that ends it. No dates.

### What I'm working toward

The requirements that sit under every senior systems role I have read:

- Operate something in production, for other people
- Design the API and the data model underneath it
- Reason about asynchronous behaviour
- Own reliability, including on-call
- Explain it plainly

---

Johannesburg, UTC+2 · [dlaminimorena@gmail.com](mailto:dlaminimorena@gmail.com)
