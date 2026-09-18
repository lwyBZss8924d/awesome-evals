# Notes - "ProgramDistill: From Interactive Web Apps to Verifiable Reference-Guided SWE Tasks"

**Authors:** Kim, Jeonghye, Kim, Minseon, Kim, Young Jin, Pereira, Matheus, Côté, Marc-Alexandre, Sordoni, Alessandro, Yuan, Xingdi, Shi, Zhengyan · **Published/Updated:** 2026-09-16 · **URL:** https://arxiv.org/abs/2609.18805 · **Type:** paper · **Found:** true

## Summary
Reference-guided web-app repair with replay-verified behaviors, prerequisite preservation, and controllable restoration depth. ⚠️ Public benchmark release pending.

## Key points
- Worker summary: Reference-guided web-app repair with replay-verified behaviors, prerequisite preservation, and controllable restoration depth. ⚠️ Public benchmark release pending.
- Worker candidate reason: The paper specifies a concrete behavioral verifier and a task-construction validity test: the target must fail after masking while prerequisites still pass, then the gold repair must recover the lineage. This adds reference-guided repair and compositional difficulty to the existing trajectory and state-based evaluation resources. Curate as a research method, with the unreleased benchmark caveat.
- Worker evidence: Primary text: https://arxiv.org/html/2609.18805v1, sections 2.2–2.4, 3.1–3.2 and 5. The verifier resets application/browser state and replays recorded actions without an LLM judge, checking the expected behavioral signals. Task validation requires a buildable masked application, preserved prerequisites, target failure, and recovery under the gold patch. Repair agents see the working reference through a browser, while reference source, grading traces and gold patches are hidden. Binary scoring requires the complete lineage; chain scoring credits recovered prefixes. The paper reports 1,975 verified behaviors across 26 applications and 4,063 constructed tasks; its nine-model partial-repair comparison uses ProgramDistill-300, not the entire generated inventory. Section 5 limits the study to self-contained web apps, structured browser observations rather than screenshot inputs, and a single construction model. Scores do not establish visual fidelity or external-service robustness. Abstract footnote 1 says a public benchmark release is still being prepared. Retrieved arXiv metadata identifies the September 16, 2026 paper by Jeonghye Kim and colleagues. These are author-reported methods and results, not independently reproduced measurements.
- Source seam: `New eval benchmarks and methods; Hugging Face Daily Papers, 2026-09-17`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.SE`

## Why it matters for agent evals
The paper specifies a concrete behavioral verifier and a task-construction validity test: the target must fail after masking while prerequisites still pass, then the gold repair must recover the lineage. This adds reference-guided repair and compositional difficulty to the existing trajectory and state-based evaluation resources. Curate as a research method, with the unreleased benchmark caveat.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.18805
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/programdistill-from-interactive-web-apps-to-verifiable-reference-guided-swe-tasks.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- New eval benchmarks and methods; Hugging Face Daily Papers, 2026-09-17
