# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 61
- Current target file: `chapters/61.md`
- Task type: single bounded revision pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: revise Chapter 61 only, focusing on sequence clarity,沈临舟出场后的情绪稳定度，以及 A13/A14/A15 信息投放节奏。
- Output required:
  - updated `chapters/61.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 61 has completed one explicit revision pass
  - no cross-chapter expansion was attempted
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
- Current recovery point: Chapter 62
- Current target file: `chapters/62.md`
- Task type: revision / cleanup

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
