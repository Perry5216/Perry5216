# Anthony Perry

<a href="https://github.com/Perry5216">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=06B6D4&background=00000000&center=false&vCenter=true&width=750&lines=Autonomous+Systems+%26+Applied+AI+Engineer;Asymmetric+Tandem%3A+Spark+Cluster+%2B+RTX+5090+Blackwell;Zero+'Green+When+Untrue'+Verification+Pipelines;Native+C%2B%2B20+Simulation+Engines+%26+Compilers;PCIe+DMA+Hardware+Memory+Introspection" alt="Typing SVG" />
</a>

**London, UK** · [LinkedIn](https://www.linkedin.com/in/anthony-perry-33b7a01a0/) · [GitHub](https://github.com/Perry5216) · [Portfolio Harness](https://github.com/Perry5216/autonomous-ai-engineering-harness)

<p>
  <img src="https://img.shields.io/badge/Hardware-NVIDIA_RTX_5090_Blackwell_(32GB_GDDR7)-76B900?style=for-the-badge&logo=nvidia" alt="RTX 5090" />
  <img src="https://img.shields.io/badge/Inference-205--303_tok%2Fs_Sustained-orange?style=for-the-badge" alt="205-303 tok/s" />
  <img src="https://img.shields.io/badge/Quantization-IQ2_XS_(18.5k_VRAM_Experts)-76B900?style=for-the-badge" alt="IQ2_XS" />
  <img src="https://img.shields.io/badge/Cache_Hit_Rate-99.5%25_Verified-brightgreen?style=for-the-badge" alt="99.5% Hit Rate" />
  <img src="https://img.shields.io/badge/Audit_Policy-DOUBLE_BLIND_CLEAN_ROOM-blueviolet?style=for-the-badge" alt="Double Blind" />
  <img src="https://img.shields.io/badge/Reflex_Triage-LIVE_WEB_GROUNDED-informational?style=for-the-badge&logo=duckduckgo" alt="Web Grounded" />
  <img src="https://img.shields.io/badge/Core-C%2B%2B20_%2F_MSVC_2022-00599C?style=for-the-badge&logo=c%2B%2B" alt="C++20" />
  <img src="https://img.shields.io/badge/Sandbox-Git_Worktrees-F05032?style=for-the-badge&logo=git" alt="Git Worktrees" />
</p>

```
[ Primary DRI & Coder: 5090 Blackwell / Spark ] <─── Tandem Loop ───> [ Independent Auditor & Reflex: 5090 Blackwell ]
  ├── 205-303 tok/s Whole-Module Synthesis (IQ2_XS 99.5% Cache Hit)     ├── < 2.5s Web-Grounded AST Triage & Zero-Leakage Double-Blind Audit
  └── 27-Skill Matt Pocock Agentic Loop (fit_max_tokens: true)           └── Fowler Smell Linter & Refactor Gate (Exit 0 + Sentinels)
```

---

## Engineering Philosophy: Empirical Rigor Over Hype

> *"In the era of AI-accelerated software engineering, the biggest risk is unearned confidence. I don't believe in 'vibe coding' or taking model outputs on faith.*
> 
> *When models can generate thousands of lines in seconds, the role of the engineer shifts from typing syntax to enforcing ground truth. That is why every system I build is anchored in ruthless determinism: binary exit codes, deterministic test sentinels, isolated sandboxes, and hardware profiling.*
> 
> *I don't ask anyone to take my word for it—I let the compiler, the test harness, and the live telemetry speak for themselves."*

---

## For Technical Hiring Managers & Headhunters: Preempting the Hard Questions

> *"Most candidates can write prompts. Very few know what happens when the compiler throws an AST recursion error at 3 AM or how to prevent an autonomous agent from destroying a production codebase."*

### 1. "Is this an API wrapper or actual systems engineering?"
- **Bare-Metal Compute Ownership**: Dedicated heterogeneous multi-GPU infrastructure running on bare metal (NVIDIA RTX 5090 Blackwell `sm_120` 32GB GDDR7 + multi-node Spark cluster + completely isolated secondary RTX 5070 Ti 16GB display/gaming GPU).
- **Sub-Second Reflex & High-Throughput DRI**: Local OpenAI-compatible endpoint delivering sustained **205.6–303.7 tokens/second** on Blackwell tensor cores under **IQ2_XS quantization with 18,514 resident expert slots (75.3% in GDDR7 VRAM)** and a verified **99.5% GPU cache hit rate**.
- **Hardware Isolation & Memory Tuning**: Reduced host RAM arena from 46.8 GB to 33.0 GB, saving **~14 GB physical RAM** so the host system can run simultaneous heavy AAA gaming loads on the secondary 5070 Ti at 95% utilization with zero micro-stutter while continuous autonomous AI engineering loops run in parallel.
- **Double-Blind Clean-Room Audit Architecture**: Enforced strict isolation between implementation and review passes: the independent auditor evaluates *only* ticket contract specifications and `git diff` with zero visibility into the author agent's internal prompt history or reasoning scratchpad, actively enforcing Fowler clean-code standards and deterministic test gates.
- **Live Web-Grounded Failure Triage & Fast SSD Knowledge Cache**: Just like a senior human engineer looking up authoritative documentation when encountering a compiler fault, the reflex triage loop extracts error signatures and automatically queries live technical documentation (Microsoft Learn, language specifications, Stack Overflow) via headless research tools, feeding verified ground-truth receipts directly into the 5090 Blackwell prompt to eliminate hallucinated fixes. Backed by a local NVMe/SSD cache with 7-day TTL auto-eviction and LRU limits, dropping repeated failure triage latency from ~3.5s down to <1ms.
- **Low-Level Native Systems**: Proven experience across physical PCIe DMA hardware capture, second-PC memory reconstruction, and C++20 game engine memory management (`ezDynamicArray`, move semantics, memory barriers).

### 2. "How do you guarantee agents don't hallucinate or pollute production repositories?"
I engineer **closed-loop deterministic harnesses**, not open-ended chat scripts. Every autonomous task is constrained by **Four Iron Invariants**:
1. **Zero "Green When Untrue"**: A test is only marked passing if **both** the binary exit code is strictly zero (`$LASTEXITCODE -eq 0`) and all required stdout sentinel regexes match. Zero mock passes.
2. **Git Worktree Sandboxing**: Every agent turn runs in an ephemeral Git worktree. Failed attempts are destroyed with `--force` at the filesystem and Git ref level. The main integration branch is only touched via fast-forward merges on certified green builds.
3. **ADR 0002 Static Architectural Linters**: Automated diff analysis rejects any patch that attempts to dump subsystem algorithms directly into core engine God-classes before compilation is even scheduled.
4. **Topological Ticket DAG**: Tasks are resolved in strict dependency order, preventing out-of-order feature execution and cyclic deadlocks.

### 3. "Can your systems handle massive native enterprise repositories?"
- **Validated Against ezEngine**: The active harness runs autonomously against `ezEngine`, a massive, production-grade C++20 multi-million-line codebase with CMake, Ninja, and MSVC toolchains.
- **135+ Verified Checkpoints**: Autonomously writes, compiles, and verifies subsystems spanning organ anatomy & bionics, 24-hour schedules, multi-octave coherent worldgen, thermodynamic heat diffusion, pressurized fluid networks, and multi-personality storytellers.
- **Autonomous Self-Healing**: Real flight recorder incident: MSVC fatal circular header dependency (`C2061`) and `ezDynamicArray` buffer reset diagnosed and patched in **2,766ms** without human intervention ([Flight Recorder JSON](https://github.com/Perry5216/autonomous-ai-engineering-harness/blob/main/telemetry/incidents/incident-2026-10-17-msvc-circular-include.json)).

### 4. "What roles am I primed to execute on day one?"
-  **Applied AI Engineer (Autonomous Coding / Codex / Devin-Class Agentic Loops)**: Designing evaluation harnesses, multi-agent co-processors, self-healing compiler loops, and deterministic execution environments.
-  **AI Systems & Inference Infrastructure Engineer**: Managing high-throughput local inference, heterogeneous cluster scheduling, GPU VRAM budgeting, and local LoRA fine-tuning pipelines.
-  **Systems & Engine Software Engineer**: Low-level C++20 architecture, simulation graphs, hardware memory introspection, and high-performance native tooling.

### 5. "How do I verify your work in 10 seconds?"
Clone the harness and run the automated integrity verification suite:
```powershell
git clone https://github.com/Perry5216/autonomous-ai-engineering-harness
powershell -ExecutionPolicy Bypass -File ./autonomous-ai-engineering-harness/scripts/verify-harness.ps1
```

---

## Production Standards: Engineering Invariants

| Conventional Agentic Setups | My Autonomous Production Harness Standard |
|---|---|
| **Unconstrained Chat Prompts** | **Topological Ticket DAG**: Strict dependency ordering prevents out-of-order execution |
| **Mocks Assertions / Accepts Failures** | **Zero "Green When Untrue"**: Dual gate ($LASTEXITCODE == 0 + stdout sentinels) |
| **Monolithic Model Overload** | **Asymmetric Tandem & Double-Blind**: DRI Coder + 5090 Blackwell Reflex & Auditor (@ 205-303 tok/s) |
| **Author Self-Grading** | **Double-Blind Clean-Room Audit**: Zero-leakage independent reviewer checks contract & diff only |
| **Working Tree Pollution** | **Git Worktree Sandboxes**: Ephemeral task workspaces with zero-residue rollback |
| **LLM Architectural Drift** | **ADR 0002 Linter**: Automated static guardrails intercept and reject God-class bloat |

---

## Flagship Systems & Active Projects

### [Autonomous AI Engineering Harness](https://github.com/Perry5216/autonomous-ai-engineering-harness)
*Production-grade autonomous engineering harness featuring asymmetric dual-model architecture, zero "green when untrue" verification, double-blind clean-room code review, and self-healing C++20 compiler loops.*

- **Asymmetric Tandem Inference & Double-Blind Review**: Spark Cluster / 5090 Blackwell generates code with the 27-skill DSH deck, while a dedicated local **NVIDIA RTX 5090 Blackwell** (:8080 @ 205.6–303.7 tok/s) acts as both the low-latency reflex triage engine and an independent, clean-room code auditor.
- **Zero "Green When Untrue" Verification**: Tests are only certified passing when **both** conditions hold: binary exit code is strictly zero (`$LASTEXITCODE -eq 0`) and all required stdout sentinels are verified. Zero hallucinated or mocked test passes.
- **Git Worktree Sandboxing**: Ephemeral task-per-worktree execution prevents dirty workspace poisoning, index lock collisions, and state leakage. Atomic promotion via fast-forward merge on green gate; zero-residue rollback on failure.
- **Autonomous Compiler Self-Healing**: Real flight recorder incident: MSVC fatal circular header dependency (`C2061`) and `ezDynamicArray` buffer reset diagnosed and patched in **2,766ms** without human intervention.
- **Deterministic Ticket DAG**: Dependency-ordered state machine resolving tasks in strict topological order.
- **Live Visual Dashboard**: [Interactive Telemetry Board](https://github.com/Perry5216/autonomous-ai-engineering-harness/blob/main/docs/index.html) - **135 / 135 Verified Checkpoints Passing**
- **Flight Recorder Incident Telemetry**: [Raw Incident JSON Dump](https://github.com/Perry5216/autonomous-ai-engineering-harness/blob/main/telemetry/incidents/incident-2026-10-17-msvc-circular-include.json)

---

### [Resilient Rate Limiter & Circuit Breaker](https://github.com/Perry5216/resilient-rate-limiter)
*High-throughput sub-bucket sliding window rate limiter and three-state circuit breaker engineered with microsecond monotonic clock seams and double-blind clean-room audit verification.*

- **Sub-Bucket Sliding Window (ADR 0001)**: Memory-bounded discrete bucket counters with exact sliding window replenishment and microsecond-precision `resetMs` calculation preventing retry storms.
- **Three-State Transient Fault Isolation**: CLOSED/OPEN/HALF_OPEN state machine featuring bounded probe concurrency, fallback execution, and deterministic recovery.
- **Double-Blind Clean-Room Audit Verified**: Full code evaluated and audited by an independent local 5090 Blackwell auditor with zero prompt leakage, scoring an **A (91/100) — APPROVED** across Fowler clean-code standards and deterministic test gates.

---

### [P.E.R.R.Y. Autonomous Orchestration Ecosystem](https://github.com/Perry5216/perry)
*Self-hosted multi-agent platform and local LoRA training pipeline running on dedicated multi-GPU infrastructure.*

- **[Perry v2](https://github.com/Perry5216/perry)**: Typed monorepo (18 packages) orchestrating autonomous task DAGs, fail-closed security gates, Cursor-style browser sidecars, and evidence-based knowledge harvesting across a heterogeneous GPU cluster (5090 Blackwell + Spark + 5070).
- **[Perry System (v1)](https://github.com/Perry5216/perry-system)**: Self-hosted multi-agent AI orchestration platform featuring an autonomous self-learning loop and LoRA fine-tuning infrastructure.
- **Blackwell sm_120 Training Pipeline**: Custom Vanilla HuggingFace LoRA fine-tuning stack (TRL + PEFT + bitsandbytes) engineered for the RTX 5090 Blackwell architecture, featuring GGUF export via llama.cpp and automated Ollama model registration.

---

## Low-Level Systems, Reverse Engineering & Hardware

- **[`eft-dma-radar`](https://github.com/Perry5216/eft-dma-radar)** — PCIe DMA hardware memory acquisition toolchain; physical memory layout discovery, scatter-read optimization, and external game state reconstruction (C#).
- **[`csgo-dma-overlay`](https://github.com/Perry5216/csgo-dma-overlay)** — Second-PC HDMI passthrough overlay fed strictly from hardware DMA-acquired memory without host software footprint.
- **[`Nathans-Tarkov-Radar-Public`](https://github.com/Perry5216/Nathans-Tarkov-Radar-Public)** — External physical memory reconstruction and real-time state synchronization pipeline.
- **[`BasicGameTrainner`](https://github.com/Perry5216/BasicGameTrainner)** — Process memory introspection and pointer-chain analysis (C++).

---

## Engine Architecture, Simulation & Graphics (C++20)

- **[ezEngine Colony Plugin](https://github.com/Perry5216/ezEngine/tree/dev/Code/EnginePlugins/ColonyPlugin)** — Complex colony simulation engine running inside ezEngine. Features 135+ automated C++20 test checkpoints across organ anatomy & bionics, 24-hour schedules, multi-octave coherent worldgen & clustered ore veins, sub-zero freezers & rot prevention, 5-factor room impressiveness, and multi-personality storytellers.
- **[`Merlin-Game-Engine-CPP`](https://github.com/Perry5216/Merlin-Game-Engine-CPP)** — Full custom C++ game engine architecture built from scratch; component systems, rendering pipeline, and memory management.
- **[`Ol-baid`](https://github.com/Perry5216/Ol-baid)** — Final-year university dissertation and capstone project integrating engine systems, custom shaders, and graphics architectures.
- **[`Spider`](https://github.com/Perry5216/Spider)** — GPU compute and animation experiment: real-time procedural spider navigation on arbitrary 3D spherical manifolds (C++ / OpenGL).
- **[`ProjectDoppelgangerV4`](https://github.com/Perry5216/ProjectDoppelgangerV4)** — Unreal Engine 5 multiplayer first-person gameplay systems (C++ / Gameplay Ability System).

---

<details>
<summary> <strong>Foundational Software & Academic Game Projects (Click to expand)</strong></summary>

- **[`flurrE`](https://github.com/Perry5216/flurrE)** — Year-one Unity physics platformer (Rayman / Super Meat Boy mechanics).
- **[`Snails`](https://github.com/Perry5216/Snails)** — Year-two team multiplayer game project (Unity / C#).
- **[`Ticketing-System`](https://github.com/Perry5216/Ticketing-System)** — Year-two C++ OOP console architecture with file-backed persistence.
- **[`Axe-Game`](https://github.com/Perry5216/Axe-Game)** — Foundational C++ game loop and collision math.
- **[`Creep`](https://github.com/Perry5216/Creep)** / **[`The-Creeper`](https://github.com/Perry5216/The-Creeper)** — Procedural 2D simulation and entity management experiments.
</details>

---

## Live GitHub Activity & Language Stack

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Perry5216&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Anthony Perry's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Perry5216&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>
<div align="center" style="margin-top: 10px;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Perry5216&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>
