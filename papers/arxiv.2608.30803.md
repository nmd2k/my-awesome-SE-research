---
tags: Software Validation, Neuro-Symbolic
url: https://arxiv.org/abs/2608.30803
publication:
date: Aug 31, 2026
dateAdded: 2026-09-01
dateModified:
---
Title: Schwarz: Solver-Aware Agentic Program Verification

TL;DR: Makes failed SMT-backed verification local and repairable through program-point snapshots, checked helper lemmas, and theory-aware solver policies.

Brief Summary: Instead of asking an LLM to rewrite whole specifications after a timeout or verifier failure, Schwarz turns proof failure into obligation-local repair tasks. The harness exposes the exact local proof boundary, lets the agent propose missing lemmas, and guides it toward solver-friendly formulations for arithmetic, memory, quantified, and floating-point obligations.

Key Result: On 475 prior agentic-verification benchmarks, Schwarz solves 95.2% of tasks; on 1,000 SV-COMP 2026 ReachSafety tasks averaging 1,427 LOC, it solves 91.5% versus 60.1% for CPAchecker.
