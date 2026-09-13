# Notes - "DuMateBench: Evaluating Autonomous Agents in Complex Real-World Workflows"

**Authors:** Zechun Niu, Yukun Zhao, et al. · **Published/Updated:** 2026-08-27 · **URL:** https://arxiv.org/abs/2608.26546 · **Type:** paper / benchmark · **Found:** true

## Summary
Session-derived workflow benchmark with restored context, fault-injected containers, and hybrid artifact grading. ⚠️ LLM-judge components and dataset preparation are required.

## Key points
- Worker summary: Session-derived workflow benchmark with restored context, fault-injected containers, and hybrid artifact grading. ⚠️ LLM-judge components and dataset preparation are required.
- Worker candidate reason: Combines compositional productivity tasks with deliberately insufficient, unstable, and noisy execution conditions, making environment recovery part of evaluation. The primary paper, project site, and released runner documentation expose both task construction and practical execution limits.
- Worker evidence: The August 27, 2026 arXiv v1 describes 200 tasks reconstructed from anonymized, privacy-screened production sessions, retaining pre-solution interaction history, persistent configurations, and workspace state; this is the authors' provenance claim. It specifies missing-resource, transient-failure, and workspace-noise conditions in Docker and hybrid deterministic/checklist plus artifact-specific LLM grading. The project site links https://github.com/baidubce/dumate-bench and the Annihi/dumate_bench Hugging Face dataset. GitHub README confirms runner/evaluator code and Harbor integration, but explains that the checked-in tasks are development examples and the full dataset is separate. Public tasks omit environment files and need template filling; the CLI requires a source checkout because its shared evaluator is not in the standalone wheel. A valid reward can represent a completed but failing task, so runner completion is distinct from task success. GitHub metadata showed an unarchived Apache-2.0 repository with five stars. No dataset download, setup, model run, or independent reproduction was performed.
- Source seam: `new eval benchmarks/tools`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Combines compositional productivity tasks with deliberately insufficient, unstable, and noisy execution conditions, making environment recovery part of evaluation. The primary paper, project site, and released runner documentation expose both task construction and practical execution limits.

## Provenance
- Canonical URL: https://arxiv.org/abs/2608.26546
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/dumatebench-evaluating-autonomous-agents-in-complex-real-world-workflows.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools

## Retrieved primary sources

- https://arxiv.org/abs/2608.26546
- https://arxiv.org/html/2608.26546v1
- https://dumatebench.com/
- https://github.com/baidubce/dumate-bench
