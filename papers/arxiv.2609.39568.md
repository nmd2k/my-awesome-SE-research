---
tags: LLMs for SE, Code LM
url: https://arxiv.org/abs/2609.39568
publication:
date: Sep 30, 2026
dateAdded: 2026-10-01
dateModified:
---
Title: Self-Spec Verifiable Code Generation

TL;DR: Introduces VeriCodeBench and CodeNova for end-to-end self-specifying, verifier-guided code generation, showing that specification quality is the main bottleneck in formally verifiable LLM code.

Brief Summary: The paper argues that prior verifiable-code benchmarks overestimate progress by supplying oracle specifications or focusing too narrowly on proof-oriented languages. It proposes VeriCodeBench, a 400-problem benchmark spanning C, Java, Rust, and Python, where the model must write its own specification, implement the code, and close the loop with verification feedback.

Key Result: CodeNova improves specification coverage, code validity, and end-to-end success under the self-spec protocol, and the study finds that stronger-looking specifications do not automatically translate into higher verification success.
