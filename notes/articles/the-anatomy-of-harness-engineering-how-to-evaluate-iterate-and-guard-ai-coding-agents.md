# Notes - "The Anatomy of Harness Engineering: How to Evaluate, Iterate, and Guard AI Coding Agents"

**Authors:** Taylor Mullen and Christian Gunderman (Google) · **Published/Updated:** 2026-09-09 · **URL:** https://developers.googleblog.com/en/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents · **Type:** blog · **Found:** true

## Summary
Behavioral evals for coding harnesses: assert observable tool use, allow valid alternative paths, and track batch pass rates alongside end-to-end benchmarks.

## Key points
- Worker summary: Behavioral evals for coding harnesses: assert observable tool use, allow valid alternative paths, and track batch pass rates alongside end-to-end benchmarks.
- Worker candidate reason: Google engineers give a concrete pytest example that inspects tool calls and a failure-to-assertion workflow for prompt, tool-schema, and model changes. This supplies an actionable regression-testing method for the harness section, including treatment of nondeterminism and complex tasks.
- Worker evidence: Retrieved the complete Google Developers Blog article dated 2026-09-09. In 'Writing a behavioral eval', the pytest example opens an Agent session, requests live weather, collects response.tool_calls, and asserts that SEARCH_WEB occurred; the target is an observable action rather than response-string equality. 'What to consider when building a behavioral suite' turns a recent failure into a narrow assertion, recommends flexible outcome assessment when complex tasks permit multiple valid paths, and tracks aggregate batch pass rates instead of gating on a single stochastic trial. The closing section explicitly keeps end-to-end benchmarks complementary. These are inspected source examples and engineering recommendations, not worker-executed tests or measured performance gains. The sample SDK code was not executed or independently API-validated; the article's timing suggestion is not promoted as a verified runtime. This fits the repository's trajectory pattern while retaining its caveat that rigid sequences penalize alternative correct solutions.
- Source seam: `company engineering blogs`
- Target README section: `## 3 · The model / harness / skill decomposition`
- Primary category: `not recorded`

## Why it matters for agent evals
Google engineers give a concrete pytest example that inspects tool calls and a failure-to-assertion workflow for prompt, tool-schema, and model changes. This supplies an actionable regression-testing method for the harness section, including treatment of nondeterminism and complex tasks.

## Provenance
- Canonical URL: https://developers.googleblog.com/en/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company engineering blogs

## Primary-source inspection

- https://developers.googleblog.com/en/the-anatomy-of-harness-engineering-how-to-evaluate-iterate-and-guard-ai-coding-agents/

Evidence type: primary engineering article and code-example inspection.

Locations inspected: Writing a behavioral eval; What to consider when building a behavioral suite; Final thoughts.

Limits: No worker execution of sample code; No independently measured speed or quality improvement.
