---
tags: Software Validation, Neuro-Symbolic
url: https://arxiv.org/abs/2605.22058
publication: 
date: May 22, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Finding Missing Input Validation in TEEs via LLM-Assisted Symbolic Execution

TL;DR: LLM-assisted symbolic execution for TEE validation vulnerability detection without hardware setup; 100% precision, 92.3% recall on 26 vulnerabilities at $0.05 per analysis via mock environment generation

Brief Summary: LLM-assisted symbolic execution for detecting missing input validation in TEE applications without hardware setup; AST-based analysis extracts vulnerable slices, LLM generates KLEE-compatible mock environments and security oracles, KLEE explores paths for concrete inputs violating assertions.

Key Result: 100% precision, 92.3% recall on 26 vulnerabilities (11 real-world + 15 synthetic); average cost $0.05 per analysis; eliminates need for complex TEE runtime setups and specialized hardware.
