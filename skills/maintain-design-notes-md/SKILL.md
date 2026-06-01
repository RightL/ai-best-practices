---
name: maintain-design-notes-md
description: "Use when the user wants to create or maintain a `DESIGN_NOTES.md` that records design rationale by scope."
---

- Treat the examples and procedures in this skill as neither necessary nor sufficient; preserve the core intent and adapt to the actual context.
- `DESIGN_NOTES.md` is design-specific project memory: it preserves durable rationale for why the project is shaped this way.
- User may use `dn` as shorthand for `DESIGN_NOTES.md`.
- Use it when a task may depend on or change durable design rationale. Reading `DESIGN_NOTES.md` does not imply it must be updated.
- A note belongs in `DESIGN_NOTES.md` only if it helps a future maintainer understand why the project should keep, change, or avoid a design choice.
- Create or update a single `DESIGN_NOTES.md` in the relevant project location only when there is durable design rationale to record, revise, or remove.
- Design notes are different from project memory: Exclude step-by-step implementation details, API inventories, and status logs unless the user explicitly asks for them.
- When updating the notes, also review existing entries for anything outdated, incorrect, or superseded by later design changes, and handle that cleanup in the same pass. THIS IS COMPULSORY!
- Record why the design is this way, not what was built and not how it was implemented. Why designed in such way is the most important thing to be written to the notes.
- If the rationale is unclear, ask the user for clarification instead of guessing.
- Organize each note by scope when that distinction matters.
- Keep each entry concrete about the rationale behind the design, such as the key constraint, tradeoff, rejected alternative, or design pressure that explains why it exists in this form. Any examples in this skill are only aids for interpretation. They are neither necessary nor sufficient; apply the rationale test above in each case.
- Keep the notes concise, durable, and easy to extend as the design evolves.
- Notes need to be easy to understand for future maintainers.
