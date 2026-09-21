# Notes - "Autoresearch Bench"

**Authors:** Emulated · **Published/Updated:** 2026-09-01 · **URL:** https://www.autoresearch-bench.com/ · **Type:** benchmark/blog · **Found:** true

## Summary
Iterative research-agent evaluation with time budgets, separate grading, and public/private score comparisons. ⚠️ Best-private scoring and excluded failed runs limit reliability conclusions.

## Key points
- Worker summary: Iterative research-agent evaluation with time budgets, separate grading, and public/private score comparisons. ⚠️ Best-private scoring and excluded failed runs limit reliability conclusions.
- Worker candidate reason: Primary project documentation exposes the scoring protocol and its caveats, giving practitioners a concrete way to examine experimental progress, overfitting, and grader isolation.
- Worker evidence: The September 1, 2026 project article describes isolated workspaces and an external grader in a separate sandbox. Many tasks retain a private score; final scoring uses the best private result. Failed runs are excluded from aggregate curves and rankings. Cross-task normalization uses frozen divisors and equal task weights. These choices support studying iterative optimization but do not establish deployment reliability. The text-only leaderboard did not expose run-level data, so no live ranking or model-performance number is proposed.
- Source seam: `new_eval_benchmarks_tools`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
Primary project documentation exposes the scoring protocol and its caveats, giving practitioners a concrete way to examine experimental progress, overfitting, and grader isolation.

## Provenance
- Canonical URL: https://www.autoresearch-bench.com/
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/autoresearch-bench.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new_eval_benchmarks_tools
