---
tags: Software Validation, Neuro-Symbolic
url: https://arxiv.org/abs/2604.12172
publication: 
date: April 14, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: COBALT-TLA: A Neuro-Symbolic Verification Loop for Cross-Chain Bridge Vulnerability Discovery

TL;DR: LLM+TLA+ model checker REPL for blockchain bridge vuln discovery; discovers Optimistic Relay Attack autonomously

Brief Summary: Neuro-symbolic verification loop pairing an LLM with TLC (TLA+ model checker) in an automated REPL: LLM generates bounded TLA+ specifications → TLC acts as semantic oracle → structured error traces injected back into LLM context to drive convergence. Evaluated on 3 cross-chain bridge targets including a faithful model of the Nomad $190M exploit.

Key Result: Reaches verified BUG_FOUND in ≤2 iterations on all targets; autonomously discovers an unprompted Optimistic Relay Attack vulnerability class not in the human-written baseline spec; TLC execution <0.30 seconds.
