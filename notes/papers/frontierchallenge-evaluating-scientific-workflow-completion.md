# Notes - "FrontierChallenge: Evaluating Scientific Workflow Completion"

**Authors:** Apodex Team · **Published/Updated:** 2026-08-25T00:00:00+00:00 · **URL:** https://arxiv.org/abs/2608.24979 · **Type:** paper/benchmark/code · **Found:** true

## Summary
Scientific agents increasingly analyze data, execute code, and produce research artifacts, yet most benchmarks emphasize final answers, isolated programs, or a single domain. We introduce FrontierChallenge, a cross-domain benchmark comprising 300 end-to-end scientific workflows. In this paper, we release and evaluate 97 of these tasks, spanning quantum chemistry, molecular dynamics, materials characterization, analytical chemistry, life science, and electrochemistry/environment. Each task provides fixed inputs and specifies a bundle of required scientific deliverables. We evaluate twelve frontier models with three agent scaffolds. Pass Rate measures the fraction of tasks satisfying the full-completion criterion, while Avg. Score captures partial progress. Each of the best-performing configurations completed only 20 of the 97 released tasks, yielding a Pass Rate of 20.6%. Partial progress translated especially poorly into complete delivery in analytical chemistry and electrochemistry/environment: Avg. Scores reached 87.6 and 94.9, but the highest Pass Rates were only 4% and 0%. Among non-passing Claude Code trajectories, 75.5% still ended with language claiming completion. These findings show that neither high partial scores nor confident claims of completion reliably indicate that a scientific task has been fully delivered, highlighting the need to evaluate end-to-end workflow execution and the completeness of scientific deliverables together.

## Key points
- Worker summary: A 97-task release of cross-domain scientific workflows grades complete, mutually consistent bundles of reports, code, tables, figures, and simulations.
- Worker candidate reason: Its all-deliverables completion gate and task-specific artifact checks expose the exact gap between plausible partial work and a genuinely finished workflow, including agents that confidently claim success after failing.
- Worker evidence: The paper releases 97 of 300 workflows across six scientific domains and evaluates 12 frontier models under three scaffolds. Best pass rate was 20.6%; some domains reached average partial scores of 87.6 or 94.9 while full-pass rates remained 4% or 0%, and 75.5% of non-passing Claude Code trajectories still claimed completion. Graders inspect required files, numeric results, formats, code execution, and cross-artifact consistency; 77 tasks additionally repeat a model-based report-quality judgment three times, an important non-deterministic component to retain in review.
- Source seam: `Hugging Face Daily Papers and alphaXiv hot-paper discovery, grounded in arXiv text and repository docs`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `not recorded`

## Why it matters for agent evals
Its all-deliverables completion gate and task-specific artifact checks expose the exact gap between plausible partial work and a genuinely finished workflow, including agents that confidently claim success after failing.

## Provenance
- Canonical URL: https://arxiv.org/abs/2608.24979
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/frontierchallenge-evaluating-scientific-workflow-completion.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers and alphaXiv hot-paper discovery, grounded in arXiv text and repository docs
