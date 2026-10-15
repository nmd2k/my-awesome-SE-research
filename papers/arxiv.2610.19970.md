---
tags: Software Understanding, Program Understanding
url: https://arxiv.org/abs/2610.19970
publication:
date: Oct 14, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: Temporal Adaptive Fine-Tuning for Code Comprehension

TL;DR: Treats repository evolution as supervision for code-comprehension QA, teaching models what changed, what became obsolete, and what must be retained as a codebase evolves.

Brief Summary: TAFT frames repository updates as a temporal adaptation problem for repository-level question answering. It derives temporally grounded QA pairs from repository transitions, aligns newly valid knowledge against obsolete answers through preference optimization, and replays transition-conditioned retention examples so the model keeps still-valid and semantically adjacent knowledge instead of overwriting it.

Key Result: On a temporal SWE-bench-style dataset with 255,295 QA entries across ten time slices, TAFT improves updated and obsolete-knowledge accuracy by 18% on average relative to baselines, roughly doubles retention accuracy, and improves neighboring-knowledge accuracy by about 1.5x. TAFT-KANT improves further when direct knowledge anchors are available.
