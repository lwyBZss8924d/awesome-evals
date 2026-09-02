# Notes - "How Many Tasks Are Enough for Agent Benchmark Decisions? A Replay Analysis of Public LLM Agent Benchmarks"

**Authors:** Wei-Jung Huang · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2607.12338 · **Type:** research paper with reproducibility package · **Found:** true

## Summary
Replay analysis over SWE-bench, AppWorld, and τ-bench shows that partial-eval sufficiency spans 15%–90% (or fails by 95%); task fractions are meaningful only with decision-error, coverage, threshold, and unresolved-comparison rules.

## Key points
- Worker summary: Replay analysis over SWE-bench, AppWorld, and τ-bench shows that partial-eval sufficiency spans 15%–90% (or fails by 95%); task fractions are meaningful only with decision-error, coverage, threshold, and unresolved-comparison rules.
- Worker candidate reason: This new quantitative methodology turns partial benchmark evaluation into an explicit decision problem, tests it on public task-level records, reports sharp cross-benchmark variation and misleading cheap-first behavior, and ships a reproducibility repository with scripts, manifests, schemas, fixed seeds, and derived tables.
- Worker evidence summary: The July 14, 2026 paper replays SWE-bench Lite/Verified, AppWorld, and τ-bench and finds sufficient budgets ranging from 15% to 90%, with no sufficient budget by 95% for SWE-bench Lite under the primary rule. It also shows that cheap-first τ-bench at 25% can use only 11.51% of cost while failing coverage completely, and that low decision error can coexist with 93.64% unresolved comparisons. The public MIT-licensed repository provides the replay package.
- Source seam: `recent arXiv agent-evaluation methodology; canonicalized from discovery feeds`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `not recorded`

## Why it matters for agent evals
This new quantitative methodology turns partial benchmark evaluation into an explicit decision problem, tests it on public task-level records, reports sharp cross-benchmark variation and misleading cheap-first behavior, and ships a reproducibility repository with scripts, manifests, schemas, fixed seeds, and derived tables.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.12338
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/how-many-tasks-are-enough-for-agent-benchmark-decisions-a-replay-analysis-of-public-llm-agen.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- recent arXiv agent-evaluation methodology; canonicalized from discovery feeds
