---
tags: Software Validation, Fuzzing & Dynamic Analysis
url: https://arxiv.org/abs/2604.20801
publication: 
date: Apr 22, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Synthesizing Multi-Agent Harnesses for Vulnerability Discovery

TL;DR: Typed-graph DSL synthesizes multi-agent harnesses; discovers 10 zero-days in Chrome 35M LOC including 2 Critical sandbox-escape CVEs

Brief Summary: Synthesizes multi-agent fuzzing harnesses via a typed graph DSL covering agent roles, prompts, tools, communication topology, and coordination protocol; feedback-driven outer loop reads runtime signals to rewrite failing harness components; evaluated on Google Chrome (35M LOC C/C++).

Key Result: 10 previously unknown zero-days discovered in Chrome including 2 Critical sandbox-escape CVEs (CVE-2026-5280, CVE-2026-6297) confirmed by Google VRP; 84.3% on TerminalBench-2.
