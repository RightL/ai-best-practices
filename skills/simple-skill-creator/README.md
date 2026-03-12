# Simple Skill Creator

→ [SKILL.md](SKILL.md)

## Why

Most skill templates are verbose — they prescribe sections like "Resources", "Steps", "Examples", and so on. When you feed that structure to an AI, it tries to fill every section, and the output becomes rigid and formulaic.

The insight is simple: **the more you constrain the format, the less the AI thinks for itself.** A minimal prompt leaves room for the AI to respond naturally to the actual request, rather than pattern-matching against a template.

## What It Does

Creates a skill as a single `SKILL.md` with only:
- YAML frontmatter: `name` and `description`
- One paragraph body with the actual instructions

That's it. No extra files, no resource folders, no rigid sections unless you explicitly ask.

## When to Use

When you want a lightweight skill that gets out of the way. Good for simple, focused tasks where you don't need a complex multi-step workflow.
