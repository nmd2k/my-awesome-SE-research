---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2609.32601
publication:
date: Sep 26, 2026
dateAdded: 2026-10-01
dateModified:
---
Title: VulContextBench: A Benchmark for Security Context Retrieval in Coding Agents

TL;DR: Measures whether coding agents retrieve and cite the code evidence behind vulnerability judgments, exposing a large gap between what agents inspect and what they justify.

Brief Summary: Rather than scoring only the final vulnerability verdict, VulContextBench annotates vulnerability-introducing commits with gold evidence at file, block, and line granularity. The dataset covers 111 commits from 83 repositories and explicitly audits labels to avoid inheriting version-history noise from prior benchmarks.

Key Result: Evaluated models usually open most of the relevant context while exploring but cite far less in their final evidence reports, with block-level reported context trailing viewed context by 37 to 73 percentage points.
