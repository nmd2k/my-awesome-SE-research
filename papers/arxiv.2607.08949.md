---
tags: Software Validation, Fuzzing & Dynamic Analysis
url: https://arxiv.org/abs/2607.08949
publication: 
date: Jul 8, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: SeedSmith: LLM-Driven Seed Synthesis for Directed Fuzzing

TL;DR: Agentic LLM pipeline for directed fuzzing: iteratively explores codebase, resolves indirect calls, identifies crash preconditions, synthesizes concrete seeds; 11.51–14.66× crash-time speedups on Magma; enables 16 previously unreachable bugs on ARVO

Brief Summary: Agentic LLM pipeline for directed fuzzing: replicates security analyst workflow starting from sink, iteratively explores codebase, resolves indirect calls, identifies crash preconditions, synthesizes concrete seeds; addresses incomplete static analysis and lack of semantic guidance for crash preconditions.

Key Result: Geometric mean crash-time speedups 11.51× (AFL++) to 14.66× (AFLGo) over default seeds on Magma; enables 16 previously unreachable bugs on ARVO spanning 10 projects with diverse input formats.
