# Awesome SE Research Work

> A curated list of awesome software engineering research papers and resources.
> Specifically focused on LLMs for SE topic; agentic systems; software security: vulnerability detection, static analysis, neuro-symbolic execution; program testing and repair.

Each paper has an atomic note in [`papers/`](papers/) with its details. The README only lists papers by topic.

If you want to contribute, please read [this](CONTRIBUTING.md).

---
Table of Content:
- [Books](#Books)
- [Talks](#Talks)
- [Papers](#Papers)
    - [AI4SE](#ai4se)
        - [Code LM](#Code-LM)
        - [Agentic SE](#agentic-se)
    - [Software Understanding](#software-understanding)
        - [Program Understanding](#program-understanding)
        - [Code Review](#code-review)
        - [Architecture & Design](#architecture--design)
    - [Software Validation](#software-validation)
        - [Program Testing](#program-testing)
        - [Neuro-Symbolic](#neuro-symbolic)
        - [Fuzzing & Dynamic Analysis](#fuzzing--dynamic-analysis)
    - [Software Security](#software-security)
        - [Vulnerability Detection](#vulnerability-detection)
        - [Program Static Analysis](#program-static-analysis)
        - [Secure Software Generation](#secure-software-generation)
    - [Maintenance & Evolution](#maintenance--evolution)
        - [Program Repair](#program-repair)
        - [Refactoring & Migration](#refactoring--migration)
    - [Empirical SE & Benchmarks](#empirical-se--benchmarks)
        - [Benchmarks & Datasets](#benchmarks--datasets)
        - [Empirical Studies](#empirical-studies)

---
## Books
* 

## Talks
* 

## Papers

### LLMs for SE

#### Code LM

- [Agentic Code Optimization via Compiler-LLM Cooperation](papers/arxiv.2604.04238.md)
- [Aligning Requirement for Large Language Model's Code Generation](papers/arxiv.2509.01313.md)
- [Beyond pass@k: Redundancy-Aware RLVR for Multi-Sample Code Generation](papers/arxiv.2605.28022.md)
- [Bridging the Gap between User Intent and LLM: A Requirement Alignment Approach for Code Generation](papers/arxiv.2604.16198.md)
- [Can Large Language Models Recover Semantic Optimization Opportunities That Compilers Miss?](papers/arxiv.2608.03983.md)
- [DecompRL: Solving Harder Problems by Learning Modular Code Generation](papers/arxiv.2607.02390.md)
- [Do LLMs Favor Their Providers? Measuring Vertical Integration Bias in Code Generation](papers/arxiv.2605.28515.md)
- [Effective and Efficient Context Retrieval via Partial Dependency Graph for Repository-Level Code Generation](papers/arxiv.2608.01927.md)
- [Efficient and Scalable Provenance Tracking for LLM-Generated Code Snippets](papers/arxiv.2605.28510.md)
- [Extrapolative Weight Averaging Reveals Correctness-Efficiency Frontiers in Code RL](papers/arxiv.2605.28751.md)
- [Failure-Aware Enhancements for Large Language Model (LLM) Code Generation: An Empirical Study on Decision Framework](papers/arxiv.2602.02896.md)
- [FLARE: Fine-Grained Diagnostic Feedback for LLM Code Refinement](papers/arxiv.2606.03852.md)
- [From SWE-ZERO to SWE-HERO: Execution-free to Execution-based Fine-tuning for Software Engineering Agents](papers/arxiv.2604.01496.md)
- [Generative Compilation: On-the-Fly Compiler Feedback as AI Generates Code](papers/arxiv.2607.13921.md)
- [How Many Tries Does It Take? Iterative Self-Repair in LLM Code Generation Across Model Scales and Benchmarks](papers/arxiv.2604.10508.md)
- [KAT-Coder-V2.5 Technical Report](papers/arxiv.2607.05471.md)
- [Learning Reasoning World Models for Parallel Code](papers/arxiv.2604.20926.md)
- [ProjAgent: Procedural Similarity Retrieval for Repository-Level Code Generation](papers/arxiv.2607.08691.md)
- [SCOPE: Leveraging Subgoal Critiques for Code Generation](papers/arxiv.2607.05810.md)
- [SecureForge: Finding and Preventing Vulnerabilities in LLM-Generated Code via Prompt Optimization](papers/arxiv.2605.08382.md)
- [Self-Spec Verifiable Code Generation](papers/arxiv.2609.39568.md) <img height="20" src="img/new.png" alt="new">
- [Surgical Repair of Insecure Code Generation in LLMs](papers/arxiv.2604.16697.md)
- [Think Anywhere in Code Generation](papers/arxiv.2603.29957.md)
- [Toward Executable Repository-Level Code Generation via Environment Alignment](papers/arxiv.2604.03622.md)
- [Triage: Routing Software Engineering Tasks to Cost-Effective LLM Tiers via Code Quality Signals](papers/arxiv.2604.07494.md)
- [Unreliable in Practice? A Comprehensive Study of Errors in LLM-Generated Code](papers/arxiv.2608.00661.md)

#### Agentic SE

- [ABTest: Behavior-Driven Testing for AI Coding Agents](papers/arxiv.2604.03362.md)
- [Agent psychometrics: Task-level performance prediction in agentic coding benchmarks](papers/arxiv.2604.00594.md)
- [Agent-as-a-Router: Agentic Model Routing for Coding Tasks](papers/arxiv.2606.22902.md)
- [AgentFixer: From Failure Detection to Fix Recommendations in LLM Agentic Systems](papers/arxiv.2603.29848.md)
- [AgentForge: Execution-Grounded Multi-Agent LLM Framework for Autonomous Software Engineering](papers/arxiv.2604.13120.md)
- [Agentic Agile-V: From Vibe Coding to Verified Engineering in Software and Hardware Development](papers/arxiv.2605.20456.md)
- [Agentic AI Software Engineers: Programming with Trust](papers/arxiv.2502.13767.md)
- [Agentic Software: How AI Agents Are Restructuring the Software Paradigm](papers/arxiv.2606.05608.md)
- [Agon: An Autonomous Large-Scale Omnidisciplinary Research System Built on Prompt Economy](papers/arxiv.2606.24177.md)
- [AI Harness Engineering: A Runtime Substrate for Foundation-Model Software Agents](papers/arxiv.2605.13357.md)
- [Ambig-SWE: Interactive Agents to Overcome Underspecificity in Software Engineering](papers/arxiv.2502.13069.md)
- [An Agentic Evaluation Framework for AI-Generated Scientific Code in PETSc](papers/arxiv.2603.15976.md)
- [AOHP: An Open-Source OS-Level Agent Harness for Personalized, Efficient and Secure Interaction](papers/arxiv.2606.23449.md)
- [Argus: A General-Purpose Agentic Reasoning Runtime for Long-Horizon Tasks](papers/arxiv.2608.05144.md)
- [Auto: The AGI Compiler](papers/arxiv.2607.04542.md)
- [Benchmarks are Not Enough: RAMP for Runtime Assessing of Agentic Models in Production Systems](papers/arxiv.2605.27492.md)
- [Beyond Generalist LLMs: Specialist Agentic Systems for Structured Code Workflow Execution](papers/arxiv.2607.14456.md)
- [Beyond Human-Readable: Rethinking Software Engineering Conventions for the Agentic Development Era](papers/arxiv.2604.07502.md)
- [CodeTracer: Towards Traceable Agent States](papers/arxiv.2604.11641.md)
- [Codified Context: Infrastructure for AI Agents in a Complex Codebase](papers/arxiv.2602.20478.md)
- [DeepSWE: Measuring Frontier Coding Agents on Original, Long-Horizon Engineering Tasks](papers/arxiv.2607.07946.md)
- [DeltaMCP: Incremental Regeneration via Spec-Aware Transformation for MCP servers](papers/arxiv.2605.28148.md)
- [Don't Blame the Large Language Model: How Agent Harness Evolution Shapes Coding Agent Quality](papers/arxiv.2607.03691.md)
- [EA-Graph: Artifact-Anchored Verification Memory for Coding Agents under Upstream Drift](papers/arxiv.2608.04278.md)
- [Engineering Reliable Coding Agents: Evaluating and Operating the System Around the Model](papers/arxiv.2608.13867.md)
- [EvoAgent: An Evolvable Agent Framework with Skill Learning and Multi-Agent Delegation](papers/arxiv.2604.20133.md)
- [From Failed Trajectories to Reliable LLM Agents: Diagnosing and Repairing Harness Flaws](papers/arxiv.2606.06324.md)
- [Harness Handbook: Making Evolving Agent Harnesses Readable,Navigable, and Editable](papers/arxiv.2607.13285.md)
- [Inside the Scaffold: A Source-Code Taxonomy of Coding Agent Architectures](papers/arxiv.2604.03515.md)
- [LACUNA: Safe Agents as Recursive Program Holes](papers/arxiv.2605.28617.md)
- [Learning When and How to Intervene: A Hindsight-Distilled Sentinel for Coding Agents](papers/arxiv.2609.39957.md) <img height="20" src="img/new.png" alt="new">
- [Learning When to Optimize: Verified Optimization Skills from Expert GPU-Kernel Lineages](papers/arxiv.2605.28213.md)
- [LLM-as-Code: Agentic Programming for Agent Harness](papers/arxiv.2606.15874.md)
- [Near-Miss: Latent Policy Failure Detection in Agentic Workflows](papers/arxiv.2603.29665.md)
- [Ouroboros: A Self-Developing Frontier Coding Agent with Reviewed Core Evolution](papers/arxiv.2608.08311.md)
- [PROJECTMEM: A Local-First, Event-Sourced Memory and Judgment Layer for AI Coding Agents](papers/arxiv.2606.12329.md)
- [Reasoning effort, not tool access, buys first-try reliability in agentic code generation: an observational study](papers/arxiv.2607.02436.md)
- [RefactorAssist: Agentic Refinement for Reliable Code Refactoring](papers/arxiv.2608.00924.md)
- [Rethinking the Value of Agent-Generated Tests for LLM-Based Software Engineering Agents](papers/arxiv.2602.07900.md)
- [SafeAgent: A Runtime Protection Architecture for Agentic Systems](papers/arxiv.2604.17562.md)
- [Self-Evolving Coding Agents](papers/arxiv.2608.03392.md)
- [SNARE: Adaptive Scenario Synthesis for Eliciting Overeager Behavior in Coding Agents](papers/arxiv.2605.28122.md)
- [Socratic-SWE: Self-Evolving Coding Agents via Trace-Derived Agent Skills](papers/arxiv.2606.07412.md)
- [Specification-first convergence with an AI coding agent: a case study of dismantling a core architectural invariant across 189 files in a 717k-line codebase with no test oracle and no human code review](papers/arxiv.2608.12440.md)
- [SPOQ: Specialist Orchestrated Queuing for Multi-Agent Software Engineering](papers/arxiv.2606.03115.md)
- [Steerability via constraints: a substrate for scalable oversight of coding agents](papers/arxiv.2607.02389.md)
- [TDAD: Test-Driven Agentic Development - Reducing Code Regressions in AI Coding Agents via Graph-Based Impact Analysis](papers/arxiv.2603.17973.md)
- [The Harness Effect: How Orchestration Design Sets the Token Economics of Enterprise Agentic AI](papers/arxiv.2607.06906.md)
- [The Semi-Executable Stack: Agentic Software Engineering and the Expanding Scope of SE](papers/arxiv.2604.15468.md)
- [Tool Forge: A Validation-Carrying Toolchain for Governed Agentic Execution](papers/arxiv.2605.28000.md)
- [TraceCoder: A Trace-Driven Multi-Agent Framework for Automated Debugging of LLM-Generated Code](papers/arxiv.2602.06875.md)
- [TraceDev: A Traceability-Driven Multi-agent Framework for Requirement-to-Code Development](papers/arxiv.2607.18886.md)
- [TTHE: Test-Time Harness Evolution](papers/arxiv.2607.08124.md)

### Software Understanding

#### Program Understanding

- [An Empirical Analysis of Static Analysis Methods for Detection and Mitigation of Code Library Hallucinations](papers/arxiv.2604.07755.md)
- [Analyzing Chain of Thought (CoT) Approaches in Control Flow Code Deobfuscation Tasks](papers/arxiv.2604.15390.md)
- [Bridging Code Property Graphs and Language Models for Program Analysis](papers/arxiv.2603.24837.md)
- [Can LLMs Deobfuscate Binary Code? A Systematic Analysis of Large Language Models into Pseudocode Deobfuscation](papers/arxiv.2604.08083.md)
- [Challenges and Future Directions in Agentic Reverse Engineering Systems](papers/arxiv.2604.14317.md)
- [E-Path: Equality Saturation for Control-Flow Graphs](papers/arxiv.2605.28694.md)

#### Code Review

- [A Survey of Code Review Benchmarks and Evaluation Practices in Pre-LLM and LLM Era](papers/arxiv.2602.13377.md)

#### Architecture & Design


### Software Validation

#### Program Testing

- [An empirical study of LoRA-based fine-tuning of large language models for automated test case generation](papers/arxiv.2604.06946.md)
- [An Iterative Test-and-Repair Framework for Competitive Code Generation](papers/arxiv.2604.05560.md)
- [Context Matters: Improving the Practical Reliability of LLM-Based Unit Test Generation](papers/arxiv.2607.19682.md)
- [DiffTestGen: Change-Directed LLM-Based Testing for Exposing Behavioral Differences](papers/arxiv.2607.16024.md)
- [Evaluating LLM-Based Test Generation Under Software Evolution](papers/arxiv.2603.23443.md)
- [From Exploration to Specification: LLM-Based Property Generation for Mobile App Testing](papers/arxiv.2604.13463.md)
- [Grounding AI Agents in Contracts: An Empirical Evaluation of Spec-Driven Test Generation](papers/arxiv.2608.17177.md)
- [LLM Test Generation via Iterative Hybrid Program Analysis](papers/arxiv.2503.13580.md)
- [LLMs taking shortcuts in test generation: A study with SAP HANA and LevelDB](papers/arxiv.2604.14437.md)
- [LogicHunter: Testing LLM Agent Frameworks with an Agentic Oracle](papers/arxiv.2607.06195.md)
- [Mining Workflow Graphs for Black-Box Boundary Testing of Conversational LLM Agents](papers/arxiv.2607.06873.md)
- [MIST-RL: Mutation-based Incremental Suite Testing via Reinforcement Learning](papers/arxiv.2603.01409.md)
- [Multi-Agent LLM-based Metamorphic Testing for REST APIs](papers/arxiv.2605.28321.md)
- [Names Are All You Need: Effective and Safe Regression Test Selection for Python](papers/arxiv.2605.25356.md)
- [NEUROTESTGEN: Neuro-Symbolic Guided Test Generation with Large Language Models](papers/arxiv.2609.30178.md) <img height="20" src="img/new.png" alt="new">
- [OptiLoop: Coordination-in-the-Loop Verification and Repair for LLM-Generated Optimization Agents](papers/arxiv.2605.27630.md)
- [SPARC: Scenario Planning and Reasoning for Automated C Unit Test Generation](papers/arxiv.2602.16671.md)
- [Specification Grounding Drives Test Effectiveness for LLM Code](papers/arxiv.2607.06636.md)
- [TDD-Agent: Test-Driven Reasoning for Code Generation](papers/arxiv.2608.16742.md)
- [TestEvo-Bench: An Executable and Live Benchmark for Test and Code Co-Evolution](papers/arxiv.2607.02469.md)

#### Neuro-Symbolic

- [Agentic Planning for Symbolic Execution](papers/arxiv.2608.06397.md)
- [Agentic Program Repair from Test Failures at Scale: A Neuro-symbolic approach with static analysis and test execution feedback](papers/arxiv.2507.18755.md)
- [Agentic Proving for Program Verification](papers/arxiv.2605.23772.md)
- [Agentic Separation Logic Specification Synthesis](papers/arxiv.2605.27531.md)
- [AgentLTL: A Trace-Verification Framework for Measuring, Enforcing, and Training Procedural Compliance in Tool-Using LLM Agents](papers/arxiv.2607.02599.md)
- [COBALT-TLA: A Neuro-Symbolic Verification Loop for Cross-Chain Bridge Vulnerability Discovery](papers/arxiv.2604.12172.md)
- [COTTONTAIL](papers/sp26-cottontail.md)
- [Defusing Logic Bombs in Symbolic Execution with LLM-Generated Ghost Code](papers/arxiv.2603.19239.md)
- [Finding Missing Input Validation in TEEs via LLM-Assisted Symbolic Execution](papers/arxiv.2605.22058.md)
- [Guiding Symbolic Execution with Static Analysis and LLMs for Vulnerability Discovery](papers/arxiv.2604.06506.md)
- [Harnessing Code Agents for Automatic Software Verification](papers/arxiv.2607.06341.md)
- [Inverting the Shield: Systematically Generating Safety Tests from Policy Specifications](papers/arxiv.2605.24883.md)
- [Large Language Model Powered Symbolic Execution](papers/arxiv.2505.13452.md)
- [Locus: Agentic Predicate Synthesis for Directed Fuzzing](papers/arxiv.2508.21302.md)
- [Neuro-Symbolic Proof-of-Vulnerability Generation with Open-Weight Models](papers/arxiv.2608.04217.md)
- [Neuro-Symbolic Reasoning for Vulnerability Detection](papers/arxiv.2607.03963.md)
- [QRS: A Rule-Synthesizing Neuro-Symbolic Triad for Autonomous Vulnerability Discovery](papers/arxiv.2602.09774.md)
- [Schwarz: Solver-Aware Agentic Program Verification](papers/arxiv.2608.30803.md)
- [Symbolon: Symbolic Execution by Learning Code Transformation](papers/arxiv.2606.29108.md)

#### Fuzzing & Dynamic Analysis

- [Coverage-Guided Multi-Agent Harness Generation for Java Library Fuzzing](papers/arxiv.2603.08616.md)
- [Directed Neuro-Symbolic Stochastic Execution for Verification of Distributed Parallel AI Programs](papers/arxiv.2608.07947.md)
- [FLARE: Agentic Coverage-Guided Fuzzing for LLM-Based Multi-Agent Systems](papers/arxiv.2604.05289.md)
- [Lie to Me: Finding Bugs in ZK DSL Toolchains with Adversarial Witness Injection](papers/arxiv.2608.30648.md)
- [SAFuzz: Semantic-Guided Adaptive Fuzzing for LLM-Generated Code](papers/arxiv.2602.11209.md)
- [SeedSmith: LLM-Driven Seed Synthesis for Directed Fuzzing](papers/arxiv.2607.08949.md)
- [SpecTrum: Specification-Guided Differential Fuzzing for Ethereum Consensus Clients](papers/arxiv.2608.17738.md)
- [Synthesizing Multi-Agent Harnesses for Vulnerability Discovery](papers/arxiv.2604.20801.md)
- [Thinking More, Harnessing Better: State Machine Guided Harness Automatic Generation with Project Digestion and Workflow Decomposition](papers/arxiv.2607.07007.md)

### Software Security

#### Vulnerability Detection

- [A Multi-Agent Framework for Automated Exploit Generation with Constraint-Guided Comprehension and Reflection](papers/arxiv.2604.05130.md)
- [AgentGuard: An Attribute-Based Access Control Framework for Tool-Use LLM-Based Agent](papers/arxiv.2605.28071.md)
- [Aletheia: Permission-Minimality Testing for Coding-Agent Rules](papers/arxiv.2609.39678.md) <img height="20" src="img/new.png" alt="new">
- [AnyPoC: Universal Proof-of-Concept Test Generation for Scalable LLM-Based Bug Detection](papers/arxiv.2604.11950.md)
- [Argus: Reorchestrating Static Analysis via a Multi-Agent Ensemble for Full-Chain Security Vulnerability Detection](papers/arxiv.2604.06633.md)
- [AutoEG: Exploiting Known Third-Party Vulnerabilities in Black-Box Web Applications](papers/arxiv.2604.00704.md)
- [AutoTrace: From Patches to Triggers via Agentic Interprocedural Exploration](papers/arxiv.2607.12058.md)
- [Beyond Function-Level Analysis: Context-Aware Reasoning for Inter-Procedural Vulnerability Detection](papers/arxiv.2602.06751.md)
- [Broken by Default: A Formal Verification Study of Security Vulnerabilities in AI-Generated Code](papers/arxiv.2604.05292.md)
- [Bulkhead: Automated Semantic Detection and Remediation of Container Escape Vulnerabilities](papers/arxiv.2607.12723.md)
- [Code-Augur: Agentic Vulnerability Detection via Specification Inference](papers/arxiv.2606.18619.md)
- [Detect Repair Verify for Securing LLM Generated Code: A Multi-Language Empirical Study](papers/arxiv.2603.00897.md)
- [Detect--Repair--Verify for LLM-Generated Code: A Multi-Language, Multi-Granularity Empirical Study](papers/arxiv.2603.23633.md)
- [Efficient Software Vulnerability Detection Using Transformer-based Models](papers/arxiv.2604.00112.md)
- [EvoRepair: Enhancing Vulnerability Repair Agents Through Experience-Based Self-Evolution](papers/arxiv.2605.30105.md)
- [False Security Confidence in Benign LLM Code Generation](papers/arxiv.2604.17014.md)
- [Graph Is the Verifier: Agentic Reinforcement Learning for Interprocedural Vulnerability Detection](papers/arxiv.2607.26656.md)
- [MIRAGE: Context-Aware Prompt Injection against Mobile GUI Agents via User-Generated Content](papers/arxiv.2605.28116.md)
- [Multi-Agent Taint Specification Extraction for Vulnerability Detection](papers/arxiv.2601.10865.md)
- [NeuroLog: Reasoning You Can Audit -- Neuro-Symbolic Vulnerability Discovery via LLM Facts, Datalog, and SMT](papers/arxiv.2606.00669.md)
- [OpenAnt: LLM-Powered Vulnerability Discovery Through Code Decomposition, Adversarial Verification, and Dynamic Testing](papers/arxiv.2606.19149.md)
- [Program Analysis Guided LLM Agent for Proof-of-Concept Generation](papers/arxiv.2604.07624.md)
- [RAVEN: Retrieval-Augmented Vulnerability Exploration Network for Memory Corruption Analysis in User Code and Binary Programs](papers/arxiv.2604.17948.md)
- [Revelio: Cost-Efficient Agentic Memory Safety Vulnerability Detection For Repository-Scale Codebases](papers/arxiv.2606.22263.md)
- [RustMizan: A Compilable, Contamination-Aware Benchmarking Framework for Rust Vulnerabilities](papers/arxiv.2607.04729.md)
- [Sandlock: Confining AI Agent Code with Unprivileged Linux Primitives](papers/arxiv.2605.26298.md)
- [Strategic Heterogeneous Multi-Agent Architecture for Cost-Effective Code Vulnerability Detection](papers/arxiv.2604.21282.md)
- [Supply-Chain Poisoning Attacks Against LLM Coding Agent Skill Ecosystems](papers/arxiv.2604.03081.md)
- [Toward Scalable Automated Repository-Level Datasets for Software Vulnerability Detection](papers/arxiv.2603.17974.md)
- [Tug-of-War within A Decade: Conflict Resolution in Vulnerability Analysis via Teacher-Guided Retrieval-Augmented Generations](papers/arxiv.2604.14172.md)
- [VCAO: Verifier-Centered Agentic Orchestration for Strategic OS Vulnerability Discovery](papers/arxiv.2604.08291.md)
- [VibeGuard: A Security Gate Framework for AI-Generated Code](papers/arxiv.2604.01052.md)
- [VulnAgent-R2: Evidence-Calibrated Multi-Agent Auditing for Repository-Level Vulnerability Detection](papers/arxiv.2603.13384.md)
- [VulnGym: Benchmarking Coding Agents for Repository-Level Vulnerability Detection](papers/arxiv.2608.02001.md)
- [When Context Gets Root: Privilege Escalation in LLM Harnesses](papers/arxiv.2608.27299.md)
- [When Labels Are Scarce: A Systematic Mapping of Label-Efficient Code Vulnerability Detection](papers/arxiv.2604.00079.md)
- [Your Agent Is Mine: Measuring Malicious Intermediary Attacks on the LLM Supply Chain](papers/arxiv.2604.08407.md)

#### Program Static Analysis

- [AFGNN: API Misuse Detection using Graph Neural Networks and Clustering](papers/arxiv.2604.07891.md)
- [Detecting Call Graph Unsoundness without Ground Truth](papers/arxiv.2604.00885.md)
- [Filament: Denning-Style Information Flow Control for Rust](papers/arxiv.2604.14357.md)
- [NESA: Relational Neuro-Symbolic Static Program Analysis](papers/arxiv.2412.14399.md)
- [Phoenix: A Modular and Versatile Framework for C/C++ Pointer Analysis](papers/arxiv.2602.01720.md)
- [PyFlow: An Inter-procedural Static Analysis Framework for Python](papers/arxiv.2608.07026.md)
- [Squeezing Juicy Variant Bugs Out of Modern Browsers](papers/usenix.2608.zhengSqueezingJuicyVariant.md)
- [Static Detection of Post-Quantum Cryptographic Algorithms in Stripped Binaries for Digital Forensic Examination and Migration Assurance](papers/arxiv.2608.25122.md)

#### Secure Software Generation

- [Enhancing Reliability in LLM-Based Secure Code Generation](papers/arxiv.2605.24300.md)

### Maintenance & Evolution

#### Program Repair

- [A Study on the Impact of Fault localization Granularity for Repository-Scale Code Repair Tasks](papers/arxiv.2604.00167.md)
- [A Systematic Study of LLM-Based Architectures for Automated Patching](papers/arxiv.2603.01257.md)
- [AgenticRepair: Multi-Faceted Program Context Engineering for Agentic Vulnerability Repair](papers/arxiv.2607.29422.md)
- [Automated Repair of TEE Partitioning Issues via DSL-Guided and LLM-Assisted Patching](papers/arxiv.2605.22087.md)
- [Bug Report Specification Refinement with Trajectory Guidance for Automated Program Repair](papers/arxiv.2607.07882.md)
- [DebugRepair: Enhancing LLM-Based Automated Program Repair via Self-Directed Debugging](papers/arxiv.2604.19305.md)
- [EviACT: An Evidence-to-Action Framework for Agentic Program Repair](papers/arxiv.2605.27238.md)
- [Formal-Method-Guided Vibe Coding: Closing the Verification Loop on AI-Generated Safety-Critical Software Through Model-Driven Engineering](papers/arxiv.2606.22413.md)
- [From Guessing to Seeing: Enhancing LLM-Based Program Repair via Trace-Guided Multi-strategy Debate](papers/arxiv.2604.02647.md)
- [GALA: Multimodal Graph Alignment for Bug Localization in Automated Program Repair](papers/arxiv.2604.08089.md)
- [Knowledge-Enhanced Agentic Vulnerability Repair](papers/arxiv.2607.00820.md)
- [LLM4C2Rust: Large Language Models for Automated Memory-Safe Code Transpilation](papers/arxiv.2604.15485.md)
- [Mitigating Implicit Inconsistencies in Patch Porting](papers/arxiv.2604.01680.md)
- [PatchRecall: Patch-Driven Retrieval for Automated Program Repair](papers/arxiv.2604.10481.md)
- [RAVEN: Agentic RAG for Automated Vulnerability Repair](papers/arxiv.2606.22647.md)
- [SCPatcher: Automated Smart Contract Code Repair via Retrieval-Augmented Generation and Knowledge Graph](papers/arxiv.2604.00687.md)
- [SHERLOC: Structured Diagnostic Localization for Code Repair Agents](papers/arxiv.2606.24820.md)
- [SYNTHFIX: Adaptive Neuro-Symbolic Vulnerability Repair](papers/synthfix.md)
- [Trustworthy Runtime Error Healing in Real-World Repositories: A Benchmark and Guardrail](papers/arxiv.2609.39086.md) <img height="20" src="img/new.png" alt="new">
- [VulKey: Automated Vulnerability Repair Guided by Domain-Specific Repair Patterns](papers/arxiv.2605.01769.md)
- [What's in a Benchmark? The Case of SWE-Bench in Automated Program Repair](papers/arxiv.2602.04449.md)
- [Why LLMs Fail: A Failure Analysis and Partial Success Measurement for Automated Security Patch Generation](papers/arxiv.2603.10072.md)

#### Refactoring & Migration

- ["Refactoring Runaway": Understanding and Mitigating Tangled Refactorings in Coding Agents for Issue Resolution](papers/arxiv.2605.22526.md)
- [Update from Hell: Can Coding Agents Survive Hidden Breakage in Dependency Upgrades?](papers/arxiv.2608.30300.md)

#### Technical Debt & Evolution


### Requirements & Process

#### Requirements Engineering


#### Software Process & Methods


#### Human Factors & Productivity


### Empirical SE & Benchmarks

#### Benchmarks & Datasets

- [Beyond Task Completion: A Verification-vs.-Conformance Gap in Tool-Evolving Agents](papers/arxiv.2604.00392.md)
- [Can Coding Agents Implement Missed Compiler Optimizations? Evaluating LLM Agents on LLVM Peephole Optimizations](papers/arxiv.2607.02684.md)
- [Code Review Agent Benchmark](papers/arxiv.2603.23448.md)
- [CodeSpecBench: Benchmarking LLMs for Executable Behavioral Specification Generation](papers/arxiv.2604.12268.md)
- [Dialogue SWE-Bench: A Benchmark for Dialogue-Driven Coding Agents](papers/arxiv.2606.13995.md)
- [Evaluating LLM-Based 0-to-1 Software Generation in End-to-End CLI Tool Scenarios](papers/arxiv.2604.06742.md)
- [FeatureBench: Benchmarking Agentic Coding for Complex Feature Development](papers/arxiv.2602.10975.md)
- [FuzzingBrain V2: A Multi-Agent LLM System for Automated Vulnerability Discovery and Reproduction](papers/arxiv.2605.21779.md)
- [GraphAlignCoder: Aligning Program and Proof Graphs for Code Generation](papers/arxiv.2608.11394.md)
- [InCoder-32B: Code Foundation Model for Industrial Scenarios](papers/arxiv.2603.16790.md)
- [IndustryCode: A Benchmark for Industry Code Generation](papers/arxiv.2604.02729.md)
- [OctoLong: Mid-Training On Cross-Repository Code Contexts Enhances Long-Context Modeling](papers/arxiv.2608.05141.md)
- [ProgramBench: Can Language Models Rebuild Programs From Scratch?](papers/arxiv.2605.03546.md)
- [RealSWE: A Compositional Evaluation of Coding Agents under Realistic User Requests](papers/arxiv.2608.27831.md)
- [RealVuln: Benchmarking Rule-Based, General-Purpose LLM, and Security-Specialized Scanners on Real-World Code](papers/arxiv.2604.13764.md)
- [Repo0: Design-Driven Zero-to-All Code Generation](papers/arxiv.2608.19854.md)
- [SaaSBench: Exploring the Boundaries of Coding Agents in Long-Horizon Enterprise SaaS Engineering](papers/arxiv.2605.17526.md)
- [StaminaBench: Stress-Testing Coding Agents over 100 Interaction Turns](papers/arxiv.2606.19613.md)
- [SWE-INTERACT: Reimagining SWE Benchmarks as User-Driven Long-Horizon Coding Sessions](papers/arxiv.2606.30573.md)
- [Toponium effects on quantum steering and Bell nonlocality of top quarks](papers/arxiv.2606.30768.md)
- [TRACE: Temporal Relationship-Aware Conversational Entrainment Detection in Dyadic Speech](papers/arxiv.2606.30543.md)
- [Vul4Py: Benchmarking Automated Vulnerability Repair in Python with Paired Exploit and Functional Oracles](papers/arxiv.2608.00692.md)
- [VulContextBench: A Benchmark for Security Context Retrieval in Coding Agents](papers/arxiv.2609.32601.md) <img height="20" src="img/new.png" alt="new">

#### Empirical Studies

- [A Large-Scale Comprehensive Measurement of AI-Generated Code in Real-World Repositories](papers/arxiv.2603.27130.md)
- [Beyond Resolution Rates: Behavioral Drivers of Coding Agent Success and Failure](papers/arxiv.2604.02547.md)
- [Code as a Weapon: A Consensus-Labeled Prompt Bank for Measuring Coding-Model Compliance with Malicious-Code Requests](papers/arxiv.2605.28734.md)
- [LLM-Enabled Open-Source Systems in the Wild: An Empirical Study of Vulnerabilities in GitHub Security Advisories](papers/arxiv.2604.04288.md)
- [SWE-chat: Coding Agent Interactions From Real Users in the Wild](papers/arxiv.2604.20779.md)
- [Technical Report: Exploring the Emerging Threats of the Agent Skill Ecosystem](papers/arxiv.2605.28588.md)
- [Trajectory-Level Security Debt in LLM Coding Agents](papers/arxiv.2609.35199.md) <img height="20" src="img/new.png" alt="new">
- [Understanding Bugs in Modern Agentic Frameworks: A Study of Symptoms, Root Causes, and Triggering Conditions](papers/arxiv.2604.08906.md)
- [Where Agent Frameworks Fall Short: Examining Functional Challenges and Usability Concerns](papers/arxiv.2602.21806.md)
