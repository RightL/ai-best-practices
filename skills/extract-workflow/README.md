# Extract Workflow

→ [SKILL.md](SKILL.md)

## Why

When working with an AI agent, you often end up explaining your way of doing things — a process, a preference, a method. The AI follows it for that session, but next time you start fresh and have to explain it all over again.

The fix is to extract those user-provided instructions and abstract them into reusable principles — stripped of project-specific context, expressed in terms that apply to a different problem of the same kind.

## What It Does

Reads a conversation and identifies moments where the user taught the AI how to do something. Ignores anything already captured in system prompts or config files (CLAUDE.md, AGENT.md, etc.). Abstracts each instruction into a domain-agnostic principle, written in whatever form fits its complexity.

## When to Use

After any session where you found yourself explaining a process or method to the AI that you'd want to reuse.
