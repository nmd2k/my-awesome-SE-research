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

## LLM & Code LM

| Paper | ArXiv / Link | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **InCoder-32B** | [2603.16790](https://arxiv.org/abs/2603.16790) | Code Foundation Model for Industrial Scenarios. | SOTA on 9 industrial benchmarks across 4 specialized domains. | - | - |
| **IndustryCode** | [2604.02729](https://arxiv.org/abs/2604.02729) | A Benchmark for Industry Code Generation. | Top model (Claude 4.5 Opus) scores 68.1% on sub-problems. | - | - |
| **FeatureBench** | [2602.10975](https://arxiv.org/abs/2602.10975) | Benchmarking Agentic Coding for Complex Feature Development. | Exposing a dramatic capability gap on real feature work (Claude 4.5 Opus 11.0%). | ICLR 2026 | - |
| **Code Review Agent Benchmark (c-CRAB)** | [2603.23448](https://arxiv.org/abs/2603.23448) | Standardized benchmark for evaluating AI-based code review agents on realistic PRs. | Enables apples-to-apples comparison across agent frameworks. | - | - |
| **Failure-Aware Enhancements for LLM Code Generation** | [2602.02896](https://arxiv.org/abs/2602.02896) | Progressive prompting study across 25 GitHub projects. | Hits 96.9% task completion vs 80.5% direct prompting. | - | - |

## Agent/Agentic System for SE

| Paper | ArXiv / Link | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **Codified Context** | [2602.20478](https://arxiv.org/abs/2602.20478) | Infrastructure for AI Agents in a Complex Codebase. | 3-component persistent memory infra across 283 dev sessions. | - | - |
| **Bugs in LLM Agent Frameworks** | [2602.21806](https://arxiv.org/abs/2602.21806) | Analysis of framework-level bugs in LangChain/CrewAI. | 998 bug reports → 15 root causes & 7 symptoms. | - | - |
| **TraceCoder** | [2602.06875](https://arxiv.org/abs/2602.06875) | A Trace-Driven Multi-Agent Framework for Automated Debugging. | Outperforms baselines on Pass@1 accuracy; reduces redundant repairs. | ICSE 2026 | - |
| **TDAD** | [2603.17973](https://arxiv.org/abs/2603.17973) | Test-Driven Agentic Development via pre-change AST-based impact analysis. | 70% regression reduction (6.08% → 1.82%) on SWE-bench Verified. | - | - |
| **ABTest** | [2604.03362](https://arxiv.org/abs/2604.03362) | Behavior-Driven Testing for AI Coding Agents under adversarial usage. | Detected 1,573 behavioral anomalies across 3 coding-agent families. | - | - |
| **Agentic AI Software Engineers: Programming with Trust** | [2502.13767](https://arxiv.org/abs/2502.13767) | Trust taxonomy + safety constraints for autonomous coding agents. | Guidelines for responsible deployment. | - | - |
| **FLARE** | [2604.05289](https://arxiv.org/abs/2604.05289) | Agentic Coverage-Guided Fuzzing for LLM-Based Multi-Agent Systems. | 96.9% inter-agent coverage, 91.1% intra-agent coverage. | - | - |

## Vulnerability Detection & Fixing

| Paper | ArXiv / Link | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **CPRVul** | [2602.06751](https://arxiv.org/abs/2602.06751) | Context-Aware Reasoning for Inter-Procedural Vulnerability Detection. | Inter-procedural CPG context + structured reasoning: +22.9% on PrimeVul. | - | - |
| **Efficient Vuln Detection via Transformers** | [2604.00112](https://arxiv.org/abs/2604.00112) | Study of program slice representations for C/C++ vulnerability detection. | Transformer on program slices beats GNN baselines on C/C++. | - | - |
| **When Labels Are Scarce** | [2604.00079](https://arxiv.org/abs/2604.00079) | Label-Efficient Code Vulnerability Detection survey. | First systematic mapping of 5 label-efficient vuln detection paradigms. | - | - |
| **PAGENT** | [2604.07624](https://arxiv.org/abs/2604.07624) | Program Analysis Guided LLM Agent for PoC Generation. | Static+dynamic analysis guided PoC generation: +132% vs prior SOTA. | - | - |
| **VulnSage** | [2604.05130](https://arxiv.org/abs/2604.05130) | Multi-Agent Framework for Automated Exploit Generation on npm. | 53.47% exploit rate on SecBench.js; 146 real zero-days found. | ICPC 2026 | - |
| **AutoEG** | [2604.00704](https://arxiv.org/abs/2604.00704) | Exploiting Known Third-Party Vulnerabilities in Black-Box Web Apps. | 82.41% black-box web exploit success vs 32.88% SOTA. | - | - |
| **Argus** | [2604.06633](https://arxiv.org/abs/2604.06633) | Multi-Agent Ensemble for Full-Chain Vulnerability Detection. | Reduces FP and hallucination rate; LLM-centered SAST workflow. | - | - |
| **SemTaint** | [2601.10865](https://arxiv.org/abs/2601.10865) | Multi-Agent Taint Specification Extraction for JavaScript. | Detected 106 vulnerabilities previously undetectable by CodeQL alone. | - | - |
| **Detect–Repair–Verify (DRV) v1** | [2603.00897](https://arxiv.org/abs/2603.00897) | Securing LLM-Generated Code. | Project-level DRV benchmark for LLM-generated code security. | - | - |
| **DRV Multi-Granularity** | [2603.23633](https://arxiv.org/abs/2603.23633) | Extension of DRV to finer-grained multi-language settings. | Multi-language × multi-granularity DRV evaluation. | - | - |
| **VulnAgent-X** | [2603.13384](https://arxiv.org/abs/2603.13384) | Layered agentic pipeline for vulnerability detection. | Best F1/AUROC on PrimeVul. | - | - |

## Program Repair & Program Testing

| Paper | ArXiv / Link | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **GALA** | [2604.08089](https://arxiv.org/abs/2604.08089) | Multimodal Graph Alignment for Bug Localization in APR. | Multimodal APR via UI Graph → structural code alignment; SoTA on SWE-bench Multimodal. | - | - |
| **FL Granularity Study** | [2604.00167](https://arxiv.org/abs/2604.00167) | Impact of Fault Localization Granularity for Repository-Scale Code Repair. | Function-level generally best for repo-scale repair, but task-dependent. | - | - |
| **SCPatcher** | [2604.00687](https://arxiv.org/abs/2604.00687) | Smart Contract Code Repair via RAG and Knowledge Graph. | RAG+KG for smart contract repair: CPR 90%, ERR 81.7%, ORR 73.5%. | - | - |
| **TraceRepair** | [2604.02647](https://arxiv.org/abs/2604.02647) | Runtime Execution Traces + Multi-Agent Debate for APR. | Correctly fixes 392 defects on Defects4J. | - | - |
| **Why LLMs Fail in Sec Patching** | [2603.10072](https://arxiv.org/abs/2603.10072) | Failure Analysis for Automated Security Patch Generation. | Tri-axis evaluation of LLM patch generation correctness vs security vs functionality. | - | - |
| **LLM-Based Architectures for Automated Patching** | [2603.01257](https://arxiv.org/abs/2603.01257) | Systematic study of LLM architecture choices for security patching. | Identifies architectural patterns that reliably improve patching. | - | - |
| **SWE-Bench Validity Study** | [2602.04449](https://arxiv.org/abs/2602.04449) | The Case of SWE-Bench in Automated Program Repair. | Raises benchmark contamination and fair-comparison concerns. | - | - |

## Static Analysis, Program Understanding, CPG, CFG & DFG

| Paper | ArXiv / Link | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **Static Analysis for Library Hallucinations** | [2604.07755](https://arxiv.org/abs/2604.07755) | Static Analysis Methods for Code Library Hallucinations. | 14–85% LLM hallucination catch rate; upper bound ~77%. | - | - |
| **Call Graph Unsoundness** | [2604.00885](https://arxiv.org/abs/2604.00885) | Detecting Call Graph Unsoundness without Ground Truth. | Precision partial orders break in Soot/SootUp/WALA/Doop due to lambdas/reflection. | - | - |
| **CodeBadger** | [2603.24837](https://arxiv.org/abs/2603.24837) | Bridging Code Property Graphs and LMs for Program Analysis. | Joern CPG + LLM for slicing, taint tracking, data flow, call graph. | - | - |
| **Phoenix** | [2602.01720](https://arxiv.org/abs/2602.01720) | Modular & Versatile C/C++ Pointer Analysis. | Flexible, configurable static analysis infrastructure. | - | - |
| **LLMSA** | [2412.14399](https://arxiv.org/abs/2412.14399) | Compilation-free static analysis via Datalog + LLM neural relations. | - | - | - |

## (Neuro) Symbolic Execution & Fuzzing

| Paper | ArXiv / Link | Brief Summary | Key Result | Conf / Journal | Insights / Data |
| :--- | :---: | :--- | :--- | :---: | :--- |
| **SAFuzz** | [2602.11209](https://arxiv.org/abs/2602.11209) | Semantic-Guided Adaptive Fuzzing for LLM-Generated Code. | Strong recall with significant time savings for algorithmic vulnerability detection. | - | - |
| **Coverage-Guided Harness Gen** | [2603.08616](https://arxiv.org/abs/2603.08616) | Multi-Agent Harness Generation for Java Library Fuzzing. | +26% median method-targeted coverage over OSS-Fuzz baselines. | - | - |
| **AutoBug (LLM-Powered Symbolic Execution)** | [2505.13452](https://arxiv.org/abs/2505.13452) | Path-based decomposition with LLMs acting as approximate symbolic executors. | - | - | - |
| **COTTONTAIL** | [PDF](https://mboehme.github.io/paper/SP26-cottontail.pdf) | LLMs augment concolic execution for complex constraint solving. | LLMs handle symbolic reasoning over path constraints. | IEEE S&P 2026 | - |
| **Agentic Neuro-Symbolic APR** | [2507.18755](https://arxiv.org/abs/2507.18755) | Neuro-symbolic automated program repair at scale. | Uses static analysis + test execution feedback loops. | - | - |
