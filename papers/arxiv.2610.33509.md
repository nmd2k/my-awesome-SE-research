---
tags: Software Understanding, Code Review
url: https://arxiv.org/abs/2610.33509
publication:
date: Oct 24, 2026
dateAdded: 2026-11-01
dateModified:
---
Title: Can Agentic Code Review Catch Vulnerabilities Before They Are Merged?

TL;DR: Introduces SecPRBench, a benchmark built from real bug-introducing commits, showing frontier review agents can catch many pre-merge security flaws but often misdiagnose the exact vulnerability mechanism.

Brief Summary: Instead of evaluating on review diffs reconstructed from later fixes, the paper builds a benchmark from validated real-world bug-introducing commits in major systems. It also uses LLM-as-a-judge to align model findings with ground-truth vulnerabilities, making the evaluation closer to how security review agents are used in practice.

Key Result: SecPRBench contains 265 tasks from nine critical systems, including Firefox, V8, and OpenSSL. Across eight frontier models, recall ranges from 32.5% to 78.1%, and 68% of misses still identify the right file while arguing for the wrong flaw mechanism.
