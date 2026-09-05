# Notes - "Terminal-Universe: Turning Agent Trajectories into Scalable Terminal Environments"

**Authors:** Wu, Jie, Zhang, Zhenru, Zhang, Beichen, Wang, Xuwu, Su, Yuhui, Chen, Mouxiang, Wang, Peng, Wang, Zhihai, Shen, Que, Zhou, Hao, Yang, An, Huang, Fei, Yang, Yujiu, Liu, Dayiheng · **Published/Updated:** 2026-09-03 · **URL:** https://arxiv.org/abs/2609.04148 · **Type:** paper · **Found:** true

## Summary
Reconstructs reusable terminal workspaces from agent traces, adds cross-workspace and multi-round tasks, and filters rollouts with executable verifiers; useful environment-construction evidence with explicit teacher-correlation limits.

## Key points
- Worker summary: Reconstructs reusable terminal workspaces from agent traces, adds cross-workspace and multi-round tasks, and filters rollouts with executable verifiers; useful environment-construction evidence with explicit teacher-correlation limits.
- Worker candidate reason: Provides a concrete route from recorded trajectories to executable evaluation and training environments, including reconstruction, final-state tests, decontamination, multi-round recovery, and ablations rather than an ungrounded benchmark launch.
- Worker evidence: The primary arXiv abstract and Sections 3–5 describe replaying file operations to restore pre-edit workspace state, completing missing dependencies, and synthesizing single-workspace, cross-workspace and multi-round tasks. Section 3.3 runs agent-authored pytest suites against final workspace state and retains intermediate failures followed by recovery in multi-round sessions. Section 5.1 excludes Terminal-Bench-derived sources and applies a 13-gram contamination check. Table 3 reports Qwen3.5-27B improving Terminal-Bench 2.1 from 46.2% to 58.1% under Terminus2-XML, with mean pass rates over six runs. Section 7 explicitly warns that one teacher generates tasks, solutions and verifiers, so correlated errors may pass its own tests; Ubuntu-only environments and source-trajectory coverage also limit fidelity.
- Source seam: `Hugging Face Daily Papers / terminal environments`
- Target README section: `7 · Evals & RL environments (verifiers, reward design, difficulty calibration, lifecycle)`
- Primary category: `Artificial Intelligence (cs.AI)`

## Why it matters for agent evals
Provides a concrete route from recorded trajectories to executable evaluation and training environments, including reconstruction, final-state tests, decontamination, multi-round recovery, and ablations rather than an ungrounded benchmark launch.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.04148
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/terminal-universe-turning-agent-trajectories-into-scalable-terminal-environments.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers / terminal environments

## Primary evidence inspected

- [abstract and citation metadata](https://arxiv.org/abs/2609.04148)
- [Sections 3.1–3.3, 5.1, Table 3, Section 7](https://arxiv.org/html/2609.04148)
- Discovery surface: https://huggingface.co/papers/2609.04148 (used to locate the resource; claims checked against the primary sources above).

Retrieved: 2026-09-05T03:46:05Z. Read primary paper after Hub reader returned only figure text; reported gains are author results, not an independent reproduction.
