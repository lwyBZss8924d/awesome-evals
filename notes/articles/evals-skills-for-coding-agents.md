# Notes - "Evals Skills for Coding Agents"

**Authors:** Hamel Husain and Shreya Shankar · **Published/Updated:** 2026-03-02 (updated 2026-08-31) · **URL:** https://hamel.dev/blog/posts/evals-skills · **Type:** blog / skills resource · **Found:** true

## Summary
Reusable agent skills turn trace review, failure discovery and human-calibrated judging into concrete product-eval workflows. ⚠️ Interactive review; repository has no declared license.

## Key points
- Worker summary: Reusable agent skills turn trace review, failure discovery and human-calibrated judging into concrete product-eval workflows. ⚠️ Interactive review; repository has no declared license.
- Worker candidate reason: Extends the section's general Agent Skills coverage with eval-specific procedures and inspectable source. Frozen repository files implement human-label data splits and judge calibration; dated GitHub metadata and an unaffiliated issue provide community-interest evidence beyond an author-only launch.
- Worker evidence: Read the author article (published 2026-03-02, modified 2026-08-31) and ai-evals-course/evals-skills at commit 2edbc5b1b0dc91f74fcfa8fd8f7eaeb302e052ab. README and skills/validate-evaluator/SKILL.md specify disjoint training, development and held-out test data, TPR/TNR and bias correction. skills/error-discovery/SKILL.md explicitly requires an interactive session. GitHub API on 2026-09-19 reported 623 stars, 51 forks, archived=false and no declared license; issue #16 has author_association=NONE and requests a license. This supports community interest, not verified production adoption. Source read only; no package installation or skill execution.
- Source seam: `known_authors_and_eval_tools`
- Target README section: `## 3 · The model / harness / skill decomposition`
- Primary category: `not recorded`

## Why it matters for agent evals
Extends the section's general Agent Skills coverage with eval-specific procedures and inspectable source. Frozen repository files implement human-label data splits and judge calibration; dated GitHub metadata and an unaffiliated issue provide community-interest evidence beyond an author-only launch.

## Provenance
- Canonical URL: https://hamel.dev/blog/posts/evals-skills
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/evals-skills-for-coding-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- known_authors_and_eval_tools

## Primary evidence and review limits

- Source inspection date: 2026-09-19.
- Status: worker candidate draft; independent review and supervisor promotion pending.
- [Primary source 1](https://hamel.dev/blog/posts/evals-skills/)
- [Primary source 2](https://github.com/ai-evals-course/evals-skills/blob/2edbc5b1b0dc91f74fcfa8fd8f7eaeb302e052ab/README.md)
- [Primary source 3](https://github.com/ai-evals-course/evals-skills/blob/2edbc5b1b0dc91f74fcfa8fd8f7eaeb302e052ab/skills/validate-evaluator/SKILL.md)
- [Primary source 4](https://github.com/ai-evals-course/evals-skills/blob/2edbc5b1b0dc91f74fcfa8fd8f7eaeb302e052ab/skills/error-discovery/SKILL.md)
- [Primary source 5](https://github.com/ai-evals-course/evals-skills/issues/16)
- No declared repository license at retrieval; see issue #16.
- Error discovery requires interactive human review.
- Community signals do not demonstrate production effectiveness.

> This skill is meant for interactive sessions only.

[Source for the excerpt](https://github.com/ai-evals-course/evals-skills/blob/2edbc5b1b0dc91f74fcfa8fd8f7eaeb302e052ab/skills/error-discovery/SKILL.md)
