---
tags: Software Security, Vulnerability Detection
url: https://arxiv.org/abs/2609.39678
publication:
date: Sep 30, 2026
dateAdded: 2026-10-01
dateModified:
---
Title: Aletheia: Permission-Minimality Testing for Coding-Agent Rules

TL;DR: Tests whether repository instruction files ask coding agents for unnecessary authority, turning over-privileged agent rules into an executable security signal.

Brief Summary: Aletheia models requested permissions in repository rule files, synthesizes sandbox variants that selectively remove one permission at a time, and reruns the same task unchanged. If the task still passes under reduced authority, the removed permission is treated as dispensable and potentially suspicious in context.

Key Result: On 314 AIShellJack attack inputs, Aletheia detects every malicious rule and reports no alarms on five benign templates; across 80 manually verified benign GHAgentFiles rules, it raises only three false positives.
