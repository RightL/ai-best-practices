---
name: port-code-with-mismatch-report
description: Convert code or algorithms from one programming language to another, then write a Markdown mismatch report explaining every intentional difference and why it remains.
---

- Treat the examples and procedures in this skill as neither necessary nor sufficient; preserve the core intent and adapt to the actual context.
- Read the source implementation first and identify the semantic contract, inputs, outputs, invariants, edge cases, and performance expectations before translating anything.
- Confirm the target language, target runtime constraints, and what must match exactly versus what may change idiomatically; if this is unclear, ask the user.
- Port the code or algorithm to the target language by preserving behavior first, then adapting syntax, types, memory model, libraries, and data structures to the target language idioms.
- Fail fast on unsupported assumptions or missing specifications; do not hide gaps with heuristics, silent fallbacks, compatibility shims, or speculative behavior changes.
- Treat parser, type-system, numeric, memory-management, concurrency, standard-library, and I/O differences as first-class translation risks and inspect them explicitly.
- Keep the translated code minimal and production-shaped; avoid carrying over source-language patterns that are unnatural or misleading in the target language unless required for correctness.
- After the port, create a Markdown document in the working area that lists every mismatch between source and translated versions, including behavioral, numeric, API, data-structure, error-handling, performance, and tooling mismatches.
- For each mismatch, state the exact location, what differs, whether the difference is intentional or forced, why it was kept, and what would be required to remove it.
- If there are no meaningful mismatches, still write the Markdown document and explicitly state that no material mismatches remain after verification.
- Prefer a deterministic filename such as `mismatch-report.md` unless the user or repo conventions require a more specific name.
