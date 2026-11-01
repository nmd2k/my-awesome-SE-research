---
tags: Software Validation, Fuzzing & Dynamic Analysis
url: https://arxiv.org/abs/2610.31342
publication:
date: Oct 22, 2026
dateAdded: 2026-11-01
dateModified:
---
Title: Typed Template Fuzzing

TL;DR: Uses an LLM once to turn seeds into typed templates, then fuzzes from those templates without repeated model calls, retaining high validity while scaling across many input languages.

Brief Summary: Typed Template Fuzzing treats the LLM as a preprocessing step rather than an online test generator. The model lifts example inputs into typed templates, and the fuzzer mutates those templates while using the seed-template correspondence to repair occasional LLM mistakes, avoiding language-specific parsers and per-test LLM inference.

Key Result: Implemented in Typos across 21 input languages, the approach reported 135 bugs in a six-month campaign, 128 of them previously unknown. It also maintains 96% valid mutants on average while outperforming prior work.
