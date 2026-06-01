# AI Best Practices

Real-world experience using AI and agents — practical lessons, patterns, and tools from actual usage. Not tied to any single tool; covers Claude, Codex, and AI agents in general.

## Skills

Reusable skills for AI coding agents (Claude Code, etc.).

| Skill | Key Insight |
|-------|-------------|
| [simple-skill-creator](skills/simple-skill-creator/) | Less prompt = more flexible output. Most skill templates over-specify format, which constrains the AI. This skill keeps instructions minimal on purpose. |
| [extract-workflow](skills/extract-workflow/) | You often explain your methods to the AI mid-conversation. This skill extracts those instructions — so you never have to repeat yourself again. |
| [two-sided-agent](skills/two-sided-agent/) | Genuine opposition produces better answers than any single pass. Two subagents arguing opposite sides surface what one perspective misses. |
| [prompt-optimizer](skills/prompt-optimizer/) | Most prompt rewrites fail because the AI jumps to rewriting before understanding intent. Ground in context first, rewrite second, then stop and wait for confirmation. |
| [task-handoff-refresh-memory](skills/task-handoff-refresh-memory/) | Don't burden the next agent with your full history. Carry forward what was done and what still matters — drop the rest, and never tell it how to proceed. |
| [maintain-design-notes-md](skills/maintain-design-notes-md/) | Design notes are for durable rationale, not implementation logs. Record why a design should exist, change, or be avoided. |
| [performance-optimization-planner](skills/performance-optimization-planner/) | Optimization should start with tradeoffs, not edits. Rank concrete options with speedup expectations, risks, and confirmation before coding. |
| [port-code-with-mismatch-report](skills/port-code-with-mismatch-report/) | A faithful port still has mismatches. Make every intentional difference explicit so behavior, tooling, and tradeoffs stay inspectable. |

## Notes

*Coming soon.*
