# Notes - "The Double Measurement Confound in Agent Benchmarks: De-Scaffolding, Ground-Truth Scoring, and Reliability Beyond the Mean"

**Authors:** Yonghong Zhang, Shadi Motaali, Vu Phong Dinh, Avin Piroutiniya, Jorge E. López de Vergara, Luis de Pedro, Ricardo Correia, Isabel M. Parra, and Yong Xie · **Published/Updated:** 2026-09-06 · **URL:** https://arxiv.org/abs/2609.09218 · **Type:** paper · **Found:** true

## Summary
A retrospective benchmark audit studies the joint confounding from scaffold-owned execution and shape-based scoring, then applies model-owned execution and seeded ground-truth grading to inspect mean and tail reliability. The full intervention is limited to a stylized extraction benchmark.

## Key points
- Worker summary: Audits scaffold-owned decisions and shape-based scoring jointly, then measures seeded outcome correctness and tail reliability. ⚠️ Preprint; full intervention is confined to a stylized extraction benchmark.
- Worker candidate reason: The paper supplies a paired scaffold/scorer intervention, fabricated-output probes, ground-truth grading, and explicit validity cards. Its retrospective self-audit explains why fixing only a scorer or only a scaffold can still conceal the intended capability, with clear limits on generalization.
- Worker evidence: Verified canonical arXiv metadata and read the version-pinned primary HTML at https://arxiv.org/html/2609.09218v1, dated 2026-09-06. Sections 3–5 describe ComtradeBench as seeded, mock-API extraction with pagination, deduplication, summary-row filtering and retry decisions. A paired scaffold/scorer intervention contrasts scaffold-owned execution with model-owned decisions and shape scoring with regenerated ground-truth F1. The introduction reports that correct and fabricated record sets both received 0.987 under the original scorer; Appendix C.2 documents canned submissions through that scorer. The paper reports mean, worst-case, CVaR and threshold reliability rather than only a mean ranking, and publishes benchmark validity cards. Section 6 limits the full ownership intervention to one stylized domain and the main spectrum to five tasks across ten seeds; a larger re-emission task is excluded by a solvability audit. Exploratory quota experiments and point-in-time model endpoints are disclosed. These are author-reported experiments inspected in the paper, not independently replayed results or proof of cross-domain validity.
- Source seam: `new evaluation benchmarks and measurement research`
- Target README section: `## 6 · Benchmark vs. eval (and benchmark integrity: contamination, saturation, label errors, leaderboard gaming)`
- Primary category: `cs.SE`

## Why it matters for agent evals
The paper supplies a paired scaffold/scorer intervention, fabricated-output probes, ground-truth grading, and explicit validity cards. Its retrospective self-audit explains why fixing only a scorer or only a scaffold can still conceal the intended capability, with clear limits on generalization.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.09218
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/the-double-measurement-confound-in-agent-benchmarks-de-scaffolding-ground-truth-scoring-and.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- new evaluation benchmarks and measurement research

## Primary-source inspection

- https://arxiv.org/abs/2609.09218
- https://arxiv.org/html/2609.09218v1

Evidence type: primary paper text and arXiv metadata inspection.

Locations inspected: Section 3: The Double Measurement Confound; Section 4: Measurement Protocol; Section 5: Experiments; Section 6: Limitations; Appendix C.2: Judge Probe.

Limits: Preprint; Retrospective self-audit; Single-domain full intervention; Small seeded suite; Experiments not replayed by worker.
