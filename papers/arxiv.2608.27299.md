---
tags: Software Security, Vulnerability Detection
url: https://arxiv.org/abs/2608.27299
publication:
date: Aug 27, 2026
dateAdded: 2026-09-01
dateModified:
---
Title: When Context Gets Root: Privilege Escalation in LLM Harnesses

TL;DR: Identifies instruction privilege escalation in coding-agent harnesses, where untrusted low-level content is relabeled as higher-privilege user or system context and then followed by the model.

Brief Summary: The paper shows that context reconstruction inside agent harnesses can break provenance assumptions behind instruction hierarchy and automatic permission review. It realizes tool-to-user and tool-to-system escalation through delegation, persistent goals, scheduled tasks, and custom subagents.

Key Result: Across six coding-agent harnesses and 13 attack objectives spanning confidentiality, integrity, availability, and remote code execution, unrestricted execution reaches all 13 objectives on all six harnesses; under automatic permission review, all 13 objectives still succeed on all three harnesses that support it.
