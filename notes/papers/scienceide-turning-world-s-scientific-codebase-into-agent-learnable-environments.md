# Notes - "ScienceIDE: Turning World's Scientific Codebase into Agent Learnable Environments"

**Authors:** Geng, Hejia, Huang, Zesen, Li, Haoyang, Li, Wenbin, Wu, Koutian, Zhou, Zihan, Pang, Yuanbo, Liu, Weihao, Xu, Zigong, Li, Zhiping, Zhang, Zongzheng, Dong, Chuanfei, Sun, Jiankai, Zheng, Tianzhe, Xie, Fengyu, Ma, Yue, Shi, Yueheng, Xie, Tong, Di, Zonglin, Liu, Xianrong, Gao, Qucheng, Liu, Yimin, Pan, Jiaming, Huang, Sheng, Ma, Xiao-Han, Yuan, Lanqing, Zhu, Zhenlin, Liu, Ziang, Xu, Ziyang, Wang, Junkai, Liang, Kangkai, Xian, Jiayi, Zhao, Zehong, Xu, Liuwei, Xie, Jingxu, Zhang, Peijin, Gao, Qiang, Xing, Chengyi, Zhao, Zhe, Wang, Xi, Xing, Yaopeng, Meng, Xing, Yin, Zhenfei, Wu, Yingcheng, Yang, Ling · **Published/Updated:** 2026-09-16 · **URL:** https://arxiv.org/abs/2609.19134 · **Type:** paper · **Found:** true

## Summary
Scientific-agent evaluation with calibrated numerical checks, witness/baseline task validation, and explicit failure accounting. ⚠️ Disclosed contamination and verification limits constrain score interpretation.

## Key points
- Worker summary: Scientific-agent evaluation with calibrated numerical checks, witness/baseline task validation, and explicit failure accounting. ⚠️ Disclosed contamination and verification limits constrain score interpretation.
- Worker candidate reason: The paper gives a detailed, reusable verifier-design method for scientific software: justify tolerances against meaningful observables, demonstrate both a successful witness and a failing baseline, and distinguish scientific failure from infrastructure failure. Its explicit integrity disclosures also make it valuable for designing and auditing evaluation infrastructure. Inclusion is for the method and qualified research evidence, not a clean-benchmark or established-tool endorsement.
- Worker evidence: Primary text: https://arxiv.org/html/2609.19134v1, sections 2.2–2.4, 3.1, 5 and appendices 8.1 and 9.1. Scientific checks select pointwise tolerances or physical invariants, align outputs by scientific identity, and require expert justification; measured variation is finite calibration evidence rather than a universal tolerance guarantee. Injected-repair admission requires a passing witness, a defective baseline with headroom, and an observable fault corrected by the reference repair. Harness failures remain ungraded, while valid budget exhaustion counts as failure. The paper separates the broad environment/task inventory from an 85-task ScienceIDE-Hard comparison of model–harness systems under a one-hour budget. Section 5 restricts claims to reference-verifiable repair/implementation, leaves external audits and adversarial reward-hacking evaluation outstanding, and does not establish transfer to unseen codebases. Appendix 9.1 discloses historical upstream fetches: 21 confirmed successful fetches, 13 scored solved, and staging-script drift from declared isolation. It describes a corrected live-container allowlist and voiding confirmed fetch trials; this does not establish that the earlier campaign was controlled or contamination-free. Curate the verifier methodology while retaining these disclosures. The linked aitofound/ScienceIDE GitHub repository was retrieved with gh: public, unarchived, created September 11 and pushed September 17, 2026. Its presence is not evidence of independently verified adoption. No benchmark execution or independent result reproduction was performed.
- Source seam: `New eval benchmarks and methods; Hugging Face Daily Papers, 2026-09-17`
- Target README section: `## 7 · Evals & RL environments (verifiers, reward design, difficulty calibration, lifecycle)`
- Primary category: `cs.CL`

## Why it matters for agent evals
The paper gives a detailed, reusable verifier-design method for scientific software: justify tolerances against meaningful observables, demonstrate both a successful witness and a failing baseline, and distinguish scientific failure from infrastructure failure. Its explicit integrity disclosures also make it valuable for designing and auditing evaluation infrastructure. Inclusion is for the method and qualified research evidence, not a clean-benchmark or established-tool endorsement.

## Provenance
- Canonical URL: https://arxiv.org/abs/2609.19134
- ETL source: daily awesome-evals scan worker accepted-candidate note draft.
- Manifest: `manifests/resources/scienceide-turning-world-s-scientific-codebase-into-agent-learnable-environments.json`
- Review status: recorded in the companion resource manifest after supervisor promotion.

## Themes
- New eval benchmarks and methods; Hugging Face Daily Papers, 2026-09-17
