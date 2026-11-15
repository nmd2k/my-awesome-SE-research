---
tags: Maintenance & Evolution, Refactoring & Migration
url: https://arxiv.org/abs/2611.08269
publication:
date: Nov 5, 2026
dateAdded: 2026-11-15
dateModified:
---
Title: Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations

TL;DR: Shows that migration repairs can easily pass typical release checks while still being semantically wrong, and that targeted edge-case inputs dramatically reduce these silent failures.

Brief Summary: This preregistered study examines 73 runtime and API migration tasks across CPython, Node.js, and SQLite, focusing on repairs that execute cleanly but subtly change behavior. Rather than measuring only whether models can produce a compiling patch, the paper studies the adequacy of the release gate itself, comparing typical-input assertions, release-note-derived edge inputs, blind LLM-written tests, and self-tests under withheld contracts.

Key Result: Typical-input gates accept wrong repairs at a rate of 0.410 over the full repair space, while adding a single release-note edge input cuts that to 0.065 and replicates on unseen clusters. The paper is valuable for this repository because it isolates a concrete failure mode in migration and repair workflows: passing the obvious tests is not enough.
