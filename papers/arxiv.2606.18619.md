---
tags: Software Security, Vulnerability Detection
url: https://arxiv.org/abs/2606.18619
publication: 
date: 
dateAdded: 2026-08-24
dateModified:
---
Title: Code-Augur: Agentic Vulnerability Detection via Specification Inference

TL;DR: Specification-first agentic vulnerability detection via reason-falsify-refine loop; LLM generates invariant assertions; grey-box fuzzer attempts falsification; surfaces real bugs or refines assumptions; finds 34–370% more bugs than Claude Code/Atlantis on benchmarks; 22 zero-days discovered in OSS projects

Brief Summary: Agentic vulnerability detection using specification-first paradigm: LLM generates invariant assertions as falsifiable predicates, grey-box fuzzer attempts to violate them, violations trigger triage (real bugs or refinement). Reason-falsify-refine loop aligns LLM understanding with code behavior.

Key Result: Finds 34–370% more bugs than Claude Code and Atlantis on AIxCC/OSV benchmarks; discovered 22 zero-days (16 fixed, 2 CVEs: CVE-2026-48113, CVE-2026-34830) in widely-used projects.
