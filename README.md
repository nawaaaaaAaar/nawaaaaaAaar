# nawaar.

*South Asian guy brewing zeros and ones.*

Computational Social Science · Applied AI · Public Policy

I study Computational Social Science at IIT Jodhpur, where my work connects
social questions with data and computational methods — digital inequality,
AI governance, and the protections people can actually rely on. Away from
research hours, I build software and fix things in the open.

## In public, upstream.

Small, reviewable patches — a reproduction case, the fix, a regression test —
merged into libraries that other people's software already depends on:

| Project | Merged |
| --- | --- |
| [fairlearn/fairlearn](https://github.com/fairlearn/fairlearn) (2.3k★) | [#1801](https://github.com/fairlearn/fairlearn/pull/1801) — stop deprecated pandas Series growth in reductions |
| [mlco2/codecarbon](https://github.com/mlco2/codecarbon) (1.9k★) | 3 merged PRs, incl. [#1439](https://github.com/mlco2/codecarbon/pull/1439) — preserve multi-digit GCP region numbers |
| [python-babel/babel](https://github.com/python-babel/babel) (1.5k★) | [#1401](https://github.com/python-babel/babel/pull/1401) — keep `timedelta` sub-second precision through `format_timedelta` |
| [petl-developers/petl](https://github.com/petl-developers/petl) (1.3k★) | [#766](https://github.com/petl-developers/petl/pull/766) — close XLSX workbooks when iteration exits early |
| [pypa/pyproject-metadata](https://github.com/pypa/pyproject-metadata) | [#345](https://github.com/pypa/pyproject-metadata/pull/345) — preserve empty inline readme and license text |
| [xarray-contrib/cf-xarray](https://github.com/xarray-contrib/cf-xarray) | [#674](https://github.com/xarray-contrib/cf-xarray/pull/674), [#675](https://github.com/xarray-contrib/cf-xarray/pull/675) — coordinate and geometry decoding fixes |
| [sara-czasak/py-simple-wrap](https://github.com/sara-czasak/py-simple-wrap) | [#402](https://github.com/sara-czasak/py-simple-wrap/pull/402) — streaming CSV row iterator for `easy_csv` |

## What I build.

Deterministic, offline-first tooling for AI agents and MCP — the same
questions as my research, asked from the engineering side: what does this
system actually do, and who does it protect?

- [agent-config-audit](https://github.com/nawaaaaaAaar/agent-config-audit) — audit AI agent config files for risky permissions, unpinned MCP servers, exfiltrating hooks and prompt-injection patterns
- [agent-threat-model](https://github.com/nawaaaaaAaar/agent-threat-model) — describe an LLM-agent system in YAML, get a deterministic STRIDE + OWASP Agentic threat model with a ranked register and residual-risk score
- [agent-security-skills](https://github.com/nawaaaaaAaar/agent-security-skills) — Claude Code plugin and agentskills.io pack for securing LLM agents
- [agentdojo-mcp](https://github.com/nawaaaaaAaar/agentdojo-mcp) — run AgentDojo's benchmark against real MCP servers
- [agentic-semgrep-rules](https://github.com/nawaaaaaAaar/agentic-semgrep-rules) — Semgrep rules for AI agent code
- [ai-agent-incidents](https://github.com/nawaaaaaAaar/ai-agent-incidents) — incident database for AI agent failures

Other work: [adaptive-knowledge-graph](https://github.com/nawaaaaaAaar/adaptive-knowledge-graph) (privacy-first RAG + Bayesian skill tracking), [aequitas](https://github.com/nawaaaaaAaar/aequitas) (bias auditing & fair ML toolkit), [agentic-evolution-harness](https://github.com/nawaaaaaAaar/agentic-evolution-harness) (reproducible agent evaluation), [HA-RohlikCZ](https://github.com/nawaaaaaAaar/HA-RohlikCZ) (Home Assistant integration for Rohlik/Knuspr/Gurkerl/Kifli/Sezamo).

## Elsewhere.

Research, writing and photography live at [nawaar.pplx.app](https://nawaar.pplx.app) —
digital inequality, AI and decolonial thought, and a camera that comes along.

*A check that runs everywhere is worth more than one that calls an API.*
