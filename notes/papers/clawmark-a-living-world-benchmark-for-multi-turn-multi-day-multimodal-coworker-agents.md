# Notes - "ClawMark: A Living-World Benchmark for Multi-Turn, Multi-Day, Multimodal Coworker Agents"

**Authors:** Fanqing Meng, Lingxiao Du, Zijian Wu, Guanzheng Chen, Xiangyan Liu, Jiaqi Liao, Chonghe Jiang, Zhenglin Wan, Jiawei Gu, Pengfei Zhou, Rui Huang, Ziqi Zhao, Shengyuan Ding, Ailing Yu, Bo Peng, Bowei Xia, Hao Sun, Haotian Liang, Ji Xie, Jiajun Chen, Jiajun Song, Liu Yang, Ming Xu, Qionglin Qiu, Runhao Fu, Shengfang Zhai, Shijian Wang, Tengfei Ma, Tianyi Wu, Weiyang Jin, Yan Wang, Yang Dai, Yao Lai, Youwei Shu, Yue Liu, Yunzhuo Hao, Yuwei Niu, Jinkai Huang, Jiayuan Zhuo, Zhennan Shen, Linyu Wu, Hannah Yao, Charles Chen, Cihang Xie, Yuyin Zhou, Jiaheng Zhang, Zeyu Zheng, Mengkang Hu, Michael Qizhe Shieh · **Published/Updated:** 2026-04-26T16:05:02Z · **URL:** https://arxiv.org/abs/2604.23781v2 · **Type:** paper/benchmark · **Found:** true

## Summary
Language-model agents are increasingly used as persistent coworkers that assist users across multiple working days. During such workflows, the surrounding environment may change independently of the agent: new emails arrive, calendar entries shift, knowledge-base records are updated, and evidence appears across images, scanned PDFs, audio, video, and spreadsheets. Existing benchmarks do not adequately evaluate this setting because they typically run within a single static episode and remain largely text-centric. We introduce \bench{}, a benchmark for coworker agents built around multi-turn multi-day tasks, a stateful sandboxed service environment whose state evolves between turns, and rule-based verification. The current release contains 100 tasks across 13 professional scenarios, executed against five stateful sandboxed services (filesystem, email, calendar, knowledge base, spreadsheet) and scored by 1537 deterministic Python checkers over post-execution service state; no LLM-as-judge is invoked during scoring. We benchmark seven frontier agent systems. The strongest model reaches 75.8 weighted score, but the best strict Task Success is only 20.0\%, indicating that partial progress is common while complete end-to-end workflow completion remains rare. Turn-level analysis shows that performance drops after the first exogenous environment update, highlighting adaptation to changing state as a key open challenge. We release the benchmark, evaluation harness, and construction pipeline to support reproducible coworker-agent evaluation.

## Key points
- Worker summary: Living-world coworker-agent benchmark with multi-turn, multi-day tasks, exogenous environment updates, multimodal evidence, and deterministic Python checkers.
- Worker candidate reason: Clears the bar because it tests a capability missing from static single-episode agent benchmarks: persistent coworker workflows where environment state changes between turns; the release includes 100 tasks, 13 scenarios, five stateful services, and 1,537 deterministic post-state checkers without LLM-as-judge scoring.
- Worker evidence: arXiv API metadata in discovery-arxiv.json plus hf-read-2604.23781.md and jina-read-clawmark.md report 100 tasks across 13 professional scenarios, five stateful services, 1,537 deterministic Python checkers, no LLM-as-judge during scoring, and strict task success of only 20.0% for the strongest system.
- Source seam: `Hugging Face Daily Papers discovery; arXiv API + Hugging Face paper read + Jina read`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.CV`

## Why it matters for agent evals
Clears the bar because it tests a capability missing from static single-episode agent benchmarks: persistent coworker workflows where environment state changes between turns; the release includes 100 tasks, 13 scenarios, five stateful services, and 1,537 deterministic post-state checkers without LLM-as-judge scoring.

## Provenance
- Canonical URL: https://arxiv.org/abs/2604.23781v2
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/clawmark-a-living-world-benchmark-for-multi-turn-multi-day-multimodal-coworker-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers discovery; arXiv API + Hugging Face paper read + Jina read
