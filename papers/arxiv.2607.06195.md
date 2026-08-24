---
tags: Software Validation, Program Testing
url: https://arxiv.org/abs/2607.06195
publication: 
date: Jul 7, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: LogicHunter: Testing LLM Agent Frameworks with an Agentic Oracle

TL;DR: Specification-aware fuzzing + Agentic Oracle discovers 40 previously unknown bugs (30 confirmed, 26 fixed) in LangChain/LlamaIndex/CrewAI; Agentic Oracle 91.17% precision vs 29.27% baseline

Brief Summary: Fuzzing framework combining specification-driven generation (fusing type constraints + usage patterns) with Agentic Oracle (ReAct-based active diagnosis via docs retrieval, source inspection, runtime states); targets LangChain, LlamaIndex, CrewAI oracle ambiguity problem.

Key Result: Discovers 40 previously unknown bugs (30 confirmed, 26 fixed); Agentic Oracle 91.17% precision vs 29.27% best baseline (+61 pp); state-of-the-art baselines found zero bugs.
