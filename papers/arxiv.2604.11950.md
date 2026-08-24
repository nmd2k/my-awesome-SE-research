---
tags: Software Security, Vulnerability Detection
url: https://arxiv.org/abs/2604.11950
publication: 
date: 
dateAdded: 2026-08-24
dateModified:
---
Title: AnyPoC: Universal Proof-of-Concept Test Generation for Scalable LLM-Based Bug Detection

TL;DR: Universal multi-agent PoC generation for bug detection; 122 new bugs confirmed in Firefox/Chromium/LLVM/OpenSSL/Redis

Brief Summary: Universal multi-agent PoC generation for validating LLM-generated bug reports at scale: Analyzer agent fact-checks the report (static), Generator agent synthesizes + executes PoC (dynamic), Checker agent re-executes and scrutinizes to prevent hallucination/reward hacking. Applied to 12 critical systems including Firefox, Chromium, LLVM, OpenSSL, SQLite, FFmpeg, Redis.

Key Result: 122 new bugs detected; 105 confirmed by developers, 86 fixed, 45 PoCs adopted as regression tests.
