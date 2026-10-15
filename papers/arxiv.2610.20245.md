---
tags: Maintenance & Evolution, Program Repair
url: https://arxiv.org/abs/2610.20245
publication:
date: Oct 14, 2026
dateAdded: 2026-10-15
dateModified:
---
Title: P2Patch: Exploit-Guided Vulnerability Repair

TL;DR: Turns vulnerability repair into an adversarial loop where each candidate patch must survive fresh exploit generation rather than only blocking the original proof of vulnerability.

Brief Summary: P2Patch starts from a normalized vulnerability finding, asks an exploitation agent to construct a reproducing proof of vulnerability, lets a patching agent repair the program, and then has the exploitation agent attack the patched program again with a distinct exploit for the same bug class. Any successful post-patch exploit becomes a permanent repair requirement, while held-out evaluation oracles stay separate from the construction-time evidence.

Key Result: Across 101 C/C++ and Java CVE subjects, the adversarial loop finds a distinct exploit after the original PoV is already blocked in 41% of runs. Relative to single-pass repair from the same finding, it raises fix-closed coverage from 78.1% to 84.7% and beyond-upstream coverage from 42.1% to 62.5%.
