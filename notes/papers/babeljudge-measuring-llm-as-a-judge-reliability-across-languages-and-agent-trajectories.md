# Notes - "BabelJudge: Measuring LLM-as-a-Judge Reliability Across Languages and Agent Trajectories"

**Authors:** Shreyas KC · **Published/Updated:** 2026-06-21T04:35:43Z · **URL:** https://arxiv.org/abs/2606.22329 · **Type:** paper/benchmark · **Found:** true

## Summary
LLM-as-a-judge has become the dominant approach to scalable evaluation in NLP pipelines, yet judges themselves carry systematic biases that raw accuracy hides: they favor responses placed in slot A (position bias), they prefer longer responses regardless of quality (verbosity bias), and their reliability degrades sharply in lower-resource languages. We introduce BabelJudge, an open-source benchmark and reliability audit framework that measures all four failure modes -- position bias, verbosity bias, order inconsistency, and cross-lingual degradation -- on any judge model, without requiring human preference labels. The key insight is gold-labelling by degradation: starting from a high-quality reference response and applying a controlled perturbation yields a pairwise item whose gold label is known by construction, eliminating annotation cost. We evaluate Qwen2.5-7B-Instruct-4bit across English, Hindi, Arabic, and Swahili and find that our composite bias-penalised reliability score drops from 0.714 in Hindi to 0.550 in Swahili, a gap that raw accuracy (0.835 vs. 0.660) understates. Swahili order consistency collapses to 0.480, meaning judge verdicts are near-random under slot-order swaps -- a failure mode invisible to accuracy alone. We further extend the framework to agentic evaluation via nine trajectory-level perturbations (argument corruption, tool swaps, hallucinated calls, missing steps) and three new metrics: tool accuracy, hallucination detection rate, and trajectory-length bias. BabelJudge is released as a Python package supporting 11 judge backends. Code: https://github.com/Shreyaskc/BabelJudge

## Key points
- Worker summary: Reliability-audit benchmark for judge position, verbosity, order, multilingual degradation, and agent-trajectory perturbation failures.
- Worker candidate reason: It contributes an open reliability audit framework and agent-trajectory perturbation tests rather than another generic judge prompt; useful for calibrating LLM-as-judge claims.
- Worker evidence: arXiv API summary reports bias-penalized scores, order consistency collapse, trajectory perturbations, and package release.
- Source seam: `LLM-as-judge reliability`
- Target README section: `## 8 · LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `cs.CL`

## Why it matters for agent evals
It contributes an open reliability audit framework and agent-trajectory perturbation tests rather than another generic judge prompt; useful for calibrating LLM-as-judge claims.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.22329
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/babeljudge-measuring-llm-as-a-judge-reliability-across-languages-and-agent-trajectories.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- LLM-as-judge reliability
