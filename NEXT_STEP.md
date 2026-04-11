# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 101 drafting edge
- Current target file: `chapters/101.md`
- Task type: next bounded drafting pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: draft Chapter 101 only，承接“双门并开”后的第一落点，优先写其中一路先动身并真正入门，控制揭示密度，只掀一层实物/实景，不要两线同章同时大爆。
- Output required:
  - new `chapters/101.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 101 exists on disk as one complete draft
  - no multi-chapter expansion was attempted
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
|- Current recovery point: Chapter 102
|- Current target file: `chapters/102.md`
|- Task type: drafting / revision

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
