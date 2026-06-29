# Notes - "GUI vs. CLI: Execution Bottlenecks in Screen-Only and Skill-Mediated Computer-Use Agents"

**Authors:** Xiao Zhou, Siyue Zhang, Yilun Zhao, Jinbiao Wei, Tingyu Song, Arman Cohan, Chen Zhao · **Published/Updated:** 2026-06-22T17:05:07Z · **URL:** https://arxiv.org/abs/2606.24551 · **Type:** paper/benchmark · **Found:** true

## Summary
Computer-use agents can execute software tasks through either graphical interfaces or programmatic command interfaces, but existing evaluations confound interaction modality with differences in tasks, initial states, verifiers, and permitted actions. We introduce a matched execution-layer benchmark of 440 desktop tasks across 18 applications and 12 workflow categories, where screen-only GUI agents and skill-mediated CLI agents receive identical goals, states, and final-state verifiers while being restricted to modality-native actions. In this controlled setting, the strongest GUI agent reaches a 59.1% full pass rate, outperforming the strongest original-skill CLI agent at 48.2%; however, verifier-guided skill augmentation raises CLI success to 69.3%, showing that much of the CLI deficit comes from incomplete skill coverage rather than model capability alone. These results suggest that GUI and CLI expose different execution bottlenecks: GUI agents are limited by reliable grounded interaction over long-horizon workflows, whereas CLI agents are limited by the coverage and scalability of their skill interfaces.

## Key points
- Worker summary: Matched desktop benchmark separating GUI grounding bottlenecks from CLI skill-interface coverage.
- Worker candidate reason: Clears the bar because it controls goals, states, verifiers, and permitted actions across 440 desktop tasks, isolating execution-layer bottlenecks instead of conflating task mix with interface modality.
- Worker evidence: arXiv API metadata retrieved 2026-06-22T17:05:07Z: Computer-use agents can execute software tasks through either graphical interfaces or programmatic command interfaces, but existing evaluations confound interaction modality with differences in tasks, initial states, verifiers, and permitted actions. We introduce a matched execution-layer benchmark of 440 desktop tasks across 18 applications and 12 workflow categories, where screen-only GUI agents and skill-mediated CLI agents receive identical goals, states, and final-state verifiers while being restricted to modality-native actions. In this controlled setting, the strongest GUI agent reaches a 59.1% full pass rate, outperforming the strongest original-skill CLI agent at 48.2%; however, verifier-guided skill augmentation raises CLI success to 69.3%, showing that much of the CLI deficit comes from incomplete skill coverage rather than model capability alone. These results suggest that GUI and CLI expose different execution bottlenecks: GUI agents are limited by reliable grounded interaction over long-horizon workflows, whereas CLI agents are limited by the coverage and scalability of their skill interfaces. Hugging Face paper metadata links GitHub repo https://github.com/rebeccaz4/gui-vs-cli and records 28 upvotes.
- Source seam: `arXiv API plus Hugging Face Daily Papers metadata`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Clears the bar because it controls goals, states, verifiers, and permitted actions across 440 desktop tasks, isolating execution-layer bottlenecks instead of conflating task mix with interface modality.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.24551
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/gui-vs-cli-execution-bottlenecks-in-screen-only-and-skill-mediated-computer-use-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arXiv API plus Hugging Face Daily Papers metadata
