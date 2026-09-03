# Notes - "Patterns and Problems in Emerging Multiagent Systems"

**Authors:** Anthropic Frontier Red Team · **Published/Updated:** unknown · **URL:** https://www.anthropic.com/research/multiagent-systems · **Type:** research article · **Found:** true

## Summary
Anthropic’s Frontier Red Team reports measured swarm experiments spanning vulnerability discovery, collaborative coding, resource markets, and hidden-information decisions, exposing coordination, conformity, collusion, and goal-conflict failures.

## Key points
- Worker summary: Anthropic’s Frontier Red Team reports measured swarm experiments spanning vulnerability discovery, collaborative coding, resource markets, and hidden-information decisions, exposing coordination, conformity, collusion, and goal-conflict failures.
- Worker candidate reason: The article studies multi-agent behavior at unusual scale with explicit environments, metrics, and caveats—including where headline swarm gains disappear under a scope-matched comparison—rather than offering generic multi-agent speculation.
- Worker evidence: Anthropic reports a 45-agent, 15-project vulnerability experiment: independent Mythos agents found 21 vulnerabilities using 6.5 million tokens, while a coordinating swarm found 266 using 27 million, but roughly half were outside the independent agents’ allowed core directories and the methods became comparable per token after scope matching. Other experiments ran coding swarms for 12 hours, observed 2.4 million job requests for only 117 accepted jobs in one resource-allocation run, and used 400 hidden-information episodes per model.
- Source seam: `company research blog`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
The article studies multi-agent behavior at unusual scale with explicit environments, metrics, and caveats—including where headline swarm gains disappear under a scope-matched comparison—rather than offering generic multi-agent speculation.

## Provenance
- Canonical URL: https://www.anthropic.com/research/multiagent-systems
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/patterns-and-problems-in-emerging-multiagent-systems.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- company research blog
