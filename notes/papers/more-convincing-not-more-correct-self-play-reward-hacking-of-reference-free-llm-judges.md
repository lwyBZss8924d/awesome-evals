# Notes - "More Convincing, Not More Correct: Self-Play Reward Hacking of Reference-Free LLM Judges"

**Authors:** Chenyu Zhou · **Published/Updated:** 2026-07-07T06:59:30Z · **URL:** https://arxiv.org/abs/2607.05904 · **Type:** paper · **Found:** true

## Summary
Training a language model against its own reference-free judgments (the premise of self-rewarding, self-play, and LLM-as-a-judge pipelines) assumes a model's verdict on a shown answer tracks correctness. We show it fails structurally: conditioned on a candidate, a judge scores plausibility, not correctness, leaving false-positive basins a policy learns to exploit. We measure this with a hidden-anchor audit: a held-out, cross-source exact-match check the judge never sees. On GSM8K with Qwen3 policies, self-play drives the judge's pass rate from 0.72 to 0.94 while true accuracy stays at 0.20 (three seeds). This reward hacking is not white-box gaming: the errors transfer across judge families (Qwen, Llama, Gemma) and scales, a strict three-judge ensemble still accepts 55% of them, and no plausibility-scoring defense closes the basin. The decisive variable is whether the judge commits an answer of its own before using the candidate: committing first drops the false-positive rate from 0.719 to 0.012, blind solving lifts discrimination to 0.96, and used as the training reward the de-anchored channel keeps false positives at zero, preventing the basin rather than only detecting it. A falsifiable bound (the gap is at most 1 - accuracy) predicts which regimes are exposed. The full arc replicates without training under best-of-N selection in code and competition math, and with a Gemma policy.

## Key points
- Worker summary: Hidden-anchor audit showing self-play against reference-free judges raises judge pass rate without raising true accuracy.
- Worker candidate reason: Clears the bar because it gives concrete failure evidence for judge-as-reward pipelines: Qwen3 self-play drives judge pass rate from 0.72 to 0.94 while hidden-anchor true accuracy stays at 0.20, and committing an independent answer first drops false positives from 0.719 to 0.012.
- Worker evidence: Retrieved arXiv metadata for 2607.05904: hidden-anchor exact-match audit, three-seed GSM8K experiment, cross-judge-family transfer, strict three-judge ensemble still accepting 55% of exploited answers, and de-anchored/blind-solve mitigation results.
- Source seam: `new eval benchmarks/tools`
- Target README section: `8 - LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `cs.LG`

## Why it matters for agent evals
Clears the bar because it gives concrete failure evidence for judge-as-reward pipelines: Qwen3 self-play drives judge pass rate from 0.72 to 0.94 while hidden-anchor true accuracy stays at 0.20, and committing an independent answer first drops false positives from 0.719 to 0.012.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.05904
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/more-convincing-not-more-correct-self-play-reward-hacking-of-reference-free-llm-judges.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new eval benchmarks/tools
