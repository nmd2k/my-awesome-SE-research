---
tags: Maintenance & Evolution, Program Repair
url: https://arxiv.org/abs/2610.39899
publication:
date: Oct 29, 2026
dateAdded: 2026-11-01
dateModified:
---
Title: ExploreRepair: Evidence-Specialized Agents for Vulnerability Repair under Information Constraints

TL;DR: Uses multiple evidence-specialized exploration agents to hypothesize vulnerability causes before converging on a repair, improving vulnerability fixing when proof-of-vulnerability tests or exact classifications are missing.

Brief Summary: ExploreRepair tackles realistic repair settings where developers have only partial vulnerability information. It runs three exploration agents over different vulnerability dimensions, aggregates both their lessons and candidate patches, and reconciles those proposals into a final repair without relying on benchmark feedback.

Key Result: On PatchEval, ExploreRepair reaches 39.6% with GPT-5.6-Luna and 71.6% with DeepSeek-V4.1-Flash, beating EvoRepair by 16.0 and 25.4 points. On VulnLoc+, it beats a LoopRepair variant without PoV tests by 20.0 and 17.1 points.
