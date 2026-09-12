# Notes - "READY or Not: Reliable Enterprise Agent Deployment"

**Authors:** Veronica Chatrath et al. (Scale AI) · **Published/Updated:** 2026-09-02 · **URL:** https://arxiv.org/abs/2609.02095 · **Type:** paper · **Found:** true

## Summary
Selects a human-oversight policy on development cases, then qualifies reliability on held-out cases while reporting review burden and cost; qualification remains conditional on declared reviewer assumptions.

## Key points
- Worker summary: Selects a human-oversight policy on development cases, then qualifies reliability on held-out cases while reporting review burden and cost; qualification remains conditional on declared reviewer assumptions.
- Worker candidate reason: Provides a statistically explicit bridge from autonomous benchmark accuracy to the reliability, oversight burden, and cost of an operating human-agent system, including a worked case where similar autonomous scores lead to different review requirements.
- Worker evidence: Primary arXiv v1, submitted 2026-09-02, was retrieved directly as https://arxiv.org/html/2609.02095v1. The paper separates workflow-specific success predicates from policy selection and qualification. Its clinical-audit case study contains 750 cases and 16 agent systems, with development and qualification partitions of 375 cases each. Section 5.6 reports systems at 72.8% and 72.5% autonomous accuracy requiring 39.2% and 29.6% review at a 76% reliability target under the evaluated oversight policy. Appendix B.1 computes a one-sided 95% exact Clopper-Pearson lower bound on accepted-case success and combines it with an assumed review-success rate; the main analysis assumes reviewer success of 0.90. Section 7 explicitly limits empirical validation to terminal accept-or-escalate policies, treats unmeasured reviewer effectiveness, latency, and cost as assumptions, and makes qualification population- and configuration-specific. Trajectory-changing intervention needs policy-in-the-loop evaluation. This is a methodology paper, not clinical deployment guidance or a universal agent certificate. The paper describes an open testbed, but no dedicated READY repository or independently reproduced implementation is claimed by this scan.
- Source seam: `alphaXiv recent agent-evaluation papers; primary arXiv HTML and metadata`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Provides a statistically explicit bridge from autonomous benchmark accuracy to the reliability, oversight burden, and cost of an operating human-agent system, including a worked case where similar autonomous scores lead to different review requirements.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.02095
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/ready-or-not-reliable-enterprise-agent-deployment.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- alphaXiv recent agent-evaluation papers; primary arXiv HTML and metadata
