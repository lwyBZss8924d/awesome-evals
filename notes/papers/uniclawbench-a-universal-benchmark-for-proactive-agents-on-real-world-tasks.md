# Notes - "UniClawBench: A Universal Benchmark for Proactive Agents on Real-World Tasks"

**Authors:** Zhekai Chen, Chengqi Duan, Kaiyue Sun, Bohao Li, Yuqing Wang, Manyuan Zhang, Xihui Liu · **Published/Updated:** 2026-07-09T17:59:32Z · **URL:** https://arxiv.org/abs/2607.08768 · **Type:** paper/benchmark/code · **Found:** true

## Summary
A capability-driven benchmark with 400 bilingual real-world tasks for proactive agents, evaluated in fresh Docker environments through an executor, hidden supervisor, and rubric-isolated public user simulator.

## Key points
- Worker summary: A 400-task bilingual benchmark for proactive agents that runs real browser, CLI, file, and GUI work in fresh containers with closed-loop user feedback and hidden checkpoint grading.
- Worker candidate reason: It clears the bar with a capability-driven taxonomy, a reproducible Docker runtime, public tasks and artifacts, and an explicit three-role design that prevents the user simulator from leaking hidden rubrics while still testing recovery across turns.
- Worker evidence: HF/arXiv paper and MIT-licensed HKU-MMLab/UniClawBench repo retrieved: 400 tasks (200 English, 200 Chinese) across five capabilities; fresh Docker execution; hidden supervisor returns pass/continue/fail; public user simulator sees only visible trajectory plus sanitized status; repository ships tasks, runtimes, traces, artifacts, and leaderboard tooling.
- Source seam: `hugging-face-daily-papers+arxiv-primary+github-project`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.CL`

## Why it matters for agent evals
It clears the bar with a capability-driven taxonomy, a reproducible Docker runtime, public tasks and artifacts, and an explicit three-role design that prevents the user simulator from leaking hidden rubrics while still testing recovery across turns.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.08768
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/uniclawbench-a-universal-benchmark-for-proactive-agents-on-real-world-tasks.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- hugging-face-daily-papers+arxiv-primary+github-project
