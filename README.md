# Awesome SE Research Work

A curated list of awesome software engineering research papers, specifically focused on LLMs, agentic systems, vulnerability detection, program repair, static analysis, and neuro-symbolic execution.

## Contents
- [LLM & Code LM](#llm--code-lm)
- [Agent/Agentic System for SE](#agentagentic-system-for-se)
- [Vulnerability Detection & Fixing](#vulnerability-detection--fixing)
- [Program Repair & Program Testing](#program-repair--program-testing)
- [Static Analysis, Program Understanding, CPG, CFG & DFG](#static-analysis-program-understanding-cpg-cfg--dfg)
- [(Neuro) Symbolic Execution & Fuzzing](#neuro-symbolic-execution--fuzzing)

---

## 🗓️ Today's Highlights — June 28, 2026

Coverage: June 21-28, 2026.

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**OpenAnt**](https://arxiv.org/abs/2606.19149) | Vuln Detection | Multi-stage LLM vulnerability discovery pipeline: static decomposition reduces analysis surface 97%; adversarial verification simulates exploitability; dynamic validation generates exploit proofs in sandboxed containers; discovers vulnerabilities in OpenSSL, WordPress, Flowise with low false positives |
| 2 | [**Code-Augur**](https://arxiv.org/abs/2606.18619) | Vuln Detection | Specification-first agentic vulnerability detection via reason-falsify-refine loop; LLM generates invariant assertions; grey-box fuzzer attempts falsification; surfaces real bugs or refines assumptions; finds 34–370% more bugs than Claude Code/Atlantis on benchmarks; 22 zero-days discovered in OSS projects |
| 3 | [**SHERLOC**](https://arxiv.org/abs/2606.24820) | Program Repair | Training-free fault localization for code-repair agents using reasoning LLMs with compact repo tools; provides diagnostic context for downstream repair; +8–12 pp improvements on SWE-bench Verified; reduces localization tokens by 36.7% on average |
| 4 | [**ACRouter (Agent-as-a-Router)**](https://arxiv.org/abs/2606.22902) | Agent/SE | Formalize model routing as Context-Action-Feedback loop; closes information deficit via execution-grounded experience accumulation; outperforms static routers by 15.3%; achieves lowest cumulative regret on in-distribution and OOD coding tasks |
| 5 | [**ProjectMem**](https://arxiv.org/abs/2606.12329) | Agent/SE | Local-first, event-sourced memory layer for AI coding agents: append-only event log + deterministic pre-action judgment gate prevents repeating failed fixes; runs fully offline; provides provenance trail for auditable AI-assisted development |
| 6 | [**Revelio**](https://arxiv.org/abs/2606.22263) | Vuln Detection | Cost-efficient agentic memory-safety vulnerability detection: inexpensive models for hypothesis generation + stronger models for sanitizer-grounded PoV construction; discovers 19 zero-days in OSS-Fuzz projects at $300 total cost ($16 per vulnerability) |
| 7 | [**Agentic Programming (LLM-as-Code)**](https://arxiv.org/abs/2606.15874) | Agent/SE | Programming paradigm where deterministic code governs control flow and LLM acts as adaptive component for reasoning; DAG-structured context; prevents token explosion and control-flow hallucination; substantially improves stability of long visual operation sequences |
| 8 | [**AOHP (Android Open Harness Project)**](https://arxiv.org/abs/2606.23449) | Agent/SE | OS-level agent harness treating AI agents as first-class system actors; enables personalized service composition, efficient agent interfaces, secure information flow; +21.12% completion rate, -51.55% token cost over conventional systems |
| 9 | [**Forge**](https://arxiv.org/abs/2606.22413) | Program Repair | Formal-method-guided vibe coding pipeline for safety-critical Java code; uses model-driven engineering to extract formal artifacts in Dafny/CSP/Z-Machines; verification failures drive iterative code-generation refinement; produces standards-relevant verification evidence |
| 10 | [**Agon**](https://arxiv.org/abs/2606.24177) | Agent/SE | Autonomous research orchestrator using Prompt Economy; massively parallel, zero-code, omnidisciplinary; validates checkable claims inside workflow, leaves judgment to humans; demonstrates scalability across 444 iterations while exposing failure taxonomy |

---

## 🗓️ Previous Highlights — June 7, 2026

Coverage: June 1-7, 2026.

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**HarnessFix**](https://arxiv.org/abs/2606.06324) | Agent/Harness | Trace-guided framework diagnoses agent failures and repairs harnesses via HTIR (Harness-aware Trace IR); maps failures to ETCLOVG layers; improves held-out test performance 15.2%–50.0% over initial harnesses across SWE-Bench, Terminal-Bench, GAIA, AppWorld |
| 2 | [**NeuroLog**](https://arxiv.org/abs/2606.00669) | Neuro-Symbolic/Vuln | Compile-free vulnerability discovery pipeline: LLM-extracted Datalog facts + SMT solver + crash synthesis; rediscovers 8 CVEs (incl. CVSS-9.8 curl heap overflow) and surfaces 5 new memory-safety bugs on libarchive with $0.005 LLM cost per target |
| 3 | [**EvoRepair**](https://arxiv.org/abs/2605.30105) | Vuln Repair | Experience-based self-evolving AVR framework: cyclic learn-and-repair process accumulates domain-specific repair knowledge; reaches 93.47% on PATCHEVAL, 87.00% on SEC-bench; outperforms LoopRepair by +39.56% and +33.50% respectively |
| 4 | [**AI Harness Engineering**](https://arxiv.org/abs/2605.13357) | Agent/Harness | Formalizes runtime substrate mediating model-harness-environment systems; defines 11 component responsibilities (task, context, tools, memory, state, observability, attribution, verification, permissions, auditing, intervention); H0-H3 ladder enables controlled harness ablation with trace-based evaluation |

---

## 🗓️ Previous Highlights — May 31, 2026

Coverage: May 24-31, 2026.

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**ProgramBench**](https://arxiv.org/abs/2605.03546) | LLM & Code LM | Agents rebuild 200 software projects from scratch via behavioral testing; none fully resolve any task; best model (Opus 4.7) passes 95% tests on only 3% of tasks, revealing fundamental limitations in architectural decision-making |
| 2 | [**FuzzingBrain V2**](https://arxiv.org/abs/2605.21779) | Vuln Detection | Multi-agent MCP-based system with Suspicious Point abstraction discovers 41 zero-days across 19 projects; deployed on 1,000+ OSS-Fuzz targets with 90% detection rate on AIxCC C/C++ dataset |
| 3 | [**SymTEE**](https://arxiv.org/abs/2605.22058) | Neuro-Symbolic/Vuln | LLM-assisted symbolic execution for TEE validation vulnerability detection without hardware setup; 100% precision, 92.3% recall on 26 vulnerabilities at $0.05 per analysis via mock environment generation |
| 4 | [**Agentic Agile-V**](https://arxiv.org/abs/2605.20456) | Agent/Process | Process framework converting conversational intent to verified artifacts via SCOPE-V (Specify-Constrain-Orchestrate-Prove-Evolve-Verify) loop; challenges vibe-coding paradigm with requirements, constraints, and evidence gates |

---

## 🗓️ Previous Highlights — May 28, 2026

Coverage: May 21-28, 2026.

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**Refactoring Runaway**](https://arxiv.org/abs/2605.22526) | Agent/SE | 3,691 Multi-SWE-bench patches: tangled refactorings reduce compilability; refactoring-aware refinement lifts compilability 19.34% -> 38.33% |
| 2 | [**RAMP**](https://arxiv.org/abs/2605.27492) | Agent Eval | Production-style compiler workflows expose long-horizon agent collapse: 100% initial-stage completion falls to 20% final-stage, with no full-pipeline completions |
| 3 | [**Spec-Agent**](https://arxiv.org/abs/2605.27531) | Static Analysis/Verification | Agentic separation-logic spec synthesis for million-LOC C++ codebases; 85% valid specs, no FPs under fuzzing/expert validation, 10x lower token cost than Claude Code Opus 4.6 |
| 4 | [**EviACT**](https://arxiv.org/abs/2605.27238) | Program Repair | Evidence-to-action APR coordinates retrieval, compile, and test gates; +1.6-6.0 pp resolve rate with 70.1-88.6% lower reported per-bug API cost |
| 5 | [**NameRTS**](https://arxiv.org/abs/2605.25356) | Program Testing | Fine-grained name-dependency regression test selection for Python; skips 69.90% tests while selecting affected tests for 99.6% commits |
| 6 | [**Sandlock**](https://arxiv.org/abs/2605.26298) | Agent Security | Rootless Linux sandbox for AI-agent commands/plugins; syscall, file, network, IPC policies with ~5 ms startup overhead and bare-metal Redis throughput |
| 7 | [**SNARE / OverEager**](https://arxiv.org/abs/2605.28122) | Agent/Vuln | Adaptive benign-scenario synthesis finds 19.51% overeager behavior across 10K coding-agent runs; framework explains more variance than base model |
| 8 | [**TEERepair**](https://arxiv.org/abs/2605.22087) | Vuln Repair | DSL-guided plus LLM patching for TEE partitioning vulnerabilities; 87.6% repair success on PartitioningE-Bench, 2 real PRs merged |
| 9 | [**VIBench**](https://arxiv.org/abs/2605.28515) | LLM & Code LM | Measures vertical-integration bias in code gen: affiliated models favor provider ecosystems up to +18.8 pp directly and +39.2 pp in agentic workflows |
| 10 | [**SOURCETRACKER/HST**](https://arxiv.org/abs/2605.28510) | LLM & Code LM | 300M code encoder plus Winnowing rerank scales provenance checks for LLM-generated snippets; logarithmic search beats Winnowing by up to 5.4% from 60-token windows |
| 11 | [**LACUNA**](https://arxiv.org/abs/2605.28617) | Agent/PL | Typed recursive program-hole model for code-writing agents rejects unsafe/generated actions before effects; matches baseline task performance on τ²-bench |
| 12 | [**Code as a Weapon**](https://arxiv.org/abs/2605.28734) | Vuln/Code LM | Consensus-labeled malicious-code prompt bank: 6,675 prompts, five-judge protocol, Fleiss' kappa 0.767; separates executable code requests from harmful knowledge |

---

## 🗓️ Previous Highlights — April 26, 2026

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**AgentFlow**](https://arxiv.org/abs/2604.20801) | Vuln/Agent | Typed-graph DSL synthesizes multi-agent harnesses; discovers 10 zero-days in Chrome 35M LOC including 2 Critical sandbox-escape CVEs |
| 2 | [**SWE-chat**](https://arxiv.org/abs/2604.20779) | Agent/SE | 6K real-user coding agent sessions: 41% vibe-coding, only 44% agent code survives to commit, agent code has more security bugs |
| 3 | [**DebugRepair**](https://arxiv.org/abs/2604.19305) | Program Repair | Self-directed debugging APR: simulated instrumentation + runtime traces; +51.3% avg over vanilla LLM, 295 Defects4J bugs fixed |
| 4 | [**SafeAgent**](https://arxiv.org/abs/2604.17562) | Agent/Vuln | Runtime middleware intercepts tool calls to block prompt injection; best NRP on ASB/InjecAgent while matching benign task rate |
| 5 | [**RAVEN**](https://arxiv.org/abs/2604.17948) | Vuln Detection | 4-agent RAG pipeline (Explorer→RAG→Analyst→Reporter) for memory corruption analysis in source & binary programs |
| 6 | [**False Security Confidence**](https://arxiv.org/abs/2604.17014) | Vuln Detection | FSC metric: measures vulnerable-but-correct LLM code; static analyzers miss FSC-hard vulnerabilities that remain dynamically triggerable |
| 7 | [**LLM4C2Rust**](https://arxiv.org/abs/2604.15485) | Program Repair | RAG+SLM framework for C→Rust memory-safe transpilation; eliminates RPDs and UTCs in Coreutils targets |
| 8 | [**CoT Deobfuscation**](https://arxiv.org/abs/2604.15390) | Static Analysis | Chain-of-Thought prompting for control-flow deobfuscation (CFF, Opaque Predicates); GPT-5 +16% CFG recon, +20.5% semantic preservation |
| 9 | [**Strategic Multi-Agent Vuln Detection**](https://arxiv.org/abs/2604.21282) | Vuln Detection | "3+1" heterogeneous agent architecture (3 expert LLMs + local verifier) for cost-effective vuln detection; AAMAS 2026 |
| 10 | [**Parallel-Code World Models**](https://arxiv.org/abs/2604.20926) | LLM & Code LM | Reasoning LLMs predict race outcomes & performance profiles for parallel code; 7B model improves race-fixing 2.7–9.1% over self-feedback |

---

## 🗓️ Previous Highlights — April 19, 2026

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**AgentForge**](https://arxiv.org/abs/2604.13120) | Agent/SE | Planner+Coder+Tester+Debugger+Critic agents with Docker sandbox; 40.0% SWE-bench Lite (+26-28 pts over single-agent) |
| 2 | [**AnyPoC**](https://arxiv.org/abs/2604.11950) | Vuln/Testing | Universal multi-agent PoC generation for bug detection; 122 new bugs confirmed in Firefox/Chromium/LLVM/OpenSSL/Redis |
| 3 | [**COBALT-TLA**](https://arxiv.org/abs/2604.12172) | Neuro-Symbolic/Vuln | LLM+TLA+ model checker REPL for blockchain bridge vuln discovery; discovers Optimistic Relay Attack autonomously |
| 4 | [**CodeTracer**](https://arxiv.org/abs/2604.11641) | Agent/SE | Traceable agent states: parses run artifacts → hierarchical trace tree → failure onset localization with replay recovery |
| 5 | [**RealVuln**](https://arxiv.org/abs/2604.13764) | Vuln Detection | Benchmark of 15 scanners on 796-entry real Python vuln dataset; LLMs outperform rule-based SAST 3× under F3 |
| 6 | [**CodeSpecBench**](https://arxiv.org/abs/2604.12268) | LLM & Code LM | Benchmarking LLMs for executable behavioral spec gen; best model at only 20.2% on repo-level tasks |
| 7 | [**LLM Shortcuts in Test Gen**](https://arxiv.org/abs/2604.14437) | Program Testing | LLMs rely on memorization (LevelDB) vs. fail on unseen proprietary SAP HANA codebase; mutation score gap exposed |
| 8 | [**PropGen**](https://arxiv.org/abs/2604.13463) | Program Testing | Automated LLM property generation for Android apps; enables property-based testing without manual spec writing |
| 9 | [**Filament**](https://arxiv.org/abs/2604.14357) | Static Analysis | Denning-style static IFC for Rust; no compiler mods needed; pc_block! for implicit flow enforcement at compile time |
| 10 | [**Tug-of-War / CRVA-TGRAG**](https://arxiv.org/abs/2604.14172) | Vuln Detection | Teacher-guided RAG resolves LLM knowledge conflicts in CVE analysis across 30K+ updated vulnerabilities |

---

## 🗓️ Previous Highlights — April 14, 2026

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**Sailor**](https://arxiv.org/abs/2604.06506) | Neuro-Symbolic/Vuln | Auto harness generation via static analysis + LLM-orchestrated symbolic execution; 379 new vulns in 6.8M LOC |
| 2 | [**SWE-HERO**](https://arxiv.org/abs/2604.01496) | LLM & Code LM | Two-stage execution-free → execution-based SFT; SWE-HERO-32B hits 62.2% on SWE-bench Verified |
| 3 | [**Beyond Resolution Rates**](https://arxiv.org/abs/2604.02547) | Agent/SE | 9,374 trajectories: context-gather-before-edit, not trajectory length, predicts coding agent success |
| 4 | [**Inside the Scaffold**](https://arxiv.org/abs/2604.03515) | Agent/SE | Source-code taxonomy of 13 coding agent scaffolds across 12 architectural dimensions |
| 5 | [**Dissecting Bug Triggers**](https://arxiv.org/abs/2604.08906) | Agent/SE | Empirical study of 409 bugs in 5 agentic frameworks; cognitive context mismanagement = key root cause |
| 6 | [**Agentic Code Optimization**](https://arxiv.org/abs/2604.04238) | LLM & Code LM | Multi-agent compiler-LLM cooperation for code optimization; up to 1.25× speedup over compiler-only |
| 7 | [**QRS**](https://arxiv.org/abs/2602.09774) | Neuro-Symbolic/Vuln | 3-agent neuro-symbolic triad auto-synthesizes CodeQL queries + semantic validation; beats SAST defaults |
| 8 | [**AFGNN**](https://arxiv.org/abs/2604.07891) | Static Analysis | MSR 2026: API Flow Graph + self-supervised GNN clustering for API misuse detection |
| 9 | [**Specine**](https://arxiv.org/abs/2509.01313) | LLM & Code LM | ICSE 2026: specification alignment for LLM code gen; +29.60% Pass@1 vs. baselines |
| 10 | [**CURE**](https://arxiv.org/abs/2604.05560) | Program Testing | Joint coder+tester training with iterative test-and-repair for competitive programming |
| 11 | [**EnvGraph**](https://arxiv.org/abs/2604.03622) | LLM & Code LM | Executable repo-level code gen via joint modeling of dependency + internal reference resolution |
| 12 | [**PatchRecall**](https://arxiv.org/abs/2604.10481) | Program Repair | Hybrid codebase + history-based retrieval improves file localization in APR |

---

## 🗓️ Previous Highlights — April 13, 2026 (Update 2)

| # | Paper | Category | One-liner |
|---|-------|----------|-----------|
| 1 | [**AMBIG-SWE**](https://arxiv.org/abs/2502.13069) | Agent/SE | ICLR 2026: interactive clarification agents close 74% gap on underspecified SWE tasks |
| 2 | [**AgentFixer**](https://arxiv.org/abs/2603.29848) | Agent/SE | 15-tool validation framework diagnoses & fixes LLM agent failures; parsing = 38% of crashes |
| 3 | [**Near-Miss**](https://arxiv.org/abs/2603.29665) | Agent/SE | Latent policy failure detection in agentic workflows; 8–17% near-miss rate even on correct outcomes |
| 4 | [**Your Agent Is Mine**](https://arxiv.org/abs/2604.08407) | Vuln | Malicious LLM API routers actively inject code & exfiltrate secrets; found in 9/428 real routers |
| 5 | [**Supply-Chain Poisoning**](https://arxiv.org/abs/2604.03081) | Vuln | DDIPE bypasses agent defenses 11–34% by embedding payloads in skill documentation |
| 6 | [**Broken by Default**](https://arxiv.org/abs/2604.05292) | Vuln | Z3-proven: 55.8% of AI-generated code artifacts have formal security vulnerabilities |
| 7 | [**VibeGuard**](https://arxiv.org/abs/2604.01052) | Vuln | Pre-publish security gate for vibe-coded projects; 100% recall on 8 real/synthetic projects |
| 8 | [**BinDeObfBench**](https://arxiv.org/abs/2604.08083) | Static Analysis | First benchmark for LLM binary deobfuscation; reasoning > scale for obfuscation robustness |
| 9 | [**Panta**](https://arxiv.org/abs/2503.13580) | Program Testing | ICSE 2026: iterative CFG+coverage-guided LLM test gen for higher branch coverage |
| 10 | [**Triage**](https://arxiv.org/abs/2604.07494) | LLM & Code LM | Cost-aware SE task routing to LLM tiers via code health signals on SWE-bench Lite |
| 11 | [**EvolveTool-Bench**](https://arxiv.org/abs/2604.00392) | LLM & Code LM | Benchmark treating LLM tool libraries as first-class SW artifacts; 18% quality gap at same task rate |
| 12 | [**Beyond Human-Readable**](https://arxiv.org/abs/2604.07502) | Agent/SE | Semantic density principle: redesign code conventions for LLM agents, not human readers |

---

## LLM & Code LM

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**CodeSpecBench**](https://arxiv.org/abs/2604.12268) | Benchmark for executable behavioral specification generation (preconditions + postconditions as executable Python functions) under execution-based eval protocol; function-level and repo-level tasks from diverse real-world codebases; 15 SOTA LLMs evaluated. | Spec generation is harder than code gen: best model achieves only 20.2% on repo-level; sharp performance degradation highlights LLMs lack deep semantic understanding of program behavior. | - | Hong Kong Polytechnic, Edinburgh, UCL |
| [**How Many Tries?**](https://arxiv.org/abs/2604.10508) | Systematic study of iterative self-repair (feeding execution errors back) for LLM code generation across 7 models (Llama 3.1/3.3/4, Qwen3-32B, Gemini 2.5 Flash/Pro) on HumanEval and MBPP Sanitized with up to 5 attempts. | Self-repair universally improves pass rates: +4.9–17.1 pp on HumanEval, +16.0–30.0 pp on MBPP; most gains in first 2 rounds; assertion/logical errors hardest to fix (~45% repair rate). | - | - |
| [**SWE-HERO**](https://arxiv.org/abs/2604.01496) | Two-stage SFT recipe: SWE-ZERO (300k execution-free trajectories for code semantics) → SWE-HERO (13k execution-backed refinement for engineering rigor); distilled from Qwen3-Coder-480B. | SWE-HERO-32B achieves 62.2% on SWE-bench Verified, new open-weight SOTA. | - | - |
| [**ProgramBench**](https://arxiv.org/abs/2605.03546) | Benchmark for full software project generation from scratch, requiring agents to architect and implement codebases matching reference executable behavior via behavioral test generation from fuzzing; 200 tasks spanning CLI tools to FFmpeg/SQLite/PHP. | Agents cannot fully resolve any task; best model (Claude Opus 4.7) passes 95% of tests on only 3% of tasks; models favor monolithic single-file implementations diverging from human code. | - | May 5, 2026 |

## Agent/Agentic System for SE

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**AgentForge**](https://arxiv.org/abs/2604.13120) | Execution-grounded multi-agent framework for autonomous bug fixing: Planner (structured plan), Coder (minimal unified-diff patches), Tester (synthesizes executable tests), Debugger (iterative repair via execution feedback), Critic (validates final result); episodic memory + live repo index; mandatory Docker sandbox enforces non-simulated execution feedback. | 40.0% resolution on SWE-bench Lite, outperforms single-agent baselines by 26–28 points. | - | - |
| [**SWE-chat**](https://arxiv.org/abs/2604.20779) | First large-scale dataset of real coding-agent sessions from open-source developers in the wild: 6,000 sessions, 63K+ user prompts, 355K+ agent tool calls; living dataset growing continuously. Analyzes adoption patterns, code quality, and human-agent dynamics in production. | 41% "vibe coding" (agent authors all committed code); only 44% of agent code survives to commit; agent-written code introduces more security vulnerabilities than human code; users push back in 44% of turns. | - | Stanford; Apr 22, 2026 |

## Vulnerability Detection & Fixing

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**OpenAnt**](https://arxiv.org/abs/2606.19149) | Multi-stage LLM vulnerability discovery system: static code decomposition filters reachable analysis units (97% reduction), adversarial verification simulates exploitability from attacker perspective, dynamic validation generates exploit environments in sandboxed containers. Evaluated on OpenSSL, WordPress, Flowise. | Identifies vulnerabilities with dramatically reduced false positives compared to traditional static analysis and fuzzing; manageable cost through efficient LLM use and sandbox validation. | - | Jun 2026 |
| [**Code-Augur**](https://arxiv.org/abs/2606.18619) | Agentic vulnerability detection using specification-first paradigm: LLM generates invariant assertions as falsifiable predicates, grey-box fuzzer attempts to violate them, violations trigger triage (real bugs or refinement). Reason-falsify-refine loop aligns LLM understanding with code behavior. | Finds 34–370% more bugs than Claude Code and Atlantis on AIxCC/OSV benchmarks; discovered 22 zero-days (16 fixed, 2 CVEs: CVE-2026-48113, CVE-2026-34830) in widely-used projects. | - | Jun 2026 |
| [**Revelio**](https://arxiv.org/abs/2606.22263) | Cost-efficient agentic memory-safety vulnerability detection: inexpensive models generate vulnerability hypotheses, stronger models construct sanitizer-grounded proofs-of-vulnerability with dynamic validation. Deployed on mature OSS-Fuzz projects undergoing 5-8 years of continuous fuzzing. | Discovered 19 previously unknown memory-safety vulnerabilities at $300 total cost (~$16 per vulnerability); outperforms advanced AI coding agent baselines on benchmarks. | - | Jun 2026 |

## Program Repair & Program Testing

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**SHERLOC**](https://arxiv.org/abs/2606.24820) | Training-free fault localization for code repair agents using reasoning LLMs with compact repository tools; provides diagnostic context (line-level hit@k metrics) for downstream repair agents. Evaluated on SWE-bench Verified with two agentic frameworks. | Quality-filtered findings improve resolution rates +8–12 pp across repair models; reduces localization tokens 36.7% on average while maintaining/improving repair performance. | - | Jun 2026 |

## Static Analysis & Program Understanding

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**Spec-Agent**](https://arxiv.org/abs/2605.27531) | Agentic separation-logic specification synthesis for C++ repositories; combines static analysis, runtime heap tracing, fuzz harnesses, and counterexample-guided refinement over a ladder of spec languages. Deployed on million-LOC codebases. | Synthesizes valid specs for 85% of target functions; zero false positives under fuzzing/expert validation; 10x lower token cost than Claude Code Opus 4.6. | - | May 26, 2026 |

## (Neuro) Symbolic Execution & Fuzzing

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**SymTEE**](https://arxiv.org/abs/2605.22058) | LLM-assisted symbolic execution for detecting missing input validation in TEE applications without hardware setup; AST-based analysis extracts vulnerable slices, LLM generates KLEE-compatible mock environments and security oracles, KLEE explores paths for concrete inputs violating assertions. | 100% precision, 92.3% recall on 26 vulnerabilities (11 real-world + 15 synthetic); average cost $0.05 per analysis; eliminates need for complex TEE runtime setups and specialized hardware. | - | May 22, 2026 |
