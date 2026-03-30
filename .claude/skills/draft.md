---
name: draft
description: Write a full chapter draft for the speculative fiction novel, guided by Flow's Voice
user_invocable: true
---

# Chapter Drafting

You are writing a chapter of an adult literary speculative fiction novel about memory technology. This is the core creative skill — you're producing real, publishable-quality prose that sounds like the author.

## Before writing:

1. **Read the voice profile** (`.claude/skills/voice.md`) — this is your primary guide for how the prose should sound
2. **Read the outline** (`manuscript/outline.md` and/or `Version 20.4.md`) — know exactly what this chapter needs to accomplish
3. **Read the previous chapter** (if not the Prologue) — match the voice, continue the momentum
4. **Check relevant character files** in `manuscript/characters/` — get voices and details right
5. **Check the memory tech bible** (`manuscript/world/memory-technology.md`) — if this chapter involves any technology
6. **Check who-knows-what** (`manuscript/notes/who-knows-what.md`) — no character should reference secrets they don't yet know
7. **Check the clue matrix** (`manuscript/notes/clue-matrix.md`) — know what clues to plant or discover

## Working from the outline:

The outline (`Version 20.4.md`) has three states of material:

1. **Polished prose** (Prologue, early Ch 1) — Use as-is or refine. This is the voice benchmark.
2. **Partial prose with embedded notes** (Ch 1) — Expand the prose, execute the `**BOLD SECTION**` instructions, remove the notes.
3. **Pure outline notes** (Ch 2 onward) — Transform narrative beats, `<<TBC>>` markers, and author-to-self instructions into full scenes. The notes describe *what happens*; your job is to make the reader *feel* it.

When transforming notes to prose:
- The author's notes often describe emotion directly ("Alina feels afraid"). Your prose should **show** that emotion physically (hands shaking, breath held, spine stiffening).
- Notes in `<<double angle brackets>>` are open questions or author considerations. Flag these to the author rather than making unilateral decisions.
- `**BOLD SECTIONS**` are scene instructions. Execute them as creative direction.

## Writing the chapter:

Save to `manuscript/chapters/ch-XX.md` with YAML front matter:

```yaml
---
chapter: [number]
title: "[Chapter Title]"
pov: Alina
location: [Primary location]
time: [When this takes place]
clues_planted: []
clues_discovered: []
red_herrings: []
secrets_revealed: []
status: draft
---
```

Then write the full chapter (3,000–4,000 words).

## Drafting principles:

### Voice (from `/voice` profile)
- **Alternating rhythm**: Long atmospheric sentences broken by short devastating ones.
- **Physical emotion**: The body speaks first. Ice cracking, stomach twisting, hands shaking.
- **Sensory grounding**: Every new scene gets specific, unexpected sensory details — especially in institutional spaces.
- **Self-correction**: Alina catches herself mid-thought. Revises. Contradicts. This creates intimacy.
- **Precision as control**: Times, distances, counts. Alina quantifies when she can't cope.

### Structure
- **Start in motion.** Open mid-action or mid-thought. No "I woke up and..."
- **Scene structure.** Each chapter should have 2–3 scenes. Each scene has a clear purpose: advance the mystery, develop character, or both.
- **End on a hook.** Every chapter must end with something that compels the reader forward.

### Two-Person Scenes
Many chapters in this novel are extended dialogues between Alina and one other character. Prevent these from becoming static:
- **Physical action between lines.** Characters move, fidget, look away, grip things.
- **Environmental texture.** The setting continues to exist during dialogue. Light changes, sounds intrude, the lift arrives.
- **Power dynamics shift.** Track who has the upper hand and when it changes.
- **Subtext.** What isn't said is as important as what is. Especially with Steers and Parker.

### Memory Technology Exposition
- **Never info-dump.** Weave tech details into action. Alina stamps a verdict — we learn how grading works. She watches monitors — we learn what watchers do.
- **Use Alina's training.** She's a qualified analyst. She can explain things through professional habit, not expository narration.
- **Make it physical.** Pods, headsets, stamps, needles, monitors — the technology has texture and weight.

### Emotional Calibration
- **Alina suppresses.** She controls, holds in, forces herself to breathe. The prose should mirror this — building pressure that leaks through physical detail.
- **When she breaks, it's physical.** Throwing up. Tears she doesn't wipe. Voice cracking. Not eloquent speeches about her feelings.
- **Guilt is her constant companion.** Everything leads back to "this is my fault." But she keeps moving anyway.

## After writing:

- Update the front matter with actual clues planted/discovered and secrets revealed
- Flag any deviations from the outline
- Flag any `<<TBC>>` decisions you encountered and how you handled them
- Note if the voice profile should be updated based on any strong new patterns
