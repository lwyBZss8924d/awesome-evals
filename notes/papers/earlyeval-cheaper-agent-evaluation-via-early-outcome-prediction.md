# Notes - "EarlyEval: Cheaper Agent Evaluation via Early Outcome Prediction"

**Authors:** Yuling Shi, Zhensu Sun, Junsen Dong, Chengcheng Wan, David Lo, Xiaodong Gu · **Published/Updated:** 2026-09-02T00:00:00Z · **URL:** https://arxiv.org/abs/2609.02783 · **Type:** paper · **Found:** true

## Summary
EarlyEval trains calibrated success and failure predictors on intermediate agent trajectories, then stops runs whose outcomes are already confident. Across SWE-bench Verified, TerminalBench, and Toolathlon, the authors report step and token savings while measuring prediction accuracy, resolve-rate distortion, and ranking fidelity under held-out-agent protocols.

## Key points
- Worker summary: EarlyEval predicts success or failure from intermediate agent trajectories and stops confidently decided runs, reducing within-task evaluation cost rather than only distilling the task set.
- Worker candidate reason: The paper evaluates a calibrated, leakage-controlled method across three agent benchmarks, reports accuracy and score-fidelity alongside token and step savings, and publishes a detailed code-only reproduction repository with its missing data artifacts disclosed.
- Worker evidence: The paper uses paired LightGBM success and failure classifiers over behavioral, textual, and optional reference-solution features with calibrated stopping thresholds. Its evaluation covers 7,805 SWE-bench Verified trajectories from 16 base models, 6,757 TerminalBench trajectories from 37 agent configurations, and 7,116 Toolathlon trajectories from 22 base models; the abstract reports eliminating 13–26% of steps and up to 44.1% input and 29.4% output tokens at 89–97% prediction accuracy, with average resolve-rate changes of one to two percentage points. The linked repository publishes active experiment and reporting code but explicitly excludes raw trajectories and generated artifacts.
- Source seam: `new evaluation method paper via arXiv and Hugging Face Daily Papers`
- Target README section: `5 · Evaluation infrastructure (the eval stack: datasets, scorers, online/offline, tracing, CI)`
- Primary category: `cs.CL`

## Why it matters for agent evals
The paper evaluates a calibrated, leakage-controlled method across three agent benchmarks, reports accuracy and score-fidelity alongside token and step savings, and publishes a detailed code-only reproduction repository with its missing data artifacts disclosed.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.02783
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/earlyeval-cheaper-agent-evaluation-via-early-outcome-prediction.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new evaluation method paper via arXiv and Hugging Face Daily Papers
