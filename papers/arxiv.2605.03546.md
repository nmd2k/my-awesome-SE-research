---
tags: Empirical SE & Benchmarks, Benchmarks & Datasets
url: https://arxiv.org/abs/2605.03546
publication: 
date: May 5, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: ProgramBench: Can Language Models Rebuild Programs From Scratch?

TL;DR: Agents rebuild 200 software projects from scratch via behavioral testing; none fully resolve any task; best model (Opus 4.7) passes 95% tests on only 3% of tasks, revealing fundamental limitations in architectural decision-making

Brief Summary: Benchmark for full software project generation from scratch, requiring agents to architect and implement codebases matching reference executable behavior via behavioral test generation from fuzzing; 200 tasks spanning CLI tools to FFmpeg/SQLite/PHP.

Key Result: Agents cannot fully resolve any task; best model (Claude Opus 4.7) passes 95% of tests on only 3% of tasks; models favor monolithic single-file implementations diverging from human code.
