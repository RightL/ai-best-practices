# Task Handoff / Refresh Memory

→ [SKILL.md](SKILL.md)

## Why

Long context degrades agent performance. Outputs become less reliable, reasoning starts to drift, and continuing the same session costs more than it's worth. The right move is to hand off to a fresh agent — but a raw dump of everything is just as noisy as the bloated context you're trying to escape.

## What It Does

Creates a structured handoff document saved to `/tmp/handoff-YYYYMMDD-HHMMSS.md`. It captures the goal, what was completed, what remains, and only the context still relevant to the next step. It deliberately omits implementation methods and anything inferred after the context got long — those are the parts you can't trust.

After writing the file, it outputs a one-line prompt you can paste directly into a new session.

## When to Use

- Context is getting long and outputs feel less reliable
- You want to hand work off to another agent or a later turn
- You're switching tasks and need a clean restart without losing what matters
