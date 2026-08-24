---
tags: Maintenance & Evolution, Program Repair
url: https://arxiv.org/abs/2604.15485
publication: 
date: Apr 16, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: LLM4C2Rust: Large Language Models for Automated Memory-Safe Code Transpilation

TL;DR: RAG+SLM framework for C→Rust memory-safe transpilation; eliminates RPDs and UTCs in Coreutils targets

Brief Summary: RAG-assisted C/C++→Rust memory-safe transpilation framework: integrates LLM with SLM, segments C code in balanced blocks, retrieves Rust documentation and compiler error context; targets elimination of Raw Pointer Dereferences (RPDs) and Unsafe Type Casts (UTCs).

Key Result: Complete elimination of RPDs and UTCs in several Coreutils targets; RAG pipeline improves both correctness and memory safety over baseline LLM transpilation.
