# Two-Sided Agent

→ [SKILL.md](SKILL.md)

## Why

A single perspective — even a careful one — tends to reinforce its own assumptions. The AI forms a view, then looks for reasons it's right. This is confirmation bias, and it's hard to avoid when thinking alone.

The fix is genuine opposition. When one subagent is explicitly tasked with defending the answer and another is explicitly tasked with attacking it, both are forced to produce real arguments. The synthesis of that conflict is more accurate than either side alone — not because it averages them, but because it has to survive scrutiny from both directions.

## What It Does

Spawns two subagents with opposing mandates — defender and attacker — given the same context. After both report back, compares their arguments directly, follows up where points are weak, and synthesizes a final conclusion that reflects what holds up and what doesn't.

## When to Use

When you're not confident a single-pass answer is good enough. Works equally for discovery (what's the right answer?), refinement (is this plan solid?), or verification (does this conclusion hold?).
