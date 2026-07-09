# Notes - "RuBench: A Repository-Level Agentic Coding Benchmark with Natively Authored Russian Task Specifications"

**Authors:** Evgeny Shilov · **Published/Updated:** 2026-07-07T15:41:22Z · **URL:** https://arxiv.org/abs/2607.06411 · **Type:** benchmark/paper/repo · **Found:** true

## Summary
Developers increasingly delegate real maintenance work to product-grade coding agents, and many state tasks in their native language, in the style of a customer request rather than a curated English issue. Existing repository-level agentic benchmarks do not measure this setting: their task statements are English by design. We introduce RuBench 1.0, a benchmark of 25 tasks mined from recent fix commits in five live open-source repositories (aiohttp, aiogram, Laravel, NestJS, Fastify; Python, PHP, TypeScript, JavaScript), where each task is specified natively in Russian -- written from scratch in the style of an actual customer request, not translated -- and judged by the upstream maintainer's regression tests, which we withhold from release. All 25 fix commits postdate the training-data cutoffs of every evaluated model, giving a contamination argument that holds task-by-task. We evaluate deployed product configurations (CLI agent + model + reasoning effort) -- Claude Code with Opus 4.8, Sonnet 5, and Haiku 4.5, and Codex CLI with GPT-5.5 -- with three independent runs each, reporting pass@1 with task-level confidence intervals, paired comparisons, dollar cost, and token usage. The best configuration resolves 78.7% of tasks; at N=25 only the gaps to the weakest model are statistically resolvable, which we state explicitly. Auditing full trajectories of a fifth, hors-concours configuration (Claude Code + Fable 5, July 2, 2026 release), we caught the product silently substituting the model: on 5 of 25 tasks (20%) an official safeguard fallback re-routed routine HTTP-protocol fixes to Opus 4.8 -- direct, reproducible evidence that the deployed product, not the model, is the unit actually measured. We release task statements, metadata, full agent trajectories, and diffs; grading oracles are withheld, with a SHA-256 manifest committed at publication time.

## Key points
- Worker summary: Repository-level coding-agent benchmark with native Russian customer-style specs and withheld maintainer regression tests.
- Worker candidate reason: Clears the bar because it ships task metadata, trajectories, diffs, harness scripts, a SHA-256 oracle manifest, repeated product-agent runs, post-cutoff task evidence, and explicit statistical caveats rather than just leaderboard numbers.
- Worker evidence: Retrieved arXiv metadata and GitHub eugeneshilow/rubench README: 25 tasks from aiohttp, aiogram, Laravel, NestJS, and Fastify; 4 product agent configurations with 3 runs each; 320 cell artifacts; task statements, metadata, full trajectories, final diffs, harness scripts, and withheld grading oracles committed by SHA-256 manifest.
- Source seam: `new eval benchmarks/tools`
- Target README section: `9 - Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.SE`

## Why it matters for agent evals
Clears the bar because it ships task metadata, trajectories, diffs, harness scripts, a SHA-256 oracle manifest, repeated product-agent runs, post-cutoff task evidence, and explicit statistical caveats rather than just leaderboard numbers.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.06411
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/rubench-a-repository-level-agentic-coding-benchmark-with-natively-authored-russian-task-spec.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools
