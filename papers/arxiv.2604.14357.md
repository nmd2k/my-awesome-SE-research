---
tags: Software Security, Program Static Analysis
url: https://arxiv.org/abs/2604.14357
publication: 
date: April 15, 2026
dateAdded: 2026-08-24
dateModified:
---
Title: Filament: Denning-Style Information Flow Control for Rust

TL;DR: Denning-style static IFC for Rust; no compiler mods needed; pc_block! for implicit flow enforcement at compile time

Brief Summary: Denning-style static information flow control (IFC) library for Rust requiring no compiler modifications; enables fine-grained explicit-flow checking via Rust's type inference + pc_block! construct for implicit flows via compile-time program counter label enforcement.

Key Result: Practical IFC for Rust at zero compiler overhead; addresses confidentiality and integrity enforcement at type-check time.
