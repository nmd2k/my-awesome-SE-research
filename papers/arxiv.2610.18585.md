---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2610.18585
publication:
date: Oct 13, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: X.js: A Live Benchmark for Node.js Taint-Style Vulnerabilities

TL;DR: Live, continuously extensible benchmark for Node.js taint-style vulnerabilities with validated exploits, traces, and mirrored dependencies for reproducible long-term evaluation.

Brief Summary: X.js addresses the staleness of existing JavaScript vulnerability datasets by continuously collecting real advisories and attaching executable security artifacts to them. The benchmark covers code injection, command injection, prototype pollution, and path traversal, and stores source/sink locations, validated exploits, execution traces, and patched versions when available. Mirrored dependencies and dedicated validation infrastructure make the benchmark maintainable as the ecosystem changes.

Key Result: From 1,738 advisories gathered through mid-2026, X.js produces 1,159 validated exploits spanning 965 packages. The accompanying analysis also shows that median vulnerable package size grew from about 250 LoC in 2021-2022 to 6,100 LoC in 2026, highlighting a shift toward larger and more complex targets.
