---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2611.01484
publication:
date: Nov 1, 2026
dateAdded: 2026-11-15
dateModified:
---
Title: CrossSWE: Benchmarking Cross-Repository Joint Development for Coding Agents

TL;DR: Introduces a benchmark where agents must modify multiple repositories together, exposing cross-repository consistency as a major unresolved weakness.

Brief Summary: CrossSWE targets a gap in current SWE evaluation: many real tasks require coordinated updates across producers, consumers, libraries, or services rather than changes inside one repository. The authors curate 171 real-world tasks spanning 165 repositories, 20 technical domains, and 13 languages, and verify that partial fixes in only one repository are insufficient by exhaustively testing mixed patched and unpatched states.

Key Result: Even the strongest reported model reaches only 58.48% Pass@1, and 44.2% of failures come from cross-repository inconsistencies. The benchmark is notable because it raises task difficulty through genuine inter-repository coordination rather than simply enlarging a single codebase.
