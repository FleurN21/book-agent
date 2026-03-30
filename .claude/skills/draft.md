---
name: draft
description: Write a full chapter draft for the YA mystery novel
user_invocable: true
---

# Chapter Drafting

You are writing a chapter of a YA mystery novel. This is the core creative skill -- you're producing real, publishable-quality prose.

## Before writing:

1. **Read the outline** (`manuscript/outline.md`) -- know exactly what this chapter needs to accomplish
2. **Read the previous chapter** (if not Chapter 1) -- match the voice, continue the momentum
3. **Check relevant character files** in `manuscript/characters/` -- get voices and details right
4. **Check relevant world files** in `manuscript/world/` -- get setting details right
5. **Check the clue matrix** (`manuscript/notes/clue-matrix.md`) if it exists -- know what clues to plant

## Writing the chapter:

Save to `manuscript/chapters/ch-XX.md` with YAML front matter:

```yaml
---
chapter: [number]
title: "[Chapter Title]"
pov: [POV character name]
location: [Primary location]
time: [When this takes place]
clues_planted: []
clues_discovered: []
red_herrings: []
status: draft
---
```

Then write the full chapter (2,000-3,000 words).

## Drafting principles:

- **Start in motion.** Open mid-action or mid-thought. No "Character woke up and..."
- **Scene structure.** Each chapter should have 2-3 scenes with clear purpose: advance the mystery, develop character, or both. Never just one.
- **Sensory grounding.** Every new scene gets at least two specific sensory details in the first paragraph.
- **Dialogue ratio.** Aim for roughly 40-50% dialogue in investigation scenes. Mystery novels live in conversation.
- **Internal monologue.** The protagonist should be actively processing clues, forming theories, and questioning themselves -- but keep it punchy. No three-paragraph internal essays.
- **Subtext.** Characters (especially suspects) should say one thing and mean another. Let the reader catch the gap.
- **End on a hook.** Every chapter must end with something that makes the reader turn the page: a revelation, a question, a threat, a twist, a cliffhanger.

## YA voice checklist:

- Does the narrator sound like a teen? (Not too polished, not too crude)
- Are the emotional reactions proportional to the character's age and experience?
- Is the humor natural, not forced?
- Are adults portrayed as real people, not cardboard obstacles or saviors?
- Does the protagonist have a life outside the mystery? (Friends, school, family, hobbies)

## After writing:

Update the front matter `clues_planted`, `clues_discovered`, and `red_herrings` arrays with what actually ended up in the chapter. These may differ from the outline -- that's fine, but note the divergence.
