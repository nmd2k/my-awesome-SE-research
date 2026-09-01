---
tags: Software Validation, Fuzzing & Dynamic Analysis
url: https://arxiv.org/abs/2608.17738
publication: ASE 2026
date: Aug 18, 2026
dateAdded: 2026-09-01
dateModified:
---
Title: SpecTrum: Specification-Guided Differential Fuzzing for Ethereum Consensus Clients

TL;DR: Mechanizes Ethereum consensus validity conditions as explicit premises, then uses premise coverage to generate differential tests that uncover client divergences missed by official tests.

Brief Summary: SpecTrum introduces Consensus-SpecTec, which makes validity conditions explicit instead of leaving them implicit in the reference implementation. It measures under-executed premises, extracts constraints from them, and generates tests that probe missing boundaries across independent consensus clients.

Key Result: Raises premise coverage from 46.3% to 91.1% and finds 27 cross-client divergence cases across five major Ethereum clients, 22 of which cannot be found without the inserted premises. Accepted at ASE 2026.
