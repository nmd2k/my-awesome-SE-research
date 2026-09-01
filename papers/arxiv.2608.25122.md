---
tags: Software Security, Program Static Analysis
url: https://arxiv.org/abs/2608.25122
publication:
date: Aug 25, 2026
dateAdded: 2026-09-01
dateModified:
---
Title: Static Detection of Post-Quantum Cryptographic Algorithms in Stripped Binaries for Digital Forensic Examination and Migration Assurance

TL;DR: Binary static analysis method for identifying ML-KEM and ML-DSA in stripped binaries using number-theoretic-transform constant-table fingerprints.

Brief Summary: Kestrel targets compiled binaries where symbols, library metadata, and runtime behavior are unavailable. It localizes post-quantum algorithm fingerprints with normalization and multiset matching, making cryptographic migration assurance possible directly from shipped binaries.

Key Result: Achieves 128/128 recall with zero false positives across four implementation lineages and all build transformations, including compiler-level obfuscation; discovers 12 uncatalogued programs containing ML-KEM in a production scan of 6,224 binaries.
