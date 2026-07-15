# Notes - "More compute, more capability: Why AI agent evaluations need to account for test-time compute"

**Authors:** UK AI Security Institute, Science of Evaluations team · **Published/Updated:** unknown · **URL:** https://www.aisi.gov.uk/blog/more-compute-more-capability-why-ai-agent-evals-need-to-account-for-test-time-compute · **Type:** empirical research report · **Found:** true

## Summary
UK AISI shows that agent capability is a curve over test-time compute: raising budgets from 1M to 10M tokens improved benchmark performance by roughly 22–25%.

## Key points
- Worker summary: UK AISI shows that agent capability is a curve over test-time compute: raising budgets from 1M to 10M tokens improved benchmark performance by roughly 22–25%.
- Worker candidate reason: The study reports multi-benchmark token-budget sweeps, task-level reliability and efficiency analysis, and human-time-horizon comparisons, directly showing why fixed-budget agent scores can be censored lower bounds.
- Worker evidence: About 8% of the cyber tasks were solved only at budgets of at least 10M tokens, some up to 50M; moving from 1M to 10M improved TerminalBench 2.0 and SWE-Bench Pro performance by about 25% and academic or math performance by about 22%, while the horizon analysis covered 211 METR software tasks and 78 AISI cyber tasks.
- Source seam: `government and company evaluation research blogs`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `not recorded`

## Why it matters for agent evals
The study reports multi-benchmark token-budget sweeps, task-level reliability and efficiency analysis, and human-time-horizon comparisons, directly showing why fixed-budget agent scores can be censored lower bounds.

## Provenance
- Canonical URL: https://www.aisi.gov.uk/blog/more-compute-more-capability-why-ai-agent-evals-need-to-account-for-test-time-compute
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/more-compute-more-capability-why-ai-agent-evaluations-need-to-account-for-test-time-compute.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- government and company evaluation research blogs
