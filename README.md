<h1>Victor <sub><sup><code>[lab]</code> data &amp; ai engineer</sup></sub></h1>

**I build systems that _think_, move data and _become product_.**

Agent graphs, LLMs running on a laptop GPU, macro-aware portfolio optimization, sync engines and dashboards that leadership actually trusts. I work end-to-end: data platforms, multi-source architecture, auth and security, multi-agent LLM systems, local inference, quant research — and the product UI on top.

[![Portfolio](https://img.shields.io/badge/portfolio-victorzorzo.com-C6F432?style=flat-square&labelColor=07080A)](https://victorzorzo.com)
[![Projects](https://img.shields.io/badge/case_studies-28-5CE1E6?style=flat-square&labelColor=07080A)](https://victorzorzo.com/projects)
[![Lab](https://img.shields.io/badge/interactive_demos-lab-FFB547?style=flat-square&labelColor=07080A)](https://victorzorzo.com/lab)
[![LinkedIn](https://img.shields.io/badge/linkedin-victor--zorzo-8B8F98?style=flat-square&labelColor=07080A)](https://www.linkedin.com/in/victor-zorzo-1166b7219)

---

### 01 / Agents & LLMs

| | |
|---|---|
| [**Self-Hosted Multi-Agent Research**](https://victorzorzo.com/projects/agent-graph) | The open-source TradingAgents graph on my own GPUs: I added parallel analysts, new providers, macro context for the final decision and a batch runner driven by my optimizer. |
| [**Local LLM Lab**](https://victorzorzo.com/projects/local-llm-lab) | A 9B model with 32k context fully on an 8 GB laptop GPU (llama.cpp); a 27B AWQ model on a rented 48 GB GPU with vLLM. Same OpenAI-compatible API for both. |
| [**Agent Harness & Context Engineering**](https://victorzorzo.com/projects/agent-harness) | Coding agents with read-only MCPs, a knowledge graph of repos, a vault as long-term memory and human checkpoints. Agents never grant access or push on their own. |

### 02 / Quant & Research

| | |
|---|---|
| [**Macro-Aware Portfolio Optimizer**](https://victorzorzo.com/projects/macro-optimizer) | From a broken Markowitz spreadsheet to a Python system with 200+ tests: regime classifier, event-study adjustments, SLSQP max-Sharpe, Monte Carlo frontier, walk-forward validation. |
| [**Quant + AI Research Terminal**](https://victorzorzo.com/projects/divergence-terminal) | The optimizer says how much to hold, the agents say why — and the rows that matter are where they disagree. |

### 03 / Data Engineering

| | |
|---|---|
| [**Sync Engines: Legacy DB → Serving Mirror**](https://victorzorzo.com/projects/mirror-sync) | Self-chaining Edge Functions, table × month units, monthly checksums so only divergent months re-sync, shadow tables with atomic publish. |
| [**Legacy MySQL Forensics**](https://victorzorzo.com/projects/legacy-mysql-ops) | Silent failures where logs said OK and numbers went wrong — traced to metadata-lock races, proven with data, turned into runbooks. |
| [**Data Reliability & Reconciliation Suite**](https://victorzorzo.com/projects/data-health) | Invariants across legacy DB × mirror × RPCs × lake × UI. Every check seeded from an incident actually seen. |
| [**Data Atlas**](https://victorzorzo.com/projects/data-atlas) | A structural map of a company's data operation — systems, tables, pipelines, metrics and traps — written for whoever arrives next. |

### 04 / Product & Frontend

| | |
|---|---|
| [**Analytics Dashboards Hub**](https://victorzorzo.com/projects/dashboards-hub) | Company reporting migrated from a legacy BI tool into one React hub of production dashboards — reproduced 1:1 first, then redesigned. |
| [**Executive Margin Cockpit**](https://victorzorzo.com/projects/margin-cockpit) | Revenue down to contribution margin per order line. Net is *always* projected, with a backtested 180-day refund curve and no dead constants. |
| [**Tiered Affiliates Dashboard**](https://victorzorzo.com/projects/affiliates-tiered) | One route, two readings by role — and no hidden number can be recomputed from what's left on screen. |
| [**Lead Processing Latency**](https://victorzorzo.com/projects/lead-latency) | Exact p50/p95 from checkout to SMS, e-mail and call center — percentiles from histograms, never averaged. |

### 05 / Auth & Security

| | |
|---|---|
| [**Auth, Roles & Invitations**](https://victorzorzo.com/projects/auth-rbac) | Google OAuth with a domain allowlist enforced at signup, per-dashboard roles, and a dev mock that can't reach production. |
| [**Postgres RPC Exposure Audit**](https://victorzorzo.com/projects/rpc-security-audit) | Functions are born with `EXECUTE` to `PUBLIC`. Measured with curl against production, revoked, verified, and turned into an invariant. |

<sub>→ Full index — context, my role, how it works and *what broke and what I changed* — at **[victorzorzo.com/projects](https://victorzorzo.com/projects)**, in English or Portuguese. Most of this is company or client work, so the code is private; when work was shared, each case says which part was mine.</sub>

---

### What I optimize for

- **Correctness over vibes** — a number that can't be reconciled doesn't ship, no matter how good the chart looks.
- **Contract-first** — canonical model and acceptance criteria before code; then humans and agents build against it.
- **File-first, then DB** — versionable artifacts on disk; the database is a queryable mirror, not the source of truth.
- **Humans approve, agents execute** — agents do the work inside guardrails; people own the decision.
- **Honest status and credit** — In production, Evolving, Shipped, Partially remediated — and when work was shared, I say which part was mine.

### Toolbox

```text
agents   Python · LangGraph · Pydantic · llama.cpp · vLLM · MCP · Claude Code
quant    NumPy · SciPy · ChromaDB · Monte Carlo · Ledoit-Wolf · walk-forward validation
data     Postgres · MySQL · SQL · Supabase · AWS Glue / Athena / S3 / Lambda · Iceberg · Parquet · DuckDB · Terraform
product  TypeScript · React · TanStack · Next.js · Tailwind · shadcn · Recharts · Playwright · Cloudflare Workers · Docker
```

### Themes over time

`Spreadsheet → Python quant engine` · `Low-code → durable services` · `Static reports → live dashboards` · `API LLMs → self-hosted models` · `Copilot → agent harness`

---

<sub>Got a system to <i>think</i> through together? → <a href="https://www.linkedin.com/in/victor-zorzo-1166b7219">LinkedIn</a> · <a href="https://victorzorzo.com/contact">victorzorzo.com/contact</a></sub>
