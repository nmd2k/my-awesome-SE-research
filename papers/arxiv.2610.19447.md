---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2610.19447
publication: USENIX Security 2026
date: Oct 14, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: BenchChecker: Assessing the Credibility of Bug-Fixing Benchmarks for LLMs

TL;DR: A forensics-based contamination checker for bug-fixing benchmarks that shows many automated program-repair scores are inflated by training leakage.

Brief Summary: BenchChecker aims to evaluate APR benchmarks more credibly without requiring access to private training corpora. It first probes whether a repository likely appeared in model training, then checks whether the target patch itself likely persisted in public history that the model could have memorized. The method only needs textual model outputs plus public repository history, so it can be applied to both open and closed models.

Key Result: On six APR benchmarks, BenchChecker achieves AUC values around 0.9 for contamination detection. Filtering contaminated samples from SWE-bench Verified and Multi-SWE-bench reduces the reported resolution rates of most models by more than 20% on medium-difficulty tasks.
