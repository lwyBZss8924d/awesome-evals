# Notes - "AgentLens: Production-Assessed Trajectory Reviews for Coding Agent Evaluation"

**Authors:** Andrey Podivilov, Vadim Lomshakov, Sergey Savin, Matvei Startsev, Roman Pozharskiy, Maksim Parshin, Sergey Nikolenko · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2607.06624 · **Type:** paper/benchmark/code · **Found:** true

## Summary
A 16-scenario, two-persona coding-agent benchmark that pairs formal repository checks with evidence-citing trajectory reviews, pairwise comparisons, bias/variance checks, and a nightly regression pipeline.

## Key points
- Worker summary: A 16-scenario, two-persona coding-agent benchmark that pairs formal repository checks with evidence-citing trajectory reviews, pairwise comparisons, bias/variance checks, and a nightly regression pipeline.
- Worker candidate reason: It evaluates the whole interactive coding trajectory instead of only final test status, ships the runner/evaluator and scenario fold under Apache-2.0, derives tasks from developer interviews and consented anonymized production summaries, and reports concrete stability and judge-bias checks that practitioners can use when building regression evals.
- Worker evidence: Retrieved arXiv metadata and the v1 PDF plus https://github.com/agent-lens/agent-lens-bench README and GitHub metadata. The released fold has 16 scenarios run with neutral and toxic personas (32 trajectories per agent); formal checks include tests, repository state, regex, build tasks, and static analysis; five LLM-review dimensions cite trajectory evidence; five repeated GLM-5.1 runs gave quality-index mean 67.28 and SD 0.94; cross-judge comparison disagreed on 23% of task-metric pairs and showed 18% own-family preference, which the paper flags as a close-model caveat. Human agreement evidence is preliminary and informal, so promotion should retain that caveat.
- Source seam: `Hugging Face Daily Papers -> canonical arXiv paper -> GitHub code/repository evidence`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
It evaluates the whole interactive coding trajectory instead of only final test status, ships the runner/evaluator and scenario fold under Apache-2.0, derives tasks from developer interviews and consented anonymized production summaries, and reports concrete stability and judge-bias checks that practitioners can use when building regression evals.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.06624
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/agentlens-production-assessed-trajectory-reviews-for-coding-agent-evaluation.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers -> canonical arXiv paper -> GitHub code/repository evidence
