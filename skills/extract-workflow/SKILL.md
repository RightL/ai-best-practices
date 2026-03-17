---
name: extract-workflow
description: "Extract reusable instructions from a conversation history with an AI coding agent (Claude Code, Codex, etc.). Use when the user wants to capture methods or processes they explained to the AI, so they don't have to re-instruct next time."
---

Read through the conversation and look specifically for moments where the user explained to the AI how to do something — a method, a process, a preference, or a way of working. Only extract instructions the user gave directly in the conversation. Ignore anything that comes from system prompts, project config files (CLAUDE.md, AGENT.md, etc.), or tool descriptions — those are already captured elsewhere. Skip anything too situational to be reusable.

For each instruction, abstract it away from the specific task context — express the underlying principle in domain-agnostic terms, so it would apply to a different problem of the same kind.

Write each extracted instruction in whatever form fits its complexity — a single line if it's simple, a few steps if it needs structure.
