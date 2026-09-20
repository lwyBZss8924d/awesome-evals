# Notes - "Beyond Outcomes: Dual-View Relational Learning for Efficient Agent Benchmarking"

**Authors:** Xinshuai Guo, Junjie Wu, Dolly Deng, Yinghui Li, Hai-Tao Zheng, Suncong Zheng, Maxm Pan · **Published/Updated:** 2026-09-16 · **URL:** https://arxiv.org/abs/2609.18909 · **Type:** paper / evaluation methodology · **Found:** true

## Summary
DualViewEval combines outcomes and trajectory signals to select compact agent-evaluation suites; inspect held-out score and ranking errors before using its estimates.

## Key points
- Worker summary: DualViewEval combines outcomes and trajectory signals to select compact agent-evaluation suites; inspect held-out score and ranking errors before using its estimates.
- Worker candidate reason: Adds a concrete benchmark-compression method with ablations and held-out agent evaluation, complementing the existing benchmark-integrity resources.
- Worker evidence: arXiv v1, 2026-09-16: Sections 3-4 describe hard Top-K selection with Kernel Ridge prediction, train/validation/test agent splits, and MAE/Kendall ranking evaluation. Appendix B defines six trace measurements, including failed calls and read-write-validation completion. Table 3 ablates outcome and process relations. Caveat: Table 2 does not support universal superiority: at 60 tasks on tau2-Bench, EssenceBench has higher Kendall tau (0.865) than DualViewEval (0.831). Results were inspected, not reproduced; code availability was not established.
- Source seam: `new eval benchmarks/tools; canonical arXiv paper`
- Target README section: `6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `cs.CL`

## Why it matters for agent evals
Adds a concrete benchmark-compression method with ablations and held-out agent evaluation, complementing the existing benchmark-integrity resources.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.18909
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/beyond-outcomes-dual-view-relational-learning-for-efficient-agent-benchmarking.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools; canonical arXiv paper
