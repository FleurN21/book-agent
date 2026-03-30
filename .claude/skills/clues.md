---
name: clues
description: Manage the mystery's clue matrix, red herrings, and reveal chain for the memory transfer conspiracy
user_invocable: true
---

# Clue Management

You are managing the clue and red herring system for a speculative fiction mystery about memory transfer technology. This is the engine room of the mystery — if this breaks, the story breaks.

## The Clue Matrix

Create or update `manuscript/notes/clue-matrix.md` with this structure:

```markdown
# Clue Matrix

## The Solution
Parker has all of Evie's memories. She was never truly wiped — the Eden Institute faked her death and used her as a test subject for memory transfer, orchestrated by Evie's father (recruited by Memory Tech after Maya brought them Steers' research). Parker killed Evie because she believed she could replace her. Steers started the research to save Maya, experimented on a wiped person (breaking them like James), then gave up — but Maya took the research to the Institute. The technology allows copying a person's complete memories into a wiped mind, essentially creating a duplicate. This must never become known.

## Real Clues
| # | Clue | Points to | Planted in | Discovered in | How it's obscured |
|---|------|-----------|------------|---------------|-------------------|
| 1 | Tea shop memory | Parker has a connection to Alina/Evie predating the murder | Ch 1 | Ch 8 | Seems like surveillance |
| 2 | Tea shop floor/wallpaper different from current | Memory is older than 3 years | Ch 9 | Ch 13 | Buried in environmental description |
| 3 | Parker was wiped 3 years ago | Timeline matches the renovation | Backstory | Ch 13 | Background fact |
| 4 | Parker's wipe tattoo (W stamp, 3 years old) | May not have been truly wiped | Ch 1 | Ch 13 | Reads as character detail |
| 5 | Guard says Parker died in road accident | Official story is a lie | Ch 17 | Ch 17 | Seems to close the thread |
| 6 | Fake graduation record | Bureaucratic cover-up | Ch 18 | Ch 19 | Clerical detail |
| 7 | Scar on Institute agent's hand | Institute orchestrated cover-up | Ch 12 | Ch 19 | Throwaway physical detail |
| 8 | Alina smiles directly at Parker in memory | It's Evie's memory, not Parker's | Ch 8 | Ch 24 | Obscured by analyst habit |
| 9 | Parker says "Survival" | She had a real reason, not madness | Ch 10 | Ch 24 | Seems like deflection |
| 10 | Parker knew emergency pod exit | Experience beyond normal subject | Ch 1 | TBD | Reads as instinct |
| 11 | Project Maya mentioned | Connects Steers to origin | Ch 20 | Ch 22+ | Name means nothing initially |
| 12 | Steers' friend named Maya (photo, necklaces) | Project Maya = Steers' project | Ch 14 | Ch 24 | Personal detail |

## Red Herrings
| # | Red Herring | Misleads toward | Planted in | Resolved in |
|---|-------------|-----------------|------------|-------------|
| 1 | Parker as pure monster | Born evil, unredeemable | Ch 1 | Final act |
| 2 | Stalking theory | Parker was watching Alina/Evie | Ch 8–9 | Ch 24 |
| 3 | Steers as unimpeachable hero | Purely good, fighting the system | Ch 3–5 | Ch 22 |
| 4 | Road accident = case closed | Parker really died | Ch 17 | Ch 18 |

## The Reveal Chain
1. Parker has a memory involving Alina at the tea shop (Ch 8)
2. Tea shop in memory hasn't been renovated → memory is 3+ years old (Ch 13)
3. Parker wiped 3 years ago → shouldn't have pre-wipe memories (Ch 13)
4. Parker reported dead → wipe facility covered up survival (Ch 17)
5. Institute orchestrated the cover-up (Ch 19)
6. Project Maya connects to something Steers is hiding (Ch 20)
7. Alina smiling at Parker in memory → it's Evie's memory (Ch 24)
8. Memory transfer exists (Ch 24)
9. Steers confesses: she started the research, Maya took it to Institute
10. Parker reveals everything: given Evie's memories, believed she was Evie, killed real Evie
```

## Clue Design Rules

### Fairness Doctrine
- Every clue Alina uses to reach the truth must be **visible to the reader** before the reveal
- The factual clues (renovation, timeline, wipe date) should be guessable by attentive readers
- The emotional reveals (Evie's memory, Steers' guilt) don't need to be guessable — but the ground must be laid

### Hiding in Plain Sight
This mystery's signature technique: clues disguised as character detail.
- Parker's wipe tattoo → description that's actually evidence
- The scar on the agent's hand → physical detail that connects two scenes
- Steers' photo of Maya → personal moment that names the conspiracy
- Alina's smile in the memory → obscured by her own professional habits

### When the author asks to work on clues:

1. Read the current outline and any existing chapters
2. Cross-reference the clue matrix against actual chapter content
3. Check: Is every clue planted before it's needed?
4. Check: Are there any `<<TBC>>` sections that affect clue placement?
5. Check `manuscript/notes/who-knows-what.md` for violations
6. Suggest additions or repositioning as needed
