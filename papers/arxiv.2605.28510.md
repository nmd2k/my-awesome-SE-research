---
tags: LLMs for SE, Code LM
url: https://arxiv.org/abs/2605.28510
publication: 
date: May 27, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Efficient and Scalable Provenance Tracking for LLM-Generated Code Snippets

TL;DR: 300M code encoder plus Winnowing rerank scales provenance checks for LLM-generated snippets; logarithmic search beats Winnowing by up to 5.4% from 60-token windows

Brief Summary: SOURCETRACKER plus HYBRIDSOURCETRACKER retrieves candidate training snippets with a 300M code encoder, then re-ranks via exact Winnowing fingerprints for license/plagiarism provenance of LLM code.

Key Result: On THESTACKV2-derived evaluation, HST matches Winnowing for 30-token adapted fragments and outperforms by up to 5.4% from 60-token windows with logarithmic-time search.
