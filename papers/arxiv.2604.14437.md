---
tags: Software Validation, Program Testing
url: https://arxiv.org/abs/2604.14437
publication: 
date: April 15, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: LLMs taking shortcuts in test generation: A study with SAP HANA and LevelDB

TL;DR: LLMs rely on memorization (LevelDB) vs. fail on unseen proprietary SAP HANA codebase; mutation score gap exposed

Brief Summary: Investigates whether LLMs genuinely reason or take shortcuts in automated test generation by contrasting performance on open-source LevelDB (in training data) vs. proprietary SAP HANA (guaranteed out-of-distribution); uses mutation score + iterative compiler-feedback repair to assess reasoning quality.

Key Result: Exposes significant gap between memorization-aided (LevelDB) and genuine reasoning (SAP HANA) test quality; reveals LLMs rely on shallow heuristics when training data is absent.
