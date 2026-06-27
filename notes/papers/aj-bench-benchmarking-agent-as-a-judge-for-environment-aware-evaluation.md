# Notes - "AJ-Bench: Benchmarking Agent-as-a-Judge for Environment-Aware Evaluation"

**Authors:** Wentao Shi, Yu Wang, Yuyang Zhao, Yuxin Chen, Fuli Feng, Xueyuan Hao, Xi Su, Qi Gu, Hui Su, Xunliang Cai, Xiangnan He · **Published/Updated:** 2026-04-20T13:23:38Z · **URL:** https://arxiv.org/abs/2604.18240 · **Type:** paper/benchmark · **Found:** true

## Summary
As reinforcement learning continues to scale the training of large language model-based agents, reliably verifying agent behaviors in complex environments has become increasingly challenging. Existing approaches rely on rule-based verifiers or LLM-as-a-Judge models, which struggle to generalize beyond narrow domains. Agent-as-a-Judge addresses this limitation by actively interacting with environments and tools to acquire verifiable evidence, yet its capabilities remain underexplored. We introduce a benchmark AJ-Bench to systematically evaluate Agent-as-a-Judge across three domains-search, data systems, and graphical user interfaces-comprising 155 tasks and 516 annotated trajectories. The benchmark comprehensively assesses judge agents' abilities in information acquisition, state verification, and process verification. Experiments demonstrate consistent performance gains over LLM-as-a-Judge baselines, while also revealing substantial open challenges in agent-based verification. Our data and code are available at https://aj-bench.github.io/.

## Key points
- Worker summary: Benchmark for judging agents that actively gather evidence across search, data systems, and GUI environments.
- Worker candidate reason: HF and arXiv metadata report 155 tasks and 516 annotated trajectories across search, data systems, and graphical interfaces, evaluating judge-agent abilities in information acquisition, state verification, and process verification; the project page confirms the ACL 2026 paper and public data/code surface.
- Worker evidence: hf-papers-computer-use-verifier.json surfaced id 2604.18240; arxiv-ajbench.json confirms the benchmark scope; project-pages.json for https://aj-bench.github.io/ confirms 155 tasks, 516 trajectories, ACL 2026 metadata, and project URL.
- Source seam: `Hugging Face paper search + project page + arXiv primary metadata`
- Target README section: `## 8 · LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `not recorded`

## Why it matters for agent evals
HF and arXiv metadata report 155 tasks and 516 annotated trajectories across search, data systems, and graphical interfaces, evaluating judge-agent abilities in information acquisition, state verification, and process verification; the project page confirms the ACL 2026 paper and public data/code surface.

## Provenance
- Canonical URL: https://arxiv.org/abs/2604.18240
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/aj-bench-benchmarking-agent-as-a-judge-for-environment-aware-evaluation.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face paper search + project page + arXiv primary metadata
