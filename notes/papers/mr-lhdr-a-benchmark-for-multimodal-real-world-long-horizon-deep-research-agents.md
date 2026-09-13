# Notes - "Mr.LHDR: A Benchmark for Multimodal Real-World Long-Horizon Deep Research Agents"

**Authors:** Minghao Guo et al. · **Published/Updated:** 2026-09-10 · **URL:** https://arxiv.org/abs/2609.11318 · **Type:** paper / benchmark · **Found:** true

## Summary
Grades final answers and prerequisite-consistent intermediate conclusions in multimodal research responses. ⚠️ Response-level grading does not verify actual tool-use traces.

## Key points
- Worker summary: Grades final answers and prerequisite-consistent intermediate conclusions in multimodal research responses. ⚠️ Response-level grading does not verify actual tool-use traces.
- Worker candidate reason: Adds an explicit dependency graph to intermediate-conclusion grading, distinguishing a correct final answer from a fully supported submitted response. The paper defines the metrics and reports controlled visual-evidence ablations; released evaluation documentation makes the scoring procedure inspectable.
- Worker evidence: Primary arXiv v1 submitted September 10, 2026, and its HTML paper describe 102 questions with hidden, annotated dependency graphs. OA measures final-answer correctness; SA requires the answer and all checklist conclusions; DACS withholds downstream credit if prerequisite conclusions are unsatisfied. The paper explicitly says these metrics grade conclusions stated in submitted responses, without observing latent reasoning or tool-use traces. GitHub API resolved the paper's Mr-LHDR-eval link to https://github.com/minghaoguo20/Mr-LHDR; its README documents separate run, LLM-judge, and score stages and links the public Hugging Face dataset. The main-results judge differs from the quick-start judge example, so comparable results require pinning the judge configuration. Retrieved repository metadata showed an unarchived Apache-2.0 repository with zero stars and zero forks; this proposal is for the research paper, with no demonstrated external software adoption. Source inspection only; benchmark results were not independently reproduced.
- Source seam: `new eval benchmarks/tools`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
Adds an explicit dependency graph to intermediate-conclusion grading, distinguishing a correct final answer from a fully supported submitted response. The paper defines the metrics and reports controlled visual-evidence ablations; released evaluation documentation makes the scoring procedure inspectable.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.11318
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/mr-lhdr-a-benchmark-for-multimodal-real-world-long-horizon-deep-research-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools

## Retrieved primary sources

- https://arxiv.org/abs/2609.11318
- https://arxiv.org/html/2609.11318v1
- https://github.com/minghaoguo20/Mr-LHDR
