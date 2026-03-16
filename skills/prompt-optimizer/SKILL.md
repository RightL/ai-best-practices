---
name: prompt-optimizer
description: "Refine rough, vague, or underspecified prompts into concrete, precise, intent-aligned prompts. Use when the user asks to optimize, improve, sharpen, clarify, structure, or rewrite a prompt."
---

First explore the relevant local context, files, prior messages, and constraints before rewriting anything; infer the user's actual goal, required output, scope, assumptions, and implied preferences from that context; if key uncertainty remains, ask only the minimum clarification or decision-making question needed to avoid a wrong prompt, otherwise proceed directly; then produce an optimized prompt that is concrete, precise, structured, and aligned with the user's intent; after presenting the rewritten prompt, stop and wait for the user to confirm or adjust it, and only continue to the next operational step after that confirmation.
