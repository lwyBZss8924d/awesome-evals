# Notes - "Continually improving our agent harness"

**Authors:** Cursor · **Published/Updated:** unknown · **URL:** https://cursor.com/blog/continually-improving-agent-harness · **Type:** production engineering case study · **Found:** true

## Summary
Cursor’s production loop combines CursorBench with live A/B tests, code keep-rate, semantic user-satisfaction signals, and per-model tool-error baselines; a focused sprint cut unexpected tool-call errors by an order of magnitude.

## Key points
- Worker summary: Cursor’s production loop combines CursorBench with live A/B tests, code keep-rate, semantic user-satisfaction signals, and per-model tool-error baselines; a focused sprint cut unexpected tool-call errors by an order of magnitude.
- Worker candidate reason: The post exposes a concrete offline-to-online evaluation loop for a deployed coding agent, including a negative result that shelved a costlier summarizer, automated anomaly triage, and model-specific harness tuning—high-signal evaluation evidence embedded inside a general agent-engineering post.
- Worker evidence summary: The April 30, 2026 source pairs public benchmarks and CursorBench with production A/B tests, latency/token/tool/cache metrics, code keep-rate, LLM-classified follow-up satisfaction, and per-tool/per-model error baselines. It reports negligible quality gains from a more expensive summarizer and an order-of-magnitude reduction in unexpected tool-call errors after a focused sprint.
- Source seam: `company engineering blog; eval insight inside a general agent-building post`
- Target README section: `## 3 · The model / harness / skill decomposition`
- Primary category: `not recorded`

## Why it matters for agent evals
The post exposes a concrete offline-to-online evaluation loop for a deployed coding agent, including a negative result that shelved a costlier summarizer, automated anomaly triage, and model-specific harness tuning—high-signal evaluation evidence embedded inside a general agent-engineering post.

## Provenance
- Canonical URL: https://cursor.com/blog/continually-improving-agent-harness
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/continually-improving-our-agent-harness.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company engineering blog; eval insight inside a general agent-building post
