# Notes - "Long-Horizon-Terminal-Bench: Testing the Limits of Agents on Long-Horizon Terminal Tasks with Dense Reward-Based Grading"

**Authors:** Zongxia Li, Zhongzhi Li, Yucheng Shi, Ruhan Wang, Junyao Yang, Zhichao Liu, Xiyang Wu, Anhao Li, Yue Yu, Ninghao Liu, Lichao Sun, Haotao Mi, Leowei Liang · **Published/Updated:** 2026-07-10 · **URL:** https://arxiv.org/abs/2607.08964 · **Type:** paper / benchmark · **Found:** true

## Summary
A 46-task long-horizon terminal benchmark with deterministic dense subtask grading, hidden stress cases, and evaluations of 15 frontier models.

## Key points
- Worker summary: Introduces 46 containerized terminal tasks with deterministic subtask graders and dense partial credit for workflows averaging 231 episodes, 9.9M tokens, and 85.3 minutes per run.
- Worker candidate reason: It measures sustained terminal-agent progress rather than only final pass/fail, releases a Harbor-compatible benchmark and harness, and validates the design across 15 frontier models on difficult scientific and engineering workflows.
- Worker evidence: Primary arXiv text and the Hugging Face markdown paper were retrieved. The benchmark filters 120 candidate tasks down to 46 containerized Harbor tasks across nine categories, uses objective in-container checks over files, tests, outputs, and simulator state, and weights hidden stress cases more heavily than public checks. Fifteen models were evaluated; the strongest result was 15.2% pass@1 at reward >=0.95 and 10.9% at perfect reward, while 10 of 15 models passed zero tasks at perfect reward. Dense rewards expose near-miss progress that binary scoring collapses.
- Source seam: `Hugging Face Daily Papers / arXiv cs.AI RSS / new benchmark`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
It measures sustained terminal-agent progress rather than only final pass/fail, releases a Harbor-compatible benchmark and harness, and validates the design across 15 frontier models on difficult scientific and engineering workflows.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.08964
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/long-horizon-terminal-bench-testing-the-limits-of-agents-on-long-horizon-terminal-tasks-with.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers / arXiv cs.AI RSS / new benchmark
