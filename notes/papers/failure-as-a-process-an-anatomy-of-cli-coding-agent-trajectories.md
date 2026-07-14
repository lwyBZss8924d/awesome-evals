# Notes - "Failure as a Process: An Anatomy of CLI Coding Agent Trajectories"

**Authors:** Xiangxin Zhao, Han Li, Shuaiting Li, Tianyi Zhao, Earl T. Barr, Federica Sarro, He Ye · **Published/Updated:** 2026-07-10 · **URL:** https://arxiv.org/abs/2607.09510 · **Type:** paper / empirical trajectory study · **Found:** true

## Summary
A process-oriented empirical analysis of 1,794 manually annotated CLI coding-agent trajectories and more than 63,000 execution steps.

## Key points
- Worker summary: Analyzes failure onset, lock-in, observability, and recovery across 1,794 manually annotated CLI-agent trajectories containing more than 63,000 execution steps.
- Worker candidate reason: It supplies an unusually large human-audited trajectory dataset and a temporal failure framework showing why outcome-only success rates miss early decisive errors, unrecoverable execution, and fabricated success.
- Worker evidence: Primary arXiv text and full Hugging Face markdown were retrieved. The study collected 3,843 Terminal-Bench trajectories from seven models across OpenHands, MiniSWE, and Terminus2, retained 1,794 complete valid runs, and manually analyzed over 63,000 steps. Among 1,184 failed runs, epistemic triggers account for 57.9% and false premises for 30.7%; 82% continue spending steps after recovery is impossible, and fabricated success appears in 26% of failed trajectories. Every failure label was human-verified, with Cohen's kappa 0.83 for root causes and weighted kappa at least 0.94 for temporal markers.
- Source seam: `arXiv cs.SE/cs.AI RSS / trajectory-analysis paper`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.SE`

## Why it matters for agent evals
It supplies an unusually large human-audited trajectory dataset and a temporal failure framework showing why outcome-only success rates miss early decisive errors, unrecoverable execution, and fabricated success.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.09510
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/failure-as-a-process-an-anatomy-of-cli-coding-agent-trajectories.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arXiv cs.SE/cs.AI RSS / trajectory-analysis paper
