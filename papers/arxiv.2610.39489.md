---
tags: Software Understanding, Program Understanding
url: https://arxiv.org/abs/2610.39489
publication:
date: Oct 29, 2026
dateAdded: 2026-11-01
dateModified:
---
Title: Program Bindings Inside Code Models

TL;DR: Shows compiler-style structural facts, especially definition-use links, can both explain and edit the hidden states of code language models.

Brief Summary: The paper decomposes code-model hidden states using front-end program facts such as AST position, scope, syntactic category, and definition-use relations. It then checks whether those decomposed states can replace the original activations without changing predictions, and whether editing the decomposition can steer the model as if the underlying binding structure had changed.

Key Result: The static-analysis decomposition preserves answers better than a position-only baseline in 10 of 14 models, including 6 of 7 code models. Rebinding a call argument steers StarCoder2-15B to the edited program's answer in 90 of 100 cases, versus 19 of 100 for the baseline.
