---
name: extract-workflow
description: "Extract reusable instructions from a conversation history with an AI coding agent (Claude Code, Codex, etc.). Use when the user wants to capture methods or processes they explained to the AI, so they don't have to re-instruct next time."
---

Read through the conversation and look specifically for moments where the user explained to the AI how to do something — a method, a process, a preference, or a way of working. These are the instructions the user shouldn't have to repeat next time. Extract at most 1-2 of the most reusable ones, generalized and stripped of task-specific details. Output each as a short, direct instruction that could be dropped into a future prompt or skill.
