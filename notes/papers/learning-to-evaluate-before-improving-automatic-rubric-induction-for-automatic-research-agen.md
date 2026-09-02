# Notes - "Learning to Evaluate Before Improving: Automatic Rubric Induction for Automatic Research Agents"

**Authors:** Xuehai Wang, Haowei Qin, Tongxin Liu, Junkai Li, Buqiang Xu, Jintian Zhang, Yijun Chen, Zirui Xue, and Shumin Deng · **Published/Updated:** 2026-08-31T00:00:00+00:00 · **URL:** https://arxiv.org/abs/2608.31076 · **Type:** paper/method/code · **Found:** true

## Summary
Autonomous scientific research agents are increasingly applied to end-to-end scientific workflows, including literature review, data analysis, experimentation, and report generation. However, open-ended research tasks often do not clearly specify the analyses, methods, and success criteria required to complete the task. As a result, agents may miss important analyses, use inappropriate methods, or draw conclusions that are insufficiently supported by evidence. To address the problem, we present AutoSciRub, an evaluation-first framework that induces a task-specific executable rubric before research execution, and uses it to guide execution, criterion-level verification as well as iterative revision. AutoSciRub decomposes an underspecified instruction into atomic scientific goals, grounds them in relevant literature and task-visible data, and synthesizes specific, actionable, and verifiable criteria. The resulting rubric makes implicit experimental and evidential requirements explicit, providing guidance for experiments and analyses. During revision, rubric-guided verification identifies unmet criteria and enables targeted refinement of the research report and its supporting artifacts. On ResearchClawBench, AutoSciRub consistently improves all tested configurations, with an average gain of 2.08 points across three backbone LLMs under the fixed Codex harness and 2.95 points across three agent harnesses using a fixed DeepSeek-V4-Flash backbone. On a randomly sampled 20-task subset of AstaBench E2E Discovery, AutoSciRub further achieves an average improvement of 16.8 points across three agent harnesses, while maintaining or increasing the number of successfully completed tasks. These results demonstrate that evaluation-first guidance provides an effective and generalizable control mechanism for autonomous scientific research (Code: https://github.com/zjunlp/AutoSciRub).

## Key points
- Worker summary: AutoSciRub induces a literature- and data-grounded executable rubric before an open-ended research run, then verifies and revises criterion by criterion.
- Worker candidate reason: The method makes underspecified scientific success criteria explicit before execution and backs the idea with fixed-model, fixed-harness, cross-harness, and ablation comparisons rather than a single self-reported showcase.
- Worker evidence: Across all 40 ResearchClawBench tasks, AutoSciRub improved three backbones under a fixed Codex harness by 2.38, 1.87, and 1.99 points and three harnesses under a fixed DeepSeek-V4-Flash backbone by 2.14, 3.11, and 3.60. On a random 20-task AstaBench subset it added 19.36, 12.61, and 18.38 points; an ablation rose from 17.25 without rubric guidance to 20.36 with the full method. The paper also reports scientific-core coverage declining from 3.35 to 3.07, so task-specific rubrics improved execution but did not reliably correct off-target scientific framing.
- Source seam: `Hugging Face Daily Papers, canonical arXiv paper, and benchmark repository`
- Target README section: `## 8 · LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `not recorded`

## Why it matters for agent evals
The method makes underspecified scientific success criteria explicit before execution and backs the idea with fixed-model, fixed-harness, cross-harness, and ablation comparisons rather than a single self-reported showcase.

## Provenance
- Canonical URL: https://arxiv.org/abs/2608.31076
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/learning-to-evaluate-before-improving-automatic-rubric-induction-for-automatic-research-agen.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers, canonical arXiv paper, and benchmark repository
