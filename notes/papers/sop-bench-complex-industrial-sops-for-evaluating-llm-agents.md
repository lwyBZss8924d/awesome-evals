# Notes - "SOP-Bench: Complex Industrial SOPs for Evaluating LLM Agents"

**Authors:** Nandi Subhrangshu et al. · **Published/Updated:** unknown · **URL:** https://www.amazon.science/publications/sop-bench-complex-industrial-sops-for-evaluating-llm-agents · **Type:** paper/benchmark/repo · **Found:** true

## Summary
KDD 2026 benchmark with 2,000+ human-validated procedural tasks across 12 business domains, executable tools, and ground-truth completion outputs.

## Key points
- Worker summary: KDD 2026 benchmark with 2,000+ human-validated procedural tasks across 12 business domains, executable tools, and ground-truth completion outputs.
- Worker candidate reason: It turns real expert-authored SOPs into open, execution-scored agent tasks and directly tests tool orchestration, cross-domain robustness, and distractor sensitivity rather than relying on an LLM judge alone.
- Worker evidence: The Amazon Science paper, companion article, public repository, and dataset describe more than 2,000 tasks derived from human expert SOPs in 12 domains; all generated artifacts were human-validated, agents execute domain tools against ground-truth outputs, and experiments span two agent architectures and 11 frontier models. Adding 20 plausible distractor tools nearly halved success, while the best model-agent pairing varied by domain, exposing both tool-selection fragility and the need to evaluate the full procedure.
- Source seam: `company research publication and benchmark repository`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
It turns real expert-authored SOPs into open, execution-scored agent tasks and directly tests tool orchestration, cross-domain robustness, and distractor sensitivity rather than relying on an LLM judge alone.

## Provenance
- Canonical URL: https://www.amazon.science/publications/sop-bench-complex-industrial-sops-for-evaluating-llm-agents
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/sop-bench-complex-industrial-sops-for-evaluating-llm-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company research publication and benchmark repository
