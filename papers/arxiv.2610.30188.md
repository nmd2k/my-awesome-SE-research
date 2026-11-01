---
tags: LLMs for SE, Agentic SE
url: https://arxiv.org/abs/2610.30188
publication:
date: Oct 20, 2026
dateAdded: 2026-11-01
dateModified:
---
Title: Agentic Verified Optimization of Real-World Software

TL;DR: Turns performance optimization into a proof-carrying agent task: port legacy code into Lean, synthesize faster rewrites, and require machine-checked equivalence proofs.

Brief Summary: The paper frames optimization as an agentic verification problem where the current implementation is the specification and every speedup must come with a correctness proof. Its Aqueduct framework migrates C, C++, Go, and Rust code into executable Lean, validates the ports by differential testing, and then searches for proved rewrites at both function and application scope.

Key Result: On 189 Verina reference implementations, agents produce faster proved rewrites for 156. Across 17 migrated real-world applications, 92 proved rewrites improve 47 of 51 application scenarios.
