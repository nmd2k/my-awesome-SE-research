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

## 🗓️ Today's Highlights — April 19, 2026

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
| [**Specine**](https://arxiv.org/abs/2509.01313) | Specification Alignment technique for LLM code gen (ICSE 2026): dual-agent (coder + tester) identifies misaligned specs, lifts LLM perception, aligns with original input specification. | +29.60% avg Pass@1 over all baselines; 65.33% Pass@1 on APPS with Gemini-1.5-Flash. | ICSE 2026 | - |
| [**EnvGraph**](https://arxiv.org/abs/2604.03622) | Executable repository-level code generation framework that jointly models external dependency satisfaction and repository-internal reference resolution as an environment alignment problem. | First to formulate repo executability as a constraint satisfaction problem; evaluated on RAL-Bench. | - | - |
| [**Agentic Code Optimization**](https://arxiv.org/abs/2604.04238) | Multi-agent system for code optimization via compiler-LLM cooperation: LLM agents at each abstraction level interleaved with compiler constituents, plus a test-gen agent and orchestrating LLM. | Outperforms both standalone compilers and LLM-only baselines; up to 1.25× speedup. | - | - |
| [**CURE**](https://arxiv.org/abs/2604.05560) | Iterative test-and-repair framework for competitive programming: jointly trains Coder and Tester within a single model; at inference the Tester filters candidate programs from the Coder. | Treats competitive code generation as a continuous targeted test-and-repair process. | - | - |
| [**Triage**](https://arxiv.org/abs/2604.07494) | Cost-aware routing of SE tasks across LLM tiers (light/standard/heavy) using code health signals; evaluated on SWE-bench Lite (300 tasks, 3 tiers). | Routes routine tasks to cheaper models; ML classifier closely tracks oracle-level savings. | - | - |
| [**EvolveTool-Bench**](https://arxiv.org/abs/2604.00392) | Benchmark that treats LLM-generated tool libraries as software artifacts, measuring reuse, redundancy, composition, regression, and safety (not just task completion). | 18% library-health gap at similar 63–68% task completion; reveals invisible SW quality risks. | - | - |
| [**Code Review Survey**](https://arxiv.org/abs/2602.13377) | Survey of 99 papers spanning pre-LLM and LLM era code review; five-domain taxonomy across 18 fine-grained tasks. | Clear shift to end-to-end generative peer review; decline in standalone change-understanding tasks. | - | - |
| [**AI-Generated Code in the Wild**](https://arxiv.org/abs/2603.27130) | Large-scale empirical study of AI-generated code in real-world repos; examines complexity, structure, defect indicators, commit patterns. | First wild-scale measurement with LLM-based detection pipeline for AI code identification. | - | - |
| [**LoRA for Test Case Gen**](https://arxiv.org/abs/2604.06946) | Empirical study of LoRA-based parameter-efficient fine-tuning of LLMs for requirement-based test case generation. | Comprehensive evaluation of PEFT trade-offs for test generation at low cost. | - | - |
| [**CLI-Tool-Bench**](https://arxiv.org/abs/2604.06742) | Structure-agnostic benchmark for LLM 0-to-1 CLI tool generation; 100 real-world repos, black-box differential testing. | Top LLMs achieve <43% success, highlighting the 0-to-1 gap. | - | - |
| [**InCoder-32B**](https://arxiv.org/abs/2603.16790) | Code Foundation Model for Industrial Scenarios. | SOTA on 9 industrial benchmarks across 4 specialized domains. | - | - |
| [**IndustryCode**](https://arxiv.org/abs/2604.02729) | A Benchmark for Industry Code Generation. | Top model (Claude 4.5 Opus) scores 68.1% on sub-problems. | - | - |
| [**FeatureBench**](https://arxiv.org/abs/2602.10975) | Benchmarking Agentic Coding for Complex Feature Development. | Exposing a dramatic capability gap on real feature work (Claude 4.5 Opus 11.0%). | ICLR 2026 | - |
| [**Code Review Agent Benchmark (c-CRAB)**](https://arxiv.org/abs/2603.23448) | Standardized benchmark for evaluating AI-based code review agents on realistic PRs. | Enables apples-to-apples comparison across agent frameworks. | - | - |
| [**Failure-Aware Enhancements for LLM Code Generation**](https://arxiv.org/abs/2602.02896) | Progressive prompting study across 25 GitHub projects. | Hits 96.9% task completion vs 80.5% direct prompting. | - | - |

## Agent/Agentic System for SE

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**AgentForge**](https://arxiv.org/abs/2604.13120) | Execution-grounded multi-agent framework for autonomous bug fixing: Planner (structured plan), Coder (minimal unified-diff patches), Tester (synthesizes executable tests), Debugger (iterative repair via execution feedback), Critic (validates final result); episodic memory + live repo index; mandatory Docker sandbox enforces non-simulated execution feedback. | 40.0% resolution on SWE-bench Lite, outperforms single-agent baselines by 26–28 points. | - | - |
| [**CodeTracer**](https://arxiv.org/abs/2604.11641) | Tracing architecture for debugging code agents: parses heterogeneous run artifacts via evolving extractors → hierarchical trace tree with persistent memory → failure onset localization (earliest failure + downstream chain). Introduces CodeTraceBench from 4 agent frameworks on diverse code tasks. | Substantially outperforms direct prompting and lightweight baselines; replaying diagnostic signals consistently recovers originally failed runs under matched budgets. | - | - |
| [**Beyond Resolution Rates**](https://arxiv.org/abs/2604.02547) | Large-scale behavioral analysis of 9,374 agent trajectories from 19 agents (8 frameworks × 14 LLMs) on 500 SWE-bench tasks; studies outcome-level, failure root-cause, and behavioral patterns. | Context-gather-before-edit + validation investment predict success; LLM drives outcome more than scaffold. | - | - |
| [**Inside the Scaffold**](https://arxiv.org/abs/2604.03515) | Source-code-level architectural taxonomy of 13 open-source coding agent scaffolds, characterizing each across 12 dimensions in 3 layers: control architecture, tool/env interface, resource management. | 5 loop primitives (ReAct, gen-test-repair, plan-execute, retry, MCTS) compose as building blocks; 11/13 agents mix multiple primitives. | - | - |
| [**Dissecting Bug Triggers**](https://arxiv.org/abs/2604.08906) | Systematic empirical study of 409 fixed bugs from 5 modern agentic frameworks (CrewAI, AutoGen, etc.); proposes a 5-layer abstraction and taxonomies for symptoms, root causes, components. | Unique agentic symptoms: unexpected execution sequences, ignored user configs; root causes include cognitive context mismanagement and model backend faults. | - | - |
| [**AMBIG-SWE**](https://arxiv.org/abs/2502.13069) | Interactive agents on underspecified SWE-Bench Verified; evaluates 3 capacities: ambiguity detection, clarification acquisition, and task resolution. | Clarification interaction yields up to 74% improvement over non-interactive settings. | ICLR 2026 | - |
| [**AgentFixer**](https://arxiv.org/abs/2603.29848) | Comprehensive validation framework with 15 failure-detection tools + 2 root-cause analysis modules; applied to IBM CUGA on AppWorld & WebArena benchmarks. | Parsing issues = 38% of all production task failures; mid-size models (Llama 4, Mistral Medium) close frontier gap after fixes. | ICSE 2026 (AGENT Workshop) | - |
| [**Near-Miss**](https://arxiv.org/abs/2603.29665) | Latent policy failure detection in agentic workflows: agents bypass required policy checks yet reach correct state by luck. Builds on ToolGuard to analyze tool-calling decisions. | 8–17% latent failure rate on τ²-verified Airlines benchmark even when final outcome is correct. | - | - |
| [**Beyond Human-Readable**](https://arxiv.org/abs/2604.07502) | Systematic analysis of human-centric SE conventions under agentic pressure; proposes semantic density optimization, program skeleton concept for navigation, and rehabilitation of classical anti-patterns. | First framework for redesigning code conventions targeting LLM-agent consumers. | - | - |
| [**Agent Psychometrics**](https://arxiv.org/abs/2604.00594) | IRT augmented with task/repo/test-case features for task-level performance prediction; decomposes agent ability into LLM vs scaffold components. | Accurately predicts task-level pass/fail for unseen benchmarks & LLM-scaffold combos. | ICLR 2026 Workshop | - |
| [**Rethinking Agent-Generated Tests**](https://arxiv.org/abs/2602.07900) | Analyzes 6 LLM agent trajectories on SWE-bench Verified; questions whether agent-written tests aid resolution. | Test writing frequency is similar for resolved vs unresolved tasks; value is mostly observational. | - | - |
| [**PETSc Agentic Eval**](https://arxiv.org/abs/2603.15976) | Agents-evaluating-agents framework (petscagent-bench) for AI-generated HPC code via MCP/A2A protocols. | Frontier models score well on readability but fail library-specific HPC conventions. | - | - |
| [**Codified Context**](https://arxiv.org/abs/2602.20478) | Infrastructure for AI Agents in a Complex Codebase. | 3-component persistent memory infra across 283 dev sessions. | - | - |
| [**Bugs in LLM Agent Frameworks**](https://arxiv.org/abs/2602.21806) | Analysis of framework-level bugs in LangChain/CrewAI. | 998 bug reports → 15 root causes & 7 symptoms. | - | - |
| [**TraceCoder**](https://arxiv.org/abs/2602.06875) | A Trace-Driven Multi-Agent Framework for Automated Debugging. | Outperforms baselines on Pass@1 accuracy; reduces redundant repairs. | ICSE 2026 | - |
| [**TDAD**](https://arxiv.org/abs/2603.17973) | Test-Driven Agentic Development via pre-change AST-based impact analysis. | 70% regression reduction (6.08% → 1.82%) on SWE-bench Verified. | - | - |
| [**ABTest**](https://arxiv.org/abs/2604.03362) | Behavior-Driven Testing for AI Coding Agents under adversarial usage. | Detected 1,573 behavioral anomalies across 3 coding-agent families. | - | - |
| [**Agentic AI Software Engineers: Programming with Trust**](https://arxiv.org/abs/2502.13767) | Trust taxonomy + safety constraints for autonomous coding agents. | Guidelines for responsible deployment. | - | - |
| [**FLARE**](https://arxiv.org/abs/2604.05289) | Agentic Coverage-Guided Fuzzing for LLM-Based Multi-Agent Systems. | 96.9% inter-agent coverage, 91.1% intra-agent coverage. | - | - |

## Vulnerability Detection & Fixing

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**AnyPoC**](https://arxiv.org/abs/2604.11950) | Universal multi-agent PoC generation for validating LLM-generated bug reports at scale: Analyzer agent fact-checks the report (static), Generator agent synthesizes + executes PoC (dynamic), Checker agent re-executes and scrutinizes to prevent hallucination/reward hacking. Applied to 12 critical systems including Firefox, Chromium, LLVM, OpenSSL, SQLite, FFmpeg, Redis. | 122 new bugs detected; 105 confirmed by developers, 86 fixed, 45 PoCs adopted as regression tests. | - | - |
| [**RealVuln**](https://arxiv.org/abs/2604.13764) | First open-source benchmark comparing 15 scanners (3 rule-based SAST, 10 general-purpose LLMs, 2 security-specialized) on 26 intentionally vulnerable Python repos (educational + CTF), 796 hand-labeled entries (676 vulns + 120 FP traps); F3 scoring (recall-weighted 9×). | Security-specialized Kolega.Dev (73.0 F3) > best LLM Claude Sonnet 4.6 (51.7 F3) ≈ 3× best rule-based Semgrep (17.7 F3); LLMs beat SAST by large margin on recall. | - | April 15, 2026 |
| [**Tug-of-War / CRVA-TGRAG**](https://arxiv.org/abs/2604.14172) | Two-stage CRVA-TGRAG framework addressing LLM knowledge conflicts in CVE analysis: 30K+ CVEs have been updated/changed over the last decade causing training data staleness, factual fabrication, and hallucination; teacher-guided RAG retrieves latest CVE knowledge and resolves conflicts between internal LLM knowledge and external retrieved context. | Reduces hallucination and factual conflicts in LLM-based CVE detection and analysis; maintains fresh knowledge without full retraining. | - | - |
| [**Your Agent Is Mine**](https://arxiv.org/abs/2604.08407) | Formalizes malicious LLM API router threat model; defines payload injection (AC-1) & secret exfiltration (AC-2) attacks. Surveyed 428 real routers from public communities and marketplaces. | 9 actively malicious routers found: inject code, exfiltrate credentials, drain ETH; 2 deploy adaptive evasion. | - | - |
| [**Supply-Chain Poisoning**](https://arxiv.org/abs/2604.03081) | Document-Driven Implicit Payload Execution (DDIPE): embeds malicious logic in skill documentation examples; agents execute payload via normal reuse without explicit prompt injection. | 11.6–33.5% bypass rate across 4 frameworks; explicit attacks get 0% under strong defenses. 4 CVEs disclosed. | - | - |
| [**Broken by Default**](https://arxiv.org/abs/2604.05292) | Formal verification study of 3,500 code artifacts from 7 LLMs across 500 security-critical prompts (5 CWE categories). Z3 SMT solver via COBALT produces mathematical witnesses. | 55.8% of all artifacts have formally proven vulnerabilities; GPT-4o worst (62.4%), Gemini 2.5 Flash best (48.4%). | - | - |
| [**VibeGuard**](https://arxiv.org/abs/2604.01052) | Pre-publish security gate for vibe-coded projects; catches artifact hygiene, packaging drift, source-map exposure, hardcoded secrets, and supply-chain risks before npm publish. | 100% recall, 89.47% precision (F1=94.44%) on 8 synthetic projects at 3 policy levels. | - | - |
| [**LLM-Enabled OSS Vulnerabilities**](https://arxiv.org/abs/2604.04288) | Empirical analysis of 295 GitHub Security Advisories (Jan 2025–Jan 2026) referencing LLM components; manual annotation of 100 advisories using OWASP Top 10 for LLM 2025. | Top risk patterns: Supply Chain, Excessive Agency, Prompt Injection; maps to established CWEs. | - | - |
| [**VCAO**](https://arxiv.org/abs/2604.08291) | 6-layer agentic OS vulnerability discovery using game-theoretic (Bayesian Stackelberg) budget allocation across kernel files/functions with LRM orchestrator + cascaded verifiers. | Strategic, coverage-efficient OS vuln discovery with safety governance. | - | - |
| [**Sailor**](https://arxiv.org/abs/2604.06506) | SAILOR (Static Analysis Informed and LLM-ORchestrated Symbolic Execution): fully automated SE harness generation pipeline — static analysis identifies candidate vulnerable locations; LLM iteratively synthesizes drivers, stubs, assertions; symbolic execution detects bugs; replay validates. | 379 distinct previously unknown memory-safety vulnerabilities (421 confirmed crashes) in 10 open-source C/C++ projects totaling 6.8M LOC. | - | - |
| [**QRS**](https://arxiv.org/abs/2602.09774) | Rule-Synthesizing Neuro-Symbolic Triad for autonomous vulnerability discovery: inverts SAST paradigm — Query agent auto-generates CodeQL queries from structured schema + few-shot examples; Review agent traces data flows for exploitability; Sanitize agent prunes false positives. | Eliminates need for expert-crafted queries; high-confidence vuln reports with exploitation suggestions. | - | - |
| [**CPRVul**](https://arxiv.org/abs/2602.06751) | Context-Aware Reasoning for Inter-Procedural Vulnerability Detection. | Inter-procedural CPG context + structured reasoning: +22.9% on PrimeVul. | - | - |
| [**Efficient Vuln Detection via Transformers**](https://arxiv.org/abs/2604.00112) | Study of program slice representations for C/C++ vulnerability detection. | Transformer on program slices beats GNN baselines on C/C++. | - | - |
| [**When Labels Are Scarce**](https://arxiv.org/abs/2604.00079) | Label-Efficient Code Vulnerability Detection survey. | First systematic mapping of 5 label-efficient vuln detection paradigms. | - | - |
| [**PAGENT**](https://arxiv.org/abs/2604.07624) | Program Analysis Guided LLM Agent for PoC Generation. | Static+dynamic analysis guided PoC generation: +132% vs prior SOTA. | - | - |
| [**VulnSage**](https://arxiv.org/abs/2604.05130) | Multi-Agent Framework for Automated Exploit Generation on npm. | 53.47% exploit rate on SecBench.js; 146 real zero-days found. | ICPC 2026 | - |
| [**AutoEG**](https://arxiv.org/abs/2604.00704) | Exploiting Known Third-Party Vulnerabilities in Black-Box Web Apps. | 82.41% black-box web exploit success vs 32.88% SOTA. | - | - |
| [**Argus**](https://arxiv.org/abs/2604.06633) | Multi-Agent Ensemble for Full-Chain Vulnerability Detection. | Reduces FP and hallucination rate; LLM-centered SAST workflow. | - | - |
| [**SemTaint**](https://arxiv.org/abs/2601.10865) | Multi-Agent Taint Specification Extraction for JavaScript. | Detected 106 vulnerabilities previously undetectable by CodeQL alone. | - | - |
| [**Detect–Repair–Verify (DRV) v1**](https://arxiv.org/abs/2603.00897) | Securing LLM-Generated Code. | Project-level DRV benchmark for LLM-generated code security. | - | - |
| [**DRV Multi-Granularity**](https://arxiv.org/abs/2603.23633) | Extension of DRV to finer-grained multi-language settings. | Multi-language × multi-granularity DRV evaluation. | - | - |
| [**VulnAgent-X**](https://arxiv.org/abs/2603.13384) | Layered agentic pipeline for vulnerability detection. | Best F1/AUROC on PrimeVul. | - | - |
| [**Scalable Vuln Dataset**](https://arxiv.org/abs/2603.17974) | Automated pipeline for building repository-level vulnerability detection datasets using LLM agents + static analysis. | Enables scalable, diverse, real-world vuln dataset construction beyond synthetic benchmarks. | - | - |

## Program Repair & Program Testing

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**PropGen**](https://arxiv.org/abs/2604.13463) | PropGen automates property generation for Android app property-based testing using LLMs; explores app behavior, extracts functional properties (preconditions + postconditions), addresses the key bottleneck that manually writing properties is expensive and limits PBT adoption. | Automated property generation for mobile apps, enabling scalable PBT without manual oracle specification. | - | April 15, 2026 |
| [**LLM Shortcuts in Test Gen**](https://arxiv.org/abs/2604.14437) | Investigates whether LLMs genuinely reason or take shortcuts in automated test generation by contrasting performance on open-source LevelDB (in training data) vs. proprietary SAP HANA (guaranteed out-of-distribution); uses mutation score + iterative compiler-feedback repair to assess reasoning quality. | Exposes significant gap between memorization-aided (LevelDB) and genuine reasoning (SAP HANA) test quality; reveals LLMs rely on shallow heuristics when training data is absent. | - | April 15, 2026; TH Köln |
| [**PatchRecall**](https://arxiv.org/abs/2604.10481) | Hybrid retrieval approach for APR file localization: combines codebase-level retrieval (semantic similarity) with history-based retrieval (similar historical patches) to balance recall and conciseness. | Addresses the critical file-localization bottleneck in repo-scale automated program repair. | - | - |
| [**CURE**](https://arxiv.org/abs/2604.05560) | Iterative test-and-repair framework for competitive code generation: jointly trains Coder and Tester within a single model; inference-time Tester generates tests from problem description to filter Coder candidates. | Treats competitive programming repair as continuous targeted test-and-repair; surpasses LLM-only baselines. | - | - |
| [**Panta**](https://arxiv.org/abs/2503.13580) | Iterative hybrid program analysis for LLM test generation: static CFG analysis + dynamic coverage feedback guide LLMs to target uncovered execution paths. | Higher branch coverage vs direct LLM test gen; emulates human iterative analysis. | ICSE 2026 | - |
| [**Patch Porting (Implicit Inconsistencies)**](https://arxiv.org/abs/2604.01680) | LLM-based approach to mitigate implicit inconsistencies when porting patches across code variants (forks, branches); addresses semantic drift in related codebases. | First work targeting implicit (non-conflict) inconsistencies in cross-variant patch porting. | - | - |
| [**LLM Test Generation Under Software Evolution**](https://arxiv.org/abs/2603.23443) | Large-scale (8 LLMs × 22,374 variants) mutation-driven study of LLM test generation sensitivity, resilience, and stability under semantic vs structural code change. | LLM-generated tests often miss semantic changes and over-fit to structural patterns. | - | - |
| [**SPARC**](https://arxiv.org/abs/2602.16671) | Neuro-symbolic C unit test gen: CFG analysis → Operation Map → path-targeted LLM synthesis → iterative compiler/runtime repair. | +31.36% line, +26.01% branch, +20.78% mutation score; matches KLEE on complex subjects. | - | - |
| [**MIST-RL**](https://arxiv.org/abs/2603.01409) | RL (GRPO) formulation for mutation-guided test suite generation; incremental mutation reward + dynamic penalties to curb redundancy. | Higher fault detection with fewer redundant tests than scaling-by-quantity baselines. | - | - |
| [**GALA**](https://arxiv.org/abs/2604.08089) | Multimodal Graph Alignment for Bug Localization in APR. | Multimodal APR via UI Graph → structural code alignment; SoTA on SWE-bench Multimodal. | - | - |
| [**FL Granularity Study**](https://arxiv.org/abs/2604.00167) | Impact of Fault Localization Granularity for Repository-Scale Code Repair. | Function-level generally best for repo-scale repair, but task-dependent. | - | - |
| [**SCPatcher**](https://arxiv.org/abs/2604.00687) | Smart Contract Code Repair via RAG and Knowledge Graph. | RAG+KG for smart contract repair: CPR 90%, ERR 81.7%, ORR 73.5%. | - | - |
| [**TraceRepair**](https://arxiv.org/abs/2604.02647) | Runtime Execution Traces + Multi-Agent Debate for APR. | Correctly fixes 392 defects on Defects4J. | - | - |
| [**Why LLMs Fail in Sec Patching**](https://arxiv.org/abs/2603.10072) | Failure Analysis for Automated Security Patch Generation. | Tri-axis evaluation of LLM patch generation correctness vs security vs functionality. | - | - |
| [**LLM-Based Architectures for Automated Patching**](https://arxiv.org/abs/2603.01257) | Systematic study of LLM architecture choices for security patching. | Identifies architectural patterns that reliably improve patching. | - | - |
| [**SWE-Bench Validity Study**](https://arxiv.org/abs/2602.04449) | The Case of SWE-Bench in Automated Program Repair. | Raises benchmark contamination and fair-comparison concerns. | - | - |

## Static Analysis, Program Understanding, CPG, CFG & DFG

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**Filament**](https://arxiv.org/abs/2604.14357) | Denning-style static information flow control (IFC) library for Rust requiring no compiler modifications; enables fine-grained explicit-flow checking via Rust's type inference + pc_block! construct for implicit flows via compile-time program counter label enforcement. | Practical IFC for Rust at zero compiler overhead; addresses confidentiality and integrity enforcement at type-check time. | - | April 15, 2026 |
| [**Agentic RE Challenges**](https://arxiv.org/abs/2604.14317) | Survey and analysis of LLM-based agentic systems for binary reverse engineering (static, dynamic, hybrid agents); identifies limitations including token constraints, struggle with obfuscation, and lack of program guardrails; cutting-edge systems still fail on complex RE with obfuscation and unique architectures. | Structured examination of technical capabilities and gaps in agentic RE; roadmap for overcoming token/obfuscation/guardrail challenges. | - | April 15, 2026 |
| [**AFGNN**](https://arxiv.org/abs/2604.07891) | API Misuse Detection using Graph Neural Networks and Clustering (MSR 2026): novel API Flow Graph (AFG) captures API execution sequence, data/control flow; self-supervised GNN pre-training; cluster-based misuse detection (small clusters = misuse). | Significantly outperforms SOTA small LMs and API misuse detectors at a fraction of model size. | MSR 2026 | - |
| [**BinDeObfBench**](https://arxiv.org/abs/2604.08083) | First comprehensive benchmark for LLM-based binary deobfuscation spanning pre-compilation, compile-time, and post-compilation stages; 9 LLMs evaluated. | Reasoning capability > model scale for robustness; task-specific fine-tuning > domain pre-training. | - | - |
| [**Static Analysis for Library Hallucinations**](https://arxiv.org/abs/2604.07755) | Static Analysis Methods for Code Library Hallucinations. | 14–85% LLM hallucination catch rate; upper bound ~77%. | - | - |
| [**Call Graph Unsoundness**](https://arxiv.org/abs/2604.00885) | Detecting Call Graph Unsoundness without Ground Truth. | Precision partial orders break in Soot/SootUp/WALA/Doop due to lambdas/reflection. | - | - |
| [**CodeBadger**](https://arxiv.org/abs/2603.24837) | Bridging Code Property Graphs and LMs for Program Analysis. | Joern CPG + LLM for slicing, taint tracking, data flow, call graph. | - | - |
| [**Phoenix**](https://arxiv.org/abs/2602.01720) | Modular & Versatile C/C++ Pointer Analysis. | Flexible, configurable static analysis infrastructure. | - | - |
| [**LLMSA**](https://arxiv.org/abs/2412.14399) | Compilation-free static analysis via Datalog + LLM neural relations. | - | - | - |

## (Neuro) Symbolic Execution & Fuzzing

| Paper | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :--- | :--- | :---: | :--- |
| [**COBALT-TLA**](https://arxiv.org/abs/2604.12172) | Neuro-symbolic verification loop pairing an LLM with TLC (TLA+ model checker) in an automated REPL: LLM generates bounded TLA+ specifications → TLC acts as semantic oracle → structured error traces injected back into LLM context to drive convergence. Evaluated on 3 cross-chain bridge targets including a faithful model of the Nomad $190M exploit. | Reaches verified BUG_FOUND in ≤2 iterations on all targets; autonomously discovers an unprompted Optimistic Relay Attack vulnerability class not in the human-written baseline spec; TLC execution <0.30 seconds. | - | April 14, 2026 |
| [**Sailor**](https://arxiv.org/abs/2604.06506) | SAILOR: fully automated symbolic execution pipeline for vulnerability discovery — static analysis identifies targets, LLM iteratively synthesizes harnesses (drivers/stubs/assertions) with compiler+SE feedback, symbolic execution detects bugs, replay validates. | 379 previously unknown memory-safety vulns (421 confirmed crashes) in 10 C/C++ projects, 6.8M LOC. | - | - |
| [**QRS**](https://arxiv.org/abs/2602.09774) | Neuro-Symbolic Triad: Query agent auto-synthesizes CodeQL queries; Review agent performs semantic reachability + data flow tracing; Sanitize agent prunes FPs. Inverts SAST from rule-filtering to rule-generation. | Enables autonomous vulnerability discovery without expert-crafted queries; high-confidence vuln reports. | - | - |
| [**Gordian**](https://arxiv.org/abs/2603.19239) | Hybrid symbolic execution: LLMs generate ghost code (inversions, surrogates, semantic partitions) to help SMT solver bypass solver-hostile fragments in KLEE. | 52–84% higher coverage vs traditional SE; 86–419% vs SOTA LLM-SE; 90–96% fewer tokens. | - | - |
| [**SAFuzz**](https://arxiv.org/abs/2602.11209) | Semantic-Guided Adaptive Fuzzing for LLM-Generated Code. | Strong recall with significant time savings for algorithmic vulnerability detection. | - | - |
| [**Coverage-Guided Harness Gen**](https://arxiv.org/abs/2603.08616) | Multi-Agent Harness Generation for Java Library Fuzzing. | +26% median method-targeted coverage over OSS-Fuzz baselines. | - | - |
| [**AutoBug (LLM-Powered Symbolic Execution)**](https://arxiv.org/abs/2505.13452) | Path-based decomposition with LLMs acting as approximate symbolic executors. | - | - | - |
| [**COTTONTAIL**](https://mboehme.github.io/paper/SP26-cottontail.pdf) | LLMs augment concolic execution for complex constraint solving. | LLMs handle symbolic reasoning over path constraints. | IEEE S&P 2026 | - |
| [**Agentic Neuro-Symbolic APR**](https://arxiv.org/abs/2507.18755) | Neuro-symbolic automated program repair at scale. | Uses static analysis + test execution feedback loops. | - | - |
