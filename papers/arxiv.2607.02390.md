---
tags: LLMs for SE, Code LM
url: https://arxiv.org/abs/2607.02390
publication: 
date: Jul 2, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: DecompRL: Solving Harder Problems by Learning Modular Code Generation

TL;DR: Learns modular code decomposition through RL: solves hard problems by factoring into sub-functions and recombining; cuts GPU token cost by ~50× vs standard generation; outperforms standard & diversity-optimized RL on LiveCodeBench & CodeContests

Brief Summary: RL algorithm for modular code generation: learns to decompose complex problems into independently solvable sub-functions whose implementations can be recombined; offline learning on small problems scales to repository tasks via CPU-efficient recombination of k implementations into k^n candidates.

Key Result: Cuts GPU token cost by ~50× vs standard generation; outperforms standard and diversity-optimized RL baselines on LiveCodeBench and CodeContests beyond 10^5 tokens per problem.
