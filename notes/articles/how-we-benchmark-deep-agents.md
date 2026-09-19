# Notes - "How We Benchmark Deep Agents"

**Authors:** Nick Hollon and Harrison Chase / LangChain · **Published/Updated:** 2026-07-23 · **URL:** https://www.langchain.com/blog/how-we-benchmark-deep-agents · **Type:** blog · **Found:** true

## Summary
LangChain describes environment-bound end-to-end evals, repeated trials, a frozen lite suite and deterministic capability tests for evaluating harness changes.

## Key points
- Worker summary: LangChain describes environment-bound end-to-end evals, repeated trials, a frozen lite suite and deterministic capability tests for evaluating harness changes.
- Worker candidate reason: A first-party engineering account with concrete task packaging and evaluation practices: inspect produced artifacts, cover different kinds of work and use benchmarks alongside fast capability checks. It connects evaluation design to decisions about removing harness middleware and simplifying prompts.
- Worker evidence: Read the 2026-07-23 engineering article, sections End-to-end evals with Harbor, What works for us and Iterate with confidence. It defines tasks through an environment, instructions and a grading script; grades resulting artifacts/state; and describes repeated trials, a frozen lite subset and capability tests. The concrete example is assessing todo-list middleware removal and prompt reduction for Deep Agents 0.7. These are the authors' reported practices and proposed changes, not independent proof of gains. Numerical speed/cost and leaderboard claims are intentionally omitted from the annotation.
- Source seam: `company_engineering_blogs`
- Target README section: `## 5 · Evaluation infrastructure (the eval stack: datasets, scorers, online/offline, tracing, CI)`
- Primary category: `not recorded`

## Why it matters for agent evals
A first-party engineering account with concrete task packaging and evaluation practices: inspect produced artifacts, cover different kinds of work and use benchmarks alongside fast capability checks. It connects evaluation design to decisions about removing harness middleware and simplifying prompts.

## Provenance
- Canonical URL: https://www.langchain.com/blog/how-we-benchmark-deep-agents
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/how-we-benchmark-deep-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company_engineering_blogs

## Primary evidence and review limits

- Source inspection date: 2026-09-19.
- Status: worker candidate draft; independent review and supervisor promotion pending.
- [Primary source 1](https://www.langchain.com/blog/how-we-benchmark-deep-agents)
- Vendor-authored account; no independent performance replication.
- Middleware removal and prompt reduction are described as under consideration, not proven successful changes.

> Run each task multiple times.

[Source for the excerpt](https://www.langchain.com/blog/how-we-benchmark-deep-agents)
