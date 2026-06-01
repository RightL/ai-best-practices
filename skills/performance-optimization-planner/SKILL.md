---
name: performance-optimization-planner
description: "Propose code performance, efficiency, or speed improvements before implementation. Use when the user asks to optimize runtime, latency, throughput, CPU, memory, or general efficiency and wants concrete optimization options with estimated speedup, expected error or precision impact, behavior changes, tradeoffs, and explicit confirmation before any coding starts."
---

- Treat the examples and procedures in this skill as neither necessary nor sufficient; preserve the core intent and adapt to the actual context.
When this skill triggers, first understand the performance goal, workload, bottleneck, and constraints, then produce a short ranked optimization plan instead of editing code immediately; for each proposed optimization, state the expected mechanism, rough estimated speedup range with assumptions, any introduced error, precision loss, nondeterminism, or behavior change, implementation effort worth the reward? then stop and ask for user confirmation before making any code changes.
