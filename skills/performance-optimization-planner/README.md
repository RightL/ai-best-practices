# Performance Optimization Planner

→ [SKILL.md](SKILL.md)

## Why

Performance work is easy to overfit. Jumping straight into code can trade correctness, precision, determinism, or maintainability for a speedup that is smaller than expected.

The fix is to plan first. Identify the workload and bottleneck, rank plausible optimizations, estimate the speedup mechanism and tradeoffs, then ask for confirmation before changing code.

## What It Does

Produces a short ranked optimization plan with expected speedup ranges, assumptions, behavior changes, precision or error impact, nondeterminism risks, and implementation effort.

## When to Use

When the user asks to optimize runtime, latency, throughput, CPU, memory, speed, or general efficiency and wants concrete options before implementation.
