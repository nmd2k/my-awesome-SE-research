---
tags: LLMs for SE, Agentic SE
url: https://arxiv.org/abs/2610.20344
publication:
date: Oct 14, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: Doc2Harness: Benchmarking LLMs on Long-Horizon Harness Engineering of Coding Agents

TL;DR: First deterministic benchmark for harness engineering itself, separating harness construction from downstream execution and showing that even frontier models fail nearly half the cases.

Brief Summary: Doc2Harness evaluates the part of agent performance that comes from the harness rather than just the underlying model. In Stage 1, a build model receives an interface-only contract skeleton plus a development document distilled from twelve frontier harnesses and constructs a complete candidate harness inside an isolated container. In Stage 2, that frozen harness is driven by a scripted mock model on 328 end-to-end test cases and scored from model requests, file outputs, process exits, and command output.

Key Result: Across nineteen frontier models with three independent builds each, the best system reaches 53.05% pass rate while the weakest reaches 27.44%. Failures concentrate on cross-cutting functionality split across modules, suggesting harness decomposition remains a major bottleneck.
