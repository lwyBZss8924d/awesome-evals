# Notes - "Monitoring production agent lifecycle with AWS DevOps Agent and AgentCore Evaluations"

**Authors:** Meghana Ashok, Samaneh Aminikhanghahi, Suren Gunturu, and Vidya Sagar Ravipati (AWS) · **Published/Updated:** 2026-09-11 · **URL:** https://aws.amazon.com/blogs/machine-learning/monitoring-production-agent-lifecycle-with-aws-devops-agent-and-agentcore-evaluations · **Type:** engineering blog / worked example · **Found:** true

## Summary
Worked airline-agent monitoring example connects sampled quality scores and trace drilldowns to infrastructure diagnosis; a missing model-invocation permission explains blank responses. ⚠️ Vendor demonstration; judges require validation.

## Key points
- Worker summary: Worked airline-agent monitoring example connects sampled quality scores and trace drilldowns to infrastructure diagnosis; a missing model-invocation permission explains blank responses. ⚠️ Vendor demonstration; judges require validation.
- Worker candidate reason: Provides a concrete airline-agent architecture, evaluation levels, sampled versus on-demand workflows, and a traced permission failure. It connects quality evaluation to operational diagnosis and explicitly documents the latency and coverage limits of asynchronous sampling.
- Worker evidence: Read the AWS author page published 2026-09-11 via Exa on 2026-09-12. The article describes an airline reservation system with supervisor/specialist agents, a dashboard joining session, trace, and span evidence, background sampling for quality scoring, and on-demand evaluation for selected sessions. Its demonstrated incident follows a user request through AgentCore runtime to a denied Bedrock call: a missing bedrock:InvokeModel permission causes blank agent output. Quality scoring and infrastructure investigation therefore answer different questions. The article explicitly warns that asynchronous sampled evaluation can score a harmful response only after the user receives it. Treat its diagrams, evaluator definitions, and incident walkthrough as implementation evidence; example percentages and estimated debugging times are not controlled production measurements. Judge calibration and independent outcome validation are not established by this vendor demonstration.
- Source seam: `eval insights inside general agent-building posts; company engineering blogs`
- Target README section: `4 · Observability & the output / eval space (the surfaces you can grade)`
- Primary category: `not recorded`

## Why it matters for agent evals
Provides a concrete airline-agent architecture, evaluation levels, sampled versus on-demand workflows, and a traced permission failure. It connects quality evaluation to operational diagnosis and explicitly documents the latency and coverage limits of asynchronous sampling.

## Provenance
- Canonical URL: https://aws.amazon.com/blogs/machine-learning/monitoring-production-agent-lifecycle-with-aws-devops-agent-and-agentcore-evaluations
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/monitoring-production-agent-lifecycle-with-aws-devops-agent-and-agentcore-evaluations.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- eval insights inside general agent-building posts; company engineering blogs
