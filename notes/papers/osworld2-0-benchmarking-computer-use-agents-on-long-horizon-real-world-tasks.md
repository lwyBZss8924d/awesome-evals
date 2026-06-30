# Notes - "OSWorld2.0: Benchmarking Computer Use Agents on Long-Horizon Real-World Tasks"

**Authors:** Mengqi Yuan, Zilong Zhou, Xinzhuang Xiong, Weiming Wu, Jiayang Sun, Jiamin Song, Kaiqian Cui, Bowen Wang, Haoyuan Wu, Yitong Li, Dunjie Lu, Haikong Lu, Qi Zhen, Xinyuan Wang, Jiaqi Deng, Yuhao Yang, Cheng Chen, Boyuan Zheng, Alex Su, Xiao Yu, Hao Zou, Saaket Agashe, Xing Han Lu, Manpreet Kaur, Zhengyang Qi, Vincent Sunn Chen, Frederic Sala, Dayiheng Liu, Junyang Lin, Zhou Yu, Yu Su, Siva Reddy, Xin Eric Wang, Peng Qi, Tianbao Xie, Tao Yu · **Published/Updated:** 2026-06-28T17:59:17Z · **URL:** https://arxiv.org/abs/2606.29537 · **Type:** paper/benchmark · **Found:** true

## Summary
Existing computer-use benchmarks fail to capture the realism, complexity, and long-horizon demands of real-world computer use, limiting their ability to reveal the limitations of frontier agents. We introduce OSWorld 2.0, a benchmark of 108 long-horizon computer-use workflows across everyday and professional tasks, designed to capture complex and challenging real-world phenomena. Each task represents a realistic end-to-end workflow that takes human users a median of about 1.6 hours to complete and requires an average of 318 tool calls with Claude Opus 4.7 using maximum thinking, compared with about 30 in OSWorld 1.0. OSWorld 2.0 targets challenge phenomena that are common in real workflows yet underrepresented in prior benchmarks, spanning interaction-design challenges such as streaming interaction and dynamic environments, as well as agent-pattern challenges such as cross-source reasoning, implicit-state inference, and visual-spatial precision. Tasks are grounded in authentic input artifacts and cross-referenced against realistic stateful user profile data, and include separate safety reports auditing safety-sensitive execution. Under our primary binary-completion metric at 500 steps, Claude Opus 4.8 with maximum thinking and batched tool calls scores best but still completes only 20.6% of tasks at a 54.8% partial score; GPT-5.5 is far more token-efficient yet plateaus near 13%. These results show that current agents are still far from professional-level computer use: rather than stumbling on basic GUI control or coding, they lose track of constraints, miss information that arrives mid-task, guess rather than ask the user, and skip verification, struggling most when a task hinges on hidden state they must recover.

## Key points
- Worker summary: Long-horizon computer-use benchmark with realistic workflows, stateful profile data, partial scoring, and safety reporting.
- Worker candidate reason: It extends OSWorld-style CUA evaluation toward hour-scale workflows and exposes bottlenecks that short desktop tasks and outcome-only scores can miss.
- Worker evidence: arXiv metadata published 2026-06-28 in cs.AI | authors: Mengqi Yuan, Zilong Zhou, Xinzhuang Xiong, Weiming Wu, Jiayang Sun et al. | abstract evidence: Existing computer-use benchmarks fail to capture the realism, complexity, and long-horizon demands of real-world computer use, limiting their ability to reveal the limitations of frontier agents. | reports 108 workflows, median human completion around 1.6 hours, and 318 average tool calls in the primary agent setting.
- Source seam: `arxiv_recent_agent_benchmarks; exa_agent_benchmark_search`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.AI`

## Why it matters for agent evals
It extends OSWorld-style CUA evaluation toward hour-scale workflows and exposes bottlenecks that short desktop tasks and outcome-only scores can miss.

## Provenance
- Canonical URL: https://arxiv.org/abs/2606.29537
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/osworld2-0-benchmarking-computer-use-agents-on-long-horizon-real-world-tasks.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- arxiv_recent_agent_benchmarks; exa_agent_benchmark_search
