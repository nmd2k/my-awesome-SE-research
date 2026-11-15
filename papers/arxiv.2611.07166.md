---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2611.07166
publication:
date: Nov 4, 2026
dateAdded: 2026-11-15
dateModified:
---
Title: Multi-step SWE: Can Coding Agents Keep Building on Their Own Code Over Long Horizons?

TL;DR: Benchmarks whether coding agents can keep extending their own earlier code over long sequences of substantial requests, and finds that whole-task success remains rare.

Brief Summary: Multi-step SWE models a common production workflow in which an agent must iteratively build, extend, migrate, and optimize the same codebase across 5 to 15 dependent steps. Each step is grounded in an external source of truth and graded with field-standard tools, so the benchmark stresses not just local patching but error accumulation, design carryover, and long-horizon maintenance of prior behavior.

Key Result: Across 69 tasks and nine frontier models, the best model solves only 18.5% of tasks in a single rollout, and 38 tasks are unsolved by every model tested. This makes the benchmark a high-signal addition for evaluating long-horizon agent reliability beyond one-shot issue resolution.
