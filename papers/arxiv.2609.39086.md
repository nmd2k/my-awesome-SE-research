---
tags: Maintenance & Evolution, Program Repair
url: https://arxiv.org/abs/2609.39086
publication:
date: Sep 30, 2026
dateAdded: 2026-10-01
dateModified:
---
Title: Trustworthy Runtime Error Healing in Real-World Repositories: A Benchmark and Guardrail

TL;DR: Pushes runtime healing from toy programs to repository-scale crashes with HealBench and adds a safety guardrail that checks whether healing code mutates protected behavior.

Brief Summary: The work studies post-crash state repair inside live processes, where LLM-generated healing code must use runtime state and repository context but also avoid unsafe side effects. It introduces HealBench with 265 runtime errors from 18 repositories and HealGuard, which restricts healing code to an analyzable subset and checks state flow to protected operations.

Key Result: The best evaluated setup resumes execution on 38.11% of cases and passes the target test on 28.68%, while HealGuard flags 17.4% of otherwise passing heals as potentially unsafe and catches all unsafe cases in a controlled evaluation.
