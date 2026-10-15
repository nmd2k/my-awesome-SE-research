---
tags: Maintenance & Evolution, Refactoring & Migration
url: https://arxiv.org/abs/2610.20027
publication: Findings of EMNLP 2026
date: Oct 14, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: LintEval: Benchmarking LLMs on Linter-Guided File Refactoring

TL;DR: Large multilingual benchmark for linter-guided file refactoring that measures whether a model can remove warnings without breaking behavior or introducing new ones.

Brief Summary: LintEval targets a common maintenance workflow that benchmark suites usually ignore: editing existing files to reduce lint alerts while preserving functionality. It contains 13,061 correct programs and 171,662 lint alerts across C++, Python, and Java, and evaluates models on alert reduction, functionality preservation, avoidance of new alerts, and edit minimality. The paper also studies how supervision format affects linter-guided refactoring ability.

Key Result: The best commercial models reach 90.4% Reduction@P but only 67.1%-68.3% Pass@1, exposing a strong trade-off between cleanup aggressiveness and correctness preservation. Refactoring-oriented supervised fine-tuning lifts Qwen2.5-Coder-7B from 24.7% to 76.0% Reduction@P.
