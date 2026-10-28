# nawaaaar

I build deterministic, offline-first security tooling for AI agents and MCP —
and I fix real bugs upstream, one reviewable PR at a time.

## Landed upstream

Bug fixes and features merged into projects people already depend on:

| Project | Merged |
| --- | --- |
| [fairlearn/fairlearn](https://github.com/fairlearn/fairlearn) (2.3k★) | [#1801](https://github.com/fairlearn/fairlearn/pull/1801) — stop deprecated pandas Series growth in reductions |
| [mlco2/codecarbon](https://github.com/mlco2/codecarbon) (1.9k★) | 3 merged PRs, incl. [#1439](https://github.com/mlco2/codecarbon/pull/1439) — preserve multi-digit GCP region numbers |
| [python-babel/babel](https://github.com/python-babel/babel) (1.5k★) | [#1401](https://github.com/python-babel/babel/pull/1401) — keep `timedelta` sub-second precision through `format_timedelta` |
| [petl-developers/petl](https://github.com/petl-developers/petl) (1.3k★) | [#766](https://github.com/petl-developers/petl/pull/766) — close XLSX workbooks when iteration exits early |
| [pypa/pyproject-metadata](https://github.com/pypa/pyproject-metadata) | [#345](https://github.com/pypa/pyproject-metadata/pull/345) — preserve empty inline readme and license text |
| [xarray-contrib/cf-xarray](https://github.com/xarray-contrib/cf-xarray) | [#674](https://github.com/xarray-contrib/cf-xarray/pull/674), [#675](https://github.com/xarray-contrib/cf-xarray/pull/675) — coordinate and geometry decoding fixes |
| [sara-czasak/py-simple-wrap](https://github.com/sara-czasak/py-simple-wrap) | [#402](https://github.com/sara-czasak/py-simple-wrap/pull/402) — streaming CSV row iterator for `easy_csv` |

## What I build

- [agent-config-audit](https://github.com/nawaaaaaAaar/agent-config-audit) — audit AI agent config files for risky permissions, unpinned MCP servers, exfiltrating hooks and prompt-injection patterns; table/JSON/SARIF output, GitHub Action, pre-commit
- [agent-threat-model](https://github.com/nawaaaaaAaar/agent-threat-model) — describe an LLM-agent system in YAML, get a deterministic STRIDE + OWASP Agentic threat model with a ranked register, Mermaid diagram and residual-risk score
- [agent-security-skills](https://github.com/nawaaaaaAaar/agent-security-skills) — Claude Code plugin and agentskills.io pack for securing LLM agents: threat modelling, config audits, Semgrep rules, guard hooks, incident DB
- [agentdojo-mcp](https://github.com/nawaaaaaAaar/agentdojo-mcp) — run AgentDojo's benchmark against real MCP servers; utility, targeted attack success, per-task call traces
- [agentic-semgrep-rules](https://github.com/nawaaaaaAaar/agentic-semgrep-rules) — Semgrep rules for AI agent code: model output reaching exec/shell/SQL/URLs, user input in system prompts, over-broad tools
- [ai-agent-incidents](https://github.com/nawaaaaaAaar/ai-agent-incidents) — incident database for AI agent failures

Other work: [adaptive-knowledge-graph](https://github.com/nawaaaaaAaar/adaptive-knowledge-graph) (privacy-first RAG + Bayesian skill tracking), [aequitas](https://github.com/nawaaaaaAaar/aequitas) (bias auditing & fair ML toolkit), [agentic-evolution-harness](https://github.com/nawaaaaaAaar/agentic-evolution-harness) (reproducible agent evaluation), [HA-RohlikCZ](https://github.com/nawaaaaaAaar/HA-RohlikCZ) (Home Assistant integration for Rohlik/Knuspr/Gurkerl/Kifli/Sezamo).

## How I work

Small PRs with reproduction cases, regression tests and changelogs.
Offline and deterministic over clever and networked — a check that runs
everywhere is worth more than one that calls an API.
