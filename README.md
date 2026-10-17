# Anthony Perry

<a href="https://github.com/Perry5216">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=06B6D4&background=00000000&center=false&vCenter=true&width=750&lines=Autonomous+Systems+%26+Applied+AI+Engineer;Asymmetric+Tandem%3A+Spark+Cluster+%2B+RTX+5090+Blackwell;Zero+'Green+When+Untrue'+Verification+Pipelines;Native+C%2B%2B20+Simulation+Engines+%26+Compilers;PCIe+DMA+Hardware+Memory+Introspection" alt="Typing SVG" />
</a>

📍 **London, UK** · [LinkedIn](https://www.linkedin.com/in/anthony-perry-33b7a01a0/) · [GitHub](https://github.com/Perry5216) · [Portfolio Harness](https://github.com/Perry5216/autonomous-ai-engineering-harness)

<p>
  <img src="https://img.shields.io/badge/Hardware-NVIDIA_RTX_5090_Blackwell_(32GB_GDDR7)-76B900?style=for-the-badge&logo=nvidia" alt="RTX 5090" />
  <img src="https://img.shields.io/badge/Inference-198.8_tok%2Fs_Sustained-orange?style=for-the-badge" alt="198.8 tok/s" />
  <img src="https://img.shields.io/badge/Context-32k_VRAM_Resident_KV-blue?style=for-the-badge" alt="32k KV" />
  <img src="https://img.shields.io/badge/Cluster-Spark_DRI_Cluster_(:8877)-brightgreen?style=for-the-badge&logo=apachespark" alt="Spark" />
  <img src="https://img.shields.io/badge/Core-C%2B%2B20_%2F_MSVC_2022-00599C?style=for-the-badge&logo=c%2B%2B" alt="C++20" />
  <img src="https://img.shields.io/badge/Sandbox-Git_Worktrees-F05032?style=for-the-badge&logo=git" alt="Git Worktrees" />
</p>

```
[ Primary DRI: Spark Cluster (:8877) ] <─── Tandem Loop ───> [ Reflex Engine: RTX 5090 Blackwell (:8080 @ 198.8 tok/s) ]
  ├── C++20 Code Generation & Test Suites                       ├── < 2.5s MSVC AST Error Triage (2k Budget)
  └── Multi-Subsystem Composition                               ├── Whole-Module Synthesis (32k Resident KV)
                                                                └── Fowler Code Smell & ADR 0002 Linter
```

---

## 🧭 Engineering Philosophy: Empirical Rigor Over Hype

> *"In the era of AI-accelerated software engineering, the biggest risk is unearned confidence. I don't believe in 'vibe coding' or taking model outputs on faith.*
> 
> *When models can generate thousands of lines in seconds, the role of the engineer shifts from typing syntax to enforcing ground truth. That is why every system I build is anchored in ruthless determinism: binary exit codes, deterministic test sentinels, isolated sandboxes, and hardware profiling.*
> 
> *I don't ask anyone to take my word for it—I let the compiler, the test harness, and the live telemetry speak for themselves."*

---

## 🎯 For Technical Hiring Managers & Headhunters: Preempting the Hard Questions

> *"Most candidates can write prompts. Very few know what happens when the compiler throws an AST recursion error at 3 AM or how to prevent an autonomous agent from destroying a production codebase."*

### 1. "Is this an API wrapper or actual systems engineering?"
- **Bare-Metal Compute Ownership**: Dedicated heterogeneous multi-GPU infrastructure running on bare metal (NVIDIA RTX 5090 Blackwell `sm_120` 32GB GDDR7 + multi-node Spark cluster + isolated display GPU).
- **Sub-Second Reflex Inference**: Local OpenAI-compatible reflex endpoint delivering sustained **198.8 tokens/second** on Blackwell tensor cores, executing compiler AST diagnostics in under **2,500 ms** (empirically benchmarked: 4,096 tokens generated in 20.6s).
- **32,768-Token VRAM-Resident KV Cache**: 131,072-token total context window with a dedicated 32k-token resident INT8 KV cache in GDDR7 VRAM, preventing host RAM thrashing during whole-module generation.
- **Empirical Rigor in Public (Zero Bluffing)**: Engineering means measuring real failure modes. When modern reasoning models starved their output token envelope inside `<think>` blocks, I diagnosed the Strata token exhaustion bug and implemented a **Two-Tier Budget Model**: strict **2,048-token / 512-reasoning-budget** envelopes for sub-3s compiler triage, and up to **32,768 tokens** for whole translation unit synthesis.
- **Low-Level Native Systems**: Proven experience across physical PCIe DMA hardware capture, second-PC memory reconstruction, and C++20 game engine memory management (`ezDynamicArray`, move semantics, memory barriers).

### 2. "How do you guarantee agents don't hallucinate or pollute production repositories?"
I engineer **closed-loop deterministic harnesses**, not open-ended chat scripts. Every autonomous task is constrained by **Four Iron Invariants**:
1. **Zero "Green When Untrue"**: A test is only marked passing if **both** the binary exit code is strictly zero (`$LASTEXITCODE -eq 0`) and all required stdout sentinel regexes match. Zero mock passes.
2. **Git Worktree Sandboxing**: Every agent turn runs in an ephemeral Git worktree. Failed attempts are destroyed with `--force` at the filesystem and Git ref level. The main integration branch is only touched via fast-forward merges on certified green builds.
3. **ADR 0002 Static Architectural Linters**: Automated diff analysis rejects any patch that attempts to dump subsystem algorithms directly into core engine God-classes before compilation is even scheduled.
4. **Topological Ticket DAG**: Tasks are resolved in strict dependency order, preventing out-of-order feature execution and cyclic deadlocks.

### 3. "Can your systems handle massive native enterprise repositories?"
- **Validated Against ezEngine**: The active harness runs autonomously against `ezEngine`, a massive, production-grade C++20 multi-million-line codebase with CMake, Ninja, and MSVC toolchains.
- **109+ Verified Checkpoints**: Autonomously writes, compiles, and verifies subsystems spanning thermodynamic heat diffusion, pressurized fluid networks, 5-factor room impressiveness, and hierarchical A* pathfinding.
- **Autonomous Self-Healing**: Real flight recorder incident: MSVC fatal circular header dependency (`C2061`) and `ezDynamicArray` buffer reset diagnosed and patched in **2,766ms** without human intervention ([Flight Recorder JSON](https://github.com/Perry5216/autonomous-ai-engineering-harness/blob/main/telemetry/incidents/incident-2026-10-17-msvc-circular-include.json)).

### 4. "What roles am I primed to execute on day one?"
- 🤖 **Applied AI Engineer (Autonomous Coding / Codex / Devin-Class Agentic Loops)**: Designing evaluation harnesses, multi-agent co-processors, self-healing compiler loops, and deterministic execution environments.
- ⚡ **AI Systems & Inference Infrastructure Engineer**: Managing high-throughput local inference, heterogeneous cluster scheduling, GPU VRAM budgeting, and local LoRA fine-tuning pipelines.
- 🎮 **Systems & Engine Software Engineer**: Low-level C++20 architecture, simulation graphs, hardware memory introspection, and high-performance native tooling.

### 5. "How do I verify your work in 10 seconds?"
Clone the harness and run the automated integrity verification suite:
```powershell
git clone https://github.com/Perry5216/autonomous-ai-engineering-harness
powershell -ExecutionPolicy Bypass -File ./autonomous-ai-engineering-harness/scripts/verify-harness.ps1
```

---

## 🛡️ Production Standards: Engineering Invariants

| Conventional Agentic Setups | My Autonomous Production Harness Standard |
|---|---|
| **Unconstrained Chat Prompts** | **Topological Ticket DAG**: Strict dependency ordering prevents out-of-order execution |
| **Mocks Assertions / Accepts Failures** | **Zero "Green When Untrue"**: Dual gate ($LASTEXITCODE == 0 + stdout sentinels) |
| **Monolithic Model Overload** | **Asymmetric Tandem**: Spark Cluster (DRI) + RTX 5090 Blackwell (Fast Reflex @ 182 tok/s) |
| **Working Tree Pollution** | **Git Worktree Sandboxes**: Ephemeral task workspaces with zero-residue rollback |
| **LLM Architectural Drift** | **ADR 0002 Linter**: Automated static guardrails intercept and reject God-class bloat |

---

## ⚡ Flagship Systems & Active Projects

### 🚀 [Autonomous AI Engineering Harness](https://github.com/Perry5216/autonomous-ai-engineering-harness)
*Production-grade autonomous engineering harness featuring asymmetric dual-model architecture, zero "green when untrue" verification, and self-healing C++20 compiler loops.*

- **Asymmetric Tandem Inference**: Spark Cluster (DRI) generates complex multi-file C++20 subsystems, while a dedicated local **NVIDIA RTX 5090 Blackwell** (:8080 @ 182 tok/s) acts as the low-latency reflex triage engine.
- **Zero "Green When Untrue" Verification**: Tests are only certified passing when **both** conditions hold: binary exit code is strictly zero (`$LASTEXITCODE -eq 0`) and all required stdout sentinels are verified. Zero hallucinated or mocked test passes.
- **Git Worktree Sandboxing**: Ephemeral task-per-worktree execution prevents dirty workspace poisoning, index lock collisions, and state leakage. Atomic promotion via fast-forward merge on green gate; zero-residue rollback on failure.
- **Autonomous Compiler Self-Healing**: Real flight recorder incident: MSVC fatal circular header dependency (`C2061`) and `ezDynamicArray` buffer reset diagnosed and patched in **2,766ms** without human intervention.
- **Deterministic Ticket DAG**: Dependency-ordered state machine resolving tasks in strict topological order.
- 📊 **[Live Visual Dashboard & Telemetry Stream](https://github.com/Perry5216/autonomous-ai-engineering-harness/blob/main/docs/index.html)** · **109 / 109 Verified Checkpoints Passing**
- ✈️ **[Flight Recorder Incident Telemetry](https://github.com/Perry5216/autonomous-ai-engineering-harness/blob/main/telemetry/incidents/incident-2026-10-17-msvc-circular-include.json)**

---

### 🧠 [P.E.R.R.Y. Autonomous Orchestration Ecosystem](https://github.com/Perry5216/perry)
*Self-hosted multi-agent platform and local LoRA training pipeline running on dedicated multi-GPU infrastructure.*

- **[Perry v2](https://github.com/Perry5216/perry)**: Typed monorepo (18 packages) orchestrating autonomous task DAGs, fail-closed security gates, Cursor-style browser sidecars, and evidence-based knowledge harvesting across a heterogeneous GPU cluster (5090 Blackwell + Spark + 5070).
- **[Perry System (v1)](https://github.com/Perry5216/perry-system)**: Self-hosted multi-agent AI orchestration platform featuring an autonomous self-learning loop and LoRA fine-tuning infrastructure.
- **Blackwell sm_120 Training Pipeline**: Custom Vanilla HuggingFace LoRA fine-tuning stack (TRL + PEFT + bitsandbytes) engineered for the RTX 5090 Blackwell architecture, featuring GGUF export via llama.cpp and automated Ollama model registration.

---

## 🔬 Low-Level Systems, Reverse Engineering & Hardware

- **[`eft-dma-radar`](https://github.com/Perry5216/eft-dma-radar)** — PCIe DMA hardware memory acquisition toolchain; physical memory layout discovery, scatter-read optimization, and external game state reconstruction (C#).
- **[`csgo-dma-overlay`](https://github.com/Perry5216/csgo-dma-overlay)** — Second-PC HDMI passthrough overlay fed strictly from hardware DMA-acquired memory without host software footprint.
- **[`Nathans-Tarkov-Radar-Public`](https://github.com/Perry5216/Nathans-Tarkov-Radar-Public)** — External physical memory reconstruction and real-time state synchronization pipeline.
- **[`BasicGameTrainner`](https://github.com/Perry5216/BasicGameTrainner)** — Process memory introspection and pointer-chain analysis (C++).

---

## 🎮 Engine Architecture, Simulation & Graphics (C++20)

- **[ezEngine Colony Plugin](https://github.com/Perry5216/autonomous-ai-engineering-harness)** — Complex colony simulation engine running inside ezEngine. Features 109+ automated C++20 test checkpoints across thermodynamic heat diffusion, fluid networks, 5-factor room impressiveness, hierarchical pathfinding, and storytellers.
- **[`Merlin-Game-Engine-CPP`](https://github.com/Perry5216/Merlin-Game-Engine-CPP)** — Full custom C++ game engine architecture built from scratch; component systems, rendering pipeline, and memory management.
- **[`Ol-baid`](https://github.com/Perry5216/Ol-baid)** — Final-year university dissertation and capstone project integrating engine systems, custom shaders, and graphics architectures.
- **[`Spider`](https://github.com/Perry5216/Spider)** — GPU compute and animation experiment: real-time procedural spider navigation on arbitrary 3D spherical manifolds (C++ / OpenGL).
- **[`ProjectDoppelgangerV4`](https://github.com/Perry5216/ProjectDoppelgangerV4)** — Unreal Engine 5 multiplayer first-person gameplay systems (C++ / Gameplay Ability System).

---

<details>
<summary>📂 <strong>Foundational Software & Academic Game Projects (Click to expand)</strong></summary>

- **[`flurrE`](https://github.com/Perry5216/flurrE)** — Year-one Unity physics platformer (Rayman / Super Meat Boy mechanics).
- **[`Snails`](https://github.com/Perry5216/Snails)** — Year-two team multiplayer game project (Unity / C#).
- **[`Ticketing-System`](https://github.com/Perry5216/Ticketing-System)** — Year-two C++ OOP console architecture with file-backed persistence.
- **[`Axe-Game`](https://github.com/Perry5216/Axe-Game)** — Foundational C++ game loop and collision math.
- **[`Creep`](https://github.com/Perry5216/Creep)** / **[`The-Creeper`](https://github.com/Perry5216/The-Creeper)** — Procedural 2D simulation and entity management experiments.
</details>

---

## 📊 Live GitHub Activity & Language Stack

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Perry5216&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Anthony Perry's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Perry5216&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>
<div align="center" style="margin-top: 10px;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Perry5216&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>
