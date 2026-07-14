# Notes - "SLBench: Evaluating How LLM Agents Follow Logical Relations in Skills"

**Authors:** Xuan Chen, Chengpeng Wang, Lu Yan, Xiangyu Zhang · **Published/Updated:** 2026-07-10 · **URL:** https://arxiv.org/abs/2607.09016 · **Type:** paper / benchmark / safety evaluation · **Found:** true

## Summary
An 86-case executable safety benchmark that checks whether skill-guided agents follow logical relations using durable artifacts and final state.

## Key points
- Worker summary: Compiles logical relations from public agent skills into 86 human-audited executable cases with artifact-first grading for unsafe gates, constraints, fallbacks, and cleanup behavior.
- Worker candidate reason: It turns natural-language skill dependencies into reproducible safety tests, evaluates real Codex and Claude Code configurations, and demonstrates both high violation rates and a concrete inference-time mitigation.
- Worker evidence: Primary arXiv text and full Hugging Face markdown were retrieved. SkillLogic sampled 5,224 public skills, materialized 4,500, found valid relations in 3,751, and constructed 86 audited local cases (39 controls, 47 violations) covering eight relation types. The grader checks durable artifacts, command traces, and final repository state rather than claims in the response. Codex and Claude Code were tested across six backbones, with unsafe rates up to 70%; the relation-aware SLGuard scaffold reduced targeted violations by 63%. The authors note the final benchmark is a curated executable subset, not a uniform taxonomy sample.
- Source seam: `arXiv cs.CR/cs.SE RSS / new benchmark / agent-skill safety`
- Target README section: `## 10 · Safety / adversarial evaluation (prompt injection, jailbreaks, action-authorization, benchmark auditing)`
- Primary category: `cs.CR`

## Why it matters for agent evals
It turns natural-language skill dependencies into reproducible safety tests, evaluates real Codex and Claude Code configurations, and demonstrates both high violation rates and a concrete inference-time mitigation.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.09016
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/slbench-evaluating-how-llm-agents-follow-logical-relations-in-skills.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arXiv cs.CR/cs.SE RSS / new benchmark / agent-skill safety
