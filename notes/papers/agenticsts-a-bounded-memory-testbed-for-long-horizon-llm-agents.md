# Notes - "AgenticSTS: A Bounded-Memory Testbed for Long-Horizon LLM Agents"

**Authors:** Xiangchen Cheng, Yunwei Jiang, Jianwen Sun, Zizhen Li, Chuanhao Li, Xiangcheng Cao, Yihao Liu, Fanrui Zhang, Li Jin, Kaipeng Zhang · **Published/Updated:** 2026-07-02T14:44:32Z · **URL:** https://arxiv.org/abs/2607.02255 · **Type:** paper/benchmark · **Found:** true

## Summary
Memory for a long-horizon LLM agent is a contract about what each future decision is allowed to see. The simplest contract appends past observations, tool calls, and reflections to every prompt, which makes prior context easy to access but also turns it into a jumbled mixture in which the effect of any single memory component is hard to isolate. We introduce and instrument an alternative bounded contract: every decision is made from a fresh user message assembled by typed retrieval, with no raw cross-decision transcript appended. The prompt thus stays bounded across runs of any length, and any single layer can be ablated in isolation. We instantiate the contract in Slay the Spire 2, a closed-rule stochastic deck-building game whose runs require hundreds of tactical and strategic decisions. A public online benchmark of frontier LLMs on the same game reports zero wins at the lowest difficulty across five configurations, and the developer-reported human win rate at the same difficulty is 16%; the task is hard but not saturated. Within our harness, a fixed-A0 ablation shows the largest observed difference when triggered strategic skills are enabled: the no-store baseline wins 3/10 games and adding the skill layer 6/10. At this sample size the comparison is directional rather than statistically decisive (Fisher exact p\approx0.37); a cross-backbone probe and public accumulating-context baselines are reported as operational comparisons rather than controlled tests of the contract variable itself. We release a reproducible testbed: 298 completed trajectories with condition tags, frozen memory/skill snapshots, prompt records, and analysis scripts -- an agent design and a validated, reusable methodology for studying how explicit memory layers shape long-horizon LLM-agent decisions.

## Key points
- Worker summary: Bounded-memory long-horizon agent testbed with reproducible trajectories, memory/skill ablations, and public code.
- Worker candidate reason: Clears the bar because it releases an inspectable long-horizon agent-evaluation testbed with 298 trajectories, tagged conditions, frozen memory/skill snapshots, prompt records, and analysis scripts; the paper explicitly separates memory-layer effects from raw accumulating context.
- Worker evidence: {'fetched': 'hf-info-2607.02255.txt', 'github_metadata': 'gh-AlayaLab-AgenticSTS.json', 'github_repo': 'https://github.com/AlayaLab/AgenticSTS', 'primary_arxiv': 'arxiv-2607.02255.xml', 'project_page': 'https://alayalab.github.io/AgenticSTS/'}
- Source seam: `huggingface-daily-papers + arxiv-primary + github-metadata`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Clears the bar because it releases an inspectable long-horizon agent-evaluation testbed with 298 trajectories, tagged conditions, frozen memory/skill snapshots, prompt records, and analysis scripts; the paper explicitly separates memory-layer effects from raw accumulating context.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.02255
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/agenticsts-a-bounded-memory-testbed-for-long-horizon-llm-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- huggingface-daily-papers + arxiv-primary + github-metadata
