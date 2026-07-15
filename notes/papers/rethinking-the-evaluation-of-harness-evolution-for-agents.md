# Notes - "Rethinking the Evaluation of Harness Evolution for Agents"

**Authors:** Yike Wang, Huaisheng Zhu, Zhengyu Hu, Yige Yuan, Zhengyu Chen, Shakti Senthil, Hannaneh Hajishirzi, Yulia Tsvetkov, Pradeep Dasigi, Teng Xiao · **Published/Updated:** 2026-07-14 · **URL:** https://arxiv.org/abs/2607.12227 · **Type:** research paper and reproducibility code · **Found:** true

## Summary
Compares agent-harness evolution with simpler task-level search and test-time scaling under matched feedback and inference budgets, finding no consistent advantage and limited generalization to held-out Terminal-Bench 2.1 tasks.

## Key points
- Worker summary: A matched-budget Terminal-Bench study finds that evolved agent harnesses do not consistently outperform simpler test-time scaling or generalize reliably to held-out tasks.
- Worker candidate reason: It directly audits a fast-growing evaluation claim with held-out tasks, matched feedback and inference budgets, frontier models, multiple search baselines, and a public repository containing the evaluation split, scripts, configurations, and outputs.
- Worker evidence: The paper compares parallel sampling, sequential refinement, harness evolution, and harness scaling on held-out Terminal-Bench 2.1 tasks using GPT-5.4 and Claude Opus 4.6 under matched feedback and inference budgets; its central result is that harness evolution does not consistently beat simple test-time scaling and shows limited held-out generalization. Code and experiment assets are published at https://github.com/rethinking-harness-evolution/code.
- Source seam: `arXiv recent papers and agent-evaluation benchmark research`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `cs.AI`

## Why it matters for agent evals
It directly audits a fast-growing evaluation claim with held-out tasks, matched feedback and inference budgets, frontier models, multiple search baselines, and a public repository containing the evaluation split, scripts, configurations, and outputs.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.12227
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/rethinking-the-evaluation-of-harness-evolution-for-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arXiv recent papers and agent-evaluation benchmark research
