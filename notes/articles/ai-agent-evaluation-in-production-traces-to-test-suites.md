# Notes - "AI Agent Evaluation in Production: Traces to Test Suites"

**Authors:** Viacheslav Dubrov · **Published/Updated:** 2026-06-10 / 2026-08-08 · **URL:** https://slavadubrov.com/blog/2026/06/10/agent-evals-traces-to-test-suites · **Type:** practitioner article / worked example · **Found:** true

## Summary
Worked trace-to-regression guide with explicit expected state, fresh agent reruns, and code-backed failure checks. ⚠️ Companion example uses synthetic tasks.

## Key points
- Worker summary: Worked trace-to-regression guide with explicit expected state, fresh agent reruns, and code-backed failure checks. ⚠️ Companion example uses synthetic tasks.
- Worker candidate reason: Shows the concrete path from a failed trace to a reviewable task contract and a fresh regression run, with examples for missing authorization, wrong arguments, and false completion. The companion evaluator checks required tools, every-invocation arguments, final state, and structured claims, rather than treating an old failed trace as a regression test.
- Worker evidence: The author's article was published June 10 and updated August 8, 2026. Its original github.io discovery page declares https://slavadubrov.com/blog/2026/06/10/agent-evals-traces-to-test-suites/ as canonical; the canonical URL returned HTTP 200. The worked guide distinguishes outcome, trajectory, and component checks, then links trace mining, deduplication, explicit expected behavior, versioned datasets, and CI. Read-only GitHub inspection of slavadubrov/trace2evals at commit 7478e023f4b0c05a4e65d25974d43dd2c6bc80a5 found evaluate.py invoking fresh agent runs per task/attempt, grading all implemented invariants plus expected arguments/state/claims, and keeping invalid attempts separate from failures. docs/evaluation.md rejects missing or unreviewed required suites and records the old uncalibrated judge's removal. The current repository is newer than the article's linked revision. Its README expressly limits evidence to a synthetic teaching suite; it does not establish production generalization or full OpenTelemetry interoperability. Metadata showed zero stars/forks and no declared license; propose the authored guide, not a standalone software recommendation. No demo or model was executed.
- Source seam: `eval insights inside general agent-building posts`
- Target README section: `## 4 · Observability & the output / eval space (the surfaces you can grade)`
- Primary category: `not recorded`

## Why it matters for agent evals
Shows the concrete path from a failed trace to a reviewable task contract and a fresh regression run, with examples for missing authorization, wrong arguments, and false completion. The companion evaluator checks required tools, every-invocation arguments, final state, and structured claims, rather than treating an old failed trace as a regression test.

## Provenance
- Canonical URL: https://slavadubrov.com/blog/2026/06/10/agent-evals-traces-to-test-suites
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/ai-agent-evaluation-in-production-traces-to-test-suites.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- eval insights inside general agent-building posts

## Retrieved primary sources

- https://slavadubrov.com/blog/2026/06/10/agent-evals-traces-to-test-suites/
- https://github.com/slavadubrov/trace2evals/blob/7478e023f4b0c05a4e65d25974d43dd2c6bc80a5/src/trace2evals/evaluate.py
- https://github.com/slavadubrov/trace2evals/blob/7478e023f4b0c05a4e65d25974d43dd2c6bc80a5/docs/evaluation.md
