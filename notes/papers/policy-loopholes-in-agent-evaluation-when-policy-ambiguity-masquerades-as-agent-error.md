# Notes - "Policy Loopholes in Agent Evaluation: When Policy Ambiguity Masquerades as Agent Error"

**Authors:** Hongliu Cao · **Published/Updated:** 2026-09-13 · **URL:** https://arxiv.org/abs/2609.14400 · **Type:** paper · **Found:** true

## Summary
A policy-first audit of τ²-bench separates ambiguous requirements from agent mistakes using clause analysis and failure traces. ⚠️ Observational evidence from two domains.

## Key points
- Worker summary: A policy-first audit of τ²-bench separates ambiguous requirements from agent mistakes using clause analysis and failure traces. ⚠️ Observational evidence from two domains.
- Worker candidate reason: Adds a distinct benchmark-integrity failure mode: a defensible policy interpretation can disagree with the single gold trajectory. The paper supplies audit criteria, task-level results and worked cases, making it useful when designing policy-grounded graders.
- Worker evidence: Read arXiv v1 (2026-09-13), especially §§3–4 and Appendix A: https://arxiv.org/html/2609.14400v1 . The study audits airline and retail policies, then checks whether failing traces rely on defensible alternative readings. It reports 1,968 runs across three models with four trials per task. Airline results contrast with retail tool guards that prevent ambiguous actions. §4.2 explicitly says policy complexity and enforcement cannot be disentangled from only two domains; the proposed mechanism remains a hypothesis. Published analysis inspected; experiments were not independently reproduced.
- Source seam: `new_eval_benchmarks_and_methods`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `cs.CL`

## Why it matters for agent evals
Adds a distinct benchmark-integrity failure mode: a defensible policy interpretation can disagree with the single gold trajectory. The paper supplies audit criteria, task-level results and worked cases, making it useful when designing policy-grounded graders.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.14400
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/policy-loopholes-in-agent-evaluation-when-policy-ambiguity-masquerades-as-agent-error.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new_eval_benchmarks_and_methods

## Primary evidence and review limits

- Source inspection date: 2026-09-19.
- Status: worker candidate draft; independent review and supervisor promotion pending.
- [Primary source 1](https://arxiv.org/abs/2609.14400)
- [Primary source 2](https://arxiv.org/html/2609.14400v1)
- Two-domain observational comparison does not establish a causal mechanism.
- No independent execution or benchmark rerun in this scan.

> their individual effects cannot be disentangled from a comparison of only two domains

[Source for the excerpt](https://arxiv.org/html/2609.14400v1)
