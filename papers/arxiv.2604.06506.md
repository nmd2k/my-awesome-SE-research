---
tags: Software Validation, Neuro-Symbolic
url: https://arxiv.org/abs/2604.06506
publication: 
date: 
dateAdded: 2026-08-24
dateModified:
---
Title: Guiding Symbolic Execution with Static Analysis and LLMs for Vulnerability Discovery

TL;DR: Auto harness generation via static analysis + LLM-orchestrated symbolic execution; 379 new vulns in 6.8M LOC

Brief Summary: SAILOR: fully automated symbolic execution pipeline for vulnerability discovery — static analysis identifies targets, LLM iteratively synthesizes harnesses (drivers/stubs/assertions) with compiler+SE feedback, symbolic execution detects bugs, replay validates.

Key Result: 379 previously unknown memory-safety vulns (421 confirmed crashes) in 10 C/C++ projects, 6.8M LOC.
