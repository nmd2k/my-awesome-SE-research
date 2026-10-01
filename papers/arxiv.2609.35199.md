---
tags: Empirical SE & Benchmarks, Empirical Studies
url: https://arxiv.org/abs/2609.35199
publication:
date: Sep 28, 2026
dateAdded: 2026-10-01
dateModified:
---
Title: Trajectory-Level Security Debt in LLM Coding Agents

TL;DR: Proposes a trajectory-aware security metric for coding agents, showing that passing tests can still coincide with substantial evolving scanner risk during agent search.

Brief Summary: The paper introduces the Security Debt Line Integral (SDLI), which accumulates static-analysis findings as an agent improves task progress instead of judging only the final artifact. It applies the metric to large sets of SWE-bench and ProgramBench outputs plus public coding-agent trajectories to study how security findings evolve during search.

Key Result: Scanner agreement on CWE classes is limited and same-task runs can diverge substantially in measured debt, highlighting that tested correctness and security posture can drift apart throughout an agent trajectory.
