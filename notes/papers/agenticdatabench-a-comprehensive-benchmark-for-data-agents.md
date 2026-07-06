# Notes - "AgenticDataBench: A Comprehensive Benchmark for Data Agents"

**Authors:** Zhaoyan Sun, Shan Zhong, Daizhou Wen, Jiaxing Han, Guoliang Li, Ying Yan, Peng Zhang, Yu Su, Xiang Qi, Baolin Sun, Chengyuan Yang, Tao Fang, Huaiyu Ruan · **Published/Updated:** 2026-07-02T03:18:59Z · **URL:** https://arxiv.org/abs/2607.01647 · **Type:** paper/benchmark · **Found:** true

## Summary
Data science aims to derive actionable insights from heterogeneous raw data, unlocking the value of the massive amounts of data generated in modern society. Automating this process is essential to reducing labor-intensive efforts for data scientists and enabling scalable data-driven applications. Recently, large language model (LLM)-based data agents have emerged as a promising solution to automate data science workflows. However, the field lacks comprehensive benchmarks to rigorously evaluate these agents across diverse scenarios with fine-grained granularity. To address this gap, we propose AgenticDataBench, a comprehensive benchmark featuring realistic tasks spanning diverse domains with fine-grained ground-truth labels. This enables evaluations to capture the diversity and complexity of data science workflows and the detailed performance of agents. First, to cover diverse domains, we collect real datasets and tasks from 15 vertical domains, including 5 real-world B2B use cases from a leading fintech company. Second, to remove redundancy in real-world tasks and generate high-quality tasks for domains lacking real data, we introduce data science skills, recurring data-centric operational patterns, and quantify benchmark coverage by the number of skills included. Representative skills are extracted from large-scale task solutions on Stack Overflow using skill-aligned hierarchical clustering. Third, for real-world business tasks, we select task-solution pairs that maximize diversity in skill composition, ensuring broad coverage of practical scenarios. Fourth, to generate realistic tasks for devise domains without real tasks, we propose a systematic LLM-based task generation approach to create workflows and tasks based on these skills. Finally, we evaluate state-of-the-art data agents using our annotated benchmark and open-sourced testbed, providing detailed skill-level insights.

## Key points
- Worker summary: Comprehensive benchmark for data agents with realistic multi-domain data-science tasks, fine-grained labels, and an open testbed.
- Worker candidate reason: Clears the bar because it evaluates data agents at task and skill granularity across 15 domains, mixes real business tasks with skill-based generated tasks, and ships an open repository/dataset surface for reproducible agent benchmarking.
- Worker evidence: {'dataset': 'https://huggingface.co/datasets/shawnzzzh/AgenticDataBench', 'fetched': 'hf-info-2607.01647.txt', 'github_metadata': 'gh-AgenticDataBench-AgenticDataBench.json', 'github_repo': 'https://github.com/AgenticDataBench/AgenticDataBench', 'primary_arxiv': 'arxiv-2607.01647.xml', 'project_page': 'https://agenticdatabench.github.io'}
- Source seam: `huggingface-daily-papers + arxiv-primary + github-metadata`
- Target README section: `9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.DB`

## Why it matters for agent evals
Clears the bar because it evaluates data agents at task and skill granularity across 15 domains, mixes real business tasks with skill-based generated tasks, and ships an open repository/dataset surface for reproducible agent benchmarking.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.01647
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/agenticdatabench-a-comprehensive-benchmark-for-data-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- huggingface-daily-papers + arxiv-primary + github-metadata
