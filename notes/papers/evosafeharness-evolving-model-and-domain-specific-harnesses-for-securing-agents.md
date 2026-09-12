# Notes - "EvoSafeHarness: Evolving Model- and Domain-Specific Harnesses for Securing Agents"

**Authors:** Nanxi Li, Yingzi Ma, Yulong Cao, Edward Suh, Bo Li, Dawn Song, Chaowei Xiao · **Published/Updated:** 2026-09-05 · **URL:** https://arxiv.org/abs/2609.05903 · **Type:** paper · **Found:** true

## Summary
Evaluates searched safety harnesses using separate utility and attack-success measures, held-out tests, transfer suites, and adversarial review designed to catch benchmark-specific rules.

## Key points
- Worker summary: Evaluates searched safety harnesses using separate utility and attack-success measures, held-out tests, transfer suites, and adversarial review designed to catch benchmark-specific rules.
- Worker candidate reason: A concrete study of how to evaluate an optimized agent harness without equating search-set gains with safety: it reports held-out and transfer tests, anti-overfitting ablations, adaptive attacks, and separate optimizer/evaluator resource accounting.
- Worker evidence: Discovered in Hugging Face Daily Papers for 2026-09-11; hf papers info confirms arXiv 2609.05903, publication 2026-09-05, and the SaFo-Lab/EvoSafeHarness repository. The Hub read command returned only an SVG caption and was discarded; primary paper text was instead retrieved directly from https://arxiv.org/html/2609.05903v1. Sections 4-7 define a policy-plus-code harness, fresh-context adversarial review, and staged candidate evaluation. The paper evaluates direct and indirect attacks, benign utility, unchanged AgentDojo-to-AgentDyn transfer, and adaptive PAIR attacks; removing its Criticizer can preserve or improve search scores while reducing held-out scores by up to 31 points. Appendix H specifies a frozen 100-task DTAP split with 30 benign and 70 attack tasks and uncertainty analysis, so low observed attack success is bounded by the tested distribution. The official GitHub README documents system_prompt_transform/on_pre_tool_call/on_post_tool_call hooks, domain overlays, frozen splits, and a comparison runner. Live metadata shows an unarchived repository with 2 stars, 0 forks, and no detected license on 2026-09-12; external deployment adoption is unproven. Accepted as an empirical paper, not as an established tool recommendation. Reported performance and separation of search/test data were not independently reproduced.
- Source seam: `Hugging Face Daily Papers 2026-09-11; primary arXiv HTML; GitHub implementation`
- Target README section: `10 · Safety / adversarial evaluation (prompt injection, jailbreaks, action-authorization, benchmark auditing)`
- Primary category: `cs.CR`

## Why it matters for agent evals
A concrete study of how to evaluate an optimized agent harness without equating search-set gains with safety: it reports held-out and transfer tests, anti-overfitting ablations, adaptive attacks, and separate optimizer/evaluator resource accounting.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.05903
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/evosafeharness-evolving-model-and-domain-specific-harnesses-for-securing-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers 2026-09-11; primary arXiv HTML; GitHub implementation
