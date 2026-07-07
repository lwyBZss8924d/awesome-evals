# Notes - "Are Performance-Optimization Benchmarks Reliably Measuring Coding Agents?"

**Authors:** Zhi Chen, Zhensu Sun, Yuling Shi, David Lo, Lingxiao Jiang · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2607.01211 · **Type:** paper/benchmark audit · **Found:** true

## Summary
Audit of GSO, SWE-Perf, and SWE-fficiency showing runtime noise and scoring rules distort coding-agent leaderboards.

## Key points
- Worker summary: Audit of GSO, SWE-Perf, and SWE-fficiency showing runtime noise and scoring rules distort coding-agent leaderboards.
- Worker candidate reason: Clears the bar because it replays 740 reference patches across four Google Cloud machine types and quantifies benchmark-validity failures, scoring-rule rank flips, and task saturation hidden by aggregate leaderboard scores.
- Worker evidence: arXiv/HF read reports cross-machine replay-valid reference patches for only 39/102 GSO tasks, 11/140 SWE-Perf tasks, and 411/498 SWE-fficiency tasks; shared GSO/SWE-fficiency submissions disagree on 9/28 pairwise rankings; worst ten SWE-fficiency tasks carry 58.5%-82.8% score weight.
- Source seam: `Hugging Face recent papers / arXiv primary read`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `not recorded`

## Why it matters for agent evals
Clears the bar because it replays 740 reference patches across four Google Cloud machine types and quantifies benchmark-validity failures, scoring-rule rank flips, and task saturation hidden by aggregate leaderboard scores.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.01211
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/are-performance-optimization-benchmarks-reliably-measuring-coding-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face recent papers / arXiv primary read
