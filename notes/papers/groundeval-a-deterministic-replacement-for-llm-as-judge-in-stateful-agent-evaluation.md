# Notes - "GroundEval: A Deterministic Replacement for LLM-as-Judge in Stateful Agent Evaluation"

**Authors:** Jeffrey Flynt · **Published/Updated:** 2026-06-22T00:41:16Z · **URL:** https://arxiv.org/abs/2606.22737 · **Type:** paper/framework · **Found:** true

## Summary
Before letting an agent operate over real context, can you prove it used the right evidence? GroundEval turns that question into a deterministic test of what the agent searched, fetched, cited, and was permitted to access. In one case study, two frontier LLM judges scored a plausible agent response above 0.85. But the trace told a different story: the agent had never retrieved the artifact its answer depended on, yielding a GroundEval score of 0.000. We introduce GroundEval, a judge-free framework for evaluating agents against grounded, time-bounded, and access-controlled evidence. GroundEval uses a domain configuration to generate questions, lets the agent choose how to answer, and then scores both the final answer and the recorded trajectory that produced it. The benchmark targets three failures that LLM-as-judge evaluation struggles to detect: whether an agent checked before claiming absence, reasoned only from evidence available to the actor at the relevant time, and used the correct causal mechanism rather than a plausible one. These correspond to three tracks: Silence, Perspective, and Counterfactual. GroundEval exposes when plausible answers rest on invalid evidence paths, and produces structured per-question diagnostics that pair tool activity with the agent's turn-level narration, making each score inspectable rather than merely reported. What our case studies turned up is that this gap isn't some rare corner case. It's exactly the blind spot that final-answer and judge-based scoring were never built to catch.

## Key points
- Worker summary: Judge-free stateful-agent evaluator that scores searched, fetched, cited, and access-permitted evidence instead of plausible final text.
- Worker candidate reason: Clears the bar by turning stateful evidence use into deterministic trajectory diagnostics; the paper reports cases where frontier judges scored plausible but unsupported answers highly.
- Worker evidence: arXiv API summary: Silence, Perspective, and Counterfactual tracks evaluate searched/fetched/cited/permissioned evidence paths.
- Source seam: `new eval benchmarks/tools`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Clears the bar by turning stateful evidence use into deterministic trajectory diagnostics; the paper reports cases where frontier judges scored plausible but unsupported answers highly.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.22737
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/groundeval-a-deterministic-replacement-for-llm-as-judge-in-stateful-agent-evaluation.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools
