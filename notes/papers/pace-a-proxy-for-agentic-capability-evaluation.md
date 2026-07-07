# Notes - "PACE: A Proxy for Agentic Capability Evaluation"

**Authors:** Yueqi Song, Lintang Sutawika, Jiarui Liu, Lindia Tjuatja, Jiayi Geng, Yunze Xiao, Daniel Lee, Aditya Bharat Soni, Vincent Lo, Xiang Yue, Graham Neubig · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2607.02032 · **Type:** paper/method · **Found:** true

## Summary
PACE selects cheap non-agentic benchmark instances that predict expensive agentic benchmark scores.

## Key points
- Worker summary: PACE selects cheap non-agentic benchmark instances that predict expensive agentic benchmark scores.
- Worker candidate reason: Clears the bar because it offers an operational cost-reduction method for agent evals, tested across 14 models, four agentic benchmarks, and 19 source benchmarks, reporting under 4% LOOCV MAE, Spearman correlation above 0.80, and around 85% pairwise ranking accuracy at less than 1% of full agent-eval cost.
- Worker evidence: arXiv page states PACE builds PACE-Bench from compact subsets of non-agentic benchmark instances to predict GAIA, SWE-Bench Multimodal, SWE-Bench Verified, and SWT-Bench scores; abstract reports <4% MAE, >0.80 Spearman, ~85% pairwise model-ranking accuracy, and <1% full evaluation cost.
- Source seam: `Hugging Face recent papers / arXiv primary read`
- Target README section: `## 5 · Evaluation infrastructure (the eval stack: datasets, scorers, online/offline, tracing, CI)`
- Primary category: `not recorded`

## Why it matters for agent evals
Clears the bar because it offers an operational cost-reduction method for agent evals, tested across 14 models, four agentic benchmarks, and 19 source benchmarks, reporting under 4% LOOCV MAE, Spearman correlation above 0.80, and around 85% pairwise ranking accuracy at less than 1% of full agent-eval cost.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.02032
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/pace-a-proxy-for-agentic-capability-evaluation.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face recent papers / arXiv primary read
