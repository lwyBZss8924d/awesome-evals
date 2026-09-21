# Notes - "How we build evals for Deep Agents"

**Authors:** Vivek Trivedy, Mason Daugherty, Eugene Yurtsev, Harrison Chase (LangChain) · **Published/Updated:** 2026-03-26 · **URL:** https://www.langchain.com/blog/how-we-build-evals-for-deep-agents · **Type:** blog · **Found:** true

## Summary
Capability-tagged evals from production traces, with correctness checked before trajectory efficiency; separates SDK plumbing tests from model capability scoring.

## Key points
- Worker summary: Capability-tagged evals from production traces, with correctness checked before trajectory efficiency; separates SDK plumbing tests from model capability scoring.
- Worker candidate reason: A concrete engineering account with an inspectable eval suite, behavior taxonomy, metric definitions, and CI workflow; complements the existing benchmark-results article with how the tests are designed.
- Worker evidence: The March 26, 2026 article describes trace-derived cases, capability tags, assertions versus semantic judges, and a solve-rate metric that becomes zero on incorrect outcomes. Its current linked eval README confirms end-to-end trajectories, correctness/efficiency scoring, and Harbor integration. The article explains that ideal trajectories are approximations for open-ended work; efficiency baselines should not be mistaken for unique valid solutions. Source inspection only; no evals executed.
- Source seam: `company_engineering_blogs`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
A concrete engineering account with an inspectable eval suite, behavior taxonomy, metric definitions, and CI workflow; complements the existing benchmark-results article with how the tests are designed.

## Provenance
- Canonical URL: https://www.langchain.com/blog/how-we-build-evals-for-deep-agents
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/how-we-build-evals-for-deep-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company_engineering_blogs
