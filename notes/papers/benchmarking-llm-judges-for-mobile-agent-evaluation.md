# Notes - "Benchmarking LLM Judges for Mobile Agent Evaluation"

**Authors:** Wang, Ziqiang, Gu, Li, Chi, Zhixiang, Liu, Zhi, Ayyoubzadeh, Seyed Mehdi, Yu, Yuanhao, Wang, Yang · **Published/Updated:** 2026-08-11 · **URL:** https://arxiv.org/abs/2608.11434 · **Type:** paper · **Found:** true

## Summary
MobileJudgeBench evaluates judges on 931 human-annotated trajectories; sampled-screenshot baselines and backend-specific error analysis show why judge reliability must be measured before ranking agents or using judge rewards.

## Key points
- Worker summary: MobileJudgeBench evaluates judges on 931 human-annotated trajectories; sampled-screenshot baselines and backend-specific error analysis show why judge reliability must be measured before ranking agents or using judge rewards.
- Worker candidate reason: Adds a mobile-specific meta-evaluation beyond the existing web-trajectory and judge entries: compares six judge methods against human labels, tests ranking fidelity, and connects false-positive/false-negative profiles to reward quality.
- Worker evidence: Primary arXiv abstract and Sections 3–5 report 931 trajectories from six benchmarks, four agents and 68 apps, labeled independently by 2–4 annotators with 88.4% pairwise agreement. Section 5.1 compares six judge methods across five backends; a simple sampled-screenshot baseline is competitive with purpose-built methods. Section 5.2 links F1 and balanced accuracy to ranking and success-rate reliability. Its matched-accuracy training comparison is suggestive: the higher-precision judge wins under best-checkpoint selection but ties the other judge on the full set at the final checkpoint. Section 7 limits training evidence to AndroidWorld and one judge method; binary completion does not evaluate trajectory efficiency or partial progress.
- Source seam: `alphaxiv-discovery / mobile-agent judge benchmarks`
- Target README section: `8 · LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `Artificial Intelligence (cs.AI)`

## Why it matters for agent evals
Adds a mobile-specific meta-evaluation beyond the existing web-trajectory and judge entries: compares six judge methods against human labels, tests ranking fidelity, and connects false-positive/false-negative profiles to reward quality.

## Provenance
- Canonical URL: https://arxiv.org/abs/2608.11434
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/benchmarking-llm-judges-for-mobile-agent-evaluation.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- alphaxiv-discovery / mobile-agent judge benchmarks

## Primary evidence inspected

- [abstract and citation metadata](https://arxiv.org/abs/2608.11434)
- [Sections 3.2, 5.1, 5.2.1, 5.2.2, 5.3, 7; Appendix C.1](https://arxiv.org/html/2608.11434)
- Discovery surface: https://www.alphaxiv.org/abs/2608.11434 (used to locate the resource; claims checked against the primary sources above).

Retrieved: 2026-09-05T03:46:05Z. Read primary paper; experiments and artifact release availability were not independently reproduced.
