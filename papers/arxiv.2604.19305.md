---
tags: Maintenance & Evolution, Program Repair
url: https://arxiv.org/abs/2604.19305
publication: 
date: Apr 21, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: DebugRepair: Enhancing LLM-Based Automated Program Repair via Self-Directed Debugging

TL;DR: Self-directed debugging APR: simulated instrumentation + runtime traces; +51.3% avg over vanilla LLM, 295 Defects4J bugs fixed

Brief Summary: Enhances LLM APR via self-directed debugging: test semantic purification removes noise from failing tests → simulated instrumentation inserts targeted debug statements → hierarchically iterative conversation-driven repair loop exploits collected runtime-state evidence (inner: patch refinement; outer: re-instrumentation).

Key Result: GPT-3.5: 224 Defects4J bugs (+26.2% over SOTA); DeepSeek-V3: 295 bugs (59 more than 2nd best); +51.3% avg over vanilla across 5 LLMs.
