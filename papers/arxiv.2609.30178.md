---
tags: Software Validation, Program Testing
url: https://arxiv.org/abs/2609.30178
publication:
date: Sep 24, 2026
dateAdded: 2026-10-01
dateModified:
---
Title: NEUROTESTGEN: Neuro-Symbolic Guided Test Generation with Large Language Models

TL;DR: Combines symbolic path constraints with LLM-driven test synthesis to generate realistic tests that hit targeted lines and branches more reliably than prior LLM-only approaches.

Brief Summary: NEUROTESTGEN uses symbolic execution to derive path-specific constraints for a target coverage goal, converts them into a guidance specification for the LLM, and iteratively validates and repairs generated tests. For object-heavy constraints that SMT solving handles poorly, it lets the LLM infer plausible structure instead of relying on pure symbolic reasoning.

Key Result: On a widely used benchmark, the approach consistently outperforms the prior state of the art across several model families, including Llama, GPT-4o Mini, and Claude variants.
