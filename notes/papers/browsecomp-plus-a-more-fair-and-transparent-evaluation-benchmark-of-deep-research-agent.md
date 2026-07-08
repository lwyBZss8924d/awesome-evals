# Notes - "BrowseComp-Plus: A More Fair and Transparent Evaluation Benchmark of Deep-Research Agent"

**Authors:** Zijian Chen, Xueguang Ma, Shengyao Zhuang, Ping Nie, Kai Zou, Andrew Liu, Joshua Green, Kshama Patel, Ruoxi Meng, Mingyi Su, Sahel Sharifymoghaddam, Yanxi Li, Haoran Hong, Xinyu Shi, Xuye Liu, Nandan Thakur, Crystina Zhang, Luyu Gao, Wenhu Chen, Jimmy Lin · **Published/Updated:** 2025-08-08 · **URL:** https://arxiv.org/abs/2508.06600 · **Type:** paper/benchmark/dataset/code · **Found:** true

## Summary
Benchmark derived from BrowseComp that uses a fixed curated document corpus, human-verified supporting documents, and challenging negatives to make deep-research agent and retriever evaluation more fair, transparent, and reproducible.

## Key points
- Worker summary: Deep-research benchmark derived from BrowseComp that replaces live opaque search with a fixed curated corpus and retriever-level judgments.
- Worker candidate reason: Clears the bar because it directly addresses benchmark fairness and reproducibility for browsing/deep-research agents with a fixed corpus, human-verified supporting documents, qrels, run-file format, retrieval-only metrics, leaderboard, and reproducible evaluation scripts.
- Worker evidence: Retrieved HF paper metadata for 2508.06600, arXiv abstract, texttron/BrowseComp-Plus README, and GitHub repo metadata. Evidence: fixed roughly 100K-document corpus; human-verified supporting documents and challenging negatives; evaluates deep-research agents and retrievers separately; provides dataset, project page, leaderboard, qrels, custom retriever docs, run evaluation script, trajectory downloads; GitHub search found texttron/BrowseComp-Plus with 311 stars and pushed 2026-05-28.
- Source seam: `hf papers + GitHub benchmark/tool discovery + arXiv`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `cs.IR`

## Why it matters for agent evals
Clears the bar because it directly addresses benchmark fairness and reproducibility for browsing/deep-research agents with a fixed corpus, human-verified supporting documents, qrels, run-file format, retrieval-only metrics, leaderboard, and reproducible evaluation scripts.

## Provenance
- Canonical URL: https://arxiv.org/abs/2508.06600
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/browsecomp-plus-a-more-fair-and-transparent-evaluation-benchmark-of-deep-research-agent.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- hf papers + GitHub benchmark/tool discovery + arXiv
