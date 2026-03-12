# Extract Workflow

→ [SKILL.md](SKILL.md)

## Why

When working with an AI agent, you often end up explaining your way of doing things — a process, a preference, a method. The AI follows it for that session, but next time you start fresh and have to explain it all over again.

The fix is to extract those user-provided instructions and turn them into reusable skills or notes. The key is to keep it focused: at most 1-2 items, generalized so they apply beyond the original task.

## What It Does

Reads a conversation and looks specifically for moments where the user taught the AI how to do something. Extracts at most 1-2 of the most reusable ones as short, direct instructions ready to drop into a future prompt or skill.

## When to Use

After any session where you found yourself explaining a process or method to the AI that you'd want to reuse.
