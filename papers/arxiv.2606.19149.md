---
tags: Software Security, Vulnerability Detection
url: https://arxiv.org/abs/2606.19149
publication: 
date: Jun 19, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: OpenAnt: LLM-Powered Vulnerability Discovery Through Code Decomposition, Adversarial Verification, and Dynamic Testing

TL;DR: Multi-stage LLM vulnerability discovery pipeline: static decomposition reduces analysis surface 97%; adversarial verification simulates exploitability; dynamic validation generates exploit proofs in sandboxed containers; discovers vulnerabilities in OpenSSL, WordPress, Flowise with low false positives

Brief Summary: Multi-stage LLM-based vulnerability discovery: code decomposition filters by reachability (97% reduction while preserving attack-relevant code); adversarial verification simulates constrained attacker capabilities; dynamic verification auto-generates exploit environments, executes in sandboxes, validates findings. Applied to OpenSSL, WordPress, Flowise.

Key Result: Identifies previously unknown vulnerabilities while maintaining manageable cost and substantially reducing false positives; demonstrates closed-loop vulnerability discovery combining semantic reasoning with exploit validation.
