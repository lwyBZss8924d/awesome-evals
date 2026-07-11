# Notes - "LLM-as-a-Verifier: A General-Purpose Verification Framework"

**Authors:** Jacky Kwok, Shulu Li, Pranav Atreya, Yuejiang Liu, Yixing Jiang, Chelsea Finn, Marco Pavone, Ion Stoica, Azalia Mirhoseini · **Published/Updated:** 2026-07-06T17:59:35Z · **URL:** https://arxiv.org/abs/2607.05391 · **Type:** paper/method · **Found:** true

## Summary
A probabilistic trajectory-verification method that uses scoring-token distributions, repeated evaluation, criterion decomposition, and a pivot tournament to produce fine-grained feedback across coding, robotics, and medical agent tasks.

## Key points
- Worker summary: Turns scoring-token probability distributions into continuous trajectory scores, then scales verification through repeated judgments, criterion decomposition, and a budget-aware pivot tournament.
- Worker candidate reason: It clears the bar with a concrete verifier algorithm, controlled ablations over three verification-scaling axes, and cross-domain agent results rather than a generic judge prompt; it directly addresses tie rates, position bias, trajectory ranking, and dense feedback for RL.
- Worker evidence: alphaXiv discovery was canonicalized to arXiv and the full HF/arXiv paper was read: the discrete judge baseline has a 27% Terminal-Bench tie rate; the method reports 86.5% on Terminal-Bench V2, 78.2% on SWE-Bench Verified, 87.4% trajectory-preference accuracy on RoboRewardBench, and 73.3% on MedAgentBench, with criteria-ensemble accuracy rising to 78.3%.
- Source seam: `alphaxiv-hot-feed+hugging-face-papers+arxiv-primary`
- Target README section: `8 · LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `cs.AI`

## Why it matters for agent evals
It clears the bar with a concrete verifier algorithm, controlled ablations over three verification-scaling axes, and cross-domain agent results rather than a generic judge prompt; it directly addresses tie rates, position bias, trajectory ranking, and dense feedback for RL.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.05391
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/llm-as-a-verifier-a-general-purpose-verification-framework.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- alphaxiv-hot-feed+hugging-face-papers+arxiv-primary
