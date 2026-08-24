---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2607.02684
publication: 
date: Jul 2, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Can Coding Agents Implement Missed Compiler Optimizations? Evaluating LLM Agents on LLVM Peephole Optimizations

TL;DR: Evaluation framework for coding agents on compiler optimization task: fixing missed peephole optimizations in LLVM's InstCombine pass; tasks derived from 21 resolved LLVM issues + 19 merged PRs with only pre-fix context provided; assesses patches for correctness and profitability.

Brief Summary: Evaluation framework for coding agents on compiler optimization task: fixing missed peephole optimizations in LLVM's InstCombine pass; tasks derived from 21 resolved LLVM issues + 19 merged PRs with only pre-fix context provided; assesses patches for correctness and profitability.

Key Result: Tension between correctness and profitability; no agent matches human developers on both dimensions; dominant failure modes: overly narrow transformations and misuse of LLVM-specific mechanisms.
