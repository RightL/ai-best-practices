# Maintain DESIGN_NOTES.md

→ [SKILL.md](SKILL.md)

## Why

Design decisions decay when the rationale lives only in conversation. Future maintainers can see what changed, but not why the shape should be kept, revised, or avoided.

The fix is a small `DESIGN_NOTES.md` focused on durable reasoning: constraints, tradeoffs, rejected alternatives, and design pressure. Examples are neither necessary nor sufficient; the test is whether the note preserves rationale that future work should respect.

## What It Does

Creates or updates `DESIGN_NOTES.md` in the relevant project location when a task depends on or changes durable design rationale. It keeps notes scoped, concise, and distinct from implementation logs or project memory.

## When to Use

When the user asks to create or maintain design notes, uses `dn` as shorthand, or makes a design choice whose rationale should survive beyond the current task.
