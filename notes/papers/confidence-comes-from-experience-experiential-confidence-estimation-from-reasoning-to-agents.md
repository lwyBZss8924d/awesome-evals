# Notes - "Confidence Comes from Experience: Experiential Confidence Estimation from Reasoning to Agents"

**Authors:** Zhang, Caiqi, Zhu, Xiaochen, Li, Chengzu, Chen, Yulong, Kumaran, Dharshan, Collier, Nigel · **Published/Updated:** 2026-09-15 · **URL:** https://arxiv.org/abs/2609.17708 · **Type:** paper · **Found:** true

## Summary
Tests confidence in completed agent runs using independently graded past episodes, with task-disjoint evaluation and silent-failure analysis. ⚠️ Requires outcome labels and recalibration as the actor changes.

## Key points
- Worker summary: Tests confidence in completed agent runs using independently graded past episodes, with task-disjoint evaluation and silent-failure analysis. ⚠️ Requires outcome labels and recalibration as the actor changes.
- Worker candidate reason: A useful evaluation-method paper for agents that finish with plausible-looking but incorrect results. It separates confidence discrimination, calibration and selective prediction; compares supervision-matched baselines; and tests whether apparent gains disappear when outcome labels or failure visibility are misleading.
- Worker evidence: Primary text: https://arxiv.org/html/2609.17708v1, sections 3–7 and appendices B–C. XConf retrieves the actor's past graded episodes using task embeddings and stated confidence, calculates a historical hit rate, and combines it with a separate reflection on retrieved evidence. The original reflection is recorded before grading; outcome-informed lessons are confined to previously graded bank entries. Section 4 uses five-fold task-disjoint rotation and supervision-matched label-consuming baselines; it reports AUROC, ECE and AURC with bootstrap uncertainty, with chronological replay separately described in appendix H. Section 5.3 evaluates completed trajectories on ScienceWorld, AppWorld and SWE-bench Verified against single-rollout baselines. ALFWorld and WebShop are excluded from the main table because their visible failure signals saturate introspective baselines; appendix B discusses why that weakens them as confidence testbeds. Section 6 reports that self-generated outcome labels fail where an independent grading signal retains value. Section 7 acknowledges a self-consistency advantage on some votable factual recall tasks and leaves integration with self-evolving memory untested. Past episodes may become stale as the actor changes. One answer generation still involves retrieval and additional confidence/reflection work; it is not a claim of one total API call. Retrieved arXiv metadata dates the paper to September 15, 2026. No production deployment or independent reproduction is claimed.
- Source seam: `New eval benchmarks and methods; Hugging Face Daily Papers, 2026-09-17`
- Target README section: `## 9 · Agent-specific evaluation (trajectories, tool use, multi-turn, world state, multi-agent, localization)`
- Primary category: `cs.CL`

## Why it matters for agent evals
A useful evaluation-method paper for agents that finish with plausible-looking but incorrect results. It separates confidence discrimination, calibration and selective prediction; compares supervision-matched baselines; and tests whether apparent gains disappear when outcome labels or failure visibility are misleading.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.17708
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/confidence-comes-from-experience-experiential-confidence-estimation-from-reasoning-to-agents.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- New eval benchmarks and methods; Hugging Face Daily Papers, 2026-09-17
