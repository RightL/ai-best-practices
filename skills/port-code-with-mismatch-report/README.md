# Port Code With Mismatch Report

→ [SKILL.md](SKILL.md)

## Why

Ports can look equivalent while hiding differences in types, numbers, libraries, errors, I/O, memory, concurrency, or performance. Those mismatches matter most when nobody writes them down.

The fix is to preserve behavior first, adapt idiomatically second, and document every remaining mismatch so future readers know what changed and why it remains.

## What It Does

Translates code or algorithms from one language to another, then writes a Markdown mismatch report covering intentional or forced behavioral, numeric, API, data-structure, error-handling, performance, and tooling differences.

## When to Use

When code or an algorithm needs to be ported between programming languages and the differences must be explicit rather than buried in the translation.
