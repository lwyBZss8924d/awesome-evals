# Notes - "WeaveBench: A Long-Horizon, Real-World Benchmark for Computer-Use Agents with Hybrid Interfaces"

**Authors:** Wanli Li, Bowen Zhou, Yunyao Yu, Zhou Xu, Yifan Yang, Dongsheng Li, Caihua Shan · **Published/Updated:** 2026-06-08T12:39:23Z · **URL:** https://arxiv.org/abs/2606.09426 · **Type:** paper/benchmark · **Found:** true

## Summary
Computer-use agents (CUAs) increasingly operate in runtimes that combine visual desktop control, command-line execution, code editing, browsers, and external tools. Existing benchmarks, however, often evaluate these interfaces as separable capabilities, leaving long-horizon cross-interface orchestration under-tested. Thus, we introduce WeaveBench, a long-horizon hybrid-interface benchmark with 114 tasks across 8 real-world work domains, grounded in real user requests and publicly verifiable artifacts. Each task requires agents to combine GUI observations/actions with CLI/code operations within a single trajectory. We evaluate these tasks on a real Ubuntu desktop inside deployed CLI-agent runtimes, augmented with a minimal desktop-control plugin. We also propose a companion trajectory-aware judge that inspects deliverables, files, screenshots, logs, and action traces, while detecting shortcut behaviors such as fabricated visual evidence or hard-coded metrics. Across frontier model-runtime pairings, the best PassRate reaches only 41.2%, showing the benchmark remains far from saturated. The trajectory-aware judge further reveals that outcome-only grading substantially overestimates agent performance. Overall, WeaveBench exposes a critical gap in CUA evaluation and provides an effective testbed to measure whether agents can orchestrate GUI, CLI, and code operations across long-horizon real-world tasks.

## Key points
- Worker summary: Hybrid GUI/CLI/code/browser benchmark with a trajectory-aware judge for long-horizon computer-use agents.
- Worker candidate reason: Primary arXiv and HF paper metadata report 114 tasks across 8 real-world work domains from real user requests; the companion judge inspects deliverables, files, screenshots, logs, and action traces while detecting shortcut behaviors, and the best PassRate reaches only 41.2%.
- Worker evidence: hf-papers-computer-use-verifier.json records the paper summary and 104 HF upvotes; discovery-arxiv.json id 2606.09426 confirms task/domain counts, hybrid-interface setup, trajectory-aware judging, shortcut detection, and 41.2% best PassRate.
- Source seam: `MCP Exa paper search + Hugging Face Daily Papers + arXiv primary metadata`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
Primary arXiv and HF paper metadata report 114 tasks across 8 real-world work domains from real user requests; the companion judge inspects deliverables, files, screenshots, logs, and action traces while detecting shortcut behaviors, and the best PassRate reaches only 41.2%.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.09426
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/weavebench-a-long-horizon-real-world-benchmark-for-computer-use-agents-with-hybrid-interface.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- MCP Exa paper search + Hugging Face Daily Papers + arXiv primary metadata
