<div align="center">

# Gökçen Çiftci

### Software Developer

[![Portfolio](https://img.shields.io/badge/Portfolio-gokcenciftci.me-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white)](https://gokcenciftci.me/)
[![Email](https://img.shields.io/badge/Email-contact%40gokcenciftci.me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@gokcenciftci.me)

</div>

---

Focused on building high-throughput database internals, embedded query compilers & bytecode VMs, resilient AI agent runtimes, and local-first CRDT state synchronization systems.

---

## 🚀 Featured Systems

<table>
<tr>
<td colspan="2" valign="top">

### [HyperSync Studio](https://github.com/gokcenciftci/hypersync-studio) — *Figma-Grade Collaborative Canvas & CRDT Studio*
**Real-Time Multiplayer Visual Workspace • 60 FPS Infinite Canvas • Mathematical CRDT Engine**

A production-grade, local-first collaborative canvas and rich-text workspace with zero-dependency **CRDT engine**, **Vector Clock causality matrix**, live multiplayer cursor tracking, and binary wire protocol.

* **Performance:** **2.62M+ ops/s** LWW mutations, **6.17M+ ops/s** Vector Clock checks, **303k+ frames/s** binary codec.
* **Stack:** `TypeScript` `React 19` `CRDT Canvas` `VectorClock` `Multiplayer` `Local-First`

[Launch Live Studio ↗](https://hypersync-studio.vercel.app/) • [Explore Source Code →](https://github.com/gokcenciftci/hypersync-studio)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [HyperSync](https://github.com/gokcenciftci/hyper-sync)
**Local-First Real-Time CRDT & State Engine**

Embedded, zero-dependency distributed state engine with sub-millisecond state convergence, delta replication, and WebSocket multiplexing.

* **Core:** `LWWRegister` (**10.6M+ ops/s**), `ORSet` (**1.34M+ ops/s**), RGA `SequenceCRDT`.
* **Sync:** `VectorClock`, $O(\Delta)$ Delta Engine, Binary Codec (**1.82M+ deltas/s**).

[Explore HyperSync →](https://github.com/gokcenciftci/hyper-sync)

</td>
<td width="50%" valign="top">

### [AegisFlow](https://github.com/gokcenciftci/aegis-flow)
**Enterprise AI Agent Runtime & Resilience Gateway**

High-throughput execution runtime for autonomous AI agents with determinism, sliding context windows, and real-time OpenTelemetry tracing.

* **Resilience:** 3-State Circuit Breakers, Token-Bucket Rate Limiter, Jittered Retries.
* **Throughput:** **2.1M+ state transitions/sec** • **94%+ test coverage**.

[Explore AegisFlow →](https://github.com/gokcenciftci/aegis-flow)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ChronosCore](https://github.com/gokcenciftci/chronos-core)
**Time-Series Storage & Segmented WAL Engine**

Embedded, zero-dependency time-series engine for microsecond ingestion, crash-resilient persistence, and windowed analytics.

* **Storage Core:** Multi-Level `TimeSkipList` (**2.38M+ inserts/s**), `RingBuffer` (**24.1M+ ops/s**).
* **Durability:** Segmented Write-Ahead Log (WAL) with CRC32 crash recovery.

[Explore ChronosCore →](https://github.com/gokcenciftci/chronos-core)

</td>
<td width="50%" valign="top">

### [AetherQL](https://github.com/gokcenciftci/aether-ql)
**Embedded Query Engine & Bytecode Virtual Machine**

Zero-dependency SQL/DSL query engine, rule-based logical optimizer (predicate pushdown, constant folding), and stack-based execution VM.

* **Compiler & VM:** Rule-based optimizer (**5.4M+ passes/s**), Pratt AST Parser (**1.46M+ ops/s**).
* **Diagnostics:** Query plan AST visualizer & bytecode disassembly (`EXPLAIN`).

[Explore AetherQL →](https://github.com/gokcenciftci/aether-ql)

</td>
</tr>
</table>

---

## 🛠️ Technical Arsenal

| Domain | Technologies, Protocols & Architectural Patterns |
| :--- | :--- |
| **Languages & Core** | `TypeScript` `Node.js (ESM)` `React 19` `ES2024+` |
| **Compilers & Query Engines** | `Pratt AST Parser` `Rule-Based Query Optimizer` `Stack-based Bytecode VM` |
| **Distributed & Real-Time** | `CRDT (LWW / OR-Set / RGA)` `Vector Clocks` `Binary Codec (CRC32)` `Local-First Sync` |
| **Storage & Data Systems** | `Append-Only Segmented WAL` `Multi-Level TimeSkipList` `RingBuffer` |
| **AI Systems & Resilience** | `Finite State Machines (FSM)` `Circuit Breakers` `Token-Bucket Rate Limiter` `OpenTelemetry` |
| **Testing & Quality** | `Vitest` `Convergence Fuzzing` `WAL Crash Recovery Harness` `Benchmarks` |

---

## 💎 Development Principles

```text
Type Safety       →  Parse, don't validate at system boundaries
Bytecode VM       →  Rule-based optimization & stack execution
State Sync        →  Mathematical CRDT & vector clock convergence
Storage & WAL     →  Append-only segmented logs & CRC32 recovery
Fault Tolerance   →  Circuit breakers, adaptive retries & budget guards
Zero Tech Debt    →  Strict immutability, zero 'any' & >= 90% coverage
```
