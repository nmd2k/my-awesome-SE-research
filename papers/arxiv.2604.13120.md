---
tags: LLMs for SE, Agentic SE
url: https://arxiv.org/abs/2604.13120
publication: 
date: 
dateAdded: 2026-08-24
dateModified:
---
Title: AgentForge: Execution-Grounded Multi-Agent LLM Framework for Autonomous Software Engineering

TL;DR: Planner+Coder+Tester+Debugger+Critic agents with Docker sandbox; 40.0% SWE-bench Lite (+26-28 pts over single-agent)

Brief Summary: Execution-grounded multi-agent framework for autonomous bug fixing: Planner (structured plan), Coder (minimal unified-diff patches), Tester (synthesizes executable tests), Debugger (iterative repair via execution feedback), Critic (validates final result); episodic memory + live repo index; mandatory Docker sandbox enforces non-simulated execution feedback.

Key Result: 40.0% resolution on SWE-bench Lite, outperforms single-agent baselines by 26–28 points.
