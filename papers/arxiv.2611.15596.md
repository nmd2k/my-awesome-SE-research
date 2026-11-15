---
tags: Software Validation, Neuro-Symbolic
url: https://arxiv.org/abs/2611.15596
publication:
date: Nov 11, 2026
dateAdded: 2026-11-15
dateModified:
---
Title: Bug Finding With Agentic Symbolic Execution

TL;DR: Uses an agent to synthesize contracts and environment models so symbolic execution can scale to large database-backed Python web applications and find bugs that direct inspection misses.

Brief Summary: The paper couples an AI coding agent with CrossHair, using the agent to write preconditions and postconditions, build symbolic database models, and validate discovered counterexamples with concrete tests. This turns symbolic execution from a manually prepared analysis into a largely automated neuro-symbolic pipeline that can run against real repositories with heavy framework and database dependencies.

Key Result: Agentic environment synthesis raises executable coverage from 4.5% to 81% across 5,406 contracted functions in 11 large Python web applications. The full pipeline finds 1,050 reproduced bugs, including 221 found by CrossHair and 312 missed by a same-model code-inspection baseline, showing that symbolic execution adds complementary value rather than just duplicating LLM inspection.
