# Notes - "ToolPrivacyBench: Benchmarking Purpose-Bound Privacy in Tool-Using LLM Agents"

**Authors:** Shijing Hu, Liang Liu, Zhu Meng, Zhicheng Zhao · **Published/Updated:** 2026-06-26T13:08:46Z · **URL:** https://arxiv.org/abs/2606.28061 · **Type:** paper/benchmark · **Found:** true

## Summary
Large language models (LLMs) have increasingly moved from standalone text generation systems to agents that invoke external tools, access environments, and execute multi-step tasks. However, conventional function-calling benchmarks mainly evaluate task completion and API correctness, while privacy evaluation benchmarks typically focus on final responses or privacy judgments. Neither perspective captures purpose-bound information flow across an executed multi-tool trajectory. Motivated by this limitation in current agent evaluation, ToolPrivacyBench audits whether task-private atoms are routed only to authorized tools and downstream sinks, thereby evaluating both task completion and privacy over-disclosure during tool use. The benchmark contains 2,150 cases, including 1,150 fully synthetic privacy-sensitive business workflows and 1,000 cases adapted from existing multi-tool and function-calling benchmarks. Each case is represented by a policy knowledge base. After an agent executes against mock business backends, the evaluator compares recorded tool arguments and backend audit logs with this policy knowledge base. The evaluation covers nine widely used agents to characterize purpose-bound privacy over-disclosure. The results show that successful tool execution does not imply appropriate privacy disclosure: an agent may complete a task while transmitting unnecessary private information through intermediate tool calls. ToolPrivacyBench therefore formalizes a need-to-know disclosure boundary, under which each tool should receive only the information necessary for its stated purpose, and uses trajectory-level auditing to identify privacy over-disclosure in multi-tool workflows.

## Key points
- Worker summary: Purpose-bound privacy benchmark that audits multi-tool agent trajectories against policy-backed disclosure boundaries.
- Worker candidate reason: Clears the bar because it scores recorded tool arguments and backend audit logs against a policy knowledge base across 2,150 cases, exposing privacy over-disclosure that task-completion metrics miss.
- Worker evidence: arXiv API metadata retrieved 2026-06-26T13:08:46Z: Large language models (LLMs) have increasingly moved from standalone text generation systems to agents that invoke external tools, access environments, and execute multi-step tasks. However, conventional function-calling benchmarks mainly evaluate task completion and API correctness, while privacy evaluation benchmarks typically focus on final responses or privacy judgments. Neither perspective captures purpose-bound information flow across an executed multi-tool trajectory. Motivated by this limitation in current agent evaluation, ToolPrivacyBench audits whether task-private atoms are routed only to authorized tools and downstream sinks, thereby evaluating both task completion and privacy over-disclosure during tool use. The benchmark contains 2,150 cases, including 1,150 fully synthetic privacy-sensitive business workflows and 1,000 cases adapted from existing multi-tool and function-calling benchmarks. Each case is represented by a policy knowledge base. After an agent executes against mock business backends, the evaluator compares recorded tool arguments and backend audit logs with this policy knowledge base. The evaluation covers nine widely used agents to characterize purpose-bound privacy over-disclosure. The results show that successful tool execution does not imply appropriate privacy disclosure: an agent may complete a task while transmitting unnecessary private information through intermediate tool calls. ToolPrivacyBench therefore formalizes a need-to-know disclosure boundary, under which each tool should receive only the information necessary for its stated purpose, and uses trajectory-level auditing to identify privacy over-disclosure in multi-tool workflows.
- Source seam: `arXiv API latest agent-evaluation search`
- Target README section: `10 · Safety / adversarial evaluation (prompt injection, jailbreaks, action-authorization, benchmark auditing)`
- Primary category: `cs.CR`

## Why it matters for agent evals
Clears the bar because it scores recorded tool arguments and backend audit logs against a policy knowledge base across 2,150 cases, exposing privacy over-disclosure that task-completion metrics miss.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.28061
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/toolprivacybench-benchmarking-purpose-bound-privacy-in-tool-using-llm-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arXiv API latest agent-evaluation search
