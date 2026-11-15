---
tags: Software Understanding, Code Review
url: https://arxiv.org/abs/2611.02566
publication:
date: Nov 2, 2026
dateAdded: 2026-11-15
dateModified:
---
Title: CR-Bench-v2: Evaluating the Real-World Utility of AI Code Review Agents

TL;DR: Recasts code review as repository-scale defect detection over real pull requests, and shows that even strong review agents still miss most actionable defects.

Brief Summary: CR-Bench-v2 converts SWE-Bench defects into code-review tasks grounded in the pull requests that introduced them, preserving full repository and PR context instead of isolated hunks or reference comments. It evaluates review agents with two task-facing metrics: Known-Defect Detection Rate for whether the real bug is caught, and Usefulness Rate for whether the generated comments are worth a developer's attention.

Key Result: The benchmark contains 584 tasks, including a 174-instance verified subset, yet the best evaluated systems identify only about one-third of known defects. That makes the paper a strong benchmark contribution for code review because it measures concrete defect-finding utility rather than text overlap with historical comments.
