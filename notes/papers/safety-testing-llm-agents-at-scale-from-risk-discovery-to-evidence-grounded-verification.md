# Notes - "Safety Testing LLM Agents at Scale: From Risk Discovery to Evidence-Grounded Verification"

**Authors:** Yunhao Feng, Ruixiao Lin, Ming Wen, Qinqin He, Yanming Guo, Yifan Ding et al. · **Published/Updated:** unknown · **URL:** https://arxiv.org/abs/2607.01793 · **Type:** paper/benchmark/tool · **Found:** true

## Summary
Vera/Vera-Bench turns agent safety risks into executable sandbox tests with deterministic evidence-grounded verifiers.

## Key points
- Worker summary: Vera/Vera-Bench turns agent safety risks into executable sandbox tests with deterministic evidence-grounded verifiers.
- Worker candidate reason: Clears the bar because it releases a concrete framework and Vera-Bench: 1,600 executable safety cases across 124 risk categories, three execution settings, and four production agent frameworks, with outcomes judged from environment state and tool-call evidence rather than model self-report.
- Worker evidence: HF read and arXiv page confirm v2 on 2026-07-04, 1,600 safety cases, 124 risk categories, OpenClaw/Hermes/Codex/Claude Code evaluation, 93.9% average multi-channel attack success, and code at https://github.com/Yunhao-Feng/Vera; GitHub README confirms evaluation_bench, deterministic verify.py, MCP gateway logs, and 12-container sandboxes.
- Source seam: `Hugging Face Daily Papers / arXiv primary read / GitHub repo`
- Target README section: `## 10 · Safety / adversarial evaluation (prompt injection, jailbreaks, action-authorization, benchmark auditing)`
- Primary category: `not recorded`

## Why it matters for agent evals
Clears the bar because it releases a concrete framework and Vera-Bench: 1,600 executable safety cases across 124 risk categories, three execution settings, and four production agent frameworks, with outcomes judged from environment state and tool-call evidence rather than model self-report.

## Provenance
- Canonical URL: https://arxiv.org/abs/2607.01793
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/safety-testing-llm-agents-at-scale-from-risk-discovery-to-evidence-grounded-verification.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- Hugging Face Daily Papers / arXiv primary read / GitHub repo
