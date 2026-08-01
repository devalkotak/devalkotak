## Deval Kotak

**I break systems to understand them, and build stronger ones.**

Cybersecurity intern at JioStar, where I run pentests against production and
build the tooling that covers what nobody has time to test by hand. Most of
what I know came from pulling something apart to find out why it behaved
strangely. Most of what I build came from not wanting to do that by hand the
next fifty times.

The longer version, plus writeups, lives at
**[devalkotak.github.io](https://devalkotak.github.io)**.

### Security

| Project | What it does |
|---|---|
| [Reachability-CVE-Triage](https://github.com/devalkotak/Reachability-CVE-Triage) | Your scanner says `flask==0.12.2` has an advisory. It does not say whether anything actually imports it. This parses the import graph, finds the HTTP routes and CLI entry points, and ranks every CVE by how close it sits to something an attacker can reach. |
| [Git-Secrets-Scanner](https://github.com/devalkotak/Git-Secrets-Scanner) | Deleting a hardcoded key in your next commit does not delete it. Walks the entire commit history on every branch and reports what is still sitting there, retrievable by anyone with clone access and five seconds. |
| [CIS-Compliance-Checker](https://github.com/devalkotak/CIS-Compliance-Checker) | Somewhere an auditor is working through a PDF checklist one registry value at a time. This is that job as a CLI flag: real CIS Benchmark control IDs, pass or fail per control, with an ISO 27001 Annex A crosswalk for the question that always comes next. |
| [GRC-AWS-Lab](https://github.com/devalkotak/GRC-AWS-Lab) | Risk assessment against live AWS infrastructure, mapped to CIS AWS Foundations v3.0.0, ISO 27001:2022 and the OWASP Top 10. |
| [Fortress-Cipher](https://github.com/devalkotak/Fortress-Cipher) | AES-256-GCM with PBKDF2 key derivation, compressing before it encrypts rather than after, because the other order does very little. |

### Data and markets

| Project | What it does |
|---|---|
| [SMACrossoverStrategy-DhanAPI](https://github.com/devalkotak/SMACrossoverStrategy-DhanAPI) | Paper-trading engine on the Dhan API. Repaint-proof signals, per-symbol state, stop-loss and take-profit, and a PnL cutoff. Built to find out how a trading loop behaves when it cannot see the whole timeline in advance. |
| [Retail-Sales-Warehouse-DBT](https://github.com/devalkotak/Retail-Sales-Warehouse-DBT) | A CRM and ERP warehouse rebuilt from T-SQL onto DuckDB and dbt. No server, no container, no credentials to hand a reviewer. Clone it and you have a star schema in about 20 seconds. |
| [Healthcare-Readmission-Analysis](https://github.com/devalkotak/Healthcare-Readmission-Analysis) | 100,000+ diabetic hospital encounters across 130 hospitals, looking at what actually associates with a 30-day readmission. Three columns were dropped rather than imputed, which was most of the work. |

### Also

Co-founded [Optiverse](https://devalkotak.github.io/optiverse), a student-run
mentorship non-profit that reached 150,000 students across 19 countries before
we paused it. Ran security at DJS ISACA for a year: CTF challenges, hackathon
infrastructure, and a lot of people learning Burp Suite for the first time.

Python, Burp Suite, Wireshark, Nmap, Linux, Bash, pandas. Working through
PortSwigger Academy in order, no skipping.

### Find me

- [devalkotak.github.io](https://devalkotak.github.io)
- [LinkedIn](https://www.linkedin.com/in/devalkotak/)
- devalktk@gmail.com
