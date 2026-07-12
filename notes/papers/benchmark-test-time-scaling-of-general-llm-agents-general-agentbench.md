# Notes - "Benchmark Test-Time Scaling of General LLM Agents (General AgentBench)"

**Authors:** Xiaochuan Li, Ryan Ming, Pranav Setlur, Abhijay Paladugu, Andy Tang, Hao Kang, Shuai Shao, Rong Jin, Chenyan Xiong · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2602.18998 · **Type:** paper/benchmark/code · **Found:** true

## Summary
Unifies seven search, coding, reasoning, and tool-use benchmarks behind one MCP tool pool, exposing general-agent degradation plus context-ceiling and self-verification limits to test-time scaling.

## Key points
- Worker summary: Unifies seven search, coding, reasoning, and tool-use benchmarks behind one MCP tool pool, exposing general-agent degradation plus context-ceiling and self-verification limits to test-time scaling.
- Worker candidate reason: It isolates a practically important harness effect by running ten models across BrowseComp, WebVoyager, SWE-bench Verified, Terminal-Bench, MathHay, tau2-bench, and MCP-Bench through one shared tool interface, then measures both longer-horizon and best-of-k scaling; the paper, task adapters, harness, setup guides, and MIT license make the results inspectable and reusable.
- Worker evidence: Retrieved the primary arXiv paper, https://general-agentbench.github.io/, and https://github.com/cxcscmu/General-AgentBench metadata/README. The benchmark samples 496 tasks across seven source benchmarks and four domains, presents every domain's tools through a shared MCP host, evaluates ten models, and reports roughly 10-30% average degradation for most models versus specialized settings. Sequential scaling plateaus or degrades past model/domain-specific context ceilings; parallel pass@k improves while self-choice lags, and even a GPT-5 external verifier does not close the gap. The repository contains the unified agent system and per-benchmark implementations under MIT.
- Source seam: `general agent-building post/project page -> canonical arXiv paper -> GitHub benchmark harness`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
It isolates a practically important harness effect by running ten models across BrowseComp, WebVoyager, SWE-bench Verified, Terminal-Bench, MathHay, tau2-bench, and MCP-Bench through one shared tool interface, then measures both longer-horizon and best-of-k scaling; the paper, task adapters, harness, setup guides, and MIT license make the results inspectable and reusable.

## Provenance
- Canonical URL: https://arxiv.org/abs/2602.18998
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/benchmark-test-time-scaling-of-general-llm-agents-general-agentbench.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- general agent-building post/project page -> canonical arXiv paper -> GitHub benchmark harness
