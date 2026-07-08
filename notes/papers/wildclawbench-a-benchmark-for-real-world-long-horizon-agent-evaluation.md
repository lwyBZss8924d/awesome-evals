# Notes - "WildClawBench: A Benchmark for Real-World, Long-Horizon Agent Evaluation"

**Authors:** Shuangrui Ding, Xuanlang Dai, Long Xing, Shengyuan Ding, Ziyu Liu, Yang JingYi, Penghui Yang, Zhixiong Zhang, Xilin Wei, Xinyu Fang, Yubo Ma, Haodong Duan, Jing Shao, Jiaqi Wang, Dahua Lin, Kai Chen, Yuhang Zang · **Published/Updated:** 2026-05-11 · **URL:** https://arxiv.org/abs/2605.10912 · **Type:** paper/benchmark/code/dataset · **Found:** true

## Summary
Native-runtime benchmark of 60 human-authored bilingual multimodal tasks for long-horizon agents, with Dockerized execution, multiple agent harnesses, and hybrid grading from deterministic checks, environment-state auditing, and LLM/VLM semantic verification.

## Key points
- Worker summary: Native-runtime benchmark with 60 long-horizon multimodal tasks across OpenClaw, Claude Code, Codex CLI, and Hermes Agent harnesses.
- Worker candidate reason: Clears the bar because the paper, GitHub repo, HF dataset, Dockerized task assets, hybrid graders, and harness-comparison leaderboard expose reproducible evidence for real long-horizon agent evaluation rather than answer-only scoring.
- Worker evidence: Retrieved HF paper metadata for 2605.10912, arXiv abstract, and InternLM/WildClawBench README. Evidence: 60 human-authored bilingual multimodal tasks; average roughly 8 minutes and 20+ tool calls; live OpenClaw plus Claude Code/Codex/Hermes harnesses; Docker isolation; grading mixes deterministic checks, environment-state auditing, and LLM/VLM semantic verification; GitHub search found InternLM/WildClawBench with 466 stars and pushed 2026-06-25.
- Source seam: `hf daily papers + arXiv + GitHub benchmark/tool discovery`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Clears the bar because the paper, GitHub repo, HF dataset, Dockerized task assets, hybrid graders, and harness-comparison leaderboard expose reproducible evidence for real long-horizon agent evaluation rather than answer-only scoring.

## Provenance
- Canonical URL: https://arxiv.org/abs/2605.10912
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/wildclawbench-a-benchmark-for-real-world-long-horizon-agent-evaluation.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- hf daily papers + arXiv + GitHub benchmark/tool discovery
