# Notes - "Measuring and improving coding audit realism with deployment resources"

**Authors:** Connor Kissane, Monte MacDiarmid, Fabien Roger · **Published/Updated:** unknown · **URL:** https://alignment.anthropic.com/2026/coding-audit-realism · **Type:** research blog / empirical evaluation study · **Found:** true

## Summary
Measures whether judges distinguish coding audits from deployment traces and tests realistic environment resources; improved realism did not significantly change reward-hacking rates.

## Key points
- Worker summary: Measures whether judges distinguish coding audits from deployment traces and tests realistic environment resources; improved realism did not significantly change reward-hacking rates.
- Worker candidate reason: Provides a worked audit-validity method, controlled resource ablations, and reproduction scripts, extending the list beyond detecting verbalized evaluation awareness.
- Worker evidence: The 2026-03-23 study compares audit/deployment transcript pairs and tests prompts, tools, and codebase resources. It reports realism win rate rising from 4.6% to 32.8% across 50 reward-hacking audits, without a significant hacking-rate change. High-stakes scenarios remain distinguishable. Limitations include narrow deployment samples and judge dependence. The linked ckkissane/petri-realism-win-rate README provides reproduction scripts but explicitly withholds the original deployment data; exact reproduction therefore requires unavailable inputs. This is an empirical article nomination, not a standalone tool-adoption endorsement.
- Source seam: `company research/engineering blogs`
- Target README section: `10 · Safety / adversarial evaluation (prompt injection, jailbreaks, action-authorization, benchmark auditing)`
- Primary category: `not recorded`

## Why it matters for agent evals
Provides a worked audit-validity method, controlled resource ablations, and reproduction scripts, extending the list beyond detecting verbalized evaluation awareness.

## Provenance
- Canonical URL: https://alignment.anthropic.com/2026/coding-audit-realism
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/measuring-and-improving-coding-audit-realism-with-deployment-resources.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company research/engineering blogs
