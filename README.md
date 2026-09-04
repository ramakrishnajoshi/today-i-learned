# Today I Learned (TIL) 🧠

Welcome to my personal engineering journal. This repository serves as a self-curated, highly modular knowledge base where I document deep-dive technical insights, edge cases, root-cause analyses, and structural engineering patterns discovered during my daily work and research.

As an Android Engineer working within large-scale enterprise environments, I use this space to maintain a tight feedback loop between execution and theory—covering core platform architecture, system design constraints, and modern AI/LLM engineering failure modes.

---

## 📂 Repository Index

### 📱 Android Deep Dives & Platform Internals
*Comprehensive deep dives into the Android OS, concurrency models, rendering pipelines, and memory optimization.*
*   [Jetpack Compose Recomposition Optimization](android/compose-recomposition.md) — *Analyzing structural stability and positional memoization.*
*   [Kotlin Coroutines Under the Hood](android/coroutines-internals.md) — *State machine transformations and thread suspension mechanics.*
*   [Memory Leak Isolation](android/leakcanary-analysis.md) — *Root-causing anonymous inner classes and lifecycle-bound reference leaks.*

### 🏗️ Mobile & Distributed System Design
*High-level architectural patterns for building scalable, offline-first, and highly performant systems.*
*   [Offline-First Sync Engine Architecture](system-design/offline-sync.md) — *Handling conflict resolution, exponential backoff, and local persistence.*
*   [Telemetry & Analytics Ingestion Pipelines](system-design/telemetry-pipeline.md) — *Designing non-blocking client-side batching mechanisms.*

### 🤖 Generative AI & LLM Systems Engineering
*Documenting behavioral biases, prompt optimization, and failure modes in autonomous agent workflows.*
*   [The "You're Absolutely Right" Trap (Sycophancy Bias)](ai-engineering/llm-sycophancy-trap.md) — *Root-causing context window contamination and auto-regressive apology loops.*
*   [System Prompt Hardening Guidelines](ai-engineering/prompt-hardening.md) — *Architectural strategies to override RLHF compliance defaults.*

---

## 🛠️ Formatting Methodology

Every entry in this repository avoids passive high-level summaries and strictly follows a production-grade diagnostic framework:
1.  **The Context/Problem:** What is the specific error, bottleneck, or structural behavior?
2.  **The Root Cause:** What are the underlying mechanics (compilation steps, mathematical constraints, or framework designs) causing it?
3.  **The Code/Architectural Example:** A minimal, isolated reproduction of the issue or pattern.
4.  **The Mitigation:** Production-ready strategies, guardrails, or code changes to eliminate the problem.

---

## 📈 Continuous Growth Tracker
*   **Active Focus Areas (2026):** Advanced Jetpack Compose Internals, Kotlin Multiplatform (KMP) Memory Management, and Multi-Agent Critic Frameworks.
*   **Total Logged Insights:** *[Update dynamically as you add files]*

---
*Feel free to explore the directories. If you find an insight helpful or notice room for correction, pull requests and discussions are always welcome!*

