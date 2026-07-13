# Notes - "Do Automated Evals Work?"

**Authors:** Parlance Labs · **Published/Updated:** unknown · **URL:** https://parlance-labs.com/blog/posts/auto-evals.html · **Type:** blog/production study · **Found:** true

## Summary
Production study comparing automated error analysis with human review on 100 real agent traces; the best system recovered 87.2% of known failures but all systems missed product-context failures invisible in the trace.

## Key points
- Worker summary: Production study comparing automated error analysis with human review on 100 real agent traces; the best system recovered 87.2% of known failures but all systems missed product-context failures invisible in the trace.
- Worker candidate reason: Clears the bar with a reproducible comparison design, real production data, explicit recall/precision/false-positive results across three eval platforms and three coding agents, and an actionable human-in-the-loop workflow for criteria drift.
- Worker evidence: Retrieved the full primary post. A domain expert labeled 100 apartment-leasing-agent traces with 39 failures; six automated systems were tested on masked traces. Reported recall ranged from 74.4% to 87.2%, precision from 77.4% to 91.0%, and every system missed failures requiring undiscovered product context such as objection handling, SMS formatting, interruptions, and mandatory handoffs.
- Source seam: `known-author practitioner blog`
- Target README section: `5 · Evaluation infrastructure (the eval stack: datasets, scorers, online/offline, tracing, CI)`
- Primary category: `not recorded`

## Why it matters for agent evals
Clears the bar with a reproducible comparison design, real production data, explicit recall/precision/false-positive results across three eval platforms and three coding agents, and an actionable human-in-the-loop workflow for criteria drift.

## Provenance
- Canonical URL: https://parlance-labs.com/blog/posts/auto-evals.html
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/do-automated-evals-work.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- known-author practitioner blog
