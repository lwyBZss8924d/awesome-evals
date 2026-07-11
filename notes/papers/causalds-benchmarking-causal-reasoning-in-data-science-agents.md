# Notes - "CausalDS: Benchmarking Causal Reasoning in Data-Science Agents"

**Authors:** Andrej Leban, Yuekai Sun · **Published/Updated:** 2026-07-09T04:03:26Z · **URL:** https://arxiv.org/abs/2607.08093 · **Type:** paper/benchmark/code/dataset · **Found:** true

## Summary
A deterministic, file-backed benchmark generated from hidden structural causal models that jointly tests causal reasoning, estimation, uncertainty, abstention, coding, and tool use across Pearl's three-rung hierarchy.

## Key points
- Worker summary: Generates file-backed causal data-science tasks from hidden structural causal models and scores estimation, uncertainty, tool use, and warranted abstention against private deterministic ground truth.
- Worker candidate reason: It clears the bar by combining all three rungs of Pearl's hierarchy with realistic tabular workflows, synthetic contamination resistance, first-class non-identifiability, deterministic grading, and released code/data; the paper also evaluates six current agents and separates content correctness from abstention and tool-use efficiency.
- Worker evidence: HF/arXiv paper and Apache-2.0 andleb/causalds repo retrieved: the reported dataset has 953 scenes with three observation variants; each task runs in a fresh network-disabled mini-swe-agent container; answers are file-backed and graded deterministically; code, generator, grader, main exam, and ablation datasets are released.
- Source seam: `hugging-face-daily-papers+arxiv-primary+github-code`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
It clears the bar by combining all three rungs of Pearl's hierarchy with realistic tabular workflows, synthetic contamination resistance, first-class non-identifiability, deterministic grading, and released code/data; the paper also evaluates six current agents and separates content correctness from abstention and tool-use efficiency.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.08093
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/causalds-benchmarking-causal-reasoning-in-data-science-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- hugging-face-daily-papers+arxiv-primary+github-code
