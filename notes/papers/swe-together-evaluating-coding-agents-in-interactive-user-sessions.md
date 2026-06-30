# Notes - "SWE-Together: Evaluating Coding Agents in Interactive User Sessions"

**Authors:** Yifan Wu, Zhuokai Zhao, Songlin Li, Ho Hin Lee, Jiacheng Zhu, Shirley Wu, Tianhe Yu, Serena Li, Lizhu Zhang, Xiangjun Fan, Shengzhi Li · **Published/Updated:** 2026-06-29T08:35:15Z · **URL:** https://arxiv.org/abs/2606.29957 · **Type:** paper/benchmark · **Found:** true

## Summary
Most coding-agent benchmarks are static: an agent receives a complete task description up front and is judged only by its final code. Real coding assistance is interactive, with users clarifying goals, adding constraints, and correcting mistakes over multiple turns. We introduce SWE-Together, a multi-turn benchmark reconstructed from real user-agent coding sessions. To make real interactions verifiable, we curate 109 repository-level tasks from 11,260 recorded sessions, selecting sessions with recoverable repository states, clear user goals, and observable outcomes. To replay these interactions across agents, we build a reactive LLM-based user simulator that preserves the original users' intents and provides feedback when the coding agent's progress requires it. To evaluate agents as collaborators, we measure both final repository correctness and the number of corrective feedback turns required during the interaction. Experiments with frontier coding agents show that stronger agents generally achieve higher final success rates while requiring fewer interventions, suggesting an improved user experience.

## Key points
- Worker summary: Multi-turn coding-agent benchmark reconstructed from real user-agent sessions, scoring final correctness plus corrective feedback turns.
- Worker candidate reason: It directly addresses the static-task blind spot in SWE-agent evaluation by replaying interactive user clarification and correction across repository-level coding tasks.
- Worker evidence: arXiv metadata published 2026-06-29 in cs.SE | authors: Yifan Wu, Zhuokai Zhao, Songlin Li, Ho Hin Lee, Jiacheng Zhu et al. | abstract evidence: Most coding-agent benchmarks are static: an agent receives a complete task description up front and is judged only by its final code. | curates 109 repository-level tasks from 11,260 recorded sessions and uses a reactive LLM-based user simulator.
- Source seam: `arxiv_recent_agent_benchmarks; hf_daily_papers_crosscheck`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.SE`

## Why it matters for agent evals
It directly addresses the static-task blind spot in SWE-agent evaluation by replaying interactive user clarification and correction across repository-level coding tasks.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.29957
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/swe-together-evaluating-coding-agents-in-interactive-user-sessions.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arxiv_recent_agent_benchmarks; hf_daily_papers_crosscheck
