---
tags: Maintenance & Evolution, Refactoring & Migration
url: https://arxiv.org/abs/2608.30300
publication:
date: Aug 31, 2026
dateAdded: 2026-09-01
dateModified:
---
Title: Update from Hell: Can Coding Agents Survive Hidden Breakage in Dependency Upgrades?

TL;DR: Introduces DepBench, a repository-level benchmark for dependency-upgrade repair, and shows that current coding agents solve only about half of real upgrade breakages.

Brief Summary: The benchmark mines dependency-bot pull requests, decomposes manifest, repair, and hidden test changes, and keeps only tasks that satisfy a four-state oracle proving the failure is genuinely upgrade-induced. It covers five ecosystems and focuses on repository-wide source adaptation rather than just version bumps.

Key Result: DepBench contains 203 oracle-clean tasks across npm/yarn, Maven, Go, Cargo, and Python. The strongest completed configuration solves 104/203 tasks (51.2%), with incomplete repository-wide migration emerging as the dominant failure mode.
