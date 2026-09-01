---
tags: Software Validation, Fuzzing & Dynamic Analysis
url: https://arxiv.org/abs/2608.30648
publication:
date: Aug 31, 2026
dateAdded: 2026-09-01
dateModified:
---
Title: Lie to Me: Finding Bugs in ZK DSL Toolchains with Adversarial Witness Injection

TL;DR: Tests zero-knowledge DSL toolchains by splicing witnesses from different executions, exposing soundness bugs that valid-execution testing cannot see.

Brief Summary: Liezz generates deterministic ZK DSL programs, runs them on two public inputs, and combines the input witness from one run with the output witness from another. A correct toolchain must reject the injected witness; acceptance proves missing constraints in the generated proof system.

Key Result: Supports Circom, Corset, Gnark, and Noir; finds 13 bugs, including 7 with soundness impact. Under the same testing budget, a valid-execution baseline misses every soundness failure that adversarial witness injection reveals.
