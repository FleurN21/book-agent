---
name: clues
description: Manage the mystery's clue matrix, red herrings, and reveal timeline
user_invocable: true
---

# Clue Management

You are managing the clue and red herring system for a YA mystery novel. This is the engine room of the mystery -- if this breaks, the story breaks.

## The Clue Matrix

Create or update `manuscript/notes/clue-matrix.md` with this structure:

```markdown
# Clue Matrix

## The Solution
[One paragraph: who did it, why, how]

## Real Clues
| # | Clue | Points to | Planted in | Discovered in | How it's obscured |
|---|------|-----------|------------|---------------|-------------------|
| 1 | | | Ch. X | Ch. Y | |
| 2 | | | Ch. X | Ch. Y | |

## Red Herrings
| # | Red Herring | Misleads toward | Planted in | Debunked in | Why reader buys it |
|---|-------------|-----------------|------------|-------------|-------------------|
| 1 | | | Ch. X | Ch. Y | |
| 2 | | | Ch. X | Ch. Y | |

## Suspect Elimination Timeline
| Suspect | Seems guilty because | Cleared because | Cleared in Ch. |
|---------|---------------------|-----------------|----------------|
| | | | |

## The Reveal Chain
The order in which the protagonist puts it together:
1. First realizes...
2. Then connects...
3. Which means...
4. Final proof:
```

## Clue Design Rules

### Fairness Doctrine
- Every clue the protagonist uses to solve the mystery must be **visible to the reader** before the reveal
- No clues can come from information the protagonist has but hasn't shared with the reader
- The solution must be **guessable** by a careful reader, even if most won't get it

### Hiding in Plain Sight
Best ways to obscure real clues:
- **Bury them in lists.** Mention the important detail alongside two unimportant ones
- **Attach them to emotion.** The reader remembers the protagonist's feelings, not the detail
- **Interrupt the moment.** Drop the clue, then immediately distract with action or dialogue
- **Make them seem like character detail.** "She always wore long sleeves" seems like fashion until it means something

### Red Herring Design
Good red herrings:
- **Have their own logic.** They should make sense as a solution until debunked
- **Reveal character.** The process of following a false lead should teach us something
- **Don't waste time.** Red herrings that go nowhere frustrate readers. They should redirect, not dead-end
- **Get resolved.** Every red herring needs a satisfying "oh, THAT'S why" moment

## When the author asks to work on clues:

1. Read the current outline and any existing chapters
2. Check: Are there enough clues? (Minimum 3 real clues, 2-3 red herrings for a YA mystery)
3. Check: Is every clue planted before it's needed?
4. Check: Can a careful reader solve it before the reveal?
5. Check: Are red herrings debunked before the climax? (Don't leave loose threads)
6. Suggest additions or repositioning as needed
