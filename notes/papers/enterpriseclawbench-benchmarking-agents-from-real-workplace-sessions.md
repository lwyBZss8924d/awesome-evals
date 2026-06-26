# Notes - "EnterpriseClawBench: Benchmarking Agents from Real Workplace Sessions"

**Authors:** Jincheng Zhong, Weizhi Wang, Che Jiang, Kai Tian, Zhenzhao Yuan, Junlin Yang, Dianqiao Lei, Kaiyan Zhang · **Published/Updated:** 2026-06-22T17:39:43Z · **URL:** https://arxiv.org/abs/2606.23654 · **Type:** paper/benchmark · **Found:** true

## Summary
Enterprise agents increasingly operate inside workspaces: they read heterogeneous files, invoke tools, and deliver business artifacts. We introduce EnterpriseClawBench, an enterprise agent benchmark constructed from proprietary, real-world agent sessions. Starting from a large archive of workplace sessions, the EnterpriseClawBench produces 852 reproducible tasks, each paired with recovered fixtures, rewritten prompts, role classes, skill subclasses, hard rules, and semantic rubrics. Because the sessions contain internal enterprise content, we do not release the benchmark data; instead, our reusable contribution is the construction and evaluation protocol. On EnterpriseClawBench, the best configuration reaches only 0.663 (Codex with GPT-5.5). These results show that enterprise agent evaluation must report harness--model combinations, artifact delivery, visual quality, cost, runtime, and skill-transfer behavior, rather than collapsing performance into a single score. Code: https://github.com/FrontisAI/EnterpriseClawBench

## Key points
- Worker summary: Enterprise-agent benchmark built from workplace sessions with fixtures, rewritten prompts, role/skill classes, hard rules, and semantic rubrics.
- Worker candidate reason: High-signal because it describes a reproducible construction protocol for 852 tasks from real workplace sessions and argues for reporting harness-model, artifact quality, cost, runtime, and skill transfer.
- Worker evidence: arXiv API summary and code pointer to FrontisAI/EnterpriseClawBench.
- Source seam: `new eval benchmarks/tools`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.CL`

## Why it matters for agent evals
High-signal because it describes a reproducible construction protocol for 852 tasks from real workplace sessions and argues for reporting harness-model, artifact quality, cost, runtime, and skill transfer.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.23654
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/enterpriseclawbench-benchmarking-agents-from-real-workplace-sessions.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools
