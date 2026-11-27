# Information-Preserving Aggregation under Finite Beam Search

This repository hosts the preprint:

> **Information-Preserving Aggregation under Finite Beam Search: Two Validation Studies of Purchase-Aware Tree Distillation**  
> Naoyuki Tomita — Independent Researcher, Tokyo, Japan

**Keywords:** recommender systems · information retrieval · candidate generation · purchase prediction · finite beam search · tree distillation

[View the paper (PDF)](https://github.com/natomi1203/purchase-aware-tree-distillation/blob/main/paper.pdf)

## What the paper studies

Candidate generation must keep the search space manageable before a recommender ranks products. This paper studies a tree-distillation aggregation rule that preserves descendant probability mass, and evaluates it under finite beam-search budgets using two independent public-data validation studies.

The paper records different results across the two settings. It does **not** claim that the aggregation rule is universally beneficial or that the observed path-survival measure establishes a causal mechanism. Instead, it reports the results, the preregistered comparisons, and the limitations needed to test the finite-beam reachability hypothesis in future controlled studies.

## Scope and reproducibility

The studies use public RetailRocket and YOOCHOOSE data. This repository intentionally contains only the paper. It does not include raw behavioral data, row-level candidates, traces, internal paths, credentials, client data, or proprietary code.

The current PDF is eight pages and has SHA-256:

```
03bbd913521a7a7790f38e658ad40a82424fadc5cdec9db113daed31166149fb
```

## Citation

```bibtex
@article{tomita2026information,
  title={Information-Preserving Aggregation under Finite Beam Search: Two Validation Studies of Purchase-Aware Tree Distillation},
  author={Tomita, Naoyuki},
  year={2026},
  note={Preprint}
}
```

## Rights

Copyright © 2026 Naoyuki Tomita. All rights reserved.
