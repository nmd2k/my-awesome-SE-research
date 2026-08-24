---
tags: LLMs for SE, Code LM
url: https://arxiv.org/abs/2607.13921
publication: 
date: Jul 15, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Generative Compilation: On-the-Fly Compiler Feedback as AI Generates Code

TL;DR: On-the-fly compiler feedback during LLM decoding via sealor transformation that converts partial programs into complete ones; Lean-verified properties; reduces non-compiling outputs and improves functional correctness on Rust repository tasks vs post-generation feedback

Brief Summary: On-the-fly compiler feedback during LLM generation via sealor: lightweight transformation converts partial programs into complete ones that standard compilers can diagnose; Lean-verified semantics-preserving properties; enables focused error detection close to error source during autoregressive decoding.

Key Result: Reduces non-compiling outputs and improves functional correctness on Rust repository tasks (C-to-Rust translation, newly updated library APIs) vs post-generation feedback; detects errors earlier, reducing cascading failures.
