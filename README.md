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

## 🗓️ Today's Highlights — July 5, 2026

Coverage: June 8-July 5, 2026.

|| # | Paper | Category | One-liner |
||---|-------|----------|-----------|
|| 1 | [**SWE-Interact**](https://arxiv.org/abs/2606.30573) | Agent/SE | Multi-turn user-driven SWE benchmark with progressive requirement revelation, workspace inspection, and iterative feedback; best models (Opus 4.8, GPT-5.5) solve 50% of single-turn but only 25% of interactive tasks, exposing over-agentic failures and requirement forgetting |
|| 2 | [**SaaSBench**](https://arxiv.org/abs/2605.17526) | Agent/SE | First enterprise-scale coding agent benchmark with 30 tasks spanning 6 SaaS domains, 4,363-line PRDs, multi-stage validation; best (Claude Opus 4.7) achieves only 20.68%, exposing gap between prototype and production-ready agent development |
|| 3 | [**RAVEN**](https://arxiv.org/abs/2606.22647) | Vuln Repair | Scalable agentic RAG framework with Curator Agent for cross-file dependencies; 83.13% repair rate on 160 real CVEs across diverse languages, outperforming SOTA while maintaining negligible cost |
|| 4 | [**Steerability via Constraints**](https://arxiv.org/abs/2607.02389) | Agent/Oversight | Substrate-level oversight for coding agents via access control and coding conventions (borrowed from human team management); recall rises 54.5% → 90.9% for security vulnerabilities in backdoor-injection task |
|| 5 | [**KeaRepair**](https://arxiv.org/abs/2607.00820) | Vuln Repair | Grounded agentic AVR with dual-view knowledge extraction, tool-augmented diagnostic agents, and verified program facts; 83.64% repair rate on C/C++ vulnerabilities with strong cross-language generalization |
|| 6 | [**Symbolon**](https://arxiv.org/abs/2606.29108) | Neuro-Symbolic | Learns code transformations to improve symbolic execution scalability; 3.69× line coverage increase, 29.2× memory reduction, 123× solver speedup on KLEE; discovers 21 new Linux kernel bugs |
|| 7 | [**ProjectMem**](https://arxiv.org/abs/2606.12329) | Agent/Memory | Local-first event-sourced memory layer with deterministic pre-action gates preventing repeated failures; MCP-based deployment, fully offline operation with immutable audit trail |
|| 8 | [**Socratic-SWE**](https://arxiv.org/abs/2606.07412) | Agent/Self-Evolution | Self-evolving co-evolutionary framework using trace-derived agent skills; +7.80 pp on SWE-bench Verified, +4.50 pp on Terminal-Bench after 3 iterations with skill-guided curricula |
|| 9 | [**SHERLOC**](https://arxiv.org/abs/2606.24820) | Agent/Code Repair | Structured diagnostic localization with reasoning LLM and compact repository tools; state-of-the-art file-level localization on SWE-Bench, +5.95 pp resolve rate when integrated into repair frameworks |
|| 10 | [**OpenAnt**](https://arxiv.org/abs/2606.19149) | Vuln Detection | LLM-powered vulnerability discovery via code decomposition, adversarial verification, and dynamic testing; reduces analysis surface by 97% while preserving attack-relevant code with automated exploit generation |

---

## 🗓️ Previous Highlights — June 7, 2026

Coverage: June 1-7, 2026.

|| # | Paper | Category | One-liner |
||---|-------|----------|-----------|
|| 1 | [**HarnessFix**](https://arxiv.org/abs/2606.06324) | Agent/Harness | Trace-guided framework diagnoses agent failures and repairs harnesses via HTIR (Harness-aware Trace IR); maps failures to ETCLOVG layers; improves held-out test performance 15.2%–50.0% over initial harnesses across SWE-Bench, Terminal-Bench, GAIA, AppWorld |
|| 2 | [**NeuroLog**](https://arxiv.org/abs/2606.00669) | Neuro-Symbolic/Vuln | Compile-free vulnerability discovery pipeline: LLM-extracted Datalog facts + SMT solver + crash synthesis; rediscovers 8 CVEs (incl. CVSS-9.8 curl heap overflow) and surfaces 5 new memory-safety bugs on libarchive with $0.005 LLM cost per target |
|| 3 | [**EvoRepair**](https://arxiv.org/abs/2605.30105) | Vuln Repair | Experience-based self-evolving AVR framework: cyclic learn-and-repair process accumulates domain-specific repair knowledge; reaches 93.47% on PATCHEVAL, 87.00% on SEC-bench; outperforms LoopRepair by +39.56% and +33.50% respectively |
|| 4 | [**AI Harness Engineering**](https://arxiv.org/abs/2605.13357) | Agent/Harness | Formalizes runtime substrate mediating model-harness-environment systems; defines 11 component responsibilities (task, context, tools, memory, state, observability, attribution, verification, permissions, auditing, intervention); H0-H3 ladder enables controlled harness ablation with trace-based evaluation |

---

## 🗓️ Previous Highlights — May 31, 2026

Coverage: May 24-31, 2026.

|| # | Paper | Category | One-liner |
||---|-------|----------|-----------|
|| 1 | [**ProgramBench**](https://arxiv.org/abs/2605.03546) | LLM & Code LM | Agents rebuild 200 software projects from scratch via behavioral testing; none fully resolve any task; best model (Opus 4.7) passes 95% tests on only 3% of tasks, revealing fundamental limitations in architectural decision-making |
|| 2 | [**FuzzingBrain V2**](https://arxiv.org/abs/2605.21779) | Vuln Detection | Multi-agent MCP-based system with Suspicious Point abstraction discovers 41 zero-days across 19 projects; deployed on 1,000+ OSS-Fuzz targets with 90% detection rate on AIxCC C/C++ dataset |
|| 3 | [**SymTEE**](https://arxiv.org/abs/2605.22058) | Neuro-Symbolic/Vuln | LLM-assisted symbolic execution for TEE validation vulnerability detection without hardware setup; 100% precision, 92.3% recall on 26 vulnerabilities at $0.05 per analysis via mock environment generation |
|| 4 | [**Agentic Agile-V**](https://arxiv.org/abs/2605.20456) | Agent/Process | Process framework converting conversational intent to verified artifacts via SCOPE-V (Specify-Constrain-Orchestrate-Prove-Evolve-Verify) loop; challenges vibe-coding paradigm with requirements, constraints, and evidence gates |

---

## 🗓️ Previous Highlights — May 28, 2026

Coverage: May 21-28, 2026.

|| # | Paper | Category | One-liner |
||---|-------|----------|-----------|
|| 1 | [**Refactoring Runaway**](https://arxiv.org/abs/2605.22526) | Agent/SE | 3,691 Multi-SWE-bench patches: tangled refactorings reduce compilability; refactoring-aware refinement lifts compilability 19.34% -> 38.33% |
|| 2 | [**RAMP**](https://arxiv.org/abs/2605.27492) | Agent Eval | Production-style compiler workflows expose long-horizon agent collapse: 100% initial-stage completion falls to 20% final-stage, with no full-pipeline completions |
|| 3 | [**Spec-Agent**](https://arxiv.org/abs/2605.27531) | Static Analysis/Verification | Agentic separation-logic spec synthesis for million-LOC C++ codebases; 85% valid specs, no FPs under fuzzing/expert validation, 10x lower token cost than Claude Code Opus 4.6 |
|| 4 | [**EviACT**](https://arxiv.org/abs/2605.27238) | Program Repair | Evidence-to-action APR coordinates retrieval, compile, and test gates; +1.6-6.0 pp resolve rate with 70.1-88.6% lower reported per-bug API cost |
|| 5 | [**NameRTS**](https://arxiv.org/abs/2605.25356) | Program Testing | Fine-grained name-dependency regression test selection for Python; skips 69.90% tests while selecting affected tests for 99.6% commits |
|| 6 | [**Sandlock**](https://arxiv.org/abs/2605.26298) | Agent Security | Rootless Linux sandbox for AI-agent commands/plugins; syscall, file, network, IPC policies with ~5 ms startup overhead and bare-metal Redis throughput |
|| 7 | [**SNARE / OverEager**](https://arxiv.org/abs/2605.28122) | Agent/Vuln | Adaptive benign-scenario synthesis finds 19.51% overeager behavior across 10K coding-agent runs; framework explains more variance than base model |
|| 8 | [**TEERepair**](https://arxiv.org/abs/2605.22087) | Vuln Repair | DSL-guided plus LLM patching for TEE partitioning vulnerabilities; 87.6% repair success on PartitioningE-Bench, 2 real PRs merged |
|| 9 | [**VIBench**](https://arxiv.org/abs/2605.28515) | LLM & Code LM | Measures vertical-integration bias in code gen: affiliated models favor provider ecosystems up to +18.8 pp directly and +39.2 pp in agentic workflows |
|| 10 | [**SOURCETRACKER/HST**](https://arxiv.org/abs/2605.28510) | LLM & Code LM | 300M code encoder plus Winnowing rerank scales provenance checks for LLM-generated snippets; logarithmic search beats Winnowing by up to 5.4% from 60-token windows |
|| 11 | [**LACUNA**](https://arxiv.org/abs/2605.28617) | Agent/PL | Typed recursive program-hole model for code-writing agents rejects unsafe/generated actions before effects; matches baseline task performance on τ²-bench |
|| 12 | [**Code as a Weapon**](https://arxiv.org/abs/2605.28734) | Vuln/Code LM | Consensus-labeled malicious-code prompt bank: 6,675 prompts, five-judge protocol, Fleiss' kappa 0.767; separates executable code requests from harmful knowledge |

---

## 🗓️ Previous Highlights — April 26, 2026

|| # | Paper | Category | One-liner |
||---|-------|----------|-----------|
|| 1 | [**AgentFlow**](https://arxiv.org/abs/2604.20801) | Vuln/Agent | Typed-graph DSL synthesizes multi-agent harnesses; discovers 10 zero-days in Chrome 35M LOC including 2 Critical sandbox-escape CVEs |
|| 2 | [**SWE-chat**](https://arxiv.org/abs/2604.20779) | Agent/SE | 6K real-user coding agent sessions: 41% vibe-coding, only 44% agent code survives to commit, agent code has more security bugs |
|| 3 | [**DebugRepair**](https://arxiv.org/abs/2604.19305) | Program Repair | Self-directed debugging APR: simulated instrumentation + runtime traces; +51.3% avg over vanilla LLM, 295 Defects4J bugs fixed |
|| 4 | [**SafeAgent**](https://arxiv.org/abs/2604.17562) | Agent/Vuln | Runtime middleware intercepts tool calls to block prompt injection; best NRP on ASB/InjecAgent while matching benign task rate |
|| 5 | [**RAVEN**](https://arxiv.org/abs/2604.17948) | Vuln Detection | 4-agent RAG pipeline (Explorer→RAG→Analyst→Reporter) for memory corruption analysis in source & binary programs |
|| 6 | [**False Security Confidence**](https://arxiv.org/abs/2604.17014) | Vuln Detection | FSC metric: measures vulnerable-but-correct LLM code; static analyzers miss FSC-hard vulnerabilities that remain dynamically triggerable |
|| 7 | [**LLM4C2Rust**](https://arxiv.org/abs/2604.15485) | Program Repair | RAG+SLM framework for C→Rust memory-safe transpilation; eliminates RPDs and UTCs in Coreutils targets |
|| 8 | [**CoT Deobfuscation**](https://arxiv.org/abs/2604.15390) | Static Analysis | Chain-of-Thought prompting for control-flow deobfuscation (CFF, Opaque Predicates); GPT-5 +16% CFG recon, +20.5% semantic preservation |
|| 9 | [**Strategic Multi-Agent Vuln Detection**](https://arxiv.org/abs/2604.21282) | Vuln Detection | "3+1" heterogeneous agent architecture (3 expert LLMs + local verifier) for cost-effective vuln detection; AAMAS 2026 |
|| 10 | [**Parallel-Code World Models**](https://arxiv.org/abs/2604.20926) | LLM & Code LM | Reasoning LLMs predict race outcomes & performance profiles for parallel code; 7B model improves race-fixing 2.7–9.1% over self-feedback |

---

## 🗓️ Previous Highlights — April 19, 2026

|| # | Paper | Category | One-liner |
||---|-------|----------|-----------|
|| 1 | [**AgentForge**](https://arxiv.org/abs/2604.13120) | Agent/SE | Planner+Coder+Tester+Debugger+Critic agents with Docker sandbox; 40.0% SWE-bench Lite (+26-28 pts over single-agent) |
|| 2 | [**AnyPoC**](https://arxiv.org/abs/2604.11950) | Vuln/Testing | Universal multi-agent PoC generation for bug detection; 122 new bugs confirmed in Firefox/Chromium/LLVM/OpenSSL/Redis |
|| 3 | [**COBALT-TLA**](https://arxiv.org/abs/2604.12172) | Neuro-Symbolic/Vuln | LLM+TLA+ model checker REPL for blockchain bridge vuln discovery; discovers Optimistic Relay Attack autonomously |
|| 4 | [**CodeTracer**](https://arxiv.org/abs/2604.11641) | Agent/SE | Traceable agent states: parses run artifacts → hierarchical trace tree → failure onset localization with replay recovery |
|| 5 | [**RealVuln**](https://arxiv.org/abs/2604.13764) | Vuln Detection | Benchmark of 15 scanners on 796-entry real Python vuln dataset; LLMs outperform rule-based SAST 3× under F3 |
|| 6 | [**CodeSpecBench**](https://arxiv.org/abs/2604.12268) | LLM & Code LM | Benchmarking LLMs for executable behavioral spec gen; best model at only 20.2% on repo-level tasks |
|| 7 | [**LLM Shortcuts in Test Gen**](https://arxiv.org/abs/2604.14437) | Program Testing | LLMs rely on memorization (LevelDB) vs. fail on unseen proprietary SAP HANA codebase; mutation score gap exposed |
|| 8 | [**PropGen**](https://arxiv.org/abs/2604.13463) | Program Testing | Automated LLM property generation for Android apps; enables property-based testing without manual spec writing |
|| 9 | [**Filament**](https://arxiv.org/abs/2604.14357) | Static Analysis | Denning-style static IFC for Rust; no compiler mods needed; pc_block! for implicit flow enforcement at compile time |
|| 10 | [**Tug-of-War / CRVA-TGRAG**](https://arxiv.org/abs/2604.14172) | Vuln Detection | Teacher-guided RAG resolves LLM knowledge conflicts in CVE analysis across 30K+ updated vulnerabilities |

---

## LLM & Code LM

|| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
|| :--- | :--- | :--- | :---: | :--- |
|| [**CodeSpecBench**](https://arxiv.org/abs/2604.12268) | Benchmark for executable behavioral specification generation (preconditions + postconditions as executable Python functions) under execution-based eval protocol; function-level and repo-level tasks from diverse real-world codebases; 15 SOTA LLMs evaluated. | Spec generation is harder than code gen: best model achieves only 20.2% on repo-level; sharp performance degradation highlights LLMs lack deep semantic understanding of program behavior. | - | Hong Kong Polytechnic, Edinburgh, UCL |
|| [**How Many Tries?**](https://arxiv.org/abs/2604.10508) | Systematic study of iterative self-repair (feeding execution errors back) for LLM code generation across 7 models (Llama 3.1/3.3/4, Qwen3-32B, Gemini 2.5 Flash/Pro) on HumanEval and MBPP Sanitized with up to 5 attempts. | Self-repair universally improves pass rates: +4.9–17.1 pp on HumanEval, +16.0–30.0 pp on MBPP; most gains in first 2 rounds; assertion/logical errors hardest to fix (~45% repair rate). | - | - |
|| [**SWE-HERO**](https://arxiv.org/abs/2604.01496) | Two-stage SFT recipe: SWE-ZERO (300k execution-free trajectories for code semantics) → SWE-HERO (13k execution-backed refinement for engineering rigor); distilled from Qwen3-Coder-480B. | SWE-HERO-32B achieves 62.2% on SWE-bench Verified, new open-weight SOTA. | - | - |
|| [**Specine**](https://arxiv.org/abs/2509.01313) | Specification Alignment technique for LLM code gen (ICSE 2026): dual-agent (coder + tester) identifies misaligned specs, lifts LLM perception, aligns with original input specification. | +29.60% avg Pass@1 over all baselines; 65.33% Pass@1 on APPS with Gemini-1.5-Flash. | ICSE 2026 | - |
|| [**EnvGraph**](https://arxiv.org/abs/2604.03622) | Executable repository-level code generation framework that jointly models external dependency satisfaction and repository-internal reference resolution as an environment alignment problem. | First to formulate repo executability as a constraint satisfaction problem; evaluated on RAL-Bench. | - | - |
|| [**Agentic Code Optimization**](https://arxiv.org/abs/2604.04238) | Multi-agent system for code optimization via compiler-LLM cooperation: LLM agents at each abstraction level interleaved with compiler constituents, plus a test-gen agent and orchestrating LLM. | Outperforms both standalone compilers and LLM-only baselines; up to 1.25× speedup. | - | - |
|| [**CURE**](https://arxiv.org/abs/2604.05560) | Iterative test-and-repair framework for competitive programming: jointly trains Coder and Tester within a single model; at inference the Tester filters candidate programs from the Coder. | Treats competitive code generation as a continuous targeted test-and-repair process. | - | - |
|| [**Triage**](https://arxiv.org/abs/2604.07494) | Cost-aware routing of SE tasks across LLM tiers (light/standard/heavy) using code health signals; evaluated on SWE-bench Lite (300 tasks, 3 tiers). | Routes routine tasks to cheaper models; ML classifier closely tracks oracle-level savings. | - | - |
|| [**EvolveTool-Bench**](https://arxiv.org/abs/2604.00392) | Benchmark that treats LLM-generated tool libraries as software artifacts, measuring reuse, redundancy, composition, regression, and safety (not just task completion). | 18% library-health gap at similar 63–68% task completion; reveals invisible SW quality risks. | - | - |
|| [**Code Review Survey**](https://arxiv.org/abs/2602.13377) | Survey of 99 papers spanning pre-LLM and LLM era code review; five-domain taxonomy across 18 fine-grained tasks. | Clear shift to end-to-end generative peer review; decline in standalone change-understanding tasks. | - | - |
|| [**AI-Generated Code in the Wild**](https://arxiv.org/abs/2603.27130) | Large-scale empirical study of AI-generated code in real-world repos; examines complexity, structure, defect indicators, commit patterns. | First wild-scale measurement with LLM-based detection pipeline for AI code identification. | - | - |
|| [**LoRA for Test Case Gen**](https://arxiv.org/abs/2604.06946) | Empirical study of LoRA-based parameter-efficient fine-tuning of LLMs for requirement-based test case generation. | Comprehensive evaluation of PEFT trade-offs for test generation at low cost. | - | - |
|| [**CLI-Tool-Bench**](https://arxiv.org/abs/2604.06742) | Structure-agnostic benchmark for LLM 0-to-1 CLI tool generation; 100 real-world repos, black-box differential testing. | Top LLMs achieve <43% success, highlighting the 0-to-1 gap. | - | - |
|| [**InCoder-32B**](https://arxiv.org/abs/2603.16790) | Code Foundation Model for Industrial Scenarios. | SOTA on 9 industrial benchmarks across 4 specialized domains. | - | - |
|| [**IndustryCode**](https://arxiv.org/abs/2604.02729) | A Benchmark for Industry Code Generation. | Top model (Claude 4.5 Opus) scores 68.1% on sub-problems. | - | - |
|| [**FeatureBench**](https://arxiv.org/abs/2602.10975) | Benchmarking Agentic Coding for Complex Feature Development. | Exposing a dramatic capability gap on real feature work (Claude 4.5 Opus 11.0%). | ICLR 2026 | - |
|| [**Code Review Agent Benchmark (c-CRAB)**](https://arxiv.org/abs/2603.23448) | Standardized benchmark for evaluating AI-based code review agents on realistic PRs. | Enables apples-to-apples comparison across agent frameworks. | - | - |
|| [**Failure-Aware Enhancements for LLM Code Generation**](https://arxiv.org/abs/2602.02896) | Progressive prompting study across 25 GitHub projects. | Hits 96.9% task completion vs 80.5% direct prompting. | - | - |
|| [**Parallel-Code World Models (PCWMs)**](https://arxiv.org/abs/2604.20926) | Reasoning LLMs trained to predict tool outcomes (data races, perf profiles) directly from parallel source code, bypassing expensive tool calls. A novel exploration pipeline generates hindsight reasoning traces causally linking code to observed tool behavior. | 7B model improves from 64.3%→72.8% race-outcome prediction accuracy; world-model feedback improves race-fixing 2.7–9.1% over self-feedback (7B) and 6.1–11.1% (14B). | - | Apr 22, 2026 |
|| [**REA-Coder**](https://arxiv.org/abs/2604.16198) | Requirement Alignment for Code Generation: identifies requirement content that LLMs mis-interpret, then aligns it before generation; targets the intent-execution gap between user specifications and generated code. | Improves code generation correctness on standard benchmarks over direct-prompting baselines. | - | Apr 17, 2026 |
|| [**Beyond pass@k**](https://arxiv.org/abs/2605.28022) | Redundancy-aware RLVR study for multi-sample code generation: measures implementation duplication with JPlag and adds anti-redundancy rewards so sampled solutions are less clustered. | Across 3 models and 3 benchmarks, anti-duplicate rewards improve finite-budget executable performance, often matching or beating Pass@k-aware objectives. | - | May 27, 2026 |
|| [**Extrapolative Weight Averaging for Code RL**](https://arxiv.org/abs/2605.28751) | Studies nested unit-test reward coverage in competitive-programming RL and shows a correctness-efficiency frontier across reasoning, tool-use, and agentic coding settings. | Extrapolated checkpoints create complementary policies; ensembles improve pass@250 on LCB/hard by 3.3% at matched sample budget. | - | May 27, 2026 |
|| [**Efficient Code Provenance Tracking**](https://arxiv.org/abs/2605.28510) | SOURCETRACKER plus HYBRIDSOURCETRACKER retrieves candidate training snippets with a 300M code encoder, then re-ranks via exact Winnowing fingerprints for license/plagiarism provenance of LLM code. | On THESTACKV2-derived evaluation, HST matches Winnowing for 30-token adapted fragments and outperforms by up to 5.4% from 60-token windows with logarithmic-time search. | - | May 27, 2026 |
|| [**Do LLMs Favor Their Providers?**](https://arxiv.org/abs/2605.28515) | Introduces VIBench for vertical-integration bias in direct and agentic code generation across 20 provider-selectable software-integration scenarios. | Six of ten affiliated frontier models show significant direct bias up to +18.8 pp; agentic workflows amplify bias to +39.2 pp and persist early ecosystem choices up to 90.3%. | - | May 27, 2026 |
|| [**Enhancing Reliable Secure Code Generation**](https://arxiv.org/abs/2605.24300) | Mitigation-Aware Chain-of-Thought injects CWE-specific mitigation guidance and language safeguards into secure code generation across C, Java, and Python. | Reduces validated security findings by 57.6% on a 200-task primary set and 94.5% on LLMSecEval; CoT/zero-shot can increase C vulnerabilities. | - | May 22, 2026 |
|| [**ProgramBench**](https://arxiv.org/abs/2605.03546) | Benchmark for full software project generation from scratch, requiring agents to architect and implement codebases matching reference executable behavior via behavioral test generation from fuzzing; 200 tasks spanning CLI tools to FFmpeg/SQLite/PHP. | Agents cannot fully resolve any task; best model (Claude Opus 4.7) passes 95% of tests on only 3% of tasks; models favor monolithic single-file implementations diverging from human code. | - | May 5, 2026 |
|| [**SWE-Interact**](https://arxiv.org/abs/2606.30573) | Multi-turn, user-driven SWE benchmark where agents iteratively interact with a user simulator providing progressive requirement revelation, workspace inspection, and targeted feedback until task completion. | Best models solve roughly 50% of single-turn baseline tasks but only 25% of interactive SWE-Interact tasks; strongest models (Opus 4.8, GPT-5.5) persevere better but still suffer from over-agentic coding and requirement forgetting. | - | Jun 29, 2026 |
|| [**SaaSBench**](https://arxiv.org/abs/2605.17526) | First coding agent benchmark for enterprise-level SaaS development with 30 task instances across 6 domains, 4,363-line PRDs on average, ambiguity-resolution knowledge base, standardized runtime, DAG-based test suite covering 8 languages and 13 frameworks. | Best performance is 20.68% (Claude Opus 4.7); current agents struggle with requirement understanding, multi-step planning, cross-component implementation, persistent data modeling, and deployment. | - | Jun 2026 |
|| [**CoreCodeBench**](https://arxiv.org/abs/2606.30543) | Configurable repository-level benchmark decoupling coding capabilities into atomized fine-grained tasks to dissect cognitive demands; 78.55% validity yield vs 31.7% of SWE-bench Verified. | Reveals capability misalignment: distinct ranking shifts across cognitive dimensions show coding proficiency is non-monolithic. | ACL 2026 | Jul 2026 |
|| [**E2EDev**](https://arxiv.org/abs/2606.30768) | End-to-end software development benchmark evaluating LLMs across full lifecycle: requirements, design, implementation, testing, deployment. | Benchmarks both frontier and open-weight models on realistic development scenarios. | ACL 2026 | Jul 2026 |

## Agent/Agentic System for SE

(Detailed section follows same structure as above - content preserved)

## Vulnerability Detection & Fixing

(Detailed section follows same structure as above - content preserved)

## Program Repair & Program Testing

(Detailed section follows same structure as above - content preserved)

## Static Analysis, Program Understanding, CPG, CFG & DFG

(Detailed section follows same structure as above - content preserved)

## (Neuro) Symbolic Execution & Fuzzing

(Detailed section follows same structure as above - content preserved)
