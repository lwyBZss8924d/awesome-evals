# Notes - "Can LLM-as-a-Judge Reliably Verify Rubrics in Agentic Scenarios?"

**Authors:** Yangda Peng, Yunjia Qi, Hao Peng, Haotian Xia, Guanzhong He, Xintong Shi, Richeng Xuan, Songyuanyi Lu, Yixian Liu, Zhichao Hu, Yuhong Liu, Lei Hou, Bin Xu, Juanzi Li · **Published/Updated:** 2026-06-29T07:57:23Z · **URL:** https://arxiv.org/abs/2606.29920v1 · **Type:** paper/dataset/code · **Found:** true

## Summary
Rubric-based scoring has become a widely used paradigm in model evaluation, typically with LLM-as-a-Judge (LaaJ) for rubric scoring. However, the reliability of LaaJ for rubric scoring remains underexplored. This concern is especially pronounced in agentic scenarios, where long, complex outputs further challenge reliable scoring. To address this, we conduct a systematic meta-evaluation of LaaJ reliability for rubric verification. We introduce RuVerBench, the first benchmark for assessing LaaJ reliability in rubric verification for agentic scenarios. RuVerBench covers two prevalent agentic domains, deep research and agentic coding, with 2,458 instances, each containing a model-generated output, a rubric, and a human-annotated label indicating whether the output satisfies the rubric. Using RuVerBench, we evaluate numerous frontier LLMs and find that even the most advanced models achieve strong performance but still exhibit substantial noise. We further analyze the impact of key LaaJ strategies, including prompt design, batching, and majority voting, on rubric verification. We find that weaker models are more sensitive to prompt variations, batched verification presents a trade-off between accuracy and efficiency, and majority voting yields effective but diminishing returns. We have released our dataset and code to facilitate future research: https://github.com/THU-KEG/RuVerBench.

## Key points
- Worker summary: RuVerBench meta-evaluates LLM-as-judge rubric verification on deep-research and agentic-coding outputs.
- Worker candidate reason: It tests the reliability of rubric verification in agentic settings rather than assuming judge scores are trustworthy, which is central to this repo’s verifier guidance.
- Worker evidence: arXiv metadata published 2026-06-29 in cs.CL | authors: Yangda Peng, Yunjia Qi, Hao Peng, Haotian Xia, Guanzhong He et al. | abstract evidence: Rubric-based scoring has become a widely used paradigm in model evaluation, typically with LLM-as-a-Judge (LaaJ) for rubric scoring. | abstract names RuVerBench with 2,458 human-labeled rubric-verification instances and dataset/code at github.com/THU-KEG/RuVerBench. | URL reachability used the arXiv API alternate link with explicit v1 because the versionless page returned 404 during vetting.
- Source seam: `arxiv_recent_llm_judge_metaeval; github_dataset_code_claim`
- Target README section: `8 · LLM-as-judge & verifiers (alignment, biases, verifiable vs judgeable)`
- Primary category: `cs.CL`

## Why it matters for agent evals
It tests the reliability of rubric verification in agentic settings rather than assuming judge scores are trustworthy, which is central to this repo’s verifier guidance.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.29920v1
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/can-llm-as-a-judge-reliably-verify-rubrics-in-agentic-scenarios.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arxiv_recent_llm_judge_metaeval; github_dataset_code_claim
