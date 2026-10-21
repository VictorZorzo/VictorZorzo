<h1>Victor <sub><sup><code>[lab]</code> data &amp; ai engineer</sup></sub></h1>

**I build systems that _think_, move data and _become product_.**

Agent graphs, LLMs running on a laptop GPU, macro-aware portfolio optimization, sync engines and dashboards that leadership actually trusts. I work end-to-end: data platforms, multi-source architecture, auth and security, multi-agent LLM systems, local inference and fine-tuning, quant research — and the product UI on top.

[![Portfolio](https://img.shields.io/badge/portfolio-victorzorzo.com-C6F432?style=flat-square&labelColor=07080A)](https://victorzorzo.com)
[![Projects](https://img.shields.io/badge/case_studies-30+-5CE1E6?style=flat-square&labelColor=07080A)](https://victorzorzo.com/projects)
[![Lab](https://img.shields.io/badge/interactive_demos-lab-FFB547?style=flat-square&labelColor=07080A)](https://victorzorzo.com/lab)

---

### 01 / Agents & LLMs

| | |
|---|---|
| [**Quant + AI Research Terminal**](https://victorzorzo.com/projects/divergence-terminal) | The optimizer decides *how much* to allocate; LLM agents explain *why* and *when*. The signal is where they disagree. |
| [**Multi-Agent Research Graph**](https://victorzorzo.com/projects/agent-graph) | LangGraph with 12 roles — parallel analysts, bull ↔ bear and risk debates, deep-model managers with structured output, SQLite checkpoints. |
| [**Local LLM Lab**](https://victorzorzo.com/projects/local-llm-lab) | 9B models with 16k context on an 8 GB laptop GPU (llama.cpp, q8_0 KV cache); a 27B AWQ model on serverless vLLM. Same OpenAI-compatible API for both. |
| [**Agent Harness & Context Engineering**](https://victorzorzo.com/projects/agent-harness) | Coding agents with read-only MCPs, a knowledge graph of repos, a vault as long-term memory and human checkpoints. Agents never grant access or push on their own. |

### 02 / Quant & Research

| | |
|---|---|
| [**Macro-Aware Portfolio Optimizer**](https://victorzorzo.com/projects/macro-optimizer) | From a broken Markowitz spreadsheet to a Python system with 200+ tests: regime classifier, event-study adjustments, SLSQP max-Sharpe, Monte Carlo frontier, walk-forward validation. |
| [**Fine-tuning & Distillation**](https://victorzorzo.com/projects/fine-tuning) | LoRA to turn macro events into calibrated signals, with similar-event RAG and a strict temporal split. |

### 03 / Data Engineering

| | |
|---|---|
| [**Sync Engines: Legacy DB → Serving Mirror**](https://victorzorzo.com/projects/mirror-sync) | Self-chaining Edge Functions, table × month units, monthly checksums so only divergent months re-sync, shadow tables with atomic publish. |
| [**Legacy MySQL Incident Forensics**](https://victorzorzo.com/projects/legacy-mysql-ops) | Silent failures where logs said OK and numbers went wrong — traced to metadata-lock races, proven with data, turned into runbooks. |
| [**Data Reliability & Reconciliation Suite**](https://victorzorzo.com/projects/data-health) | Invariants across legacy DB × mirror × RPCs × lake × UI. Every check seeded from an incident actually seen. |
| [**Canonical Gold Marts on a Medallion Lake**](https://victorzorzo.com/projects/gold-marts) | Canonical marts materialized as Iceberg tables on Glue / Athena / S3, managed with Terraform. |

### 04 / Product & Frontend

| | |
|---|---|
| [**Analytics Dashboards Hub**](https://victorzorzo.com/projects/dashboards-hub) | Company reporting migrated from a legacy BI tool into one React hub of production dashboards — reproduced 1:1 first, then redesigned. |
| [**Executive Margin Cockpit**](https://victorzorzo.com/projects/margin-cockpit) | Revenue down to contribution margin per order line. Net is *always* projected, with a backtested 180-day refund curve and no dead constants. |
| [**Tiered Affiliates Dashboard**](https://victorzorzo.com/projects/affiliates-tiered) | One route, two readings by role — and no hidden number can be recomputed from what's left on screen. |
| [**Support Ops Cockpit**](https://victorzorzo.com/projects/support-cockpit) | From an 8 MB static HTML to a container with fresh data and ~50 ms filters on TypedArrays. |

### 05 / Auth & Security

| | |
|---|---|
| [**Auth, RBAC & Invitations**](https://victorzorzo.com/projects/auth-rbac) | Google OAuth with a domain allowlist enforced at signup, per-dashboard roles, and a dev mock that can't reach production. |
| [**Postgres RPC Exposure Audit**](https://victorzorzo.com/projects/rpc-security-audit) | Functions are born with `EXECUTE` to `PUBLIC`. Measured with curl against production, revoked, verified, and turned into an invariant. |

<sub>→ Full index with case studies, architecture and *what broke and what I changed* at **[victorzorzo.com/projects](https://victorzorzo.com/projects)**. Most of this is company or client work, so the code is private.</sub>

---

### What I optimize for

- **Correctness over vibes** — a number that can't be reconciled doesn't ship, no matter how good the chart looks.
- **Contract-first** — canonical model and acceptance criteria before code; then humans and agents build against it.
- **File-first, then DB** — versionable artifacts on disk; the database is a queryable mirror, not the source of truth.
- **Humans approve, agents execute** — agents do the work inside guardrails; people own the decision.
- **Honest status** — In production, Evolving, R&D, Shipped, Partially remediated. No demo pretends to be a product.

### Toolbox

```text
agents   Python · LangGraph · Pydantic · llama.cpp · vLLM · LoRA (unsloth / axolotl) · MCP · Claude Code
quant    NumPy · SciPy · ChromaDB · Monte Carlo · Ledoit-Wolf · walk-forward validation
data     Postgres · MySQL · SQL · Supabase · AWS Glue / Athena / S3 / Lambda · Iceberg · Parquet · DuckDB · Terraform
product  TypeScript · React · TanStack · Next.js · Tailwind · shadcn · Recharts · Playwright · Cloudflare Workers · Docker
```

### Themes over time

`Spreadsheet → Python quant engine` · `Low-code → durable services` · `Static reports → live dashboards` · `API LLMs → local + fine-tuned models` · `Copilot → agent harness`

---

<sub>Got a system to <i>think</i> through together? → <a href="https://victorzorzo.com/contact">victorzorzo.com/contact</a></sub>
