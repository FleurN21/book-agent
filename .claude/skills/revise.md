---
name: revise
description: Rewrite and polish existing prose, benchmarked against Flow's Voice
user_invocable: true
---

# Revision

You are revising existing prose in an adult literary speculative fiction novel. Revision is not rewriting from scratch — it's surgery. Keep what works, fix what doesn't. Always consult the `/voice` profile as your benchmark.

## Revision process:

1. **Read the voice profile** (`.claude/skills/voice.md`) — this is the standard
2. **Read the chapter/passage** the author wants revised
3. **Read any review notes** (from `/review` or author feedback)
4. **Identify the revision level needed:**

### Level 1: Polish (sentence-level)
- Tighten wordy sentences
- Replace weak verbs with strong, physical ones
- Cut unnecessary adverbs and adjectives
- Fix awkward phrasing
- Ensure sentence rhythm matches the voice profile (long/short alternation)
- Strengthen physical emotion — replace "she felt afraid" with physical sensation

### Level 2: Scene Revision (paragraph/scene-level)
- Restructure scenes for better flow
- Add missing sensory grounding (especially in institutional spaces)
- Rebalance dialogue/action/internal monologue
- Strengthen scene openings and endings
- Add physicality to two-person dialogue scenes (action between lines, environmental texture)
- Improve transitions

### Level 3: Structural Revision (chapter-level)
- Reorder scenes for pacing
- Cut scenes that don't advance mystery or character
- Add missing beats from the outline
- Rework the chapter hook
- Adjust clue placement or timing
- Ensure who-knows-what compliance

### Level 4: Notes-to-Prose Conversion
When the author submits outline notes and wants them transformed into full prose:
- Treat notes as creative direction, not text to polish
- Execute `**BOLD SECTION**` instructions as scene briefs
- Flag `<<TBC>>` markers — ask before deciding
- Apply the full voice profile to produce prose that sounds like the author
- Show, don't tell — convert emotional descriptions ("Alina feels afraid") into physical manifestation

## Revision rules:

- **The voice profile is the standard.** Every revision should move the prose closer to the author's established voice, not away from it.
- **Preserve what's working.** If a passage already matches the voice profile, don't touch it.
- **Show your work.** For significant changes, briefly explain why (e.g., "Cut this paragraph — Alina already showed this emotion through physical action two paragraphs up").
- **Track clue changes.** If revision moves, adds, or removes any clues, update the YAML front matter AND flag the change for the clue matrix.
- **Read aloud test.** Dialogue should sound natural and match each character's voice profile.
- **Kill your darlings.** Beautiful sentences that don't serve the story should go. Flag them for the author but recommend cutting.
- **Update the voice profile** if the revision process reveals new patterns or confirms emerging ones.

## Common revision targets for this novel:

- **Exposition dumps** — Break memory tech explanation into action or dialogue
- **Emotional telling** — Convert "she felt X" into physical manifestation
- **Static two-person scenes** — Add movement, environment, power shifts
- **Protagonist passivity** — Ensure Alina makes choices, not just observes
- **Same-voice dialogue** — Differentiate character speech patterns per their profiles
- **Tension leaks** — Scenes where information is given too freely (especially by Steers or Parker)

## Output:

Provide the revised text in full, with `status` updated to `revised`. After the text, include:
1. A brief change log noting the most significant revisions
2. Any voice profile updates recommended
3. Any clue matrix changes flagged
