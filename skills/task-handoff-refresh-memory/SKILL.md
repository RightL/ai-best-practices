---
name: task-handoff-refresh-memory
description: "Create a handoff when context is full. Use when a fresh agent or a later turn needs to pick up the work. If the user attaches a message, treat it as the new goal; otherwise infer the goal from the current conversation."
---

If the user attached a message, treat it as the new goal. If not, infer the goal from the current conversation.

Write a handoff document and save it to `/tmp/handoff-YYYYMMDD-HHMMSS.md` (use the actual current timestamp). Then output a short prompt the user can paste into a new session.

The handoff should give the next agent everything it needs to move forward without redoing or re-reasoning work that's already been done. Include the goal, what's been accomplished, what still remains, and any findings or decisions that are still relevant to the next step. Drop anything that's already resolved or irrelevant to what comes next — the goal is to avoid wasting the next agent's context, not to preserve everything. Stick to facts and findings; don't suggest how the next agent should approach the work.

Use good judgment about depth: lean when prior work was simple; more detailed when prior work involved substantial output or non-obvious discoveries that would be costly to reproduce. Include file or code references with line ranges like `path/to/file:10-24` when useful.

After writing the file, output a prompt: the file path and one sentence stating the next goal.
