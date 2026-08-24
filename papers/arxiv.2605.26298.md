---
tags: Software Security, Vulnerability Detection
url: https://arxiv.org/abs/2605.26298
publication: 
date: May 25, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Sandlock: Confining AI Agent Code with Unprivileged Linux Primitives

TL;DR: Rootless Linux sandbox for AI-agent commands/plugins; syscall, file, network, IPC policies with ~5 ms startup overhead and bare-metal Redis throughput

Brief Summary: Lightweight rootless Linux sandbox for AI agents running generated shell commands, third-party scripts, and plugins; combines kernel-enforced static policy with a narrow runtime supervisor.

Key Result: Enforces file, network, IPC, syscall, execve, and reversible filesystem policies with roughly 5 ms startup overhead and Redis throughput within measurement noise.
