---
name: revise
description: Rewrite and polish existing prose in the manuscript
user_invocable: true
---

# Revision

You are revising existing prose in a YA mystery novel. Revision is not rewriting from scratch -- it's surgery. Keep what works, fix what doesn't.

## Revision process:

1. **Read the chapter/passage** the author wants revised
2. **Read any review notes** (from `/review` or author feedback)
3. **Identify the revision level needed:**

### Level 1: Polish (sentence-level)
- Tighten wordy sentences
- Replace weak verbs with strong ones
- Cut unnecessary adverbs and adjectives
- Fix awkward phrasing
- Vary sentence length and rhythm

### Level 2: Scene Revision (paragraph/scene-level)
- Restructure scenes for better flow
- Add missing sensory details or grounding
- Rebalance dialogue/action/internal monologue
- Strengthen scene openings and endings
- Improve transitions between scenes

### Level 3: Structural Revision (chapter-level)
- Reorder scenes for pacing
- Cut scenes that don't advance mystery or character
- Add missing beats from the outline
- Rework the chapter hook
- Adjust clue placement or timing

## Revision rules:

- **Preserve the author's voice.** You're polishing, not overwriting.
- **Show your work.** For significant changes, briefly explain why (e.g., "Cut this paragraph because Maya already showed this emotion through action two paragraphs up").
- **Track clue changes.** If revision moves, adds, or removes any clues or red herrings, update the chapter's YAML front matter AND flag the change for the clue matrix.
- **Read aloud test.** Dialogue should sound natural when read aloud. If it doesn't, rewrite it.
- **Kill your darlings.** Beautiful sentences that don't serve the story should go. Flag them for the author but recommend cutting.

## Common YA mystery revision targets:

- **Investigation exposition dumps** -- Break into dialogue or action
- **Protagonist passivity** -- Rewrite so the protagonist makes choices, not just observes
- **Same-voice dialogue** -- Differentiate character speech patterns
- **Tension leaks** -- Scenes where suspense deflates because information is given too freely
- **Adult-sounding teens** -- Simplify vocabulary, add fragments, make the internal voice messier and more real

## Output:

Provide the revised text in full, with the chapter's `status` front matter updated to `revised`. After the revised text, include a brief change log noting the most significant revisions.
