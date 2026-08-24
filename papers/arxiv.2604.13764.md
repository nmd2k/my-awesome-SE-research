---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2604.13764
publication: 
date: April 15, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: RealVuln: Benchmarking Rule-Based, General-Purpose LLM, and Security-Specialized Scanners on Real-World Code

TL;DR: Benchmark of 15 scanners on 796-entry real Python vuln dataset; LLMs outperform rule-based SAST 3× under F3

Brief Summary: First open-source benchmark comparing 15 scanners (3 rule-based SAST, 10 general-purpose LLMs, 2 security-specialized) on 26 intentionally vulnerable Python repos (educational + CTF), 796 hand-labeled entries (676 vulns + 120 FP traps); F3 scoring (recall-weighted 9×).

Key Result: Security-specialized Kolega.Dev (73.0 F3) > best LLM Claude Sonnet 4.6 (51.7 F3) ≈ 3× best rule-based Semgrep (17.7 F3); LLMs beat SAST by large margin on recall.
