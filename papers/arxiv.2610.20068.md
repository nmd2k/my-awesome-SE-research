---
tags: Software Understanding, Architecture & Design
url: https://arxiv.org/abs/2610.20068
publication:
date: Oct 14, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: The Code of Theseus: Can Agents Rebuild Software from Recovered Design Documents?

TL;DR: Recovers requirements and architecture artifacts from repositories at scale, then shows those artifacts improve structural fidelity when agents rebuild software even when test pass rates barely move.

Brief Summary: The paper reconstructs aligned stakeholder intent, requirements, and architecture from a compact repository representation, a static dependency graph, and a small set of contextual files. It releases recovered artifacts for 10,764 repositories, then evaluates whether coding agents can rebuild 29 Commit0 libraries from intent alone or from intent plus the recovered design artifacts while only seeing interface contracts and part of the tests.

Key Result: Recovered artifacts do not materially change held-out pass rate (33.7% vs. 35.8%), but they raise module-structure F1 from 0.54 to 0.63. The main insight is that reconstructed design documents preserve architectural information that tests alone do not expose.
