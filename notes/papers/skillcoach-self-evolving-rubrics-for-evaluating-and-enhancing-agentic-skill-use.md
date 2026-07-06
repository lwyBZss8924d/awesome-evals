# Notes - "SkillCoach: Self-Evolving Rubrics for Evaluating and Enhancing Agentic Skill-Use"

**Authors:** Jiayin Zhu, Kelong Mao, Yudong Guo, Dengbo He, Sulong Xu, Simiu Gu, Yutao Yue · **Published/Updated:** 2026-07-02T08:28:51Z · **URL:** https://arxiv.org/abs/2607.01874 · **Type:** paper · **Found:** true

## Summary
Skills are becoming a reusable operational layer for LLM agents, encoding SOPs, domain rules, tool workflows, scripts, and validation routines. In realistic skill repositories, overlapping skills make reliable skill-use difficult. Final verifier success is too coarse for both evaluation and training, since an agent may pass through trial and error while selecting distractor skills, skipping required steps, composing workflows incorrectly or omitting final checks. We introduce SkillCoach, a self-evolving rubric framework for evaluating and enhancing agentic skill-use. SkillCoach derives skill-grounded process rubrics from real rollouts and evaluates trajectories along four dimensions: skill selection, skill following, skill composition, and skill-grounded reflection. It keeps the external verifier as a separate outcome signal, allowing process quality to be distinguished from accidental task success. The evolved rubrics further serve as process supervision for selecting high-quality training trajectories. Experiments show that evolved rubrics substantially improve evaluation quality, expose failures hidden by final accuracy, and provide stronger supervision signals than outcome-only filtering for enhancing agentic skill-use.

## Key points
- Worker summary: Agent-skill evaluation paper that derives process rubrics from rollouts and separates skill-use quality from final verifier success.
- Worker candidate reason: Clears the bar because it targets a specific agent-evaluation blind spot: final success can hide distractor-skill selection, skipped steps, bad composition, and missing final checks; its four-dimension rubric provides a concrete process-evaluation method for skill repositories.
- Worker evidence: {'fetched': 'hf-info-2607.01874.txt', 'primary_arxiv': 'arxiv-2607.01874.xml'}
- Source seam: `huggingface-daily-papers + arxiv-primary`
- Target README section: `3 · The model / harness / skill decomposition`
- Primary category: `cs.AI`

## Why it matters for agent evals
Clears the bar because it targets a specific agent-evaluation blind spot: final success can hide distractor-skill selection, skipped steps, bad composition, and missing final checks; its four-dimension rubric provides a concrete process-evaluation method for skill repositories.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.01874
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/skillcoach-self-evolving-rubrics-for-evaluating-and-enhancing-agentic-skill-use.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- huggingface-daily-papers + arxiv-primary
