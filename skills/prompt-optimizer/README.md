# Prompt Optimizer

→ [SKILL.md](SKILL.md)

## Why

Most prompt rewrites fail because the AI jumps straight to rewriting. It produces something polished-looking that misses the actual intent — wrong scope, wrong output format, wrong assumptions baked in.

The fix is grounding first. Read the context, infer what the user actually needs, and only then rewrite. And once you've produced the new prompt, stop — don't execute it. The user needs to confirm the direction before anything runs.

## What It Does

Explores local context and prior conversation to infer the user's real goal, asks at most one clarifying question if something critical is ambiguous, then produces a concrete, structured, intent-aligned prompt. Presents the result and waits for confirmation before proceeding.

## When to Use

When a prompt is rough, vague, or underspecified and you want a better version before running it. Especially useful before long or expensive operations where a misaligned prompt wastes significant work.
