---
tags: Maintenance & Evolution, Refactoring & Migration
url: https://arxiv.org/abs/2611.05457
publication:
date: Nov 3, 2026
dateAdded: 2026-11-15
dateModified:
---
Title: Hybrid LLM-Deterministic Pipelines for Enterprise-Scale Code Migration at Bloomberg

TL;DR: Reports a large industrial migration effort showing that bounded LLM transformations work best when embedded inside deterministic classification, validation, and rollout pipelines.

Brief Summary: The paper describes Bloomberg's Automated Uplift system for fleet-wide code migration, covering both Python packaging and C++ build-system modernization across thousands of repositories. Its main engineering idea is to keep archetyping, prompt rendering, validation, and rollout deterministic while reserving the LLM for the narrow transformation step, with runtime telemetry used to enrich migration context where source code alone is insufficient.

Key Result: Across roughly 8,600 candidate repositories, the system generated 2,333 pull requests and led to 729 successful migrations. The most useful lesson is operational rather than model-centric: generation quality mattered less than validation depth, repository uniformity, and the downstream human cost of reviewing and deploying the changes.
