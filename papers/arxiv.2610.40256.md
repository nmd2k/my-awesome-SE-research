---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2610.40256
publication:
date: Oct 29, 2026
dateAdded: 2026-11-01
dateModified:
---
Title: When Requirements Interact: Scaling Long-Horizon Coding via Interdependent Specifications

TL;DR: Builds interdependent-spec coding tasks instead of checklist-like ones, yielding a 4,670-task training corpus and a 100-task benchmark that better separates long-horizon coding agents.

Brief Summary: The paper introduces CodeSpecWeave, a synthesis pipeline that mines real developer requirement seeds, generates coupled specifications together with executable tests, and then audits solver trajectories to repair false positives and false negatives in the verifier. The resulting tasks emphasize interacting constraints such as compatibility, state consistency, and error handling rather than isolated edits.

Key Result: CodeSpecWeave produces 4,670 training tasks across 2,865 repositories and CodeSpecWeave-Bench with 100 tasks and 1,044 specifications. Reinforcement learning on the corpus substantially improves DeepSWE-v1.1 over strong existing training baselines.
