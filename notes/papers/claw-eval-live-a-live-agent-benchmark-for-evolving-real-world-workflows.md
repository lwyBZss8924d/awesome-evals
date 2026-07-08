# Notes - "Claw-Eval-Live: A Live Agent Benchmark for Evolving Real-World Workflows"

**Authors:** Chenxin Li, Zhengyang Tang, Huangxin Lin, Yunlong Lin, Shijue Huang, Shengyuan Liu, Bowen Ye, Rang Li, Lei Li, Benyou Wang, Yixuan Yuan · **Published/Updated:** 2026-04-30 · **URL:** https://arxiv.org/abs/2604.28139 · **Type:** paper/benchmark/code · **Found:** true

## Summary
Live workflow-agent benchmark that separates refreshable public workflow-demand signals from reproducible release snapshots, with controlled services, workspace fixtures, execution traces, audit logs, and per-task graders.

## Key points
- Worker summary: Live workflow-agent benchmark that refreshes task construction from public workflow-demand signals while preserving reproducible released snapshots.
- Worker candidate reason: Clears the bar because it contributes a concrete live-benchmark construction loop: signal-to-task pipeline, 105 released tasks, controlled services/workspace fixtures, per-task graders, execution traces, audit logs, and family-level leaderboard diagnostics.
- Worker evidence: Retrieved HF paper metadata for 2604.28139, arXiv abstract, and Claw-Eval-Live README. Evidence: 105 tasks across 17 workflow families; quarterly refresh design; ClawHub Top-500 demand signals; fixtures and graders per task; deterministic checks plus structured judges; execution traces, audit logs, service state, and post-run workspace artifacts; GitHub search found Claw-Eval-Live/Claw-Eval-Live with 43 stars and pushed 2026-06-17.
- Source seam: `hf papers + arXiv + GitHub benchmark/tool discovery`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Clears the bar because it contributes a concrete live-benchmark construction loop: signal-to-task pipeline, 105 released tasks, controlled services/workspace fixtures, per-task graders, execution traces, audit logs, and family-level leaderboard diagnostics.

## Provenance
- Canonical URL: https://arxiv.org/abs/2604.28139
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/claw-eval-live-a-live-agent-benchmark-for-evolving-real-world-workflows.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- hf papers + arXiv + GitHub benchmark/tool discovery
