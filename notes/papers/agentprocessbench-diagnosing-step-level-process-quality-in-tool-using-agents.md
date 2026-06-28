# Notes - "AgentProcessBench: Diagnosing Step-Level Process Quality in Tool-Using Agents"

**Authors:** AgentProcessBench authors; RUCBM project · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2603.14465 · **Type:** paper/benchmark · **Found:** true

## Summary
Step-level benchmark for judging tool-using agent trajectories with human-labeled process annotations.

## Key points
- Worker summary: Step-level benchmark for judging tool-using agent trajectories with human-labeled process annotations.
- Worker candidate reason: Clears the bar because it targets process quality rather than only final success: 1,000 diverse trajectories, 8,509 human-labeled step annotations, ternary step labels, and reported inter-annotator agreement.
- Worker evidence: arXiv abstract fetched in evidence-arxiv-selected.xml reports 1,000 trajectories, 8,509 human-labeled step annotations, 89.1% inter-annotator agreement, ternary labels for correct/neutral/error steps, and code/data at github.com/RUCBM/AgentProcessBench; gh repo metadata fetched in evidence-gh-agentprocessbench.json.
- Source seam: `new eval benchmarks/tools via Exa + arXiv API + HF Papers`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
Clears the bar because it targets process quality rather than only final success: 1,000 diverse trajectories, 8,509 human-labeled step annotations, ternary step labels, and reported inter-annotator agreement.

## Provenance
- Canonical URL: https://arxiv.org/abs/2603.14465
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/agentprocessbench-diagnosing-step-level-process-quality-in-tool-using-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools via Exa + arXiv API + HF Papers
