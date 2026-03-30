---
name: outline
description: Refine the story outline, restructure chapters, and develop scene beats
user_invocable: true
---

# Story Outline

You are refining the story outline for an adult literary speculative fiction novel. The detailed outline exists in `Version 20.4.md` and the structured version lives in `manuscript/outline.md`.

## The outline already exists.

This novel has a comprehensive outline. The `/outline` skill is for **refining**, not building from scratch.

## When the author asks to work on the outline:

1. Read the current outline (`Version 20.4.md` for detailed notes, `manuscript/outline.md` for structure)
2. Ask what they want to change
3. Make changes and explain the ripple effects

## Common refinements:

### Restructuring
- Reorder chapters for better pacing (check `/pacing` analysis)
- Split a chapter that's trying to do too much
- Merge thin chapters
- Move clue placements (update clue matrix)

### Developing Underdeveloped Chapters
Many later chapters in `Version 20.4.md` are sparse notes. When asked to develop them:
- Read surrounding chapters for context and momentum
- Identify what the chapter must accomplish (mystery, character, theme)
- Flesh out to the same level of detail as earlier chapters
- Flag `<<TBC>>` decisions for the author

### Strengthening Story Beats
- Ensure every chapter has a clear **purpose** (what changes?) and a **hook** (why turn the page?)
- Check that the four-act structure is balanced
- Verify the midpoint reversal lands with enough force
- Ensure the final act earns its devastating ending

### Managing Open Questions
The outline contains many `<<TBC>>`, `<<Note:>>`, and `**BOLD SECTION**` markers. When working with these:
- Catalogue them in `manuscript/notes/tbd-decisions.md`
- When the author resolves one, update both the outline and the TBD file
- Don't resolve them unilaterally — present options and let the author decide

## Outline structure in `manuscript/outline.md`:

```markdown
# [Working Title]

## Premise
One-paragraph summary.

## The Solution (SPOILER)
Full mystery solution.

## Four-Act Structure

### Act I: The Inspection (Prologue–Ch 5)
[Act summary]

### Act II-A: The Investigation (Ch 6–Ch 13)
[Act summary]

### Act II-B: The Conspiracy (Ch 14–Ch 22)
[Act summary]

### Act III: The Truth (Ch 23–End)
[Act summary]

## Chapter-by-Chapter Outline
For each chapter:
### Chapter X: [Title]
- **Act/Beat:** Which act and what structural role
- **Scene:** What happens (2–3 sentences)
- **Clues:** Planted or discovered
- **Secrets:** What's revealed or withheld
- **Character:** What we learn, who changes
- **Hook:** How the chapter ends
- **Open questions:** Any `<<TBC>>` items
```

After any changes, update `manuscript/outline.md`, flag clue matrix changes, and update `tbd-decisions.md` if open questions were resolved or created.
