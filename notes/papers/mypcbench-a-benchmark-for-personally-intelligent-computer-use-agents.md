# Notes - "MyPCBench: A Benchmark for Personally Intelligent Computer-Use Agents"

**Authors:** Lawrence Keunho Jang, Andrew Keunwoo Jang, Jing Yu Koh, Ruslan Salakhutdinov · **Published/Updated:** 2026-06-15T14:08:09Z · **URL:** https://arxiv.org/abs/2606.16748v1 · **Type:** paper/benchmark/project · **Found:** true

## Summary
Current benchmarks for computer-use agents evaluate models in impersonal environments. This leaves a gap between evaluation and deployment where personal assistants are expected to work across a user's whole digital life, including their context, historical data, and logged-in accounts. This gap is widest on web tasks, where live web evaluations cannot exercise sites that require logging in or personal information, the kind of site a real personal assistant has to drive. We introduce MyPCBench, which tests computer-use agents as personal assistants on a Linux desktop populated with 17 simulated real-world web applications and a full desktop stack, all seeded for one canonical persona, Michael Scott from The Office. We define 184 tasks in this environment, each inspired by a real request drawn from the OpenClaw community, and benchmark six closed and open-weight models with a uniform computer+bash tool surface. We find that the best model, Claude Opus 4.6, fully solves 55.4\% of the tasks, the only model above 50\%. Model failures cluster on tasks that span many applications and on long trajectories, where personalization stresses an assistant the most. We release the environment, task set, and agent harness at https://mypcbench.com.

## Key points
- Worker summary: Personal-assistant computer-use benchmark on a Linux desktop seeded with a persona, 17 simulated web apps, 184 tasks, and a uniform computer+bash tool surface.
- Worker candidate reason: Clears the bar because it evaluates computer-use agents under personalization and logged-in-account constraints missing from impersonal desktop/web benchmarks; the paper reports the best model fully solves only 55.4% and failures cluster on multi-app, long-trajectory tasks.
- Worker evidence: arXiv API metadata in discovery-arxiv.json, hf-read-2606.16748.md, and jina-read-mypc.md report 17 simulated real-world web apps, a full desktop stack, one seeded persona, 184 OpenClaw-inspired tasks, six benchmarked models, and project release at https://mypcbench.com.
- Source seam: `Hugging Face Daily Papers discovery; arXiv API + Jina read + project link from paper abstract`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.LG`

## Why it matters for agent evals
Clears the bar because it evaluates computer-use agents under personalization and logged-in-account constraints missing from impersonal desktop/web benchmarks; the paper reports the best model fully solves only 55.4% and failures cluster on multi-app, long-trajectory tasks.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.16748v1
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/mypcbench-a-benchmark-for-personally-intelligent-computer-use-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers discovery; arXiv API + Jina read + project link from paper abstract
