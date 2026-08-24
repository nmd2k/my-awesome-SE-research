---
tags: Software Validation, Neuro-Symbolic
url: https://arxiv.org/abs/2606.29108
publication: 
date: Jun 29, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Symbolon: Symbolic Execution by Learning Code Transformation

TL;DR: Learns diverse code transformations context-sensitively to improve symbolic execution; offline learning distilled into agent skills; 3.69× line coverage improvement on KLEE, 29.2× memory reduction; uncovers 21 new bugs in Linux kernel

Brief Summary: Framework learning diverse code transformations context-sensitively to improve symbolic execution: formulates transformation discovery as search over program representations; learns transformations cheaply offline on small programs, distills into reusable agent skills, applies context-sensitively on repo-level targets.

Key Result: 3.69× average line coverage increase on KLEE across 16 search strategies, 29.2× peak memory reduction, 123× solver time reduction; uncovers 21 new bugs in Linux kernel all reported to maintainers.
