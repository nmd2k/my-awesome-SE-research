---
tags: LLMs for SE, Agentic SE
url: https://arxiv.org/abs/2605.28617
publication: 
date: May 27, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: LACUNA: Safe Agents as Recursive Program Holes

TL;DR: Typed recursive program-hole model for code-writing agents rejects unsafe/generated actions before effects; matches baseline task performance on τ²-bench

Brief Summary: Programming model for agents as typed recursive program holes: generated action code is type-checked against surrounding program, tool/data bounds, and all-or-nothing execution before effects occur.

Key Result: Rejects 8.6% of BrowseComp-Plus generations before execution with 0.7 retries/query; solves 76.0% of 392 τ²-bench tasks, matching baseline performance.
