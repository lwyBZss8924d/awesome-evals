# Notes - "Efficient Benchmarking of AI Agents"

**Authors:** Franck Ndzomga · **Published/Updated:** 2026-03-24T22:17:11Z · **URL:** https://arxiv.org/abs/2603.23749 · **Type:** paper · **Found:** true

## Summary
Historical task-difficulty filtering for cheaper agent rankings under scaffold and temporal shift. ⚠️ Ranking fidelity does not imply calibrated capability scores.

## Key points
- Worker summary: Historical task-difficulty filtering for cheaper agent rankings under scaffold and temporal shift. ⚠️ Ranking fidelity does not imply calibrated capability scores.
- Worker candidate reason: Primary paper supplies nested validation, matched-budget baselines, failure cases, and linked code/data, making reduced-suite selection assessable beyond a generic cost-saving claim.
- Worker evidence: Version 1, submitted March 24, 2026, selects tasks with historical pass rates between 30 and 70 percent using training folds only. Sections 3.4 and 4 compare held-out scaffolds and temporal arrivals. Sections 5.1 and 6 retain full-suite checks for drift and capability jumps; the method fails when too few tasks have intermediate difficulty, illustrated by SciCode. Cost estimates assume linear scaling with task count. The linked public repository exists and is unarchived; experiments were not replayed.
- Source seam: `new_eval_benchmarks_tools`
- Target README section: `6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Primary paper supplies nested validation, matched-budget baselines, failure cases, and linked code/data, making reduced-suite selection assessable beyond a generic cost-saving claim.

## Provenance
- Canonical URL: https://arxiv.org/abs/2603.23749
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/efficient-benchmarking-of-ai-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new_eval_benchmarks_tools
